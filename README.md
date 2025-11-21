
# Analysis and Visualization of Advertising Campaigns 2021

## Dataset

- ad_date
- campaign_name
- total_spend
- total_impressions
- total_clicks
- total_value
- cpc
- cpm
- ctr
- romi

## Technologies Used
- Python
- Pandas
- Seaborn
- Matplotlib
- Jupyter Notebook

## Data processing
- **Missing values:** (NaN) were replaced with 0
- **Date conversion:** date columns were converted to datetime format
- **Sorting:** data was sorted by date
- **Grouping:** data was grouped by date or campaign for analysis

## Visualizations
- **Line charts** - trends of spend and ROMI (aggregated by date)  
- **Bar plots** - trends of spend and ROMI (aggregated by campaign)  
- **Heatmap** - correlation analysis between metrics  
- **Boxplots** - distribution of ROMI by campaign  
- **Histograms** - comparison of values across groups  
- **Scatterplots with linear regression** - relationship between spend and revenue

# Аналіз рекламних кампаній
  ## Загальна динаміка витрат та ROMI
   - Витрати на рекламу протягом часу коливалися і були нестабільними.
   - ROMI у більшості періодів залишався стабільним, в середньому ~1.25
   - Найвища пряма кореляція спостерігається між витратами та доходом, проте ця залежність працює лише при **малих та середніх витратах.**
  ## Розподіл витрат за кампаніями
   - Основна частка бюджету зосереджена у кампаніях: **Lookalike, Electronics та Wholesale.**
   - Ці кампанії характеризуються стабільністю та середнім ROMI, з найменшим розкидом результатів:
       - Lookalike: 1.1 - 1.4
       - Wholesale: 1.1 - 1.3
       - Electronics: 0.9 - 1.4
   - Кампанія **Trendy** демонструє високу ефективність з ROMI у межах 1.6 - 2.1, при цьому ROMI досить стабільний.
   - Кампанія **Promos** також показує високий ROMI (1.75 - 1.85), але є значний розкид та наявність викидів.
  ## Висновки щодо ефективності кампаній
   - **Середній Romi та стабільність :** Lookalike, Wholesale, Electronics - мінімальний ризик, прогнозований результат.
   - **Високий ROMI, але ризикована:** Promos - вищі доходи, але з більшим розкидом та потенційними викидами.
   - **Високий ROMI та мінімум витрат:** Trendy - скоріш за все, запустили продукт чи акцію, яка користувалась високим попитом без додаткових витрат на залучення.
   - **Оптимізація бюджету:** інвестиції в Lookalike та Wholesale забезпечують стабільний прибуток, тоді як Trendy і Promos доцільно використовувати для підвищення доходу, але з контролем витрат, щоб уникнути падіння ефективності при високих витратах.
