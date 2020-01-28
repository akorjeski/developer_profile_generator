### Alexander Korjeski
### January 28th, 2020
### Penn LPS Coding Bootcamp
### Homework 9: Developer Profile Generator
### Deployed Application: https://akorjeski.github.io/developer_profile_generator/.
### Github Repository:  https://github.com/akorjeski/developer_profile_generator
### Technologies: HTML, CSS, Javascript, node.js, NPM

## User Story:
AS A product manager

I WANT a developer profile generator

SO THAT I can easily prepare reports for stakeholders

## The purpose of this application is to create a command-line application that dynamically generates a PDF profile from a GitHub username. 
The PDF will be populated with the following:
 1. Profile Image
 2. Username
 3. Links to the following:
    1. User location via Google Maps
    2. User Github prifle
    3. User blog
    4. User bio
4. Number of Public Repos
5. Number of Followers
6. Number of Following
7. Number of Github Stars



The application will be invoked with the following command:  	__node index.js__
Initially the user is prompted for 2 inputs: 

1.	Their Github username (string)
2.	Color preference from a prefabbed list (Green,Blue,Pink,Red)

After this, the application creates a .pdf file within the parent folder. Open it to see how it looks!
