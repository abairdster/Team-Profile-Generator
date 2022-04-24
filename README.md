
# <center>*Team-Profile-Generator*</center>


![Screenshot of HTML output](https://)


##### <center>*Description*</center>


The Team Profile Generator is a command-line-input application run in Node that requests information from the user about members of an engineering team and generates an HTML file displaying that information.  Before running the application the user must perform an npm install to install all required dependencies.

### <center>*Getting Started*</center>

User launchs the application they are asked to describe the first member of their team.  The user then enters the team member's name and selects that member's role from a list: Engineer,Intern and Manager. User then enters: the member's ID, enters the member's email address and they must enter another piece of information that will depend on what role the User selected.  If Engineer was selected the app asks for the users team member's GitHub username. If Intern was selected the team members school is requested. 




### <center>*Approach Tech*</center>


This app was created using OOP(Object-Oriented Programming). Using constructors and classes to create team member profile objects based on information entered by the User.  The application is run off nodeJs and uses the Inquirer and Filing System nodeJs modules. Objects of files should also be stored in separate JS files and passed among one another using module.exports and require.

### *Dependencies*


 - [GitHub](https://github.com/)

 - [Google](https://google.com/)  [/ Fonts](https://fonts.google.com/)

 - [Read the Docs](https://readthedocs.org/)

 - [MkDocs](https://www.mkdocs.org/)

 - [Jest.io](https://jestjs.io/docs/getting-started)

 - [Node Package Manager](https://www.npmjs.com/)

 - [Stack Overflow](https://stackoverflow.com)


 ## *Installing*


 Jest is used to perform tests on all the class constructors. The FS node module is used to generate an HTML file from strings written in JavaScript.  Since the app will work no matter how many team members the user adds to the system. The HTML is built in a piece by piece mode. It all starts with the head and part of the body.  For each team member the object is created. A new column with a card inside containing the team member information is added.  Then when the last member has been added the last piece of the HTML is added to the file.







## *Authors*

- [abairdster](https://github.com/abairdster)






![GitHub](https://img.shields.io/github/license/abairdster/Team-Profile-Generator?color=%2339FF14)