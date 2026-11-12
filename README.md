# Informatika viktorina (Vercel + Supabase Realtime + Gemini)

## 1. Supabase (bepul, jadval kerak emas)
1. supabase.com → New project.
2. Project Settings → API: **Project URL** va **anon/publishable key** ni nusxalang.
   (Realtime sukut bo‘yicha yoqilgan; Broadcast/Presence uchun jadval yaratish shart emas.)

## 2. Gemini kaliti
aistudio.google.com/apikey → Create API key.

## 3. Vercel
Loyihani GitHub’ga yuklang → vercel.com → Add New Project → import. Framework: "Other".
Environment Variables:
- GEMINI_API_KEY   – Gemini kaliti
- SUPABASE_URL     – Supabase Project URL
- SUPABASE_ANON_KEY – Supabase anon/publishable key
- TEACHER_PASS     – mentor paroli (savol yaratishni begonalar ishlatmasligi uchun)
- GEMINI_MODEL     – ixtiyoriy (standart: gemini-2.5-flash)

Deploy qiling. Tayyor: mentor sahifani ochib "Mentor" → sinf → mavzu; o‘quvchilar o‘sha havolada "O‘quvchi" → kod + ism.

Eslatma: tizim 30–40 o‘quvchigacha qulay. Mentor brauzeri o‘yin davomida ochiq qolishi kerak (o‘yin holati shu yerda turadi).
