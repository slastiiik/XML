# <h1 align="center"> XML </h1>
Create an remote repository named XML.

A repository is created in github.

	=> respositories => new
	
Clone the XML repository to the local machine.

	git clone
 
Inside the local XML, create a "new.xml" file.

	touch new.xml
	
Add file to git.

	git add new.xml
	
Commit the file.

	commit –m “add new.xml”
	
Submit a file to an remote GitHub repository.

	git push
	
Edit the content of the “new.xml” file - write information about yourself (name, age, number of pets, future desired salary). Everything is written in XML format.

	vim new.xml

to start editing
	
	=> i

	<xml>
	<Name>"Anastasia Aleksandrovna"</full name>
	<Age>"20"</Age>
	<Number of pets>"1 cute kitty"</Number of pets>
	<Future desired salary>"100 million"</Future desired salary>

to exit editing
	
	=> esc => :wq
	
Push changes to an remote repository.

	git add new.xml

	git commit –m “edited content”
 
	git push

Create preferences.xml file

	touch preferences.xml

In the preferences.xml file, add information about your preferences (Favorite movie, favorite series, favorite food, favorite season, side you would like to visit) in XML format.

	vim preferences.xml

to start editing
	
	=> i
	
	<xml>
	<Favorite Movie>"The Maid"</Favorite Movie>
	<Favorite series>"Killing Eve"</Favorite series>
	<Favorite Food>"Noodles"</Favorite Food>
	<Favorite season>"Spring and autumn"</Favorite season>
	<Country I want to go to>"France"</Country I want to go to>

to exit editing
	
	=> esc => :wq
 
Create a sklls.xml file add information about the skills that will be studied in the course in XML format

vim skills.xml

to start editing
	
	=> i
	
	<xml>
	<Skills>"Basic theory. HTTP structure and methods. JSON, XML, their structure. API testing via Postman. Mobile testing. SQL basics." </Skills>

to exit editing
	
	=> esc => :wq

Make a commit in one line.

	git commit –m “new xml files”

Send 2 files at once to an external repository.
	
	git add .
	
	git push
	
Create a bug_report.xml file on the web interface.

The bug_report.xml file is created in the github.

	add file=>create new file

Make Commit changes on the web interface.

	сommit changes

Modify the bug_report.xml file on the web interface, add a bug report in XML format.

The bug_report.xml file changes in the github.

	=>Edit this file
	
	<xml>
	<Summary>"Persistent sneezing"</Summary>
	<Project>"Nastya"</Project>
	<Component>"Nasopharynx"</Component>
	<Version>"1.20" </Version>
	<Severity>"S5 Trivial"</Severity>
	<Priority>"P3 Low"</Priority>
	<Status>"New"</Status>
	<Author>"Anastasia" </Author>
	<Assigned To>"Anastasia"</Assigned To>
	<Description>"The bug was found at home, this error was caused by allergies or dust, just take a deep breath and the error will repeat. </Description> 
	<Actual result>”sneezing” </Actual result>
	<Expected result>”no sneezing”</Expected result>
	
Make Commit changes (save) changes on the web interface.
	
	сommit changes

Synchronize remote and local XML repository

	git pull (to check if everything is synced correctly use the git fetch command)
