## Robotic Process Automation final project.

**Functionality:**
<br>

 - logs in the user 
 - searches jobs acording to his preferences (domain,city, level of experience and job type)
 - adds each job to "Favourites" ( we did not want to directly apply for a job, we want to let the user make this kind of commitent, however this can easily be changed)
 - the user has to write his credentials and his preferences in an Excel input file, he can add more records with different data and they will all be proccessed sequentially  
 - if the program finds incomplete or corrupt input data (like wrong job name, city or domain) it passes on to the next record from the excel file
 
 <br>
 
 **How it works:**
 <br>
 
 - first the robot reads all the data from the excel and stores it in a data table
 - then it opens the browser(Chrome) and searches for Hipo.ro
 - it types in the credentials of the user and loggs in the user
 - next it goes to the search bar page, it types in the name of the job, domain, and city. If any of these are wrong it 
 just logs out and moves on to the next record. 
 - after searching jobs with these preferences, it adds the job level and job type(full time,partime) 
 - on the data rendered by the site it makes Data scrapping adding the job names, companies and the URLs for the jobs page to another excel file
 - in a for loop it access each URL in the excel and adds each job to "Favourites" list of the user who is currently loged in
 - at the end it logs the user out and moves on to the next record.
 
 **Link for the demo(5 data sets):**
 <br>
 https://youtu.be/RCaOD4cbkMk
 <br>
 <br>
  **Link for the demo with error handling:**
  <br>
  https://youtu.be/SF2bT2DWFHU
 <br>
 

by [@IoanaBajan](https://github.com/IoanaBajan) and [@BetyDobre](https://github.com/BetyDobre)
