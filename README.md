# CodePath Week 8

1\. **Challenge 1 - Username Enumeration:** The vulnerability is present in the Green website. The mistake that was made was that when a username is found, the error is in bold, but when a username does not exist, the error appears in normal print.

2\. **Challenge 2 - Insecure Direct Object Reference:** The vulnerability is present in the Red Website. This can be see when we input id numbers 10 or 11 into the url. The other two redirect to the territories.php page if the salesperson does not currently work at globitek

3\. **Challenge 3 - SQL Injection:** The blue one does not properly santize the id that is submitted using the url. If we input ' OR SLEEP(5)=0--' as the id, it will sleep for 5 seconds, whereas the other two automatically return to the territories.php page.

4\. **Challenge 4 - Cross-Site Scripting:** This vulnerability is present in the green website in the feedback page, which does not correctly sanitize stored data.

5\. **Challenge 5 - Cross-Site Request Forgery:** The red site is vulnerable to cross site scripting. The code for an html form that changes Jim's name to "JIMSTER" is located in the html file named "CSRF.html". I could not figure out how to submit the form without redirecting to the red site.

6\. **Challenge 6 - Session Hijacking/Fixation:** The blue website is vulnerable to this attack.