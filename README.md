# Tutoring Website
I decided to address a need in our school community for a comprehensive platform to coordinate math tutoring. I am using my newfound knowledge in PHP to code and program a website for the school's math department. It is still in development - so far the login script has been made (for which the directories are shown above). This is definitely the largest project that I am undertaking, which has allowed me to appreciate the breadth of software development, and gaining satisfaction gained from making software to achieve a goal.

An algorithm which determines which students in their specific time frames can connect to tutors within their availability is currently being developed for the website.

This login script has taken me several months to complete with various complications along the way. This was done in tandem with my IB workload, I coded all of the files and respective directories shown above. That being said, it would have been finished earlier if I had put my undivided attention to it. The localhost is stored on WAMPSERVER2.5. The database is created on the server under phpmyadmin, where a query such as - INSERT INTO `users` (`username`, `password`, `first_name`, `last_name`, `email`) VALUES ('Aryan', '5f4dcc3b5aa765d61d8327deb882cf99', 'Aryan', 'Cheema', 'aryan.cheema.152@my.aquinas.me') is executed onto the user database on MYSQL, since, it is the command that will be iterated for every user that registers onto the website through the registration form.

The most important function that I learnt was breaking up the HTML template into various directories. The "core" directory contains functions, initialization and database connections. The "generic" includes folder houses the template itself, the widget on the right-hand side of the website which houses the login form has its independent folder. The "includes" folder also has the "overall" folder which will be made up of the header and the footer of the website. Breaking up the template and organizing it in different directories of the root directly allowed me to edit the text if necessary with ease. In order to make sure the broken up piece of the template links back to the original HTML template - the following script is implemented. 

If we wanted to replace the header with the original script, this following code would be written into the directory:

<? php
include 'includes/head.php';
?>

Moreover, I also learnt how to organize user data, establish error handling with various prompts for an incorrect password, incorrect email, registration, account activation, username/password combination, and many other errors (the script for these can be located on the login.php file above). I also learnt how to validate data after it was fed through the registration form on the website, which - in turn established connection with the mySQL user database on phpmyadmin on my server. 

The next step in making the login process better is by protecting the website by preventing people who haven't logged in or registered from accessing information which shouldn't be available to them. If you would like to ask any questions about my process you can contact me at - aryan.cheema.152@my.aquinas.me.

I have hosted the website using 000webhosting, and using an FTP client to transfer my files from a local to a live server. 

Since I'm implementing the Javascrip code into the website I have taken it down. If you would like the website address I can host it temporarily if someone would like to take a look at it. Contact me by my email - aryan.cheema.152@my.aquinas.me

<img width="896" alt="kjbvkdn" src="https://cloud.githubusercontent.com/assets/16159880/13625634/c22c5c42-e587-11e5-8506-61008bc3f466.PNG">
<img width="838" alt="diweudfj" src="https://cloud.githubusercontent.com/assets/16159880/13625636/c374521c-e587-11e5-8710-f107cbecbf18.PNG">


The following screenshots are of the website with the localhost sever on my computers "cas_project" directory (look on the URL of the screenshots).
