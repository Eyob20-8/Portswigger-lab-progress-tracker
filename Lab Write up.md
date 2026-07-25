Vulnerbitiy: Path transversal
Level: Appenrentice,Practitioner
The common Path transversal vulnerabilitys are 
- File path traversal, simple case:
  simply modify the parameter of filename to passwd file using relative path.  
- File path traversal, traversal sequences blocked with absolute path bypass
   retrive file accorfing to current directory for which doest allow the traversal sequence.
- File path traversal, traversal sequences stripped non-recursively
- File path traversal, traversal sequences stripped with superfluous URL-decode
- File path traversal, validation of start of path
- File path traversal, validation of file extension with null byte bypass
  1.Lab:File path traversal, simple case
    Step1:click the detail of one the product which is listed.
    Step2:intercept and modify the request  filename parameter into ../../../etc/passwd.
    Step3:As result ../../../etc/passwd will appper.
  2.Lab:File path traversal, traversal sequences blocked with absolute path bypass
    Step1:click the detail of one the product which is listed.
    Step2:intercept and modify the request  filename parameter into /etc/passwd.
    Step3:As result /etc/passwd will appper.
  3.Lab:File path traversal, traversal sequences stripped non-recursively
    Step1:click the detail of one the product which is listed.
    Step2:intercept and modify the request  filename parameter into ..//..//..//etc/passwd.
    Step3:As result ..//..//..//etc/passwd will appper.
  
