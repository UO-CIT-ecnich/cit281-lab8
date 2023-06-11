# Description

In this lab, my main objective was to create a Node.js application using Fastify and node-fetch to fetch data from the JSONPlaceholder API. The lab consisted of several steps, so let's go through them:

First, I created a new file called "lab-08.js" in the cit281/p7/lab8 folder and initialized it as a Node.js folder using npm. This allowed me to set up the project and manage its dependencies easily.

Next, I installed the required packages, fastify, and node-fetch, using the npm command. These packages were essential for building the server and making HTTP requests to the JSONPlaceholder API.

After installing the packages, I added the Fastify starter code to my lab file. This code included four TODOs with instructions to follow for completing the lab.

The first two TODOs focused on declaring the fastify and fetch objects. I imported the fastify package and initialized the fastify object by executing the imported function. Similarly, I imported the node-fetch package and declared the fetch object.

For the third TODO, I implemented the "/photos" route, which aimed to retrieve all photos from the JSONPlaceholder site using the fetch function. I handled the returned Promise using two .then() chain methods to return a status code of 200 and an object containing the photos. Additionally, I used a single .catch() chain method to return a 404 status code in case of any errors.

The fourth TODO involved implementing the "/photos/:id" route to fetch a single photo from the JSONPlaceholder site based on the provided photo ID. Similar to the previous step, I used the fetch function and handled the Promise with .then() and .catch() chain methods. I also utilized Object.keys() to check if the returned object had properties, indicating a valid photo ID. I returned a 200 status code along with the photo data or a 404 status code for an invalid photo ID.

Throughout the lab, I learned how to set up a Node.js application with Fastify, install and manage packages using npm, and use node-fetch to make HTTP requests. I also gained experience in handling Promises and chaining .then() and .catch() methods to handle asynchronous operations and potential errors. These skills are crucial for building server-side applications and integrating external APIs into our projects.
