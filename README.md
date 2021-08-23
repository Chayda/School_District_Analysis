# School_District_Analysis
Analysis of test scores by school district using Python and Jupyter Notebook

## Overview:
### The purpose of this analysis was to replace the grade nine math and reading scores for one of the schools in the dataset – Thomas High School (THS) – with NaNs, due to evidence of academic dishonesty among this group. The school district analysis code was utilized, refactored, and re-run, with the Thomas High School ninth grade scores removed.

## Results:

•	The overall school district summary didn’t appear to be affected very much by the removal of the grade nine THS scores; however, the scores for Thomas High School were affected as per below:

### District summary prior to removal of THS grade 9 scores:
![district_summary](https://user-images.githubusercontent.com/74624855/130458161-7cd485c1-dfe0-4e42-8515-a40ef9b46987.png)

### District summary after removal of THS grade 9 scores:
![district_summary_NaNs](https://user-images.githubusercontent.com/74624855/130458190-5cfeee54-7d61-4714-9854-b0931678a784.png)


•	The school summary for Thomas High School saw the percentages of passing grades in math and reading go up with the removal of the grade nine scores. Prior to the removal of the 9th grade scores, the Overall Passing percentage for THS was 65.08%. With the removal of the 9th grade scores, the overall passing jumped to 90.63%, which is a significant increase.

### Summary by School prior to removal of THS grade 9 scores:
![school_district_summary_original](https://user-images.githubusercontent.com/74624855/130458531-a18a3510-7a13-42aa-a4fd-f08f831dd45a.png)

### Summary by School after removal of THS grade 9 scores:
![school_district_summary_NaNs](https://user-images.githubusercontent.com/74624855/130458522-37dd1ad1-d5ca-4ac0-86f5-888c06b48105.png)


•	Replacing the 9th grader’s math and reading scores significantly raised the overall passing averages for Thomas High School, and put this school as one of the top five schools, a category it was not a part of in the original dataset. 

### Top five schools after removal of THS grade 9 scores:
![NaNs_top_five_schools](https://user-images.githubusercontent.com/74624855/130458548-e45b79c9-976c-43e7-aff6-40bee69e9796.png)

### Bottom five schools after removal of THS grade 9 scores:
![NaNs_bottom_five_schools](https://user-images.githubusercontent.com/74624855/130458555-a885cb95-cd3c-4c8c-a8b7-be6dc01c01a0.png)


### Replacing THS 9th grade scores affected the following:
•	Math and reading scores by grade were not affected, as THS 9th grade scores were omitted but the remainder of the dataset stayed intact.
•	Scores by school spending were not drastically affected. The range $585-629 had an original overall passing of 81% and with the THS grade 9s removed brought this spending bin to 90%. This is the only spending bin that had a noticeable change.
•	There wasn’t much of a difference in scores by school size.
•	Scores by school type also didn’t show much of a difference. Overall, the Charter schools had a higher overall passing percent than the district schools. THS is a charter school, but changing the data for this one school didn’t have a lot of weight on the overall passing for charter schools in general. 

## Summary:

1.	Thomas High School was moved into the top five schools for overall passing percent, where it originally sat in the middle of the dataset.
2.	The top five schools were all charter and the bottom five schools were all district school types.
3.	Scores by grade were pretty consistent across, but when compared with overall passing percentages, which would indicate a larger standard deviation in the schools with lower overall passing percentages.

