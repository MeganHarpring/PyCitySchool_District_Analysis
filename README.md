# **School_District_Analysis:**
## **PyCitySchool**
### **Overview of the school district analysis:**
##### We are helping Maria, a data scientist for a city school district. We are going to help her analyze all the Math and Reading standardized testing data and funding data in the district to look for different trends and/or patterns. We will take the data from all (15) different schools, 9th - 12th grades, and see what trends or patterns we find that will help the school district.
We were recently informed that there have been some reading and math scores that have been altered for students at Thomas High School in the 9th grade. Maria would like us to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.

## **Results:**

#### **District Summary:**

###### - The district summary would be affected by the new total student count; there are less total students included in the data after the 9th graders from Thomas High School were removed. There is a total of 39,170 students once we remove the 461 9th graders at Thomas HS there are a total of 38,709. With such a large data set of students (39,000) removing the 461 9th graders won't affect the district data very much, if at all. Below we can see the district summary with the 39,170 students first, then the second picture is the district summary with 38,709 students.  

<img src="https://user-images.githubusercontent.com/100392991/162073545-43fe3169-e269-468c-9e55-423411549ab1.PNG"
     width="700" height="200">
<img src="https://user-images.githubusercontent.com/100392991/162073561-dcab8daa-5631-425a-913f-326e68d4f7c9.PNG"
     width="800" height="200">



#### **School Summary:**

###### - The school summary was affected a little bit. The first picture is the school summary originally for Thomas HS. The second picture shows what happened to Thomas HS once we removed the the ninth grade student scores but didn't adjust the total student count. This made the percentages for the school go down quite a bit as you can see below. We then adjusted the Thomas HS summary by removing the ninth grade scores and adjusting the total student count. As you can see in the third picture below the percents went back up to where they were originally, they differ by just a few tenths perct. This is a more acurate reading for the school if we need to remove the ninth grader scores. 

<img src="https://user-images.githubusercontent.com/100392991/162073652-43eacb1b-fc49-43ac-909c-8e56064988db.PNG"
     width="1000" height="200">


<img src="https://user-images.githubusercontent.com/100392991/162077780-3375c636-efee-491e-a3d1-7dc22dac3e5f.PNG"
     width="1000" height="150">

<img src="https://user-images.githubusercontent.com/100392991/162073675-db629ae1-c1e1-43c0-b5d4-e915f5c65be9.PNG"
     width="1200" height="150">

###**Replacing the ninth graders' math and reading scores at Thomas HS:**
- When we removed the ninth graders scores, Thomas HS went from 2nd place to 13th in performance compared to the other schools. Once we replaced the ninth graders' scores with NaN you can see how it affected Thomas HS in the above pictures by sending them back to 2nd place. By using  the NaN function we can calculate Thomas HS scores with just the Tenth-Twelfth graders scores. 

### **Replacing scores affect on Math and Reading scores by grade:**
### - Replacing the ninth-grade scores do not really affect any of the reading or math scores except you will see NaN under the 9th grade scores for math and reading at Thomas High School. All the other math and reading scores are not affected.

### **Replacing the scores affect on the following:**
### - As you will be able to see from the two pictures below (1st picture is before the ninth graders scores were replaced and the 2nd is after) replacing the scores did not affect the socres by school size. You will see the same results for 'Scores by Spending" and 'Scores by Type'. Once we replaced the ninth graders' scores with the NaN funcition it really didn't affect anything except for the performance at Thomas HS a little bit but not enough to make a difference or to be noticed. 

Scores by Size:

<img src="https://user-images.githubusercontent.com/100392991/162073978-a28ef422-a4c2-4ce7-87d2-0faa7cd60a04.PNG"
     width="800">

<img src="https://user-images.githubusercontent.com/100392991/162073999-a227b520-11cb-4b3d-98d7-3e61265cc9d4.PNG"
     width="800">


Scores by Spending:

<img src="https://user-images.githubusercontent.com/100392991/162074044-94eab834-2399-46bb-9a87-607df645a14b.PNG"
     width="800">
     
<img src="https://user-images.githubusercontent.com/100392991/162074055-d53c67dc-0038-474e-9bc6-c62834c868a4.PNG"
     width="800">


Scores by Type:

<img src="https://user-images.githubusercontent.com/100392991/162074106-090646b2-84e9-4590-8771-f54d73d7b73d.PNG"
     width="800">
<img src="https://user-images.githubusercontent.com/100392991/162074115-94bb3ecc-2cf1-4d50-b476-8bdb2191d044.PNG"
     width="800">
