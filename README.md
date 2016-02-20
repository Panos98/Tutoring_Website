# Tutoring_Website
I decided to address a need in our school community for a comprehensive platform to coordinate math tutoring. Having some degree of programming knowledge, I am using my newfound knowledge in PHP to code and program a website and web app for the school's math department. It is still in development - so far the login script has been made (for which the files are shown above).

An algorithm which determines which students in their specific time frames can connect to tutors within their availability is being integrated into website.

This login script took me more than a month to construct on top of my IB workload. It would have been finished earlier if I had put my undivided attention to making it. I downloaded WAMPSERVER2.5 which is where I host the website. The database is created on the server under phpmyadmin, where a query such as - INSERT INTO `users` (`username, `password`, `first_name`, `last_name`, `email`) VALUES ('Billy', '5f4dcc3b5aa765d61d8327deb882cf99', 'Aryan', 'Cheema', 'aryan.cheema.152@my.aquinas.me') is executed onto the user database on MYSQL since, it is the command that will be iterated for every user that registers onto the database. 

The most important function that I learnt was breaking up the HTML template into various directories. The "core" directory inside contains functions, initialization and database connections. The generic includes folder houses the template itself, the widget on the right-hand side of the website which houses the login form has its independent folder as well. The includes folder also has the "overall" folder which will be made up of the header and the footer of the website. Breaking up the template and organizing it in different directories of the root directly allowed me to edit the text if necessary with ease due to simple navigation of various parts of the HTML template (for ex. the header, footer, aside, widgets, menu etc.) In order to make sure the broken up piece of the template links back to the original HTML template - the following script is implemented. 

If we wanted to replace the header with the original script, this following script would be implemented:

<? php
include 'includes/head.php';
?>

Moreover, I also learnt how to organize user data, establish good error handling with various prompts for an incorrect password, incorrect email and other queries. I also learnt how to validate data after it was fed through the registration form on the website, which - in turn establishing connection with the mySQL user database on phpmyadmin on my server. 

The next step in making the login process better is by protecting the website by preventing people who haven't logged in or registered from accessing information which shouldn't be available to them. If you would like to ask any questions about my process you can contact me at - aryan.cheema.152@my.aquinas.me
