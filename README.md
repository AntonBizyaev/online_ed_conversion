# Online Education: Trial Class Conversion

An online edtech company offers English classes for kids. It has free trial classes for potential students. Some of them later purchase a full course.

## Problem
We need to determine factors that affect conversion from a trial class into a purchase. 

## Data
50k entries with 20 features for April-May 2019.

## Analysis

1. Data grouped by parents to maintain observations' independence
2. Core features identified
3. Observations split into "purchasers" (group 1) and "non-purchasers" (group 0)
4. Two groups compared across core features to find statistically significant differences using A/B tests (t-test for mean, proportions test for percentages)

## Results

1. “Purchasers” use desktop devices more frequently. An inquiry into company's mobile app is required, i.e. it could have technical issues, inefficient customer journey map ("too many clicks needed"), or unintuitive UI.

1. Purchases are more likely for parents with kids aged 3-4 and less likely for ages 5-7. The explanation could lie in "overtargeting" a specific audience at the company's website, i.e. customers using company's website might conclude that the courses are better suited for younger kids. Also this might be due to more factors competing for kids attention as they grow, which requires broader market competition analysis.

1. Topics 1418 and 1643 have higher probability of conversion while 1513 and 1310 - lower. This might be due to the latter having inconsistent curriculum or teachers' self-selection.

1. Bookings during Sundays are more likely to become a purchase while bookings during Thursdays are less so. Also, booking a trial class between 5 to 6 AM is less likely to achieve conversion. This could be attributed to using UTC timing without proper time zone segregation. Enriching the data with geography could further benefit the analysis.

Features that showed no statistically significant results received attention too.  
Results have been wrapped up in a presentation for management decision making.

## Links
**Code:** <a href='https://github.com/AntonBizyaev/online_ed_conversion/blob/main/online_ed_conversion.ipynb'>jupyter notebook</a>  
**Presentation:** <a href='https://github.com/AntonBizyaev/online_ed_conversion/blob/main/edtech_results.pdf'>main results</a>  
**Data:** <a href='https://github.com/AntonBizyaev/online_ed_conversion/blob/main/data.csv'>source</a>  
