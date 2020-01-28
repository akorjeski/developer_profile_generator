# Alexander Korjeski
# January 28th, 2020
# Penn LPS Coding Bootcamp
# Homework 9: Developer Profile Generator
# Deployed Application: https://akorjeski.github.io/developer_profile_generator/.
# Github Repository:  https://github.com/akorjeski/developer_profile_generator
# Technologies: HTML, CSS, Javascript, node.js, NPM

## User Story:
AS A product manager

I WANT a developer profile generator

SO THAT I can easily prepare reports for stakeholders

## The purpose of this application is to create a command-line application that dynamically generates a PDF profile from a GitHub username. 
The PDF will be populated with the following:
•	Profile image
•	User name
•	Links to the following: 
        o	User location via Google Maps
        o	User GitHub profile
        o	User blog
        o	User bio
•	Number of public repositories
•	Number of followers
•	Number of GitHub stars
•	Number of users following

The application will be invoked with the following command:  	__node index.js__
Initially the user is prompted for 2 inputs: 

1.	Their Github username (string)
2.	Color preference from a prefabbed list (Green,Blue,Pink,Red)

After this, the application creates a .pdf file within the parent folder. Open it to see how it looks!
