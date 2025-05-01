# Life Expectancy & GDP Analysis

![Life_GPD_Project](https://github.com/user-attachments/assets/e5afdcf9-bd0b-4714-95e3-0df13f0c9516)

## 📊 Project Overview

This project analyzes the relationship between GDP and life expectancy using data from the World Health Organization. Through data visualization and statistical analysis, I explore how economic development correlates with health outcomes across diverse economies from 2000 to 2015.

The findings have been compiled into a comprehensive analysis for the World Health Organization website, providing actionable insights for policymakers and health professionals.

## 🔍 Research Questions

- How has life expectancy changed over time in different countries?
- What is the relationship between GDP and life expectancy?
- Do wealthier countries always have higher life expectancy?
- How do economic crises impact health outcomes?

## 📋 Dataset

The analysis uses `all_data.csv` which contains:

| Column | Description |
|--------|-------------|
| Country | Name of the country |
| Year | Year of observation (2000-2015) |
| Life expectancy at birth (years) | Average life expectancy |
| GDP | Gross Domestic Product in USD |

### Countries Included:

- 🇨🇱 Chile
- 🇨🇳 China
- 🇩🇪 Germany
- 🇲🇽 Mexico
- 🇺🇸 United States of America
- 🇿🇼 Zimbabwe

## 📈 Visualizations & Key Findings

### 1. Life Expectancy Trends (Line Plot)

![Life Expectancy Trends by Country (2000-2015)](https://github.com/user-attachments/assets/d03bbc08-216a-42fa-b909-6d1f1fde66ba)


**Analysis:**
- All countries show generally positive trends in life expectancy from 2000-2015
- Zimbabwe demonstrates the most dramatic improvement, rising from ~46 to ~61 years
- Developed nations show a plateauing effect, with smaller incremental gains
- China shows consistent year-over-year improvements

### 2. GDP vs. Life Expectancy (Scatter Plot with Trend Lines)

![GDP vs Life Expectancy (2000-2015)](https://github.com/user-attachments/assets/0dae439b-cc9e-4769-a80a-d62557442cad)

**Analysis:**
- Positive correlation between GDP and life expectancy across most countries
- Zimbabwe's recovery from economic/health crisis is clearly visible
- Logarithmic relationship suggests diminishing returns - after a certain GDP threshold, life expectancy gains are minimal
- China shows simultaneous growth in both GDP and life expectancy

### 3. Country Comparison (Bar Plot)

![Life Expectancy by Country (2015)](https://github.com/user-attachments/assets/b741709e-d92a-49f0-852f-565d2e33e706)

**Analysis:**
- Despite having the highest GDP, the U.S. doesn't lead in life expectancy
- Germany and Chile outperform the U.S. in life expectancy despite lower GDP
- Zimbabwe shows the lowest life expectancy, correlating with its lower GDP
- Suggests that factors beyond GDP (healthcare systems, lifestyle, policy) significantly impact life expectancy

### 4. Multi-factor Analysis (Pair Plots)

![Pair Plot Analysis](https://github.com/user-attachments/assets/8467a097-5215-459a-ae0e-014f57df4868)


**Analysis:**
- Comprehensive view of relationships between year, GDP, and life expectancy
- Clear temporal patterns in both GDP and life expectancy
- Country-specific trajectories reveal unique development paths
- Distribution patterns highlight global inequality in both wealth and health outcomes

## 🧰 Technical Implementation

### Python Libraries
- **Data Visualization:** Seaborn, Matplotlib
- **Data Manipulation:** Pandas
- **Statistical Analysis:** NumPy

### Techniques Applied
- **Logarithmic scaling** (`plt.xscale('log')`) for handling the wide range of GDP values
- **Faceted visualizations** for multi-country comparative analysis
- **Color-blind friendly palettes** for accessibility
- **Tight layout optimization** (`plt.tight_layout()`) for presentation-quality figures
- **Regression analysis** to quantify GDP-life expectancy relationships

## 💡 Key Insights

1. **Economic development generally correlates with increased life expectancy**, but with diminishing returns at higher GDP levels

2. **GDP alone doesn't determine health outcomes** - countries with similar economic status can have different life expectancies

3. **Economic and political crises have quantifiable impacts on population health**, as demonstrated by Zimbabwe's data

4. **Developing economies can achieve significant health improvements** even with modest GDP growth through targeted policy interventions

## 🌟 Personal Development

This project enhanced my skills in:

- Data wrangling and transformation using Pandas
- Creating publication-quality visualizations with Seaborn and Matplotlib
- Implementing statistical analysis to derive meaningful insights
- Technical writing and data storytelling for non-technical audiences
- Advanced visualization techniques:
  - Log-scale transformations for skewed data
  - Multi-variable relationship visualization
  - Layout optimization for complex figures
  - Annotation techniques for highlighting insights

## 🔮 Future Work

Potential extensions of this analysis include:

- Incorporating additional health metrics (infant mortality, healthcare access)
- Expanding the country sample for more comprehensive global insights
- Including demographic factors (age distribution, urbanization)
- Time-series forecasting for projecting future trends

## 📝 Conclusion

This analysis demonstrates the complex relationship between economic development and health outcomes. While GDP is an important factor in life expectancy, other considerations such as healthcare policy, lifestyle factors, and political stability play crucial roles.

The findings support targeted development strategies that prioritize both economic growth and healthcare initiatives to maximize population health outcomes.

## 🔗 Resources

For a complete analysis and interactive visualizations, please visit my article on the [My blog][(https://example.who.int/gdp-life-expectancy-analysis)](https://medium.com/@loudiern.tharon.pro/the-gdp-life-expectancy-connection-what-global-data-reveals-about-our-health-e9dd0becfe22).

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.
