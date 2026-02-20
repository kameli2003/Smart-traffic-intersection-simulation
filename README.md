# Smart-traffic-intersection-simulation
# Emergency Vehicle Priority Traffic Simulation  
شبیه‌سازی تقاطع هوشمند با اولویت‌دهی به خودروهای امدادی

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Threading](https://img.shields.io/badge/Concurrency-Threading-yellow)
![License](https://img.shields.io/badge/license-MIT-green)

## توضیح پروژه

این پروژه یک **شبیه‌سازی چندنخی (multi-threaded)** از تقاطع چهارراه شهری است که:

- از الگوریتم **وزن‌دهی به لاین‌ها** (lane weighting) استفاده می‌کند
- **اولویت مطلق** به خودروهای امدادی می‌دهد
- از **قفل‌های مسیر (path locks)** برای جلوگیری از تصادم استفاده می‌کند
- زمان عبور هر لاین متناسب با ترافیک آن تنظیم می‌شود

مناسب برای دانشجویان، پژوهشگران و علاقه‌مندان به **هوش مصنوعی ترافیک**، **کنترل concurrency** و **شبیه‌سازی سیستم‌های واقعی**

## ویژگی‌های اصلی

- اولویت‌دهی ۱۰۰٪ به خودروهای امدادی (حتی اگر لاین‌های دیگر در صف باشند)
- مدیریت ایمن تقاطع با استفاده از **path-specific locks**
- وزن‌دهی پویا به هر لاین (lane weights)
- شبیه‌سازی زمان واقعی عبور (crossing time)
- چاپ وضعیت ورود و خروج خودروها به صورت خوانا

## ساختار پروژه
