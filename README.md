# FIFA 22 Player Analysis 🎮⚽

## Overview
An end-to-end data analysis project on the FIFA 22 
complete player dataset exploring what factors 
affect a player's Overall rating.

## Dataset
- Source: Kaggle — FIFA 22 Complete Player Dataset
- 19,000+ players
- 100+ original features

## Objectives
- What is the distribution of player ratings?
- Do physical attributes like Age, Height, 
  Weight affect Overall rating?
- Do financial features like Value and Wage 
  reflect a player's rating?
- Do skill attributes like Pace, Shooting, 
  Passing, Dribbling, Defending and Physic 
  affect Overall rating?
- Does positional versatility affect rating?

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Project Structure
- Data Preparation
  - Feature selection
  - Missing value handling
  - Feature engineering (Is_Loaned, 
    Position_Count, Value_Wage_Ratio)
- Exploratory Data Analysis
  - Univariate Analysis ✅
  - Bivariate Analysis (ongoing)

## Key Findings — Univariate Analysis

### Overall Rating
- Most players are rated between 60-65
- Distribution is right skewed with very 
  few elite players

### Physical Features
- Age is right skewed — most players are 
  between 20-25 with one active player aged 54
- Height and Weight are normally distributed
- No abnormal physical values found

### Financial Features
- Market Value and Wage are heavily right 
  skewed — log transformation applied for 
  correlation analysis
- Most players valued between 525k to 2.1M EUR
- Most players earn between 1k to 9k EUR weekly

### Skill Features
- Pace — left skewed, Kylian Mbappe highest at 97
- Shooting — bimodal distribution, CBs average 
  37 vs non-CBs average 57, Ronaldo highest at 94
- Passing — normally distributed, 
  De Bruyne highest at 93
- Dribbling — slightly left skewed, 
  Messi highest at 95
- Defending — bimodal distribution, defenders 
  average 62 vs non-defenders average 50, 
  Van Dijk highest at 91
- Physic — approximately normal (skew = -0.45), 
  Casemiro highest at 90

### GK Analysis
- All 2132 GK players analyzed separately
- GK Overall distribution mirrors outfield players

## Status
🔄 In Progress — Bivariate Analysis ongoing
