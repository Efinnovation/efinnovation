# efinnovation
This is efinnovation website

# Setup

# Environtment
	Need 1. NodeJS > 8.0.0
     	     2. ReactJS

# Development

	1. install <code>npm install -g create-react-app</code>
	this will install the module to your system not on a folder

# Getting the project [use the cmd/terminal, assuming you have git installed already]

	1. Git Pull <code>git pull https://github.com/Efinnovation/efinnovation.git</code>
	2. <code>cd efinnovation</code>
	3. <code>npm install </code>

# Testing | Running Project

	1. <code>npm start</code>
	 *should start a server on port 3000 and load the website to your default web browser*

# Deployment

	This projec uses firebase to deploy the website. 

	Please make sure you have firebase login details.
	

	Then:
		1. install <code>npm install -g firebase-tools</code>
		2. run <code>firebase -v</code> to see the version of firebase installed.
		3. run <code>npm run build && firebase deploy</code> to deploy changes to the website.
		4. check your changes from the website if changes are applied then push code, by visiting <i>efinnovation.com</i>

# Commit your changes to git
	
	Once you have made your changes to git you have tested them that they are working correctly. 
	Then you need to add the changes to out git repo.

	1. cofirm files that you have changed by runnig <code>git status</code> will list all the files that you have changed.
	2. Add the files to git stream by running <code>git add . </code> this will add all file. 
	   You can run <code>git add [file name]</code> to add a specific file
	3. Commit changes to git by running <code>git commit -m [reason/explanation of the change]</code> 
	   Please always provide a reason why you made the change so that we can track our work.
	4. Push code to our repo <code>git push https://github.com/Efinnovation/efinnovation.git </code>

	Now visit the git repo at <i>https://github.com/Efinnovation/efinnovation.git</i> to see your resent commit.
	

