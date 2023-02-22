# Online Education: Trial Class Conversion

An online edtech company offers English classes for kids. It has free trial classes for potential students. Some of them later purchase a full course.

## Main problem
We need to determine factors that affect conversion from a trial class into a purchase. 

## Data
50k entries with 20 features for April-May 2019.

## Analysis

1. Data grouped by parents to maintain observations' independence
2. Core features identified
3. Observations split into "purchasers" (group 1) and "non-purchasers" (group 0)
4. Two groups compared across core features to find statistically significant differences using A/B tests (t-test for mean, proportions test for percentages)

## Results

Two groups have shown differences in:
* desktop vs mobile devices usage
* kids' age
* preferred study topics
* booking time.  

For each difference, a business-related explanation was suggested with a course-of-action component.  
Features that showed no statistically significant results received attention too.  
Results have been wrapped up in a presentation for management decision making.

## Links
**Code**: <a href='https://github.com/AntonBizyaev/online_ed_conversion/blob/main/online_ed_conversion.ipynb'>jupyter notebook</a>  
**Presentation**: <a href='https://github.com/AntonBizyaev/online_ed_conversion/blob/main/edtech_results.pdf'>main results</a>
