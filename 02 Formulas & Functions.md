# Chapter2 Formulas 公式 & Functions
[List of Google Sheets functions](https://support.google.com/docs/table/25273?hl=en)

## 1. Formulas & Functions definition
<img width="808" alt="image" src="https://user-images.githubusercontent.com/105503216/196190243-0b9945b5-d26d-4a56-8483-6b081c916b9b.png">   
<img width="217" alt="image" src="https://user-images.githubusercontent.com/105503216/196192040-63251923-c358-4848-a3dd-268dcedb1c25.png">   

parentheses 括号  
colon 冒号 a colon between the cell references shows that you are using a range  
<img width="685" alt="image" src="https://user-images.githubusercontent.com/105503216/196323313-2ed5ac2c-df8e-487f-8f6e-e5b843e0ecd7.png"> 


## 2. cell reference
<img width="578" alt="image" src="https://user-images.githubusercontent.com/105503216/196189451-913b3d34-287f-430e-a3c7-2aa6a4f9dfb0.png">   

## 3. COUNT/COUNTA
COUNTA: count the total number of values within a specific range  
<img width="229" alt="image" src="https://user-images.githubusercontent.com/105503216/201504573-4c658910-ce64-4694-86e6-8ba5b0d72794.png">  

COUNT: only count numerical values within a specific range  


## 4. IFERROR  
deal with div error  
<img width="486" alt="image" src="https://user-images.githubusercontent.com/105503216/196192334-d42b521e-e48e-4082-a126-1f98d04a21a3.png">  


## 5. VLOOKUP
VLOOKUP(data to look up, 'where to look up'!range, return column, FALSE/TRUE)  
the return column should be a number, instead of a range  
TRUE tells VLOOKUP to look for approximate matches, and FALSE tells VLOOKUP to look for exact matches.  
<img width="800" alt="image" src="https://user-images.githubusercontent.com/105503216/199386870-161e3450-e7be-4dc7-be4c-2471b7476c5e.png">  

### 5.1 VLOOKUP can only return a value from the data to the right. It can't look left
get around the problem by copying and pasting a column to the left of the data they want to look at.   
This way, the lookup value is in the leftmost column and the data they want is to the right of it.   
<img width="558" alt="image" src="https://user-images.githubusercontent.com/105503216/202825771-e8ad0d12-d878-412d-8ed6-dcee608ae3b3.png">


## 6. SORT
= SORT(xx:xx, column number, TRUE/FALSE)  
<img width="1268" alt="image" src="https://user-images.githubusercontent.com/105503216/202197185-e4346192-121b-4de4-94a2-20cbd8cb781d.png">

## 7. CONCATENATE 连接
<img width="1001" alt="image" src="https://user-images.githubusercontent.com/105503216/198883215-5826ffe9-754e-4b65-a6e8-f621da7f20db.png">  

You can also add a space/xxx between two variables     

``` 
=CONCATENATE(A1," ", B1)
```

<img width="1184" alt="image" src="https://user-images.githubusercontent.com/105503216/199388967-b08bc205-0263-4870-bf92-39716f8f1866.png">    

You can also combine three or more columns  

```
=CONCATENATE(C2," ",D2,", ",E2)
```

## 8. LEN
<img width="247" alt="image" src="https://user-images.githubusercontent.com/105503216/198881517-e5e71756-7894-44aa-b910-03870aea11c8.png">  
often used with conditional formatting to see if the length of a character is right  
<img width="1262" alt="image" src="https://user-images.githubusercontent.com/105503216/198881557-f71f6efb-77d2-4521-9126-2121a5a78673.png">  

## 9. LEFT & RIGHT & MID
LEFT/RIGHT(range, number of characters)  
<img width="302" alt="image" src="https://user-images.githubusercontent.com/105503216/198881649-7f11be21-a3ed-4e1d-814f-e81a7fdde071.png">  

MID(range, reference starting point, number of middle characters)  
<img width="232" alt="image" src="https://user-images.githubusercontent.com/105503216/198881839-bc6b3360-f665-428d-820f-2111a116a95e.png">  

## 10. TRIM
fix extra spaces   
<img width="254" alt="image" src="https://user-images.githubusercontent.com/105503216/198883321-286d7137-b6d3-4d13-86ba-c66fd7bbb946.png">  

## 11. COUNTIF & COUNTIFS
quickly counts how many items in a range of cells meet a given criterion  
<img width="765" alt="image" src="https://user-images.githubusercontent.com/105503216/196191178-8042e151-9c08-4946-89f6-479efbb713d9.png">
<img width="493" alt="image" src="https://user-images.githubusercontent.com/105503216/198881312-9b762541-bd8e-40ea-97cf-3871479e9ebe.png">  

=COUNTIFS(criteria_range1, criterion1, [criteria_range2, criterion2, ...])  
<img width="788" alt="image" src="https://user-images.githubusercontent.com/105503216/202903148-db589b3c-f84d-44c0-b4b6-a9d6b463387d.png">

## 12. FIND
```
=FIND("searched value", from xx)
```

return the FIRST index of target value  
<img width="619" alt="image" src="https://user-images.githubusercontent.com/105503216/202648027-39de0ca2-a701-43ae-8f4b-93d54ef74ac4.png">  

Extract Date and Time respectively from Datetime  
<img width="459" alt="image" src="https://user-images.githubusercontent.com/105503216/202647792-b9c05374-06de-4313-aff5-9f99ab672af3.png"><img width="464" alt="image" src="https://user-images.githubusercontent.com/105503216/202647815-015c5c33-bec6-4fa9-9a7a-11075b29f796.png">

## 13. SUMIF & SUMIFS
=SUMIF(range, criteria/condition, [sum_range])   
<img width="1211" alt="image" src="https://user-images.githubusercontent.com/105503216/202902443-18601bef-b118-4868-9773-ffa2836d0573.png">   

=SUMIFS(sum_range, criteria_range1, criterion1, [criteria_range2, criterion2, ...])   
build in multiple conditions by using the SUMIFS function   
<img width="813" alt="image" src="https://user-images.githubusercontent.com/105503216/202903108-dc4de84c-dd49-45e5-9f70-83349e2f5f64.png">

## 14. AVERAGEIF
=AVERAGEIF(range, criteria, [sum_range])  
<img width="775" alt="image" src="https://user-images.githubusercontent.com/105503216/202904943-d115a10a-4872-443a-8f1a-000fdb6be15a.png">  

## 15. MAXIFS
=MAXIFS(max_range, range1, criteria1, [range2], [criteria2], ...)
<img width="790" alt="image" src="https://user-images.githubusercontent.com/105503216/202905113-f33446b4-dcf3-49a6-880d-03eaad5d2ec6.png">

## 16. SUMPRODUCT
=SUMPRODUCT(array1, array2, array3, ...)  
multiplication & additional calculations  
<img width="615" alt="image" src="https://user-images.githubusercontent.com/105503216/202906350-117375e3-b5a5-4286-8908-a0d715b55906.png">  
<img width="899" alt="image" src="https://user-images.githubusercontent.com/105503216/202906378-64dab671-fb82-43fa-a61e-36c4b0a649d3.png">


