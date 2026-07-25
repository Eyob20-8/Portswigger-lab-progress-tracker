Vulnerbitiy: Path transversal
Level: Appenrentice,Practitioner
The common Path transversal vulnerabilitys are 
- File path traversal, simple case:
  simply modify the parameter of filename to passwd file using relative path.  
- File path traversal, traversal sequences blocked with absolute path bypass
   retrive file according to current directory for which doest allow the traversal sequence.
- File path traversal, traversal sequences stripped non-recursively
  doulbe the slash(/) for validing the filename parameter 
- File path traversal, traversal sequences stripped with superfluous URL-decode:
   web server input sanitisation using by URL-encodingg otherwise it may strip which if it is transversal sequence.
- File path traversal, validation of start of path
  validate the filename parameter based on start of the path which may be the root of the file.
- File path traversal, validation of file extension with null byte bypass
   The web server validate the filename at end of the which is expected the file extension such as png ,jpg,pdf and soon.
  1.Lab:File path traversal, simple case
    Step1:click the detail of one the product which is listed.
    Step2:intercept and modify the image request  filename parameter into ../../../etc/passwd.
    Step3:As result etc/passwd file will appper.
  2.Lab:File path traversal, traversal sequences blocked with absolute path bypass
    Step1:click the detail of one the product which is listed.
    Step2:intercept and modify the image request  filename parameter into /etc/passwd.
    Step3:As result /etc/passwd file will appper.
  3.Lab:File path traversal, traversal sequences stripped non-recursively
    Step1:click the detail of one the product which is listed.
    Step2:intercept and modify the image request  filename parameter into ..//..//..//etc/passwd.
    Step3:As result etc/passwd file will appper.
  4.Lab: File path traversal, traversal sequences stripped with superfluous URL-decode
     Step1:click the detail of one the product which is listed.
     Step2:intercept and modify the image request  filename parameter into URL-encode of passwd which is ..%252f..%252f..%252fetc/passwd.
     Step3:As result etc/passwd file will appper.
  5.Lab: File path traversal, validation of start of path
     Step1:click the detail of one the product which is listed.
     Step2:intercept and modify the image request  filename parameter into start from base file which is /var/www/images/../../../etc/passwd.
     Step3:As result etc/passwd file will appper.
  6.Lab:File path traversal, validation of file extension with null byte bypass
     Step1:click the detail of one the product which is listed.
     Step2:intercept and modify the image request  filename parameter into start from base file which is ../../../etc/passwd.png
     Step3:As result etc/passwd file will appper.
