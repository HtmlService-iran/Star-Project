<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0a0e27&height=200&section=header&text=StarProject%20HelpDesk&fontSize=45&fontColor=00d2ff&animation=fadeIn&fontAlignY=38&desc=Modern%20Ticket%20System%20%7C%20VIP%20Features&descAlignY=58&descSize=18" width="100%"/>

# ⭐ StarProject - HelpDesk System

### نرم‌افزار پشتیبانی دسکتاپ با امکانات VIP و رابط کاربری مدرن 🚀

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](#)
[![CustomTkinter](https://img.shields.io/badge/CustomTkinter-1a1a1a?style=for-the-badge&logo=python&logoColor=white)](#)
[![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)](#)
[![GitHub API](https://img.shields.io/badge/GitHub_API-181717?style=for-the-badge&logo=github&logoColor=white)](#)

<br>

<img src="https://user-images.githubusercontent.com/74038190/212284158-e840e285-664b-44d7-b79b-e264b5e54825.gif" width="400" alt="coding">

</div>

---

## 📖 درباره پروژه (About)

این ریپازیتوری شامل نسخه دسکتاپ سیستم پشتیبانی **StarProject** است. 
ما این سیستم را با استفاده از **پایتون (Python)** و کتابخانه **CustomTkinter** طراحی کرده‌ایم تا کاربران بتوانند به راحتی با تیم پشتیبانی در ارتباط باشند.

سیستم از یک دیتابیس ابری (**Supabase**) برای مدیریت کاربران استفاده می‌کند و تیکت‌ها را مستقیماً از طریق **GitHub API** در بخش Issues ثبت می‌کند.

---

## ✨ ویژگی‌های برنامه

### ۱. سیستم کاربری (Client)
- 🔐 **ثبت‌نام و ورود امن:** رمزهای عبور با الگوریتم SHA-256 هش می‌شوند.
- 🎫 **ارسال تیکت:** ارسال مستقیم تیکت به گیت‌هاب همراه با مشخصات کاربر.
- 📋 **تاریخچه تیکت‌ها:** مشاهده لیست تیکت‌ها و پاسخ‌های ارسال شده توسط پشتیبانی.
- 👤 **پروفایل کاربری:** تغییر نام کاربری و تغییر رمز عبور.
- 🌐 **لینک‌های ارتباطی:** دسترسی سریع به وب‌سایت و گیت‌هاب پروژه.

### ۲. امکانات VIP
- ⏱️ **پشتیبانی اولویت‌دار:** تیکت‌های VIP با برچسب `[VIP-PRIORITY]` در بالای لیست ادمین قرار می‌گیرند.
- 👑 **تم‌های اختصاصی:** دسترسی به تم‌های رنگی خاص (سایبرپانک، ماتریکس، لوکس) فقط برای کاربران VIP.
- 🎁 **دریافت VIP:** امکان دادن اشتراک VIP (با تعیین تعداد روز) توسط ادمین.

### ۳. پنل مدیریت (Admin Panel)
- 🔑 **ورود با رمز اختصاصی:** امنیت بالا برای جلوگیری از دسترسی غیرمجاز.
- 🎫 **مدیریت تیکت‌ها:** مشاهده، پاسخ دادن، بستن و حذف کامل تیکت‌ها.
- 👥 **مدیریت کاربران:** مشاهده لیست کاربران و دادن/گرفتن اشتراک VIP.
- 💻 **مشخصات سیستم:** مشاهده IP و سیستم‌عامل کاربرانی که وارد برنامه شده‌اند.

---

## 🖼️ محیط برنامه (UI)

- 🎨 **تم تاریک و مدرن (Dark Theme)**
- 🌈 **پشتیبانی از ۴ تم رنگی:** طلایی، آبی، نئون قرمز، ماتریکس
- ✨ **افکت شیشه‌ای (Glassmorphism)** در کارت‌ها و منوها
- ⚡ **انیمیشن‌های نرم** هنگام جابجایی بین صفحات

---

## 🛠️ نحوه اجرا (Installation)

برای اجرای برنامه، به **پایتون نسخه 3.8 یا بالاتر** نیاز دارید.

**۱. نصب کتابخانه‌های مورد نیاز:**
```bash
pip install customtkinter requests
