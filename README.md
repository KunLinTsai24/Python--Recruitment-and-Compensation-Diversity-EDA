# Recruitment and Compensation Diversity EDA

## Summary
* In response to growing emphasis on workplace diversity, our company undertook a comprehensive analysis to assess its current diversity landscape. The primary objectives were to identify the most effective recruiting sources for diversity, uncover potential pay inequities, and evaluate the organization's overall diversity profile concerning race, gender, and age. Data visualization played a pivotal role in this analysis. Bar plots revealed wage disparities by gender in specific departments, with women in the Software Engineering department earning more on average, albeit with a smaller sample size. Scatter plots highlighted pay rate variations in the Admin Offices and Software Engineering departments. Age diversity was depicted using distribution plots, indicating a concentration of employees in their late 30s to early 40s. Histogram showcased gender distribution across recruitment sources and departments, revealing sources like newspaper/magazine and Indeed as more favorable for recruiting women. Key findings included Diversity Job Fair emerged as a cornerstone in diversifying Dental Magic. At IT/IS, people of two or more races are paid significantly less than other workers in the same job position. Women constituting 60% of the workforce, yet earning less on average than men. Most workers aged 60+ in Production work at lower-paid positions.

## Introduction
* In the contemporary business landscape, there's a growing emphasis on fostering diversity and inclusion within organizations. Our company, like many others, recognizes the myriad benefits of a diverse workforce, from enhanced creativity to better financial performance. However, there have been concerns raised, both internally and from external stakeholders, about the current state of diversity within our organization. Questions have emerged about the effectiveness of our recruiting sources in promoting diversity, potential pay inequities across different departments, and the overall diversity profile of the company. Given the importance of these issues, both from an ethical standpoint and for the company's long-term success, there was a pressing need to conduct a comprehensive diversity analysis, focusing on race, gender, and age.

## Project Requirement

The main purposes of this project are: <BR>

* What are our best recruiting sources if we want to ensure a diverse organization?
* Are there areas of the company where pay is not equitable?
* What is the overall diversity profile of the organization?

We will be analyzing each matter with regard to race, gender, and age.

## Process Outline
### Racial Diversity

