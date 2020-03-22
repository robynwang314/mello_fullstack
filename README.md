# Mello App Full Stack- Trello Clone #

Trello Clone with Ruby, jQuery, JavaScript, modals, authentication, and drag and drop functionality

## Table of Contents ##
<ul> 
  <li><a href="#about"> About </a></li>
  <li><a href="#technologies"> Built With </a></li>
  <li><a href="#setup"> Getting Started </a></li>
  <li><a href="#usage"> Deployment </a></li>
  <li><a href="#contact"> Contact</a></li>
</ul>

<div id="about"></div> 

## About ##
Mello allows users who log in to create new boards, and lists within these boards. Users can drag, drop, edit, and delete cards across boards. They may also add or remove contributors who have access to viewing and editing the boards. 

<div id="technologies"></div> 

## Built With ##
This app integrates the following: 
<ul>
  <li>jQuery</li>
  <li>Rails API</li>
  <li>FactoryBot</li>
  <li>RSpec</li>
</ul>


<div id="setup"></div> 

## Getting Started ##
This project will require a backend Rails-API and database. 

### Set Up Development ###
Change your working directory to <code>mello-rails-api-master</code>.

Create role in the PostgreSQL database for the user vagrant with these commands:
<pre>sudo su - postgres
createuser vagrant -s
exit</pre>

Then, start the Rails server.

In your development environment, run the <code>bundle install</code> command to install the required dependencies.
<br/>Run <code>bin/rake db:setup</code> to configure the database.<br/>
Run <code>bin/rails s</code> to start the server.

<div id="usage"></div> 

## Deployment ##
<img src="screenshot.png" alt="Mello Screenshot" width="45%">

This live project can be view at: https://robyn-mello-app.herokuapp.com/

And it's code can be found at: https://github.com/robynwang314/mello_fullstack


<div id="contact"></div> 

## Contact ##

<ul>
  <li><a href="http://robynwang-portfolio.herokuapp.com/" target="_blank">Portfolio</a></li>
  <li><a href="https://www.linkedin.com/in/tyrobynwang" target="_blank">LinkedIn</a></li>
  <li><a href="https://github.com/robynwang314" target="_blank">GitHub</a></li>
</ul>





