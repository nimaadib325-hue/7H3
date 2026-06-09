# Fib MA Bands Pro — راهنمای نصب روی GitHub Pages

## فایل‌های پروژه
- `index.html` — اپ اصلی
- `manifest.json` — تنظیمات PWA
- `sw.js` — Service Worker (آفلاین)
- `icon-192.png` / `icon-512.png` — آیکون اپ

---

## مراحل آپلود روی GitHub Pages

### ۱. ساخت Repository جدید
- وارد [github.com](https://github.com) بشید
- روی **New** کلیک کنید
- نام: `fib-ma-bands-pro`
- حالت: **Public**
- روی **Create repository** کلیک کنید

### ۲. آپلود فایل‌ها
- روی **uploading an existing file** کلیک کنید
- همه ۵ فایل رو (index.html, manifest.json, sw.js, icon-192.png, icon-512.png) drag & drop کنید
- پایین صفحه روی **Commit changes** کلیک کنید

### ۳. فعال‌سازی GitHub Pages
- به تب **Settings** برید
- از منو سمت چپ **Pages** رو انتخاب کنید
- زیر **Source** گزینه **Deploy from a branch** رو انتخاب کنید
- Branch: **main** — Folder: **/ (root)**
- روی **Save** کلیک کنید

### ۴. لینک اپ شما
بعد از ۱-۲ دقیقه اپ روی این آدرس فعال میشه:
```
https://[username].github.io/fib-ma-bands-pro/
```

---

## لینک‌گذاری در سایت
```html
<a href="https://[username].github.io/fib-ma-bands-pro/" target="_blank">
  باز کردن Fib MA Bands Pro
</a>
```

---

## قابلیت‌های اپ
- ✅ چارت کندل‌استیک زنده از Binance
- ✅ Fib MA Bands (SMMA 250 + ATR 300 + Smooth 300)
- ✅ MA 50 و MA 100
- ✅ سطوح سیستم 7H (Entry 0.266 / TP1 0.86 / TP2 1.1 / SL -0.13)
- ✅ تایم‌فریم‌های مختلف (5m تا 1W)
- ✅ انتخاب ۸ جفت‌ارز
- ✅ Signal Bar (BULL / BEAR / WAIT)
- ✅ Crosshair با اطلاعات کندل
- ✅ PWA — قابل نصب روی موبایل
- ✅ آپدیت زنده از WebSocket Binance
