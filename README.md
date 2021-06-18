# Django Project Git Upload and Error Fixing

<h3>Create Django Project and App</h3>
<p>Create a new directory and install django</p>
<code>pip install django</code><br/>
<code>django-admin startproject project_name .</code><br/>
<code>python manage.py startapp app_name</code>

<h3>Upload Project In Github</h3>
<p>Create new repository in github. In the terminal open project path. Then paste the following command</p>
<code>git init</code><br/>
<code>git add .</code><br/>
<code>git commit -m "Initial Commit"</code><br/>
<code>git branch -M main</code><br/>
<code>git remote add origin https://github.com/mohammad2745/Django-git-error.git</code><br/>
<code>git push -u origin main</code><br/><br/>

<p>After Changing code process to add code in the existing repository</p>
<code>git add .</code><br/>
<code>git commit -m "Changes Applied"</code><br/>
<code>git push -u origin main</code><br/><br/>

<p>To add .gitignore visit <code>gitignore.io</code>. And create .gitignore file in the main directory.</p>
<br/><br/>
<h3>Error Handling</h3>
<p>While committing this error "fatal: remote origin already exists" may show.</p>
<p>To solve this error, you should first check if the current remote associated with the “origin” keyword has the correct URL. You can do this using the git remote -v command:</p>
<code>git remote -v</code><br/><br/>
<p>You will see a list formatted like this:</p>
<code>origin    https://github.com/career_karma_tutorials/git (fetch)<br/> 
origin   https://github.com/career_karma_tutorials/git (push)</code>
<br/><br/>
<h6>The Solution </h6>
<p>To remove the existing remote and add a new one, we can set a new URL for our remote:</p>
<code>git remote rm origin</code><br/>
<code>git remote add origin https://github.com/mohammad2745/Django-git-error</code><br/><br/>
<p>This removes our existing “origin” remote and replaces the remote with a new one called “origin”, using the URL we have specified. But, this method uses two commands instead of the one that we used earlier.</p>
