The following application talks about Digital Encryption Standard (DES) and it's implemenation

INSTALLATION REQUIREMENTS:
 	Jquery
	Flask
	Python3
	AJAX

To aceess the main page in this repository, go to src/lab/exp7/Introduction.html



Introduction.html provides an intro to DES
Theory.html provides for theory regarding the same
Objective.html provides the aim for the experiment
Experiment.html gives the experiment to be performed
Manual.html provides instructions for the experiment
Quizzes.html gives a quiz on the same topic to test your knowledge, it also uses database elements to store answers
Procedure.html summarizes the procedure for the experiment  
Further Readings.html provides more links to learn about DES_output

In src/lab/js/des.js, we have a function that generates random keys and plaintext to be used for the DES function

Controllers.py recieves questions and options from the database and forwards them to quiz.js
Models.py initalizes the class and loads the questions and options into it.
Quiz.js alters the HTML file Quizzes.html to present the quiz and recieve user answers for the same.
