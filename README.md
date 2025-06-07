## 📊 Mexico Toy Sales - KPI Dashboard in Power BI ##

Welcome to my Power BI project based on the Mexico Toy Sales dataset! 🎉
The main goal of this project was to create a professional KPI report that provides clear insights into toy sales across different locations and categories.

1-st page
![image](https://github.com/user-attachments/assets/1f885700-f913-49fe-a85c-bfd229c989a4)

2-nd page
![image](https://github.com/user-attachments/assets/d75a3553-2680-4cf6-bd4e-f5e8edd4ada8)


📈 What’s inside?
This interactive dashboard includes:

✅ Key KPIs like Total Orders, Revenue, and Profit calculated using DAX Measures

📍 Filtering options based on Store Location (e.g., Airport, Commercial, Downtown, Residential)

🧸 Breakdown of orders by Product Category (Toys, Games, Electronics, etc.)

📅 Time trends showing Monthly Revenue & Profit

📊 Visually appealing charts and intuitive layout for ease of analysis

📌 Technologies
* Power BI
* DAX
* Data modeling & relationships

📂 Data Source:
Data has been taken from [Maven Analytics - Data Playground](https://mavenanalytics.io/data-playground) - "Mexico Toy Sales". 

🧠 Created by Karol Szeląg | 173223 (student index)


## DESCRIPTION IN POLISH

### 🟢 Strona 1 – Podstawowe KPI & Analiza sprzedaży

Na pierwszej stronie raportu przedstawiono kluczowe wskaźniki KPI oraz przegląd danych sprzedażowych:

#### 📊 Zawartość:
- **Total Orders** – łączna liczba zamówień  
- **Revenue** – suma przychodów (w tysiącach zł)  
- **Profit** – suma zysków (w tysiącach zł)  
- Wykresy trendów: zamówienia, przychód i zysk w ujęciu miesięcznym  
- **Top 5 kategorii produktów** wg liczby zamówień  
- **Wykres liniowy Revenue vs Profit by Month**  

#### 🧰 Dodatkowe funkcjonalności:
- Możliwość filtrowania danych według **lokalizacji sklepu** (`Store_Location`)  
- Profesjonalna wizualna forma i przejrzystość danych  

🟩 **Cel:**  
Szybki przegląd najważniejszych statystyk i identyfikacja najlepiej sprzedających się produktów oraz sezonowości sprzedaży.

---

### 🔵 Strona 2 – Prognoza i Dekompozycja zysku

Druga strona skupia się na analizie trendów i głębszym zrozumieniu źródeł zysków:

#### 📈 Wykres z linią trendu i prognozą:
- Pokazuje **dzienne przychody (`Total Revenue`)**
- Dodano linię trendu oraz prognozę na najbliższe dni
- Umożliwia wizualne przewidywanie przyszłej sprzedaży w oparciu o dotychczasowe dane

📘 _Opis:_  
Wizualizacja pokazuje sezonowość i zmienność przychodów w czasie, a funkcja prognozowania w Power BI pomaga w szacowaniu przyszłych wyników sprzedażowych.

#### 🌳 Drzewo dekompozycji:
- Analizowana miara: **Total Profit**
- Dekompozycja wg: `Product_Category`
- Pozwala szybko zidentyfikować, które kategorie generują największe zyski

📘 _Opis:_  
Dzięki drzewu dekompozycji można w łatwy sposób zrozumieć, które grupy produktów mają największy wpływ na zysk firmy. Najwyższe zyski generują **Toys** i **Electronics**.
