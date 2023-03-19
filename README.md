
# Feedback system

The website is developed as a task for AI Unreal Engines which is used to take input for student feedback system and fetch the feedback to the database.


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


## Screenshots



