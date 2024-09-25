# Optimizing Anti-Doping Strategies: Analysis of USADA Sanctions (2014-2024)

## 1. Background and Overview

### Project Context:
This project analyzes doping violations in sports using data from the United States Anti-Doping Agency (USADA). The data encompasses sanctions from 2014 to 2024, focusing on American athletes and international athletes tested/sanctioned by USADA on US soil. The project aims to explore trends in doping violations, identify key patterns, and present actionable insights to drive further anti-doping education.

### Main Goal:
To uncover the drivers and relationships behind doping violations across various sports, substances, and years, ultimately informing strategies to reduce positive doping cases.

### Key Metrics (North Star KPIs):
- Number of sanctions per year.
- The most common substances leading to doping violations.
- Sports with the highest number of sanctions.

### Data Sources:
Data was scraped from USADA’s official sanctions page using Python libraries such as requests and BeautifulSoup. The data includes fields like athlete name, sport, substance or reason for the sanction, sanction terms, and the date of announcement.

### Tools Used:
- Python (Pandas, BeautifulSoup, Requests, Matplotlib, Numpy, Seaborn) for data scraping, cleaning, and analysis.
- Tableau for data visualization.

---

## 2. Data Structure Overview

### Dataset Summary:
The dataset consists of key columns:
- `athlete_name`: Name of the sanctioned athlete.
- `sport`: Sport associated with the athlete.
- `substance_or_reason`: Reason for the sanction (e.g., substance used).
- `sanction_announced`: Date when the sanction was announced.
- `sanction_term`: The length and terms of the sanction.

_Include a picture of data_

---

## 3. Executive Summary

### Key Insights Summary:
1. **Sanctions by Sport**: Cycling, Track and Field, and Weightlifting emerged as the sports most impacted by doping violations.
2. **Substance Violations**: Androgenic Anabolic Steroids were the most common substances leading to doping sanctions, with trends becoming clearer after grouping it with substances like Testosterone and Stanozolol. Cannabinoids were the second most common reason for suspensions.

### Dashboard Overview:
The dashboard highlights key trends, including a steady decrease in positive tests since 2018.

### Key Performance Metrics:
- **Year with the most sanctions**: 2018, with 86 violations.
- **Substance trends**: Androgenic Anabolic Steroids accounted for the highest number of violations.
- **Year-over-year reduction**: Positive tests dropped from 86 in 2018 to 44 in 2023, marking a 48.8% decrease.

---

## 4. Insights Deep Dive

- **Cycling and Track & Field - Leading in Doping Violation**
  - **Quantified Value**: In 2018, there were 86 positive doping tests, the highest number in the dataset.
  - **Business Impact**: This spike potentially means that stronger education efforts should have been targeted during this period.
  - **Historical Trend**: Sanctions have steadily decreased since 2018, potentially suggesting successful anti-doping education or better adherence by athletes.
  - **Sport**: Cycling and Track and Field contributed significantly to the spike in violations during this period.

- **Cannabinoids**
  - **Quantified Value**: Although cannabinoids are only banned in competition, they remain a common cause of doping violations.
  - **Business Impact**: Educating athletes on the in-competition ban, the substance's clearance rate from the body, and its impact on recovery could lead to fewer violations.
  - **Historical Trend/Story**: Violations involving cannabinoids persist, especially in sports where athletes may use them for pain relief, indicating a gap in awareness.
  - **Target Certain Sports**: Sports like combat and endurance disciplines, where pain management is critical, could benefit from targeted educational efforts on cannabis use and its risks.

- **Anabolic Steroids - The Most Abused Substance:**
  - **Quantified Value**: Anabolic Steroids (including Testosterone and Stanozolol), accounted for a large portion of the violations.
  - **Business Impact**: Targeting education around these substances could help reduce future violations.
  - **Historical Trend**: Anabolic Steroid use has remained a consistent issue, with variations across sports.

---

## 5. Recommendations

1. **Educate athletes about cannabinoids**:
   - Focus on educating athletes about the rules around cannabinoid use, especially the differences between in-competition and out-of-competition bans. Provide guidance on how body composition affects the clearance of the substance from the system.

2. **Raise awareness of potential health risks of steroids**:
   - Increase educational efforts on the negative long-term health effects of steroid use.

3. **Whereabouts management education**:
   - Promote tools or practices for better whereabouts management (e.g., having teammates or coaches check the accuracy of location entries) to avoid sanctions due to missed tests.

4. **Promote third-party certified supplements**:
   - Encourage athletes to use third-party certified supplements to avoid unintentional doping violations due to contaminated products.

5. **Focus on high-violation sports**:
   - Target education efforts specifically toward athletes in sports like Cycling and Track and Field, which are consistently among the top sports for doping violations.

---

## Optional: Caveats and Assumptions
- **Data limitations**: The data only includes sanctions overseen by USADA, which may not represent the global scope of doping violations.
- **Assumptions**: The classification of substances such as combining 'Testosterone' and 'Stanozolol' under the broader 'Androgenic Anabolic Steroid' category was made to streamline analysis.
