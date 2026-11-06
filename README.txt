OLOT MASLAHATCHILARI — boshlang'ich kirish sahifasi

1. index.html faylini matn muharririda oching.
2. PASTE_YOUR_PUBLISHABLE_KEY_HERE o'rniga Supabase > Settings > API Keys > Publishable key (sb_publishable_...) qiymatini qo'ying.
3. Faylni saqlang va ZIPni qayta yarating (index.html ZIP ildizida tursin).
4. Cloudflare > Upload your static files sahifasiga ZIPni yuklang va Deploy bosing.

Muhim: hech qachon secret/service_role keyni qo'ymang.
Login: olot_admin yoki Supabase Auth emaili. Parol Supabase Auth paroli.
Bu hozircha faqat kirish prototipi. Dashboard va rolga asoslangan ruxsatlar hali ishlab chiqilmagan.
Login taxallusi index.html ichida emailga bog'langan; keyinchalik xavfsiz server-side username lookup kerak bo'ladi.
Supabase RLS siyosatlarini tekshirmasdan maktab ma'lumotlarini ochiq ko'rsatmang.
