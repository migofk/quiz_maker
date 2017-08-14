# quiz_maker
Quiz web app, build in php laravel 5.4 framework.  you can create quizzes with tags and put different score for every question. 
 <br>
  <br>
<strong>What is quiz maker?</strong> <br>
Quiz maker is a free web app for creating quizzes or tests and all quizzes will be available for your audience. you can download the project and add your website templates as any laravel 5.4 project. 
<br>
 <br>
<strong>How to use it?</strong> <br>
It's so simple if you are familiar with laravel 5.4. You need to create your own website template but you can start the app with the current template for development purposes only once you are live you must remove the template,logos, favicon and anything related to a4mweb.com.   
 <br>
<ol type="1">
<li>Download the project and unzip it. </li>
<li>Configure the app with your local environment. Migrate the tables “php artisan migrate” </li>
<li>Open the web app as any laravel site and run a local server “php artisan serve”.  Then got to “/register”.. Ex:  http://127.0.0.1:8000/register  and register a new account .</li>
<li>open the Users table in your database and insert “admin” in role column at your record. </li>
<li>got to “/home” then click on add new tag link and add new tag. NOTE The app doesn’t work without adding tags first  </li>
<li>Press add new quiz and add you first quiz, A. Name of the quiz B. The total score C. The instruction. D.category(tag) then click next to add the questions  </li>
<li>A. Question and question score B. every Answer with its score. Click save to save the question (you don’t say). You can add a new question or click cancel to go back to “ / ”  </li>
<li> in  “ / ” if you are an admin you will see “Edit” link next to the quiz link. </li>
<li>Click the Edit link if you want to Edit  (Really click Edit to Edit) and add new a question or delete a question. Update, name, tag, answers and questions.(that’s it.) No, wait, there is more you can delete the whole quiz.</li>
</o>
 <br>
 <br>
 <strong>
 Tips</strong> <br>
You can create admin middleware to prevent users to add quizzes. In the project folder  routes\web.php at line 23   “//admin area” comment  all the below routes are for admin. In Users table insert “admin” in role column to make a user an admin.  <br>
 <br>
Finally. This is not a 100% complete project. You need to make a web design to it for frontend as well as the backend and customize the app to suit your needs.
