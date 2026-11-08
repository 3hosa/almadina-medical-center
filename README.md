# 🏥 Al-Madina Medical Center Portal | بوابة مجمع المدينة الطبي

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/)
[![Nginx](https://img.shields.io/badge/Nginx-Production-009639?logo=nginx&logoColor=white)](https://nginx.org/)
[![Docker](https://img.shields.io/badge/Docker-Ready-2496ED?logo=docker&logoColor=white)](https://www.docker.com/)
[![License](https://img.shields.io/badge/License-Proprietary-red.svg)](LICENSE)

---

## 📌 نبذة عامة (Project Overview)

**بوابة مجمع المدينة الطبي (Al-Madina Medical Center Portal)** هي منصة ويب طبية متكاملة وحديثة، مصممة لاستعراض التخصصات الطبية، العيادات، المختبرات، وقسم الأشعة، مع تمكين المرضى من حجز المواعيد إلكترونياً.

تم تجهيز المشروع بحاويات **Docker** ومخدم **Nginx** عالي الأداء مع دعم كامل للخطوط وتجاوز قيود CORS للنشر المباشر على منصات السحاب مثل Railway.

---

## 🏗️ أقسام البوابة (Portal Sections)

* **الرئيسية (`index.html`):** استعراض لأحدث الخدمات والأجهزة الطبية وأوقات الدوام.
* **العيادات التخصصية (`clinics.html`):** تغطية شاملة لكافة العيادات (الباطنية، الأطفال، العيون، الأسنان، العظام).
* **الأطباء والاستشاريون (`doctors.html`):** نبذة عن الكادر الطبي وسنوات الخبرة والمواعيد المتاحة.
* **المختبرات والتحاليل (`labs.html`):** قائمة بالفحوصات الشاملة وباقات التحاليل الدورية.
* **مركز الأشعة والتصوير الطبي (`radiology.html`):** أحدث تقنيات التصوير بالرنين والمقطعي والسونار.
* **حجز المواعيد أونلاين (`appointment.html`):** نموذج حجز ذكي وسريع.

---

## 🚀 دليل التشغيل والنشر (Deployment Guide)

### تشغيل المشروع باستخدام Docker
```bash
# بناء الصورة وتشغيل الحاوية
docker build -t almadina-portal .
docker run -d -p 80:80 almadina-portal
```
*البوابة ستكون متاحة مباشرة على: `http://localhost`*

---

## 📄 الترخيص (License)
جميع الحقوق محفوظة للمطور © **3hosa**.
