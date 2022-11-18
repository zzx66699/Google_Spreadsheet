# Chapter2 Formulas 公式 & Functions

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
VLOOKUP(data to look up, 'where to look up'!range, return column, false)  
the return column should be a number, instead of a range  
<img width="800" alt="image" src="https://user-images.githubusercontent.com/105503216/199386870-161e3450-e7be-4dc7-be4c-2471b7476c5e.png">  

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
