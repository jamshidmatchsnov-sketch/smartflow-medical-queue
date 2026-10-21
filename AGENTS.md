# SmartFlow qoidalari

## Manba
- Asosiy hujjat: docs/TZ.docx. Unga zid ish qilma.
- Loyiha BITTA shifoxona uchun. Tenant/ko'p shifoxona qismini qo'shma.

## Papkalar
- backend_api: NestJS + TypeScript + PostgreSQL + Socket.IO
- mobile_app: bemor PWA (React + Vite + TypeScript)
- web_admin: shifokor, registrator, administrator paneli (React + Vite + TypeScript)
- database_docs: migratsiyalar, seed, ER-diagramma, DB hujjatlari
- Lokal PostgreSQL docker-compose.yml orqali.

## Ish tartibi
- Avval REJA yoz, men tasdiqlamaguncha kod yozma.
- Bir vaqtda faqat bitta bosqich bilan ishla.
- Har bosqich oxirida testlarni ishga tushir va natijani ko'rsat.
- Har bosqichdan keyin git commit xabarini taklif qil.
- Tushunarsiz joyda taxmin qilma, savol ber.

## Texnik qoidalar
- Navbat va slot mantig'i faqat backend tranzaksiyasida (TZ 5 va 6-bo'lim).
- Secret'larni kodga yozma, faqat .env.example.
- UI matnlari o'zbek va rus tillarida (i18n fayllar).
- Faqat sun'iy (seed) ma'lumot ishlat, haqiqiy bemor ma'lumoti yo'q.

## BMI MVP chegarasi
- SMS provayderi mock (kod konsolga chiqadi).
- Push bildirishnoma va Redis keyingi bosqichga.