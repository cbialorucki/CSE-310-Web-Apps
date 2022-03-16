# CSE 310 Web Apps
# Overview

This is a polling web application, themed after the Everybody Votes Channel from the now unsupported Nintendo Wii console. Much of the code in this project comes from the official Django beginner tutorial, but I have extended it and added additional functionality. 

To run this project, download the source code and run this command while in the root of the project

`python manage.py runserver`

NOTE: You will need Python and Django installed for this to work.

I wrote this web app in order to learn about Django. Unfortunately, I did not spend as much time as I would have liked. I will continue to work on other Django projects to get a better grasp on how to use it. I come away from this project feeling that Django tries so hard to abstract away web fundamentals that it makes it harder to understand.

[Software Demo Video](https://youtu.be/yz0svaV2i5s)

# Web Pages

This web app has three pages with dynamic content. The home page lists all the polls currently available to vote on. Clicking on any of the polls will lead you to the detail page for that poll.

The detail page lists the question text, and allows a user to select a choice from a list of possible choices. The user can then vote through a form, where the are sent to the results page.

The results page lists how popular each item was. All this information is driven by a SQLite database and is interfaced with Django using models.

To reduce boilerplate code, or repeated code, helper templates were also created to share the header, footer, and some elements in the head section of each HTML page.


# Development Environment

Tools
* Visual Studio Code

Programming Languages and Libraries
* Python
* Django
* SQLite
* HTML/CSS

# Useful Websites

* [Django Official Documentation](https://docs.djangoproject.com/)
* [Real Python: Getting Started with Django](https://realpython.com/get-started-with-django-1/)

# Future Work

* More fully developed template pages would make the web app much more entertaining to use. 
* I needed to dedicate more time to learning Django to appreciate it more. Instead, I got frustrated working with it and wished I was working with a different web app framework instead.
* An account system would result in a more honest voting system and could provide interesting information for people looking back at what they had done on the platform.