![](https://github.com/KunLinTsai24/Recruitment-and-Compensation-Diversity-Report/blob/main/img/Racial%201.jpg)
* Unsurprisingly, the Diversity Job Fair plays a crucial role in promoting racial diversity. Indeed and On-campus Recruiting can also be lauded for bringing non-white employees more often than not.
* On the other hand, Pay Per Click, On-line Web applications, CareerBuilder, and Company Intranet have no contribution to racial diversity at all.

![](https://github.com/KunLinTsai24/Recruitment-and-Compensation-Diversity-Report/blob/main/img/Racial%202.jpg)
* There are a few differences in median and mean payment across races. For instance, Hispanics are placed a bit higher.

![](https://github.com/KunLinTsai24/Recruitment-and-Compensation-Diversity-Report/blob/main/img/Racial%203.jpg)
* The plot reveals that employees of two or more races group are actually being paid less than colleagues in the same position. This could be the result of discriminatory practices. Let’s investigate further to see if there are any reasonable causes for the wage gap:

![](https://github.com/KunLinTsai24/Recruitment-and-Compensation-Diversity-Report/blob/main/img/Racial%204.jpg)
* The performance and tenure of two or more races of employees are rather leveled with that of colleagues in the same position, yet their pay rates are lower than any other. As far as the dataset goes, this points to the existence of discrimination.

### Gender Equality

![](https://github.com/KunLinTsai24/Recruitment-and-Compensation-Diversity-Report/blob/main/img/Gender%201.jpg)
* In the plot, we identify some divergences in average pay by gender. Women’s average pay is quite high in the Software Engineering department. However, it is important to note that only a handful of employees work there, in such a way that it doesn’t affect the overall statistics so much.
* On the other hand, Production plays a big part in broadening the wage gap because the department has the lowest pay rate; since it contains the largest number of workers, most of them being women, this decreases female mean compensation by a lot; considering the employee amount, even though the inequality within Production itself isn’t great, it ends up making a significant impact.
* We can see a substantial wage gap at Admin Offices; there, women’s average income is much lower than men’s.

![](https://github.com/KunLinTsai24/Recruitment-and-Compensation-Diversity-Report/blob/main/img/Gender%202.jpg)
![](https://github.com/KunLinTsai24/Recruitment-and-Compensation-Diversity-Report/blob/main/img/Gender%203.jpg)
* An in-depth analysis reveals that the wage disparity at Admin Offices, the largest throughout departments, comes from the presence of two men working in a high-paid position (shared services manager), contrasted with three women employed as administrative assistants.
* Among those whose title is Accountant I, the female employee’s pay rate is only marginally lower than that of a male colleague. We can also see that only women work as Sr. Accountants, which shows that females aren’t necessarily kept away from higher positions in this department.

![](https://github.com/KunLinTsai24/Recruitment-and-Compensation-Diversity-Report/blob/main/img/Gender%204.jpg)
![](https://github.com/KunLinTsai24/Recruitment-and-Compensation-Diversity-Report/blob/main/img/Gender%205.jpg)

* We now see that a male is an outlier.
* He is the manager of the department, but his pay is registered as the lowest one. It is highly unlikely that his pay rate is lower than his subordinates’. Also, the data doesn’t point to bad performance. It might be sensible to assume that this piece of information is actually incorrect, possibly due to input error.

### Age Diversity

![](https://github.com/KunLinTsai24/Recruitment-and-Compensation-Diversity-Report/blob/main/img/Age%201.jpg)
* Monster.com, and Search engine score the highest, hiring 4 mature employees, followed by Billboard, with 2. The numbers are really low, in such a way that no source is currently bringing a reasonable amount of older people to the company.
* Age diversity is not truly promoted by any recruitment source. The organization should review its hiring practices to remove any potential bias.

![](https://github.com/KunLinTsai24/Recruitment-and-Compensation-Diversity-Report/blob/main/img/Age%202.jpg)
* The graph clarifies that it is generally not the case that older workers are getting a lower salary than their position’s average. Matures’ pay rates are limited because almost all of them work in lesser functions (Production Technician I and II).


## Result
**1. Which sources yield the best results for recruiting a diverse workforce?**

* An evaluation has shown that participating in the Diversity Job Fair is crucial for enhancing Dental Magic's diversity and should be further promoted. Most hires from Indeed and college recruitment initiatives belong to minority groups, whereas other sources predominantly attract Caucasian candidates, which warrants further investigation.

* The company falls short in achieving age diversity, with no recruitment source standing out in this regard.

**2. Does the company have any pay equity issues?**

* Within the IT/IS department, multiracial employees receive considerably less pay compared to their peers in the same roles, with no clear reason for this disparity.

* Overall, women earn less, especially in Production where they are the majority, and in Administrative roles where a significant gender pay gap exists. Moreover, employees over 60, particularly in Production, tend to hold lower-paying jobs.

**3. What does the diversity profile of the company look like?**

* Racially, whites are a majority, but job distribution among minorities is more equitable than national averages. Hispanics earn slightly more on average, while Native Americans or Alaska Natives earn less, although this is based on a small sample and cannot be definitively attributed to discrimination.

* Gender-wise, the company employs predominantly women, including its CEO, which is noteworthy in an employment landscape that typically favors men for leadership roles. The high number of women in Production is also significant. However, the company must address the gender pay gap that still exists.

* Age diversity is lacking, with only 5.2% of employees aged 60 or above, which is low compared to national figures. This is particularly concerning in the Software Engineering and Administrative departments with minimal representation of employees over 45, while the Sales department shows a better inclusion of older, well-compensated employees.


