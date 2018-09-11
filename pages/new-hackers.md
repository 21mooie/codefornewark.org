---
title: New hackers
author: Code For Newark
layout: default
permalink: /new-hackers/
---

The information you need to get started with Code for Newark.

#### Civic Hacking 101

<iframe width="640" height="360" src="https://www.youtube.com/embed/wH6LnW_qjeI" frameborder="0" gesture="media" allowfullscreen></iframe>

#### What is Github?

Github is a platform that is used by millions of developers all over the world to help share their projects and allow others to easily collaborate. On the Codefornewark team, we use Github for this exact purpose.

<iframe width="640" height="360" src="https://www.youtube.com/embed/w3jLJU7DT5E" frameborder="0" gesture="media" allowfullscreen></iframe>

#### History and Difference between Git and Github

It is important to know that there are two distinct but cooperating tools used by devs called Git and Github. Git is the program used to track changes in a project whereas Github is the hosting platform that is used to make a project available to collaborators. This video dives deeper into the history of how these tools came about. While the whole video is informative and you are recommended to watch, you can skip ahead to 1:26 where the more pertinant information begins.

<iframe width="640" height="360" src='https://www.youtube.com/embed/1h9_cB9mPT8' frameborder="0" gesture="media" allowfullscreen></iframe><a href=''></a>

#### A Common Git/Github Workflow

This depicts a common way Git and Github are used in actual projects by developers. It walks you through different commands used by these tools. Look through these definitions as you watch the video below.

- <b>Repository</b> is the project that is being developed. These usually are made using one or more programming languages, is intended to complete a defined purpose, and usually uses a version control system such as Git to track its changes during development.
- <b>Commit</b> is a snapshot of a project at a specific point in time which can always be revisited later on in a project's development making it like an enhanced version of saving.
- <b>Branch</b> is a different version of the repository that allows for potentially breaking changes to be developed safely with the original version still in tact with the intent that once these changes are safe they can be safely merged back into the original repository.
- <b>Pull</b> brings changes in a different repository than the one currently being used. This merges those changes into the repository.
- <b>Pull Request</b> is when you have made changes to a repository that is owned by someone else in your own local version and you are <em>requesting</em> that they incorporate those changes into their repository.
- <b>Push</b> takes your local changes and gives them to a remote repository most commonly the repository hosted on Github.
- <b>Fork</b> creates a new version of a repository that allows you to develop while having the freedom of not being tied down to the original version of the repository.

<iframe width="640" height="360" src="https://www.youtube.com/embed/_ALeswWzpBo" frameborder="0" gesture="media" allowfullscreen></iframe>

#### Let's create a Github account!

Talk is cheap. Let's create our own Github account so we can start developing our own project: a personal website!

<a href='https://github.com' target="\_blank"> Click here to sign up.</a>

#### Let's fork this repository

<a href='https://github.com/21mooie/small-web-projects' target="\_blank"> Go to the repository here. </a>

Click on the fork button in the top right corner.
<img src="{{ "images/new-hacker-images/Fork_Screenshot.png" | relative_url }}"  alt="Screenshot of Github Fork button" class="img-responsive"/>

#### The Github Desktop Client

Normally, developers will use the command line during development to invoke specific commands such as Git's commands. It can be hard to remember these when you are just starting out with development so often it is nice to have a graphical tool that has the power to execute the same commands on the command line. The desktop client is just that tool. It will give us the power to commit changes, create new branches, push to our Github repository, pull changes from our Github repository all without touching a terminal.

<a href='https://desktop.github.com/' target="\_blank">Let's download the Github desktop client</a>

Login to your Github account with the desktop client then pull your repository down to your local machine.

Once logged in, you will need to clone the repository that already exists on your Github account to your local computer so click the Clone a Repository button.


<img src="{{ "images/new-hacker-images/Clone_Github_Repo_Screenshot.png" | relative_url }}"  alt="Screenshot of Github Fork button" class="img-responsive"/>

Select the small-web-project repository, if you just created your Github account it should be the only project listed.

<img src="{{ "images/new-hacker-images/Selecting_Repository.png" | relative_url }}"  alt="Screenshot of Github Fork button" class="img-responsive"/>

Let's have a small break and enjoy this cat gif :)
![Alt Text](https://media.giphy.com/media/vFKqnCdLPNOKc/giphy.gif)

<img src="{{ "images/new-hacker-images/Clean_Project_View.png" | relative_url }}"  alt="Screenshot of Github Fork button" class="img-responsive"/>

What we are looking at now is the project view. On the left panel, at the top, you see what the current project you are viewing is. Right now, it should say small-web-projects. To the right of that is the name of the branch you are currently on. This should say master.

Underneath the current repo header, there should be a tab that says Changes, when this is selected, it will show all the changes that have been made in the project since the last tracked commit. To the right of that is History, this should show the complete history of commits from that branch. 

<img src="{{ "images/new-hacker-images/History_View.png" | relative_url }}"  alt="Screenshot of Github Fork button" class="img-responsive"/>

You now have Github Desktop installed and are ready to start editing your code. But wait ... we need an editor to do the editing.

#### A Tale of three text editors

A text editor is to a software developer as a canvas to a painter. There are many strong feelings in the community about what text editors need to be able to do well and which one is the (queue air quotes) <em> best </em>. Just so you know, there is no best editor, there is only the best <b> for you </b>. This video showcases three popular choices for text editors. Choose one so we can continue working on our website. At some point in time, it is recommended that you atleast try each of these options to get a better feel for what you like from a text editor.

<iframe width="640" height="360" src="https://www.youtube.com/embed/J-CCFzoVywY" frameborder="0" gesture="media" allowfullscreen></iframe>

#### Choose your Pokémon

- <img src="{{ "images/new-hacker-images/squirtle.png" | relative_url }}"  alt="Image of Squirtle" class="img-responsive"/>
<a href='https://code.visualstudio.com' target="\_blank">Visual Studio Code</a>
<br>
A very composed editor that has many features all included giving you the ability to be productive from initial download.

- <img src="{{ "images/new-hacker-images/bulbasaur.png" | relative_url }}"  alt="Image of Bulbasaur" class="img-responsive"/>
<a href='https://atom.io' target="\_blank">Atom</a>
<br>
Popular and used by developers all over, support for this editor is managed by Github itself, meaning help using this editor is always a quick Google search away.

- <img src="{{ "images/new-hacker-images/charmander.png" | relative_url }}"  alt="Image of Charmander" class="img-responsive"/><a href='https://www.sublimetext.com' target="\_blank">Sublime Editor</a>
<br>
This editor is lightning fast and very small. It uses such little memory that you won't have to worry about using other computer resources during development.

#### Edit website

Make changes to the code based on information in README.md of project. There are some things which need to be fixed. When finished, push your changes back to your forked repository on Github.

#### Submit a pull request

Now we need your changes to be put into the version hosted by Code For Newark.

<a href='https://github.com/21mooie/small-web-projects' target="\_blank"> Let's submit a pull request </a>

#### Thank you!

You have made it to the end of this tutorial used by Code For Newark. We have a short little survey that we would like you to fill out to help us improve as an organization.

<a href='https://docs.google.com/forms/d/e/1FAIpQLSeig-UI6YfagGOhnj4g4Z7pYlaX_YhNXzag3vge4j6GaPmoHA/viewform' target="\_blank">Please complete this survey</a>
