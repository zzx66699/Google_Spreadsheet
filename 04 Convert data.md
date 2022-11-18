# Chapter4 Convert data
## 1. String to date
Regardless of how Google Sheets formats dates for you to see in cells, spreadsheets always store them as integers. It's an automatic Google Sheets date format that helps to treat dates correctly.  
<img width="500" alt="Screenshot 2022-11-18 at 9 42 43 AM" src="https://user-images.githubusercontent.com/105503216/202597372-eee7104e-0c30-473f-939f-3271616c24c8.png"> 
<img width="500" alt="image" src="https://user-images.githubusercontent.com/105503216/202597461-11ab3688-e21b-4997-8b0a-d5edabc99c0b.png">
### 1.1 Default Google Sheets date format
<img width="500" alt="image" src="https://user-images.githubusercontent.com/105503216/202598006-0e997b54-7005-4f7b-8b21-9221168181db.png"><img width="500" alt="image" src="https://user-images.githubusercontent.com/105503216/202598120-741410e3-0f93-4253-adf0-7a8bbeafa373.png">  

### 1.2 Custom date formats
Format > Number > Custom date and time   
<img width="500" alt="Screenshot 2022-11-18 at 10 07 26 AM" src="https://user-images.githubusercontent.com/105503216/202600866-afa9e65a-b778-4035-8339-8b188f801926.png" >
<img width="500" alt="image" src="https://user-images.githubusercontent.com/105503216/202600922-e40dc8e5-728d-4db3-8dab-23ac8c1b2c08.png">

### 1.3 QUERY function for Google Sheets to format dates
<img width="465" alt="image" src="https://user-images.githubusercontent.com/105503216/202601923-52469e08-5cd5-4bae-94fc-0ae8a1ffacb4.png"><img width="500" alt="image" src="https://user-images.githubusercontent.com/105503216/202602417-28ed1876-336b-4fab-be14-f878257b8916.png">

## 2. Date to number
### 2.1 Convert date to number by changing the format
<img width="824" alt="image" src="https://user-images.githubusercontent.com/105503216/202602975-6b73213a-85f4-49b9-aac8-64729d308b34.png">

### 2.2 DATEVALUE function for Google Sheets

```
=DATEVALUE(date_string)
```

<img width="740" alt="image" src="https://user-images.githubusercontent.com/105503216/202603181-f1ffb886-ddad-410a-bf86-7a5e72f7dbb8.png">

## 3. Date/number to string/text

```
=TEXT(number,format)
```

change number to text:  =TEXT(B2,"mmmm")
<img width="928" alt="image" src="https://user-images.githubusercontent.com/105503216/196333559-05ce8ece-7911-4c86-a04c-a6f78fe669f1.png">
<img width="673" alt="image" src="https://user-images.githubusercontent.com/105503216/202603710-bb161364-5162-4cf2-878a-164591cbd3d4.png">

## 4. String to numbers

``` 
= VALUE("string")
```
<img width="493" alt="image" src="https://user-images.githubusercontent.com/105503216/202604018-df3a15c6-0f70-4db4-8888-a62b97e305c2.png">

### 4.1 Replace Dots with Comma to Convert Text to Numbers

```
=REGEXREPLACE(A2, "[.]", ",")
```
<img width="477" alt="image" src="https://user-images.githubusercontent.com/105503216/202604138-2abc1de0-8231-4d1e-8a9c-b895386fecc3.png">

### 4.2 Converting Data with Currency Text to Number

``` 
=TO_PURE_NUMBER(A2)
```

<img width="489" alt="image" src="https://user-images.githubusercontent.com/105503216/202605143-e5fc5d54-dead-46b2-a064-589596cbeb65.png">

### 4.3 Extracting Numbers From Text

``` 
SPLIT(J11,CONCATENATE(SPLIT(J11,".0123456789")))
```

<img width="1118" alt="image" src="https://user-images.githubusercontent.com/105503216/202606562-2b25c5fd-8311-4d5d-a5a8-55b4789239a1.png">

```
=SPLIT(REGEXREPLACE(J11, "[^\d\.]+", "|"),"|")
```

<img width="1115" alt="image" src="https://user-images.githubusercontent.com/105503216/202607377-5c3e6d3f-40f5-4fbb-9f6e-da7de41d56b0.png">


## 5. Numbers to percentage
```
TO_PERCENT(A1)
```

<img width="223" alt="image" src="https://user-images.githubusercontent.com/105503216/202596442-22a882f0-a805-4c8b-9afc-96333ad816e8.png">

## 6. CONVERT to another unit
### 6.1 Celsius & Fahrenheit
<img width="737" alt="image" src="https://user-images.githubusercontent.com/105503216/202594858-3c4c206a-52ef-492c-899e-7c78380f974a.png">  
when adding data into the table using formula, go back and paste the data in as values afterwards  
<img width="682" alt="image" src="https://user-images.githubusercontent.com/105503216/202595400-c68dfdb9-b61d-411a-a360-74905cb1677f.png">

### 6.2 miles per hour (mph) & meters per second (m/s)
<img width="747" alt="image" src="https://user-images.githubusercontent.com/105503216/202595540-e4ad3f86-3db9-41f4-afc8-58458f698811.png">

## 7. To currency
<img width="994" alt="image" src="https://user-images.githubusercontent.com/105503216/202594204-2a7deaa4-58df-4230-9df4-4960cda0ad8d.png">
