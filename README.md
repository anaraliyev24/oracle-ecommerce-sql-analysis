🛒 Oracle SQL: E-Ticarət Satış Analizi Layihəsi
Bu layihədə Oracle SQL vasitəsilə mini e-ticarət sisteminin verilənlər bazası modelini qurmuşam və real biznes ssenarilərinə uyğun analitik sorğular hazırlamışam. 

🛠 Verilənlər Bazası Modeli
Layihə bir-biri ilə əlaqəli 4 əsas cədvəldən ibarətdir:


customers: Müştəri məlumatları. 


products: Məhsul siyahısı və qiymətlər. 


orders: Sifarişlərin qeydiyyatı. 


order_items: Sifarişlərin detalları. 

📈 Əsas Analitik Sorğular və Nəticələr
Layihə çərçivəsində aşağıdakı biznes analizləri aparılmışdır:

1. Müştəri Seqmentasiyası
Müştərilər xərclərinə görə VIP, Regular və New kateqoriyalarına bölünüb. 


VIP müştərilər: 2000 AZN-dən çox xərcləyənlər. 

2. Satış Trendləri (2024)
Yanvar ayından Mart ayına doğru satışlarda davamlı artım trendi müşahidə olunur. 


Mart ayı ən yüksək satış olan aydır. 

3. Məhsul və Kateqoriya Analizi

Dominant Kateqoriya: Electronics bölməsi ümumi satışın 70%-dən çoxunu təşkil edir. 


Top 3 Məhsul: Laptop Dell, iPhone 14 və Samsung TV ən çox gəlir gətirən məhsullardır. 


Orta Sifariş Dəyəri (AOV): Təxminən 1,131 AZN. 

🚀 İstifadə Olunan Texnologiyalar
Database: Oracle SQL


Analitik Funksiyalar: RANK(), SUM() OVER(), CASE WHEN, WITH (CTE).
