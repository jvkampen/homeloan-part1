Home Loan Project on Blueprint (OSGi)
=========================================

We have a system, that takes in XML files from different vendor's home loan application, 
they will place their customer input into 2 different XML files, one with it's customer data, 
the other with their housing details. Both files will be place into same folder either 
by FTP or Batch generated overnight.

Our job is to take in and process the information, first we need to separate the 2 kinds of files, 
because they are handled differently. And appraised the value of the house before sending it to a 
messaging broker for further process.


To build this project use

    mvn install

To run the project you can execute the following Maven goal

    mvn camel:run


    
Blog Post
http://wei-meilin.blogspot.tw/2014/07/red-hat-jboss-fuse-getting-started-home.html

Video 
https://vimeo.com/99901083

