# Homework 9
    This five basic tutorials are completed on the learn.knockoutjs.com.

# Introduction
   In this part of the tutorial students will experience some of the basics of building a web UI with the Model-View-ViewModel (MVVM). when users run this program they will get two text box with default fist and last name from the program itself. When user enter the name in the box it will display the name on the window. And it will allow user to capitalize the last name using Go caps button. 
  
# Working with list and collections
    In this tutorial stdents gets to work with list and collection of items, students will build a dynamic UI for reserving seats and meals. The program lets the user to add and delete the list of reservations. The program provides user with the button to add reservation and link to delete reservation. 
  
# Single Page Application
    In this part of the tutorial students will webmail client. The output of this application looks and act like gmail, outlook, yahoo, etc.. This tutorial go through the methods to build such webmail which lets client to view their Inbox, archieve, sent, and spam messages. The program provides the user with folder on the top to view type of messages such sent, spam, archieve, or Inbox, and below it display the list of emails to/from people, and they can actually read the messages by clicking on the list of emails. 
  
# Creating Custom Binding
    In this tutorial we will create something like a survey. Here we will ask user a question, the particular quesftion asked on the program is "Which factors affect your technology choices?", and we gave them options, in code it looks like this: 
    
    ko.applyBindings(new SurveyViewModel("Which factors affect your technology choices?", 10, [
   "Functionality, compatibility, pricing - all that boring stuff",
   "How often it is mentioned on Hacker News",    
   "Number of gradients/dropshadows on project homepage",        
   "Totally believable testimonials on project homepage"
]));

And we provide start based rating system to rate which option is more important to them. 

# Loading and Saving Data
    In this part of the tutorial we create a list of tasks that are in need of complication. We wrote a program that allows user/client to add the list of work or task they need to do, and once those task are completed we implement the function on the program to let the user delete that task from the list. Then, the program allows client to save their list using save button after adding or deleting the list of task.  
This exercise was the great review and experience on MVVM. 
