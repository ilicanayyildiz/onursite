# Troll Site

Static tek sayfa — Vercel’e deploy için hazır.

## Vercel’e deploy

### 1. Git ile (önerilen)

1. Projeyi Git ile başlat:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   ```
2. GitHub’da yeni bir repo oluştur, projeyi push et.
3. [vercel.com](https://vercel.com) → **Add New** → **Project** → Repo’yu seç → **Deploy**.

### 2. Vercel CLI ile

1. [Vercel CLI](https://vercel.com/cli) yüklüyse:
   ```bash
   npx vercel
   ```
2. Giriş yap, sorulanları onayla. Proje klasöründe `npx vercel --prod` ile production deploy alabilirsin.

---

**Not:** Build step yok, sadece statik HTML. `framework: null` ile Vercel bunu otomatik algılar.
