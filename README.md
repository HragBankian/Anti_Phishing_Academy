# Best AI Project in Cybersecurity at JACHacks 2024

Devpost: https://devpost.com/software/anti-phishing-academy

Welcome to Anti-Phishing Academy, the winner of the Best AI Project in Cybersecurity at JACHacks 2024!

Anti-Phishing Academy implements a spam email detection logistic regression machine learning model trained with 10,000+ records of data using Python's *scikit-learn* and *joblib* libraries. The model is able to predict if a given email is spam or not with 94% accuracy!

Anti-Phishing Academy also has an educational aspect to it, meant to be used by employers who want to provide Cybersecurity training to their employees. The web application allows employees to create an account and login. Upon doing so, employees can take a quiz to assess their knowledge on spam emails. The quiz prompts sample emails from a pool of ~5000 emails, and the employee has to identify whether the given email is spam or not. For each employee, the number of quizzes attempted and the results of said quizzes are available to the employer.

Our web application is dedicated to educating users about phishing emails and safeguarding against online scams. Explore our comprehensive resources to learn about the tactics used by cybercriminals to trick unsuspecting individuals, and discover practical tips and best practices for identifying and avoiding phishing attempts. From recognizing suspicious email patterns to understanding common phishing techniques, we provide invaluable insights to empower you to protect your personal and financial information online. Stay informed, stay vigilant, and stay safe with our expert guidance on phishing prevention.

In order to successfully run this application, one must make sure the necessary libraries are installed.
To do so, run the following commands:
- pip install numpy
- pip install pandas
- pip install matplotlib
- pip install seaborn
- pip install scikit-learn
- pip install flask
- pip install joblib

For full functionality:
- Run the "submmission_checker.py" file in the "BackEnd" folder.
- Locally host the website found in the "FrontEnd" folder.
- Initialize database parameters properly in "db_connection.php".
