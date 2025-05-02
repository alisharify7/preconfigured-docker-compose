# 🧾 Contribution Guide

Hello and thank you for considering contributing to this project!  
Please read the following guidelines before submitting a Pull Request to keep the project clean, organized, and maintainable.

## 📁 Project Structure

- Each service must be placed in the **correct directory based on its category**:
  - Databases → `database/`
  - Development tools → `development-tools/`
  - Monitoring tools → `monitoring/`
  - Web servers & gateways → `web-servers/`
  - Other tools → `others/` or any other suitable category
- Avoid creating unnecessary or unstructured folders.



## 📄 Docker Compose File Rules

- Use the **latest stable versions** of `docker` and `docker-compose`.
- **Avoid hardcoding** values like:
  - Image version (e.g., `latest` or numeric tags)
  - Username / password
  - Ports
  Instead, use environment variables through a `.env` file:

```yaml
image: redis:${REDIS_VERSION:-latest}
environment:
  - REDIS_PASSWORD=${REDIS_PASSWORD}
```
For every service, include a .env.sample file to help users easily create their own .env.


---

## 🧩 Standard Header in Compose Files

Please include the following header at the top of every `docker-compose.yaml` file, and replace the `author` field with your GitHub username:

```yaml
#
#  * <service-name>
#  * author: @<your-github-username>
#  * Under GPL-3.0 license.
#  * email: alisharifyofficial@gmail.com
#  * read more at repo: https://github.com/alisharify7/preconfigured-docker-compose
```
example:
```
#
#  * grafana
#  * author: @hootanht
#  * Under GPL-3.0 license.
#  * email: alisharifyofficial@gmail.com
#  * read more at repo: https://github.com/alisharify7/preconfigured-docker-compose
```



---

## 📝 Documentation

- After adding a new service:
  - Add it to the main `README.md` file under the appropriate section.
  - Write a brief one-line description for it.
- Optionally, you may also create a dedicated `README.md` inside the service folder for more details.


## 🔀 Pull Requests

- Submit a **separate PR for each service**.
- Use the naming format `feature/<service-name>` for your branch.
- PR titles and descriptions should be clear and informative.
- Link any related issues within the PR when applicable.


## 🧪 Testing

Before submitting a PR:
- Run the service with `docker-compose up` and make sure it works.
- Ensure there are no errors and everything starts correctly.


## 📄 License

By contributing to this project, you agree that your code will be released under the [GPL-3.0](LICENSE) license.

---

Thank you for your contribution 🙌  
If you have any questions, feel free to open an issue or email us.

Best regards,  
Ali sharifi 🎉
