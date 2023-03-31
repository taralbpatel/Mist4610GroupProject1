# Team 1 Mist 4610 Group Project 1

## Team Name: 
21479 Group 1 

## Team Members:

1. Taral Patel [@taralpatel](https://www.github.com/taralbpatel)
2. Angel Marsh [@angelmarsh](https://www.github.com/apm83682)
3. Riley Doggett [@rileydoggett](https://www.github.com/RileyDoggett)
4. Ripley Kurtz[@ripleykurtz](https://www.github.com/RipleyKurtz)
5. Sequoyeth Simpson [@sequoyethsimpson](https://www.github.com/quoysimpson)

## Problem Description:
The task at hand is to model and build a reltional database for the general workings of a resort company. The central entity in the model is the Hotel entity of the resort- Hotel being each physical inn the company owns and operates in various locations. The hotel is operated in conjunction with the activities, dining establishments, transportation service, etc. that it offers to the guests who book with them. We are interested in accurately modeling these relationships, generating sample data, and populating the entities and their attributes with this sample data. Furthermore, we are interested in performing functioning queries on this data so that they may provide us with valuable business insight about the resort and its operations.

## Data Model
An explanation of the data model including the relationships between the entities in natural English.

![Screen Shot 2023-03-30 at 9 42 10 PM](https://user-images.githubusercontent.com/128402101/229001455-ddc3361b-422f-483c-b4d8-01edc47e4afa.png)

## Data Dictionary:
![Screen Shot 2023-03-30 at 9 47 17 PM](https://user-images.githubusercontent.com/128402101/229002096-362cf55c-86b7-40e0-ae42-6120c5ab3d51.png)

![Screen Shot 2023-03-30 at 9 47 45 PM](https://user-images.githubusercontent.com/128402101/229002159-c7242e00-592e-4b10-9a09-1510a2728a4d.png)

![Screen Shot 2023-03-30 at 9 48 13 PM](https://user-images.githubusercontent.com/128402101/229002240-9817894f-9efd-4b15-af49-9712e8ec225b.png)

![Screen Shot 2023-03-30 at 9 55 12 PM](https://user-images.githubusercontent.com/128402101/229003109-3e9ec7ce-6368-4b85-95c8-facfa2fc1859.png)

![Screen Shot 2023-03-30 at 9 55 31 PM](https://user-images.githubusercontent.com/128402101/229003151-df7093e1-2245-4c2c-a2ed-7ae4b63c0f3f.png)

![Screen Shot 2023-03-30 at 9 56 18 PM](https://user-images.githubusercontent.com/128402101/229003272-e4f940d4-a2e6-428a-b009-719a7677b888.png)

![Screen Shot 2023-03-30 at 9 56 39 PM](https://user-images.githubusercontent.com/128402101/229003314-fe200a9c-db98-4447-b5d6-5f7d84e3f135.png)

![Screen Shot 2023-03-30 at 9 57 21 PM](https://user-images.githubusercontent.com/128402101/229003410-d264d5fa-52f4-412c-9663-7171571ad564.png)

![Screen Shot 2023-03-30 at 9 57 51 PM](https://user-images.githubusercontent.com/128402101/229003478-1b07581a-b8a2-4687-a4a7-9687c1cb2139.png)

![Screen Shot 2023-03-30 at 9 58 07 PM](https://user-images.githubusercontent.com/128402101/229003507-19f9582f-49a2-4cae-9d88-4eadb842ba66.png)

![Screen Shot 2023-03-30 at 9 58 29 PM](https://user-images.githubusercontent.com/128402101/229003554-6ae5e483-a161-4060-a113-ff7bbb5e4c1d.png)

![Screen Shot 2023-03-30 at 9 58 48 PM](https://user-images.githubusercontent.com/128402101/229003594-e640c190-4e87-4d4d-a81b-7f04085cbed8.png)

## Ten Queries:

1. Include a natural language description of the query 
2. A justification as to why each query is relevant from a managerial perspective (why would a manager be interested in the query results).
3. Screenshots of the query and responses
4. Break down of features covered in each query in matrix form

Avoid having queries that are almost identical to one another. You may include screenshots of the
query as well as the response of each query. You can also use the code markdown to highlight the
SQL code and copy and paste the results into the file.

To ensure the complexity of the queries some of the things that may be considered include
multiple table join, subquery, correlated subquery, GROUP BY, GROUP BY with HAVING,
multi condition WHERE, Built-in functions (e.g., AVG) or a calculated field, REGEXP, NOT
EXISTS, and more.

You may combine some of the preceding list of features into a single query (still have to provide
10 queries). Indicate in matrix format in your report which features are covered in a query. A
sample matrix is shown

3. Query 3 lists the information for all the guests who have not made an activity reservation.

![Screen Shot 2023-03-30 at 10 05 39 PM](https://user-images.githubusercontent.com/128402101/229004419-f6e5df9d-fece-4251-8ff0-9d073fa69c66.png)

Query 3 allows the resort to market toward specific customers and contact them (e.g. promotional emails/coupons) about must-try activities. This helps to maximize revenue and increase efficiency by specifically targeting those who are not engaging in activities, rather than wasting time and resources to advertise to those who are already aware of and partaking in these activities.

4. Query 4 lists the names and phone numbers of dining employees who work in the highest rated dining establishment.
 
![Screen Shot 2023-03-30 at 10 07 04 PM](https://user-images.githubusercontent.com/128402101/229004593-33dd9e6b-ff0d-4893-8fee-a4a611b3263f.png)

A restaurant with a high star rating is a large source of revenue for the resort and management may want to know the names of the employees who work there and how to contact them to reward them for maintaining such a high achieving restaurant (e.g. via a bonus, raise, awards, recognition) or to know which employees to target for continuous training and supervision in order to keep service within the establishment in top shape.

5. Query 5 lists the guests’ names and the hotel they are checking into if their reservation is during the PM, their room is a single or suite, their check in dates are between 2023-04-01 and 2023-04-10, and their hotel rating is above a 4.

![Screen Shot 2023-03-30 at 10 09 24 PM](https://user-images.githubusercontent.com/128402101/229004878-8f76c354-f888-48e7-9812-dd510315a44c.png)

Query 5 allows the resort to manage how busy their check in will be during the PM hours of early April in their better hotels where the check in rooms are singles or suites. This can help the resort determine how many employees need to be working the check in desks to check in single or suite reservations in the afternoon of these dates in these specific hotels.

6. Query 6 lists the names of guests who have over 10 activity reservations and the activities that they have those reservations in.

![Screen Shot 2023-03-30 at 10 09 53 PM](https://user-images.githubusercontent.com/128402101/229004928-5ff708ee-d901-4af0-afb4-1dc44495b08a.png)

Query 6 allows the resort to determine what guests are contributing the most to each activity’s revenue. It also enables the resort to send reqards to their most loyal customers to thank them for their contributions and enagement with the resort.  


## Database information:
1.Name of the database: ns_21479_1
