# HTML
* **Block elements** are elements that start on their own line.
	* h1, h2...
	* p
	* ul
	* li
	* p 
	* hr

* **Inline elements ** are elements that do not start on their own line. They share a line with other elements.
	* em
	* strong 
	* a href 
	* img  

# Bootstrap (http://getbootstrap.com/getting-started/#download)
	* CDN
	* Download directly into project
* class="container"
* class="jumbotron"
* Helper classes (http://getbootstrap.com/css/#helper-classes)
	* bg-success
	* bg-info
	* well
	* panel panel-default
	* panel panel-info
		* panel-body
	* panel-heading
		* panel-title

# Unix commands
* cd 
* cd ..
* mkdir
* pwd
* ls
* ls -a
* cp -R SOURCE-FOLDER-FILE DESTINATION-FOLDER-FILE
	* cp -R 02_Git-HTML-CSS/01my-first-webpage/my-first-webpage.html 03_Git-HTML-CSS/

# Git commands
* git init
* git status
* git diff
* git add
* git add .
* git add -A
* git commit -m "COMMENTS"
* git push

* git remote add origin <URL OF REMOTE REPO>
	**THIS WILL ADD REMOTE REPO AS NICKNAME ORIGIN 

* git remote -v
	**THIS WILL TELL YOU THE NICKNAME AND URL OF REMOTE GIT REPO

* git push -u origin master
	**THIS WILL PUSH TO REMOTE ORIGIN FROM LOCAL MASTER

* git log
* git about
* git commit --amend <THIS AMENDS LAST COMMIT MESSAGE>
	* THIS WILL OPEN VIM EDITOR ON MACBOOK BY DEFAULT.
	* TO SAVE CHANGES (AND STILL IN INSERT MODE)...(https://www.cyberciti.biz/faq/linux-unix-vim-save-and-quit-command/)

	  * If you are currently in insert or append mode, press Esc key.

		* Press : (colon). The cursor should reappear at the lower left corner of the screen beside a colon prompt.

		* Enter the following command (type :x and press Enter key):

		* x
		* OR

		* x!
		* OR

		* wq!
		* This will quit the editor, and all changes you have made to the document will be saved to the file.