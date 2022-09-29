---
layout: archive
permalink: /Global_Data_Analysis/
title: "Global Data Analysis"
author_profile: false
---
An essential part of the Gender Profit gaps project is understanding the global business and policy environment for women-owned enterprises (WOE). Having this information will help contextualize the country-level data that is being collected and prepared. This is done through analyzing and manipulating large global datasets like the [World Bank Women, Business, and Law (WBL)](https://wbl.worldbank.org/en/wbl) survey and [UCLA Gender Data](https://ph.ucla.edu/research/centers/world-policy-analysis-center). The specialty of the datasets is that they span almost 50 years, with the WBL data going from 1971 to 2020 and the UCLA data going from 1995 to 2013. They have 197 observations- for every country in the world. The datasets ask questions that assess the constraints that women in the workplace face in different countries. Some example questions are if they get maternity leave, if they can breastfeed at work, if they can travel outside the country, if they can become heads of the household, etc. These variables were then divided into five constraint categories as shown below with an example for reference.

| Constraint | Example | 
|:------------------------:|:----------------------------------------------------------:|
| Labor Constraint         | Is paid leave of at least 14 weeks available to mothers?   | 
| Capital Constraint       | Does the law prohibit discrimination in access to credit based on gender? |
| Productivity Constraint  | Does the law mandate equal remuneration for work of equal value? | 
| Market Access Constraint | Can a woman register a business in the same way as a man? |
| Entry Constraint         | Does the law prohibit discrimination in employment based on gender? | 


Using the programming language Stata we were able to merge the WBL and UCLA datasets and create indices of the different constraints women face i.e. a number assigned to each country that reflects the barriers for women. The larger the number, the higher the barriers. We were then able to create a slider map using Python where sliding the marker down shows how barriers for women have changed over time globally. The map is color-coded where the darker colors indicate higher barriers. This allows us to represent our findings visually and check how trends have changed over time. We can then use this information to see whether the gender profit gap has changed accordingly or hone in on particular countries.

The maps for 1971 and 2020 are shown below:

