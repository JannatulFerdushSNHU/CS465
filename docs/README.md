# Architecture

## Frontend Development Comparison

In this project, I deployed Express HTML and JavaScript to handle the development at the frontend level. Express HTML is a software that allows face changing on the server side with the help of data of HTML page. On the other hand, JavaScript was used for making the interactions, handling the events, or performing actions such as form validation, loading new content on the page on the button click, or performing the API calls etc.

I also looked at Single Page Application (SPA) architecture, in which only a single HTML page is loaded and content is updated without having to reload the page. It makes the user experience much better this way. Unlike dull HTML rendering where every new page opening involves a request to the server, SPAs use JS frameworks such as React or Angular to assist in managing the transitions and dynamic updates of pages.

## Why Choose NoSQL MongoDB for the Backend?

This particular application has the backend support of NoSQL MongoDB as its database. MongoDB is a NoSQL database that stores data in JSON-like documents, which are schema-free. This is ideal for use in applications like ours since it is able to deal with unstructured data and has simple scalability. For example, in this project, the choice of MongoDB as the NoSQL database allowed for the data storage of other data types provided as users’ profiles, orders, and product details. This was especially useful in a dynamic application where the structure might change over time.

# Functionality

## JSON vs JavaScript and Its Role in Full Stack Development

JSON is a lightweight data markup language used to represent the data to be transferred to the front end, stored, and retrieved. It is very clear to see that JSON is just a data format with key-value attributes, unlike JavaScript, which is a programming language. JSON is used to transmit data from the backend (server) to the frontend (client). In my full stack project, JSON was used to pass information between the frontend and the backend, such as providing user credentials or product details.

## Refactoring Code for Better Functionality

Refactoring Code for Better Functionality is the process of restructuring existing code to improve performance and maintain functionality. I had to "recode" the application multiple times to smoothen and optimize its operations. For instance, I developed reusable UI elements like buttons, form inputs, and navigation bars. This approach kept the code more consistent, reduced the amount of code, and made the project more efficient. However, there were challenges to reusability—if one component changed, the adjustments would ripple across the entire project, making it faster and less prone to mistakes.

# Testing

## API Testing and Security

In full stack development, API testing is crucial to check the functionality of the endpoints that enable frontend and backend communication. I used tools like Postman to test various endpoints for actions like login, creating orders, retrieving data, and more. When security features like JWT authentication were added, testing became more complex, as each request needed a valid token. This added an extra layer of security, ensuring that only authorized users could access certain endpoints.

Security also played a major role during the testing of the login feature. Ensuring that password hashing and session management were secure required careful attention to prevent unauthorized access to sensitive user data.

# Reflection

## What I Learned from This Course in Achieving My Professional Objectives

This course has been quite useful in my journey to becoming a full stack developer. It taught me both the frontend and backend sides of application development, and now I am comfortable working with HTML, JavaScript, MongoDB, and Express.js. I have learned how to organize the components and structure of a full stack web application from scratch, reinforcing my coding skills.

The knowledge gained from this course will help me be well-equipped for software development roles, especially in areas like API integration, secure authentication, and frontend responsiveness. These skills will make me more marketable when seeking a position in any software development company. The experience I gained from working on a real-world project will also enable me to stand out to potential employers and demonstrate my ability to handle challenging tasks effectively.
