# Cookie-Sales---Power-Pivot-Project

## **Phase 1: Developing the Data Model** 

<img width="515" alt="image" src="https://github.com/davidpham1996/Cookie-Sales---Power-Pivot-Project/assets/148404076/da3304dd-e18f-40a2-9bb6-3157a833ceff">


<img width="607" alt="image" src="https://github.com/davidpham1996/Cookie-Sales---Power-Pivot-Project/assets/148404076/91dd546a-e7d1-4de3-b6b2-4f8ab90696b1">

## **Phase 2: Writing DAX Calculations**  

<img width="301" alt="image" src="https://github.com/davidpham1996/Cookie-Sales---Power-Pivot-Project/assets/148404076/9f2e1640-bd27-4733-8331-7954bc56d495">

- Calculating Revenue per Unit: =RELATED('Cookie Types'[Revenue Per Cookie])*Orders[Units Sold]
- Calculating Cost per Unit: =RELATED('Cookie Types'[Cost Per Cookie])*[Units Sold]
- Calculating Profit per Unit: =[Revenue]-[Cost]

Result: 

<img width="164" alt="image" src="https://github.com/davidpham1996/Cookie-Sales---Power-Pivot-Project/assets/148404076/d5b4fdf6-2510-4c5a-a731-3015b8323f6c">

Answering BI questions:

How many customers did we have? 
- DAX Expression: Total Number of Customers:=DISTINCTCOUNT(Customers[Customer ID])

What was our total Profit?
- DAX Expression: Total Profit:=SUM(Orders[Profit])

What was the average profit per customer?
- Avg Profit per Customer:=Customers[Total Profit]/[Total Number of Customers]

Result: 

<img width="181" alt="image" src="https://github.com/davidpham1996/Cookie-Sales---Power-Pivot-Project/assets/148404076/e3d03d37-3d97-4403-b49a-4c275b303afd">


## **Phase 3: Analyzing with Pivot Tables**  

What was the total order amount from each main customer?

<img width="196" alt="image" src="https://github.com/davidpham1996/Cookie-Sales---Power-Pivot-Project/assets/148404076/b4cf2531-5f29-4bde-93f7-8a87acd121b3">

What was the total profit of each customer? 

<img width="194" alt="image" src="https://github.com/davidpham1996/Cookie-Sales---Power-Pivot-Project/assets/148404076/81bff0a8-2ffc-4ee6-9937-af095e689916">

How many units were sold by cookie type annually?

<img width="265" alt="image" src="https://github.com/davidpham1996/Cookie-Sales---Power-Pivot-Project/assets/148404076/de8bae6d-41da-4c6c-8028-77ad9f03bccb">

## **Phase 4: Forecasting** 

<img width="806" alt="image" src="https://github.com/davidpham1996/Cookie-Sales---Power-Pivot-Project/assets/148404076/05889c43-ecae-495b-ab8c-48bd53934f9a">
