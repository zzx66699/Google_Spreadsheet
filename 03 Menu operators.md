# Chapter3 Menu operators

## 1. Conditional formating
### 1.1 Find null values
format > conditional formatting 条件格式  
<img width="390" alt="image" src="https://user-images.githubusercontent.com/105503216/198544326-d660f3eb-71a4-48cf-90bd-5be9875e96a0.png">  

### 1.2 Check the specific value
<img width="1051" alt="image" src="https://user-images.githubusercontent.com/105503216/202628164-bce854ed-3bd6-44f9-8bae-b13b3a37557b.png">
<img width="1084" alt="image" src="https://user-images.githubusercontent.com/105503216/202628350-0b164bd8-41b2-45df-926b-ca696bdc34da.png">

### 1.3 Check the date
<img width="933" alt="image" src="https://user-images.githubusercontent.com/105503216/202628678-d2960859-9e06-498e-a1f5-581ada1d323b.png">

### 1.4 Color scale
<img width="918" alt="image" src="https://user-images.githubusercontent.com/105503216/202901434-695b860b-1032-4c22-aad1-182d00ddf48a.png">

### 1.5 Highlight the cells that appear more than once
<img width="287" alt="image" src="https://user-images.githubusercontent.com/105503216/206954545-2e95303f-8eb1-4877-b232-1b6b406d324d.png">
<img width="676" alt="image" src="https://user-images.githubusercontent.com/105503216/206954572-2d5eb9cf-5bd8-4e0b-9626-0fb78b5fa7bd.png">

## 2. PIVOT TABLE
Insert > Pivot table  

### 2.1 Change the dimension of time  
<img width="681" alt="image" src="https://user-images.githubusercontent.com/105503216/203010838-c7f315c3-67a8-4651-a7ef-4ce1964b95c9.png"><img width="234" alt="image" src="https://user-images.githubusercontent.com/105503216/203010935-4eb0b3f6-140d-4db0-96cb-913e8d1ae04b.png">
 
### 2.2 Filter the condition 
remember the condition will apply to all the values!  
<img width="237" alt="image" src="https://user-images.githubusercontent.com/105503216/203011947-3e9e9c24-d9d0-4307-ba4d-10ed627b3064.png">
<img width="309" alt="Screenshot 2022-11-21 at 5 17 17 PM" src="https://user-images.githubusercontent.com/105503216/203012217-430b4561-6442-44c9-9db6-d0916c1d4075.png"><img width="324" alt="image" src="https://user-images.githubusercontent.com/105503216/203017872-dba8b068-5f6b-426d-9506-1d840a030dd6.png">

<img width="998" alt="image" src="https://user-images.githubusercontent.com/105503216/203018379-cdb96688-92e0-4edb-8dbe-7477e03c7bf6.png">


### 2.3 Sort the rows
<img width="407" alt="image" src="https://user-images.githubusercontent.com/105503216/203017550-2763a275-b6dc-44fa-b439-1c3297e84a62.png">

### 2.4 Calculate Field
A calculated field is a new field within a pivot table that carries out certain calculations based on the values of other fields.  
<img width="361" alt="image" src="https://user-images.githubusercontent.com/105503216/203014494-09bf3380-8ea1-4323-9a3b-29d7e4a2e7d9.png">
<img width="650" alt="image" src="https://user-images.githubusercontent.com/105503216/203016295-6931263d-b339-4a0b-bb6f-5940ade19db5.png">

## 3. Data Validation
Data > Data Validation  
### 3.1 Add custom dropdown lists with predetermined options
<img width="614" alt="image" src="https://user-images.githubusercontent.com/105503216/202618347-78f25d12-35ad-4a82-93fd-c1ded33fb522.png"><img width="222" alt="image" src="https://user-images.githubusercontent.com/105503216/202618375-46347559-dffa-4f74-85eb-4cfc8a2086a5.png">

### 3.2 Create custom checkbox
<img width="500" alt="image" src="https://user-images.githubusercontent.com/105503216/202618796-d05402d7-e295-49f4-9ed7-ccb862341872.png"><img width="500" alt="image" src="https://user-images.githubusercontent.com/105503216/202618823-366b723d-41e8-4194-a598-a5acd81eaa28.png">

### 3.3 Protect structured data and formulus 
<img width="590" alt="image" src="https://user-images.githubusercontent.com/105503216/202619102-4a9e6068-c751-4dd2-84cf-970f2d59a14d.png">

## 4. Remove duplicate
data > data clean > remove duplicate   
<img width="648" alt="image" src="https://user-images.githubusercontent.com/105503216/198545144-c2154bcd-28c4-4c4c-b9cd-58c58046683e.png">

## 5. Split the column
data > split text to columns  
<img width="444" alt="Screenshot 2022-10-28 at 4 48 49 PM" src="https://user-images.githubusercontent.com/105503216/198545940-0ea38e9a-fc02-48e5-9257-2b96011bda93.png">    

### 5.1 Use SPLIT function
```
=SPLIT(F2,"-")    
```

The first entry (F2) refers to the cell where the text is located.   
The second entry (“-”) refers to the fact that you are dividing the text based on the minus sign.  

### 5.2 Fix the instances of number stored as text
<img width="231" alt="image" src="https://user-images.githubusercontent.com/105503216/198547338-1a5a34d0-8c51-4d70-ac9f-ff80408141f7.png"><img width="168" alt="image" src="https://user-images.githubusercontent.com/105503216/198547427-72e3ed55-b18a-4928-9264-7bdf3addd828.png">

## 6. Insert visualization
Insert > chart   
<img width="1337" alt="image" src="https://user-images.githubusercontent.com/105503216/203043543-14d7e3c3-2d90-4e77-9ce1-11d9d591846b.png">
### 6.1 Change the chart type
<img width="282" alt="image" src="https://user-images.githubusercontent.com/105503216/204818738-87698e3d-10cf-4977-be5d-def2dac1ea13.png">
<img width="606" alt="image" src="https://user-images.githubusercontent.com/105503216/204818784-c21998ec-0936-4f7e-8626-1b646a260634.png">

### 6.2 Filter in visuals
<img width="500" alt="image" src="https://user-images.githubusercontent.com/105503216/204820889-de76824e-458e-4bf9-946f-df5cb14eb9d8.png"><img width="300" alt="image" src="https://user-images.githubusercontent.com/105503216/204826996-f27753f8-df9c-45a5-bedf-490b29e4ce12.png">
<img width="500" alt="image" src="https://user-images.githubusercontent.com/105503216/204825009-d2c2ca3d-9032-4315-a3ab-cb28c9eade0a.png">  


### 6.3 Chart style
series > fill colour  
<img width="308" alt="image" src="https://user-images.githubusercontent.com/105503216/204827978-c5dd7168-c4b0-46cf-aec7-5039fca23344.png">



