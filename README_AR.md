
# دليل Whonix للمبتدئين

<p align="center">
  <img src="images/banner.png" width="100%" />
</p>

## 🌐 اللغة
- 🇸🇦 العربية
- 🇺🇸 [English](README.md)

---

# عن المشروع

هذا المشروع عبارة عن دليل عملي ومرئي لمساعدة المبتدئين على تعلم واستخدام Whonix بشكل احترافي.

---

# ما هو Whonix؟

Whonix نظام تشغيل يركز على الخصوصية ويستخدم جهازين وهميين:

- Gateway
- Workstation

لتوجيه الاتصال عبر شبكة Tor.

```txt
المستخدم → Workstation → Gateway → Tor → الإنترنت
```

---

# التثبيت

## الخطوة الأولى — تثبيت VirtualBox

https://www.virtualbox.org

![VirtualBox](images/virtualbox-install.png)

---

## الخطوة الثانية — تحميل Whonix

https://www.whonix.org/wiki/Download

قم بتحميل:
- Gateway
- Workstation

---

## الخطوة الثالثة — استيراد الأجهزة الوهمية

افتح:

```txt
File → Import Appliance
```

ثم استورد:
- Gateway
- Workstation

---

## الخطوة الرابعة — تشغيل Gateway أولًا

قم بتشغيل:
1. Gateway
2. Workstation

---

# التحقق باستخدام Wireshark

يمكن استخدام Wireshark لمراقبة:
- اتصال Tor
- حركة الشبكة
- DNS
- سلوك الحزم

---

# تثبيت Wireshark

https://www.wireshark.org

أثناء التثبيت:
- قم بتثبيت Npcap
- اترك الإعدادات الافتراضية

---

# نصائح أمنية

- حدّث النظام باستمرار
- استخدم كلمات مرور قوية
- افصل الهويات المختلفة
- تجنب الملفات المشبوهة

---

# حل المشاكل

## لا يوجد اتصال

الحلول:
- إعادة تشغيل Gateway
- التحقق من إعدادات الشبكة
- التحقق من الإنترنت

---

# تنويه

هذا المشروع لأغراض تعليمية وتوعوية فقط.

---

# المطور

Feras Hamamdeh
