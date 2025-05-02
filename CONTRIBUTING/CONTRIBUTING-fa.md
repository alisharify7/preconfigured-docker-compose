# 🧾 راهنمای مشارکت در پروژه

سلام و ممنون که قصد دارید در این پروژه مشارکت کنید!  
لطفاً پیش از ارسال Pull Request موارد زیر را رعایت کنید تا ساختار پروژه منظم و قابل نگهداری باقی بماند.



## 📁 ساختار پروژه

- هر سرویس باید **در مسیر مناسب بر اساس دسته‌بندی** قرار بگیرد:
  - دیتابیس‌ها → `database/`
  - ابزار توسعه → `development-tools/`
  - ابزار مانیتورینگ → `monitoring/`
  - وب سرورها و گیت‌وی‌ها → `web-servers/`
  - سایر ابزارها → `others/` یا دسته مناسب دیگر
- از ایجاد ساختار پوشه‌ای غیرضروری یا نامنظم خودداری کنید.



## 📄 قوانین فایل‌های Docker Compose

- از **آخرین نسخه‌های stable** برای `docker` و `docker-compose` استفاده کنید.
- از **هاردکد کردن اطلاعات حساس یا وابسته به نسخه** مثل:
  - image version (مثلاً `latest` یا عددی)
  - username / password
  - پورت‌ها
  خودداری کرده و بجای آن از متغیرهای محیطی (`.env`) استفاده کنید:
  
```yaml
image: redis:${REDIS_VERSION:-latest}
environment:
  - REDIS_PASSWORD=${REDIS_PASSWORD}
```


---

## 🧩 هدر استاندارد در فایل‌های Compose

در ابتدای هر فایل `docker-compose.yaml`، لطفاً از الگوی زیر برای مستندسازی استفاده کنید و مقدار `author` را با یوزرنیم گیت‌هاب خودتان جایگزین نمایید:

```yaml
#
#  * <service-name>
#  * author: @<your-github-username>
#  * Under GPL-3.0 license.
#  * email: alisharifyofficial@gmail.com
#  * read more at repo: https://github.com/alisharify7/preconfigured-docker-compose
```

مثال:
```
#
#  * grafana
#  * author: @hootanht
#  * Under GPL-3.0 license.
#  * email: alisharifyofficial@gmail.com
#  * read more at repo: https://github.com/alisharify7/preconfigured-docker-compose
```



---

### 📝 مستندسازی

- پس از اضافه کردن هر سرویس:
  - آن را در `README.md` اصلی ریپو در بخش مناسب قرار دهید.
  - یک توضیح کوتاه (یک خطی) برای معرفی سرویس بنویسید.
- در صورت نیاز، می‌توانید داخل پوشه‌ی سرویس، یک `README.md` مجزا برای اطلاعات بیشتر اضافه کنید.


## 🔀 Pull Request

- لطفاً برای هر سرویس، **یک PR جداگانه** باز کنید.
- شاخه (branch) خود را به صورت `feature/<service-name>` نام‌گذاری کنید.
- عنوان و توضیحات PR باید شفاف و مشخص باشند.
- در صورت وجود Issue مرتبط، لطفاً آن را در PR لینک کنید.


## 🧪 تست

پیش از ارسال PR:
- سرویس را با `docker-compose up` تست کنید.
- مطمئن شوید همه چیز بدون خطا بالا می‌آید.


## 📄 لایسنس

با مشارکت در این پروژه، شما موافقت می‌کنید که کد شما تحت لایسنس [GPL-3.0](LICENSE) منتشر شود.

---

ممنون بابت مشارکت شما 🙌  
در صورت داشتن سوال، Issue باز کنید یا به ما ایمیل بزنید.

با احترام،  
 Ali sharifi 🎉
