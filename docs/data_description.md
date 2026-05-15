## Data Source

- **Platform**: Wenjuanxing (问卷星) online survey platform
- **URL**: https://www.wjx.cn
- **Collection Method**: Online questionnaire survey
- **Collection Date**: May 15, 2025
- **Number of Observations**: 200 rows
- **Number of Variables**: 33 columns

# Data Description and Codebook

## Overview

**Dataset**: survey_data.csv  
**Sample Size**: 200 respondents  
**Data Collection**: May 2025  
**Missing Data**: None  

---

## Variable List

### Demographic Variables

| Variable | Description | Type | Values |
|----------|-------------|------|--------|
| ID | Respondent ID | Numeric | 1–200 |
| Gender | Gender | Categorical | 1=Male, 2=Female, 3=Other |
| Age | Age group | Categorical | 1=Under 18, 2=18-25, 3=26-35, 4=36-45, 5=46+ |
| Occupation | Occupation | Categorical | 1=Student, 2=Employee, 3=Freelancer, 4=Civil Servant, 5=Self-employed, 6=Other |
| Income | Monthly disposable income (CNY) | Categorical | 1=<2000, 2=2000-5000, 3=5001-8000, 4=8001-12000, 5=>12000 |
| Shopping_Freq | Online shopping frequency | Categorical | 1=Almost daily, 2=2-3 times/week, 3=Once/week, 4=2-3 times/month, 5=Once/month or less |

---

### AI Recommendation Features (5-point Likert: 1=Strongly Disagree, 5=Strongly Agree)

| Variable | Description |
|----------|-------------|
| RA1 | AI recommendation systems can accurately identify my shopping needs |
| RA2 | AI-recommended products usually match my interests and preferences |
| RA3 | AI recommendation systems understand my shopping habits |
| RT1 | AI recommendation systems respond quickly to my browsing behavior |
| RT2 | Recommendation content updates immediately based on my real-time actions |
| RT3 | AI recommendations capture my current shopping needs in a timely manner |
| EI1 | AI recommendation systems make me feel warm and friendly |
| EI2 | AI recommendation copy and expressions resonate with me emotionally |
| EI3 | AI recommendation systems feel like communicating with a friend who understands me |

---

### Psychological Cognition (5-point Likert: 1=Strongly Disagree, 5=Strongly Agree)

| Variable | Description |
|----------|-------------|
| PP1 | I feel AI recommendations are customized specifically for me |
| PP2 | AI recommendations make me feel valued by the platform |
| PP3 | AI recommendation systems understand my unique needs |
| ER1 | AI-recommended products often touch my emotions |
| ER2 | I feel pleased when seeing AI-recommended products |
| ER3 | AI recommendations evoke emotional connections with products |
| PC1 | I worry that AI recommendation systems collect too much personal information |
| PC2 | AI recommendations make me feel my privacy is violated |
| PC3 | I feel uneasy about AI recommendation systems using my data |

---

### Dependent Variable (5-point Likert: 1=Strongly Disagree, 5=Strongly Agree)

| Variable | Description |
|----------|-------------|
| IB1 | I often buy products I did not plan to buy because of AI recommendations |
| IB2 | I often place orders immediately when seeing AI-recommended products |
| IB3 | AI recommendations make me feel "I need to buy it now" |
| IB4 | I buy AI-recommended products without sufficient consideration |

---

### Moderating Variable (5-point Likert: 1=Strongly Disagree, 5=Strongly Agree)

| Variable | Description |
|----------|-------------|
| IT1 | I am an impulsive person |
| IT2 | I often make impromptu decisions when shopping |
| IT3 | I find it hard to resist buying temptations |
| IT4 | I often shop on a whim |

---

## Composite Scores

| Score | Formula |
|-------|---------|
| Accuracy | Mean(RA1, RA2, RA3) |
| RealTime | Mean(RT1, RT2, RT3) |
| Emotional | Mean(EI1, EI2, EI3) |
| Personalization | Mean(PP1, PP2, PP3) |
| Resonance | Mean(ER1, ER2, ER3) |
| Privacy | Mean(PC1, PC2, PC3) |
| ImpulseBuy | Mean(IB1, IB2, IB3, IB4) |
| ImpulseTrait | Mean(IT1, IT2, IT3, IT4) |

---

## Data Quality

- Minimum response time: 60 seconds
- IP restriction: One response per IP
- All items required: No missing values
- Valid responses: 200/200

---

*Last Updated: May 2025*
