# School_District_Analysis
Anaconda: Jupiter Notebook

## Challenge Overview

### Purpose:
   There is evidence of academic dishonesty of reading and math grades for Thomas High School ninth graders. The grades appear to have been altered. The purpose of this analysis is to help Maria replace the math and reading scores for Thomas High School ninth graders with NaNs so the school board can uphold state-testing standards.
	
	
	
## Results: 

**1. How is the district summary affected?**

   > The only thing that had to be changed was the total number of students because we had to substract the number of students that were in ninth grade at Thomas High School from the total student count. We used the new total student count to recalculate the math, reading passing percentages, and also the overall passing percentage. This slightly lowered the average math score and the math, reading, and overall passing percentages.
    
![1 District Summary](https://user-images.githubusercontent.com/89308251/133859142-c42d9880-07a4-44c3-a164-7497f0be18d2.png)

 
 
**2.  How is the school summary affected?**

   > The result of the school summary that excluded the 9th grade of Thomas High School hasn't affected that much at all from the previous data. The things have changed are that the average of reading scores is slightly higher, the average of math scores and the percentages of passing math and reading including overall passing percentage are slightly lower from before.
    
![2 School Summary](https://user-images.githubusercontent.com/89308251/133859168-8f51b889-ef3b-42d0-9623-4d99e8569ce6.png)
    
	
  
**3. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**

   > Replacing the ninth graders’ math and reading scores did not affect Thomas High School’s performance relative to the other schools because Thomas High School is still the 2nd place in the top five high schools after the data of Thomas High school changed by excluding 9th grade.

![3 top_five_school](https://user-images.githubusercontent.com/89308251/133859181-f89fd268-860c-45fd-90ab-b78628ff2f1c.png)



**4. How does replacing the ninth-grade scores affect the following:**


- Math and reading scores by grade
        
	- > Replacing the ninth-grade scores only affected the 9th grade scores of Thomas High School. It now shows "nan", or empty data. It did not affect other grade levels in the same school.
	
![4 1_Math_Reading_Scores_by_Grade](https://user-images.githubusercontent.com/89308251/133859231-3008c240-b629-4d4a-b133-c070dd82728c.png)


- Scores by school spending
    
	- > Replacing the ninth-grade scores did not affect anything by school spending.
	
![4 2_Scores_by_School_Spending](https://user-images.githubusercontent.com/89308251/133859235-c0036659-59ee-41df-8d2d-f992f00f9165.png)
    
    
- Scores by school size
    
	- > Replacing the ninth-grade scores did not affect anything by school size.

![4 3_Scores_by_School_Size](https://user-images.githubusercontent.com/89308251/133859243-cde2cef4-2229-4e54-98a3-eff683f768f1.png)
    
    
- Scores by school type
    
	- > Replacing the ninth-grade scores did not affect anything by school type.
      
 ![4 4_Scores_by_School_Type](https://user-images.githubusercontent.com/89308251/133859252-80c04b2e-10da-4604-8587-039e3cc33227.png)
    
        
    

## Challenge Summary: 

   There are 4 changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs. First is the total student count in the District summary dataframe. Second is the average math and reading score. Third are the passing percentages of math, reading. Last is the overall passing percentage in both district summary dataframe and the school summary dataframe.
   

