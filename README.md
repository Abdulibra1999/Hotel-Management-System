# Hotel-Management-System
The ER system will enable the hotel to record natural data and manage the basic works of any hotel.

 Starting from the hotel (Hotel_ID(PK) Hotel_Name , Location as Multivalued , Rate) ,  and will have a group of rooms(Room_No(PK) , Room_Type) and employees(EMP_ID(PK) , EMP_Name as composite , BDate , Address as composite  , Salary , Age as Derived attribute) , one of the employee will be the manager of one hotel. Employees will be able to manage Many rooms and check the payment process. Customer (SSN(PK), CName, Email, Phone,) will be able to reserve (Start_Date, End_Date) a room while extracting the bill (Bill_No (PK), Date, Amount) to pay, in addition that they can order many foods (Type, Rate,Name).
 
 
 
 ER for the system:

 ![image](https://user-images.githubusercontent.com/109043428/201722262-c983ee8d-0604-4c09-b75d-1c9d8f49a6cf.png)

Relation schema for the system :

![image](https://user-images.githubusercontent.com/109043428/201722574-27fb9046-d2e0-4a8b-af60-e47b4bf98c6c.png)
