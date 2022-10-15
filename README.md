# EmoryOJ
This is Emory OJ System, work under development
An OJ is one that is used to determine the programming capability of a user, commonly used in coding interviews alongside competitions of algorithms. Many online OJ are available, but this one is used to help in particular Emory students and faculty with the judging of assignments. The highlight of this project is to offer developers an opportunity to demonstrate their familiarity with web design, and to allow a more custom-based design.
The OJ is divided into two parts:
1) Front end: The place in which the interface is shown. An interface is consisted of i) the login page ii) the coding page, in which there is the prompt and a space to submit a code iii) a result page, in which the user will either be  or not be able to see the results or details of their or their peers' submission. If a result is allowable to be seen, they will be informed of only i) pass or ii) not pass, because of several abstract error message (code not compiled, wrong answer, or too long time). If a detail is allowable to be seen, they will be informed of on which specific test cases their run did not pass.
2) Back end: This is where the users' code are run against a specific set of input data. For adminstartive roles' users, they are allowed to configure a set of data and their answers. The back end will then run a single submitted user's code, and compare it against the proper answer. If all tests are passed within a time limit, they will return the front end based on the judgement protocol. If not, the backend must record the information so that visibility can be easily changed.

This code repertoire will thus be updated, so that eventually a website will be generated, and proper validation should be done to allow students to submit their code and the faculty to submit their results.

To cooperate with the front end and back end, a specific database must be maintained, and proper login methods and information must be stored correctly. IN addition, tests will be often for the time being. 

The following is an example:
<img width="935" alt="image" src="https://user-images.githubusercontent.com/52821055/195997615-2da4aaba-318e-4dfd-b457-378b98e5bd6c.png">
1) We have a login and sign up on the top 
2) A description is pulled from database
3) Several input and output will be provided by administrator
4) A submission link will be provided and user is to be able to submit
(http://www.hustoj.org/status)
Please see the webpage for more trials.
A submission page should look like the following:
<img width="924" alt="image" src="https://user-images.githubusercontent.com/52821055/195997746-53499b2f-8e0a-44b2-a44b-72741b1cb5f2.png">
(https://open.kattis.com/)
The sole purpose of the project is to pull from an existing open-source software and update so one can learn the process of web development without developing much of the actual code. 
