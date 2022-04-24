
# <center>*Team-Profile-Generator*</center>


![Screenshot of HTML output](https://)


##### <center>*Description*</center>


The Team Profile Generator is a command-line-input application run in Node that requests information from the user about members of an engineering team and generates an HTML file displaying that information.  Before running the application the user must perform an npm install to install all required dependencies.

### <center>*Getting Started*</center>

Upon launching the app, the user is asked to describe the first member of their team.  The user enters the team member's name, selects that member's role from a list: Engineer,Intern and Manager.,Then User enters: the member's ID, enters the member's email address and then must enter another piece of information that will differ depending on what role was selected.  If Engineer was selected, the app asks the user for the team member's GitHub username. If Intern was selected; the member's school is requested. If Manager was chosen, the user is prompted for the team member's phone number. When all information on the team 




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


 Jest is used to perform tests on all the class constructors to ensure that they behave as expected.  The FS node module is used to generate an HTML file from strings written in JavaScript.  Since the app will work no matter how many team members the user adds to the system, the HTML is built in a piecemeal fashion, starting with the head and part of the body.  For each team member object created, a new column with a card inside containing the team member information is added.  Then when the last member has been added, the last bit of the HTML is added to the file.  One complication experienced during this process was that since the fs.appendFile method is asynchronous, the bottom part of the HTML could be added before the HTML containing information on the last team member had been added.  In order to deal with this, the function that adds the team member information to the HTML was converted into a promise, and only once the promise was resolved would the bottom part of the HTML be added to the output file.








## *Authors*

- [abairdster](https://github.com/abairdster)






![GitHub](https://img.shields.io/github/license/abairdster/Team-Profile-Generator?color=%2339FF14)