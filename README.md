# CortenCloud

Node.js (Express) + PostgreSQL. Ma'lumotlar serverda saqlanadi.

## Render'ga joylash
1. Bu papkadagi hamma fayllarni GitHub repozitoriyga yuklang (`node_modules` va `data` papkalarisiz).
2. Bepul PostgreSQL oching (neon.tech tavsiya etiladi) va `DATABASE_URL` ni nusxalang.
3. Render -> New -> Blueprint -> repozitoriyni tanlang. So'ralganda kiriting:
   - `DATABASE_URL`  : Neon/Render Postgres manzili
   - `ADMIN_PASSWORD`: admin paroli (yangi, murakkab parol)
4. Deploy tugagach sayt ochiladi. Admin: login `admin`, parol = `ADMIN_PASSWORD`.

## Kompyuterda sinash
    npm install
    npm start        # http://localhost:3000  (admin / admin12345, faqat sinov uchun)
