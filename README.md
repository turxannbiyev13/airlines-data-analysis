# Airlines Flights Data Analysis (Project - 1)

Bu layihə aviaşirkətlərin uçuş məlumatlarını analiz etmək, datanı vizuallaşdırmaq və qiymətlərə təsir edən faktorları araşdırmaq üçün hazırlanmış bir Data Analitika layihəsidir.

## 📌 Layihə Haqqında
Məlumat bazası (dataset) aviaşirkətlərin uçuşları, bilet qiymətləri, uçuş müddətləri, biletin neçə gün əvvəl alınması və digər mühüm faktorları əhatə edir. Layihə çərçivəsində datanın təmizlənməsi (Data Cleaning), kəşfiyyat xarakterli analizi (EDA) və vizuallaşdırılması həyata keçirilmişdir.

## 📊 Dataset Strukturu
`df.info()` nəticəsinə əsasən, datada **39,048 sətir** və **14 sütun** mövcuddur:
- `index`: Unikal sətir nömrəsi
- `airline`: Aviaşirkətin adı
- `flight`: Uçuş nömrəsi
- `source_city`: Uçuşun başladığı şəhər
- `departure_time`: Uçuş vaxtı (səhər, günorta, axşam və s.)
- `stops`: Dayanacaqların (köçürmələrin) sayı
- `arrival_time`: Çatma vaxtı
- `destination_city`: Təyinat şəhəri
- `class`: Səyahət klassı (Economy / Business)
- `duration`: Uçuş müddəti (saatla)
- `days_left`: Uçuşa qalan günlərin sayı
- `price`: Biletin qiyməti
- `buying_time`: Biletin alındığı vaxt periodu
- `days_left_group`: Qalan günlərin qruplaşdırılmış forması (Kateqoriya)

## 🛠️ Data Təmizlənməsi Mərhələsi (Data Cleaning)
Layihədə yerinə yetirilən əsas təmizləmə addımları:
1. **Dublikatların Yoxlanması:** `df.duplicated().sum()` vasitəsilə tam təkrar sətirlər yoxlanılmışdır. Mövcud `index` sütununa görə sətirlər unikal göründüyü üçün, əsas biznes sütunları üzrə əlavə yoxlanışlar edilmişdir.
2. **Boş (Missing) Dəyərlərin Tapılması:** Sütunlardakı əksik dəyərlər (NaN) müəyyən edilərək təmizlənmiş və ya doldurulmuşdur.
3. **Data Tiplərinin Strukturlaşdırılması:** Sütunlar analizə uyğun olaraq `category`, `float64` və `object` tiplərinə gətirilmişdir.

## 🚀 İstifadə Olunan Kitabxanalar
Layihə Python proqramlaşdırma dilində və Google Colab mühitində yazılmışdır:
- `pandas` - Data manipulyasiyası və analizi
- `numpy` - Riyazi və massiv əməliyyatları
- `matplotlib` - Qrafiklərin qurulması
- `seaborn` - İnkişaf etmiş statistik vizuallaşdırma

## 📈 Əsas Analiz Sualları (EDA)
- Hansı aviaşirkətin biletləri daha bahadır?
- Uçuşa qalan günlərin sayı qiymətə necə təsir edir?
- Business və Economy klasslar arasında qiymət fərqi nə qədərdir?
- Dayanacaq sayı (stops) uçuş müddətinə və qiymətə necə təsir göstərir?

## 💻 Layihəni Lokal Kompüterdə İşə Salmaq

1. Repozitoriyanı klonlayın:
   ```bash
   git clone [https://github.com/turxannbiyev13/airlines-data-analysis.git](https://github.com/turxannbiyev13/airlines-data-analysis.git)
