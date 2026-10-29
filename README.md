# AETHERIS / Nononick Content Studio (Flat structure)

ساختار کاملاً فلت — همه فایل‌ها در ریشه برای کار راحت با موبایل.

## اجرا

```bash
npm install
cp .env.example .env.local
# GEMINI_API_KEY را تنظیم کنید
npm run dev
```

## فایل‌های اصلی
- `main.tsx` / `App.tsx` — نقطه ورود
- `*View.tsx` — صفحات و ویوها
- `media.ts` / `types.ts` — تایپ‌ها
- `mediaData.ts` و سایر data — داده‌ها
- تصاویر jpg در ریشه
- `server.ts` — سرور Express + Vite
