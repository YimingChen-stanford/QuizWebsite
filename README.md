# QuizWebsite
This is a course project I collaborated with (Wei Wang and Biao Song);

I implemented the following features independently:
- Randomly display questions in different orders;
- Display questions in one page or multiple pages at user's choice;
- For multiple pages, user can select immediate feedback which offers feedback when finishing each question.(If not selected, feedback will noly be available upon finishing the whole quiz);
- User can choose practice mode in which the system will not record the user's performance on the quiz. The computer provides additional assistance in practice mode by repeating questions that the user has difficulty with and removing questions that the user knows well;
- User will unlock achivements after he has taken or created enough quizzes;
- Compute user's score based on different modes and different question types;
- User can edit the quiz if he/she is the eidtor of that quiz;
- User can send messages to a friend;
- User can search other users and make friend with them;

I participated in the creation of the following features which are collabarotive work:
- User can be promoted as administritor who has the right to delete users or quizzes.


## The question types we support:

-------------
| Question-Response |
-------------
This is a standard text question with an appropriate text response. For example: Who was President during the Bay of Pigs fiasco?:

-------------
| Fill in the Blank |
-------------
This is similar to standard Question-Response, except a blank can go anywhere within a question. For example: “One of President Lincoln’s most famous speeches was the __________ Address.”

-------------
| Multiple Choice |
-------------
Allow the user to select from one of a number of possible provided answers. Please present multiple-choice questions using radio buttons—this should not be treated as a Question-Response question where the user enters an “A”, “B”, or “C” into a blank textfield.

-------------
| Picture-Response Questions |
-------------
In a picture response question, the system will display an image, and the user will provide a text response to the image. 

-------------
| Multi-Answer Questions |
-------------
This is similar to the standard question-response, except there needs to be more than one text field for responses. Allow the quiz creator to determine if the responses need to be in a particular order or not. For example, list the 50 states in the US (order not relevant) or list the 10 most populous countries in the world in order from largest to smallest.

-------------
| Multiple Choice with Multiple Answers |
-------------
This is similar to a standard multiple choice question, except the user can select more than one response. For example: please mark each statement below which is true (1) Stanford was established in 1891, (2) Stanford has the best computer science department in the world, (3) Stanford will be going to a bowl game this year.

-------------
| Matching |
-------------
User has an equal number of choices on the left side and the right side, and will be asked to pair them on a one-to-one basis. 


