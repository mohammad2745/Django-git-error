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