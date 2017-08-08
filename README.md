# Assurant-Martian-Robots
Assurant Martian Robots
 Architecture:
  - C# ASP.NET MVC 5.2 application using Razor based Views and jQuery
  - Developed with Visual Studio 2017 for Mac and tested using the Mono runtime
 
 Assumptions:
  - Proof of Concept application to solve problem descibed in Coding Execrise document
  - Data persistence, service layer extension and unit test project development are out of scope for Proof of Concept
  - User will either click the 'Mars' navigation tab or the 'Click Here to Send Robots to Mars' link on the home page view to get to the 'Mars' module
  - Missions will send 3 robots at a time in sequence and all form fields will be populated before hitting 'Submit'
  - Output will be displayed in read only fields located below the 'Submit' button
  - Fields for X and Y coordinates and N,E,W,S direction were created seperately for easier validation and better user experience
  - User understands X and Y coordinates for robot start positions must be within the bounds of the maximum X and Y boundaries
  - Data will be entered using a keyboard into a browser for Proof of Concept
  - Input fields prohibit a user from keying in invalid character to specific fields for Proof of Concept
  - A 2 week sprint could be planned for a beta release of the solution with some of the following in scope:
      - An admin module to create users and roles
      - User authentication with user name and password
      - Saving robot mission data in a relational data model
      - Extending the logic to a service layer
      - Refactoring UI for responsive design and mobile use
      - Enhancing validation
      - Creating automated unit tests
      - Ability to add any number of robots to a mission
      - Evaluating validation of robot move commands to avoid loss of robots
      - Basic analytic reports of mission and robot data

Source Code Provided:
  - Please find 'mars.zip' which contains the solution in this repo
