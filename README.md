# Jmeter

1. Tests.jmx

This Project contains my case studies using Jmeter
Perfomance Testing of an Application

First Test Case

  In the first test we test with 5 users and assume all the users are trying to access the server at the same time
   
   All the users access 3 pages in the selected page (jmeter.apache.org)

   All the users have a waiting time before accessing the pages

   It is assumed that URL can be changed in the future, therefore a base URL has been added

   And finally a tabular report with a graph is generated 



Second Test Case

  In the second test we test with 10 users and assume all the users are trying to access the server in time span of 60 seonds
   
   All the users access 3 pages in the selected page (jedox.com)

   Verify all requests perform its task within 5 seconds else fail reason is given
   
   We should not get any Error or Warning text in response
   
   It is assumed that URL can be changed in the future, therefore a base URL has been added

   And finally a tabular report with a graph is generated 


Third Test Case

  In the Third test we test with 10 users and assume all the users are trying to access the server in time span of 120 seonds
   
   All the users access 3 pages in the selected page at the same time (jedox.com)

   The data which is coming from the server is saved for future reference
   
   We should not get any Error or Warning text in response
   
   It is assumed that URL can be changed in the future, therefore a base URL has been added

   And finally a tabular report with a graph is generated 

   
   2. performance.jmx
      The peformance of www.jedox.com is tested using jp@gc - Stepping Thread Group. The results are shown in different graphical methods
      
   3. RegularExpression.jmx

      The use of regular expression in Jmeter is tested. First it navigate to  www.jedox.com main page and navigate to a sub-page based on the regular expressions specified. 
