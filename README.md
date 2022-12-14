# PyCity_Schools

## Project Overview
The purpose of this analysis was to investigate a claim of academic dishonesty within the district. It was suspected that the math and reading grades for the ninth grade class of Thomas Highschool were altered. In this notebook I went over the data for all the high schools in the district and turned all the ninth grade data from Thomas Highschool into a NaN values, as well as repeated the analysis to get a better idea of the overall affect it had on the district. 

## Project Results
While looking over the data and the reformatted data frames, I have come to a couple of conclusions,

* The first is that charter and district schools don't have many differences in performance, execpt for charter schools beating out district schools in math as seen below:

![school_type_summary](https://github.com/lrngdtascinc/PyCity_Schools/blob/0249598189ef532149271185407a06162933e39e/school_type_summary.png)

* Then if we start looking at the budget each school has available, we can see huge differences. Charter schools seem to have a smaller budget compared to District schools, this can because of the amount of students in charter schools is significantly less than District schools. But if we look at the Budget Per Student, we see that Charter schools seem to spend less per student when compared to District schools:

![per_school_summary](https://github.com/lrngdtascinc/PyCity_Schools/blob/472735e6d9e66b4c4441e8a2c0dc5cf5f2576913/per_school_sum.png)

* So considering that Thomas HIghschools 9th grade classes math and reading scores we're converted to Nan values, the small class size on Thomas Highschools 9th grade, and that they're a Charter school we can conclude that the overall analysis was not effected much by the NaN values.  

## Summary
All in all although academic dishonesty was suspected, we can see that after converting Thomas Highschools 9th grade class math and reading scores it didn't seem to knock the school from being in the top five schools based on overall students passing. We can also see that, even though the 9th grade class was excluded it still did not turn the numbers in favor of district schools, so although there might be a slight difference, because of the small size of the 9th grade class compared to the other years, the difference wasn't significant enough the create any wild cahnges in the data.
