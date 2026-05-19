# WGMB API Website — Setup Guide

## Folder Structure
```
wgmb-cms/
├── index.html              ← Home page
├── contact.html            ← Contact page
├── netlify.toml            ← Netlify config
├── site-data.json          ← All content (CMS editable)
├── _data/
│   └── hero.json           ← Home page hero content
├── _products/              ← Products (CMS managed)
├── _pages/                 ← Extra pages (CMS managed)
├── admin/
│   ├── index.html          ← CMS Panel
│   └── config.yml          ← CMS fields config
├── images/                 ← All images
└── components/
    ├── nav.js              ← Header + Footer
    └── style.css           ← All styles
```

---

## STEP 1 — GitHub Pe Upload Karo

1. **github.com** pe login karo (username: gmbconsult)
2. **"New repository"** click karo (+ icon top right)
3. Repository name: `wgmb-website`
4. **Public** select karo
5. **"Create repository"** click karo
6. "uploading an existing file" link click karo
7. **Saari files drag & drop** karo (sab select karke)
8. "Commit changes" click karo ✅

---

## STEP 2 — Netlify Se GitHub Connect Karo

1. **app.netlify.com** pe jao
2. Apna existing site kholo → **Site Settings**
3. **Build & Deploy** → **Link to Git**
4. **GitHub** select karo
5. **gmbconsult/wgmb-website** repo select karo
6. Branch: **main**
7. **Deploy** click karo ✅

---

## STEP 3 — Netlify Identity Enable Karo

1. Site Settings → **Identity** tab
2. **"Enable Identity"** button dabao
3. **Registration** → **Invite Only** set karo
4. **Git Gateway** → **Enable Git Gateway** dabao
5. Upar **"Invite users"** → Apni email daalo → Invite karo
6. Email mein link aayega → Password set karo ✅

---

## STEP 4 — Admin Panel Use Karo

1. Browser mein jao: `https://yoursite.netlify.app/admin`
2. Login karo apni email + password se
3. **Edit karo:**
   - ⚙️ Site Settings → Phone, email, address, stats, testimonials, FAQs
   - 📦 Products → Add/edit/remove products with images
   - 📄 Pages → Naye pages banao, menu mein auto-add
   - 🏠 Home Page → Hero text, images, video URL
4. **Save** karo → GitHub mein auto-commit → Netlify auto-deploy → **Live in 30 sec!** ✅

---

## Admin Panel URL
```
https://yoursite.netlify.app/admin
```

## Support
Call: 8962904124 | Email: support@gmbconsult.in
