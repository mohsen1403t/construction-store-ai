# construction-store-ai - Starter bundle

این بسته، اسکلت پایه‌ای از پروژه‌ی **Construction Store** را به‌صورت آماده و قابل اجرا محلی شامل می‌کند.
در داخل: `backend/` (Express + Mongoose) و `frontend/` (Next.js app router + Tailwind).

## راه‌اندازی سریع (محلی)

### Backend
1. برو به پوشه backend:
```bash
cd backend
npm install
cp .env.example .env
# و متغیرها را در .env پر کن
npm run dev
```

### Frontend
1. برو به پوشه frontend:
```bash
cd frontend
npm install
cp .env.local.example .env.local
# اگر لازم بود NEXT_PUBLIC_API_BASE را تنظیم کن
npm run dev
```

## محتویات مهم
- backend/server.js
- backend/config/db.js
- backend/models/Product.js, User.js
- frontend/app/page.jsx, frontend/app/shop/page.jsx
- frontend/components/ProductCard.jsx

## نکات
- این یک اسکلت اولیه است؛ برای تولید بهینه‌تر و امن‌تر باید لایه‌های امنیتی، اعتبارسنجی ورودی‌ها و مدیریت خطا توسعه یابند.
- برای ادغام OpenAI و زرین‌پال کلیدها را در .env قرار بدهید و نمونه‌های endpoint را در backend/server.js یا utils بسازید.

