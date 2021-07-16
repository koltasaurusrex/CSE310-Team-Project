# Overview


Django-Flash-Cards is an educational application developed to help students study
more effectively and was created by Chris Soares, Christine Helfrich, Lauren Warren, Jacob
Bird and Kolton Heaps.

As the name describes, this project uses the Django framework to handle the back-end services
and allows for easy administration of users and card sets through the built-in admin panel.

To use Django-Flash-Cards you will need to [install Django](https://docs.djangoproject.com/en/3.2/topics/install/)
and then download the project as a zip and extract or run `git clone https://github.com/koltasaurusrex/Django-Flash-Cards.git` to clone the project to your current directory.
After downloading the project, you will need to be in the /Django-Flash-Cards/Django-Flashcards-Web-App folder
and run `python manage.py runserver` to start the server. A web address will be displayed
that you can then navigate to in your browser.

[Software Demo Video](https://youtu.be/Nnio1nj1NNc)

# Network Communication


The architecture of this project is client/server and was accomplished by using python socketserver and socket.
It establishes a TCP connection from server to client and sends data as bytes over the socket stream.


# Development Environment

{Describe the tools that you used to develop the software}
Developed in Atom IDE
Written in Python 3
Libraries
 - socketserver
 - socket
 - pyqt5 for gui

Ubuntu vm running in Virtualbox for better understanding

# Useful Websites

{Make a list of websites that you found helpful in this project}
* [socketserver documentation](https://docs.python.org/3/library/socketserver.html#module-socketserver)
* [QT documentation](https://doc.qt.io/qtforpython/)

# Future Work

{Make a list of things that you need to fix, improve, and add in the future.}
* Scrolling message view in GUI
* Serve message to separate client
* Better GUI
