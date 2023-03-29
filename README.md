## Team Name and Members

Team Name: 21479_2

    Team Members:
    1. Carson Hall
    2. Jacob Hoover
    3. Ryan Restino
    4. Mason Sprinkle
    5. Owen Swonger



## Business Description

The industry that our team is focusing on is the film industry.
The specific aspect of the film industry that we are looking
after is the distribution, budgeting, and awarding of a film
after it has been created by the studio. This process is usually very convoluted and spread thin across many parties, while our model consolidates and simplifies many of these processes. We provided two improvements that will allow the studio to better understand how the film is being distributed and the performance of the film. With these improvements, our project looks at both the qualitative and quantitative aspects of a film after production to see, overall, how well the film did.

    Improvements:
        1. The first improvement we made was to develop a way 
        for the studio’s to track contract details by storing
        the information in a database rather than contract
        details just being on paper or on various files held by
        different people. This allows for everyone to access
        the same details in the database. This makes seeing
        where the film rights are going much more convenient
        and easier to track the performance of the
        distribution. 
        2. The second improvement we made was to add a way for
        the companies to track the distribution of films to
        streaming services. With the rise of streaming
        services, films are no longer only distributed to
        cinemas to be shown in theaters. This was a key
        addition as it will help the studios to accurately
        track the distribution rights of the various films they
        have. This can be seen later as the StreamingServices
        entity in our data model.


 
    
## Data Model
![App Screenshot](https://raw.githubusercontent.com/carsonehall15/21479_2/254805237a59ecfc223e16e3f7165fc65e38f0ad/Data%20Model.png)


## Data Model Description

As stated earlier in our business description, the specific aspect of the film industry that we are looking at is the distribution, budgeting, and awarding of a film after it has been created by the studio. The relationships between the entities are important to understand since they are the basis for how we are able to conduct queries and investigate various aspects of the company. 

    ONE TO MANY RELATIONSHIPS: 
    1. A Country has many Studios 
    2. A Studio has many Films 
    3. A Film have many Expenses
    4. A Film can have many Budgets 
    5. A Film can have many ContractDeals 
    6. A StreamingService have many ContractDeals
    7. A Cinema have many ContractDeals

    MANY TO MANY RELATIONSHIPS:
    1. Films have many Genres but a Genre has many Films 
    2. Films can have many Awards but an Award can also 
        be won by many films


## Data Dictionary
## Query #1 : Write a query that displays each film’s department and their correlated expenses in ascending order

This query is relevant to management because it allows them to see which departments are using the most financial resources. Tracking expenses is a key part of business to allow the company to see where they can cut costs.





## Query #2: Write a query to list the filmName and total expenses for that film if expenses are greater than or equal to    .

This query is relevant to management because it allows them to see the total amount of expenses incurred by each Film for films that have larger expenses.

## Query #3: Write a query to see how over budget a film was based on if total expenses are greater than the budget.

This query is relevant to management because it allows them to see whether or not the film is staying on the right track financially or if it was over budget. 
## Query #4: Write a query to list the budget of films that won 3 or more awards.

This query is relevant to management, because it would be beneficial to see if there is a correlation between the amount of money spent on producing a film and the amount of awards those films win. 
## Query #5: Write a query to show the amount of different films that a studio is producing (group by studio name). 

This query is relevant because it allows the user to see the exact number of films that a studio may be producing at a given time.

## Query #6: Write a query to list the average revenue of each genre produced by our studio.

This query is relevant to management because it would be beneficial to know which genres of film are on average the most successful financially and which genre’s may struggle more financially on average. 
## Query #7:  Write a query that lists out filmName and total expenses for films whose total expenses are greater than the average total expenses for films from the same country.

This would help management to look at what films have greater than average expenses relative to films that are being made in the same country since expenses around the world can vary. 

## Query #8:
  
## Query #9
## Query #10
## Features Covered In Queries
