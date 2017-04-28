"# nicholasmooney.com" 

This is a personal project to drive my education in web development. The code is open to anyone to read through, critique, offer suggestions, etc.

You are also welcome to Clone and modify for your own use moving forward.



A couple of key notes for my own sake:

WINDOWS
git add * 
## adds whatever files you've modified and would like to commit
git commit -m "message"
## commits the changes to master unless another branch specified
git push origin master
## pushes to github master directory. This will help with transfer of latest files between windows desktop and macbook.
gsutil cp * gs://www.nicholasmooney.com
## this copies all files to google cloud storage for the site. This will only be true while the site is still a static .html site. Once I get to the MEAN stack application, will probably use a different command (gcloud something).


MAC
# Need to add