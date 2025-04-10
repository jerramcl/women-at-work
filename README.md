# Gender Disparities in the Workplace 

<p align="center">
  <img src="https://github.com/user-attachments/assets/4de0eb73-d820-4f6c-967c-dcfad09fac86" alt="download" />
</p>

Despite decades of progress toward gender equity, significant disparities in earnings and leadership representation persist—particularly for women of color and women with advanced degrees. This study explores the complex dynamics shaping women’s economic and professional trajectories using data from the 2021 **National Survey of College Graduates (NSCG),** a dataset maintained by the National Science Foundation (NSF) that provides comprehensive information on the education, employment, and demographic characteristics of individuals with a bachelor’s degree or higher in the United States.

This project investigates:
1. Which sector and occupations have the largest salary gaps between men and women?
2. How do men’s and women’s salary differentials vary throughout their careers?
3. How do educational attainment and racial identity affect women’s leadership status?

## Findings
### Salary Regression Analysis
I used a multivariate linear regression model to examine wage differentials by gender within the business sector, controlling for years at a job, partnered status with children, professional training, and education level.
- Women earn approximately **84%** of what men earn, holding other factors constant.
- Job tenure improves salary by **1%** per year.
- Partnered women with children earn **14% more**, possibly due to selection or institutional support factors.
- Professional training adds about 2.5% to salary.
- Higher education is associated with higher earnings, and working in the business sector boosts salary by **1.36%.**
- An interaction term between gender and the business sector revealed that **while the sector raises wages overall, women benefit less than men**, amplifying the gender wage gap within business.

Note: All results are statistically significant at the 5% level, and VIF checks confirmed low multicollinearity.

### Leadership Representation Analysis 
I used a logistic regression model to explore the likelihood of women holding leadership roles. It is important to note that the definition of “leadership” includes all levels, from mid-level managers to executives, potentially diluting patterns in top-tier roles. Future analyses should disaggregate C-suite and senior leadership positions to sharpen insights.

- 44% of all leaders are women, but **only 33% of C-suite executives are women, compared to 70% in lower-paying managerial roles.**
- Years at job is statistically significant, but the effect size is minimal.
- Partnered with children positively predicts leadership status.
- Professional development (wrktrni) is not a significant predictor.
- Compared to White women:
    - Hispanic women are significantly more likely to hold leadership roles.
    - Other racial groups show positive but non-significant relationships.
- Compared to those with Bachelor’s degrees:
    - Women with Doctorate or Professional degrees are less likely to hold leadership roles (statistically significant).
    - Those with Master’s degrees have a positive but non-significant association.

### Career Trajectory Insights
- The gender pay gap **widens** over time: women’s earnings grow more slowly than men’s as they age.
- Longer tenure helps salary, but **women experience less gain** from this over time.

## Conclusion
This project reveals deep-seated gender disparities in both earnings and leadership access across sectors. Women face systemic barriers that limit both salary growth and upward mobility, even in high-paying sectors like business.

## Recommendations
1. Prioritize Pay Transparency
  - Conduct regular audits of salary by gender, race, and tenure
  - Implement clear, transparent compensation and promotion policies
2. Provide Targeted Support
  - Develop mentorship, sponsorship, and leadership training programs for women
  - Design sector-specific initiatives, especially in business, where disparities are most pronounced

















The code and NSCG dataset are linked in files above. 
