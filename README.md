
# Feedback system

The website is developed as a task for AI Unreal Engines which is used to take input for student feedback system and fetch the feedback to the database.
The system have a responsive design that works on different screen sizes and devices.


## API Reference

#### Get all items

```http
 http://localhost/phpmyadmin/
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `phpmyadmin` | `url` | **Required**. Your database reference. |


#### Get Average

```http
  SELECT AVG(crating) AS AVERAGE_COURSE_RATING FROM FORM;
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `crating`      | `integer` | Average of all course rating. |

#### avreage(crating, irating)

Returns the average rating of the course and instructor.


## Deployment

To deploy this project run

```bash
  localhost/dashboard
```
To run the deployed project we've to create a database in MySQL with the help of PHP.

```bash
  create database and a table 
```


## Screenshots!


Basic User Interface

<img width="900" alt="Screenshot 2023-03-19 at 3 37 28 PM" src="https://user-images.githubusercontent.com/89736941/226200889-0c268d5f-8304-4379-bb07-942ea1acb9dc.png">

## Procedure & Steps:

Step 1: Fill the Form.

<img width="900" alt="Screenshot 2023-03-20 at 12 33 23 AM" src="https://user-images.githubusercontent.com/89736941/226203514-ea271210-6e68-4805-9653-d3d366575294.png">

Step 2: Form will be submitted succefully.

<img width="900" alt="Screenshot 2023-03-20 at 12 33 37 AM" src="https://user-images.githubusercontent.com/89736941/226203575-f20b2efe-e8e0-4fc2-bcef-bb4e4ec440f3.png">

Step 3: All the submitted form data will be reflecting in the database.

<img width="900" alt="Screenshot 2023-03-20 at 12 35 16 AM" src="https://user-images.githubusercontent.com/89736941/226203682-776a14b9-16f7-4c86-b00a-eb21622e7e66.png">

## Calculate Average:

Step 1: Insert the mentioned SQL query

<img width="900" alt="Screenshot 2023-03-20 at 12 36 46 AM" src="https://user-images.githubusercontent.com/89736941/226204065-b3392632-d4c3-45dc-98df-189a18f6e333.png">

Step 2: Average Course & Intructor Rating will be displayed 

<img width="900" alt="Screenshot 2023-03-20 at 12 37 10 AM" src="https://user-images.githubusercontent.com/89736941/226204153-7dc8a024-7a21-4384-9cd1-837174229b24.png">

<img width="900" alt="Screenshot 2023-03-20 at 12 39 10 AM" src="https://user-images.githubusercontent.com/89736941/226204163-1802c6e1-fc90-4706-b9b6-481a905d4cb2.png">

 



