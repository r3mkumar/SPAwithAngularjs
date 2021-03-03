# Single-Page-Web-Applications-with-AngularJS
## assignment 1
this assignment is to create a front-end application that presents the user with a textbox where they can list comma-separated items they usually eat for lunch. Once that's entered, the user has to click the "Check If Too Much" button.

### [Module 1 Coding Assignment](https://r3mkumar.github.io/SPAwithAngularjs/solution/mod1_solution/)
<hr>

##  assignment 2
this assignment is to create a "check off" shopping List application.

Think of being in a store with a shopping list that allows you to "check off" the items you've already bought, except instead of checking them off, the bought item simply moves to the "Already Bought" list.

### [Module 2 coding Assignment](https://r3mkumar.github.io/SPAwithAngularjs/solution/mod2_solution/)

<hr>

## assignment 3
You are going to be building a much simplified search of the menu item descriptions using the restaurant server REST API we used in Lecture 25, Part 2.

The idea here is for the user to search the descriptions of menu items. Then, given the list of matches of his search, give the user the ability to throw the items they for sure don't want off the list, thus narrowing it down to what they do want.

Your task is create a text box and a button with the label "Narrow It Down For Me!".

### [Module 3 coding Assignment](https://r3mkumar.github.io/SPAwithAngularjs/solution/mod3_solution/)

<hr>

## assignment 4

Super simple idea behind this week's assignment: use the restaurant menu REST API to create a master/detail view pair.

Your application should have 3 views (i.e., 3 view states): home (home), categories list (categories), items list (items).

### [Module 4 coding Assignment](https://r3mkumar.github.io/SPAwithAngularjs/solution/mod4_solution/#/)

<hr>

##  assignment 5

Task 1: When the user clicks on the Sign Up button, they should be taken to a view that lets them "sign up" for the newsletter (that will never come :-) ) of the restaurant. The sign up form should ask for the following information: first name, last name, email address, and phone number. It should also ask the user to specify the menu number that's their favorite dish. (The menu number is the short_name attribute of each menu item).

Everything in the form (except the short_name) must be validated through AngularJS validation we learned in this module. When the user clicks the Submit button (after all other fields are validated), try to retrieve the menu item the user specified as their favorite through the following REST endpoint https://YOUR-CHOSEN-SUBDOMAIN.herokuapp.com/menu_items/SHORT-NAME.json, where YOUR-CHOSEN-SUBDOMAIN is the subdomain discussed in Lecture50 (Restaurant Server Setup), and the SHORT-NAME is the name the user provided. If the server returns an error, you will know that the item name specified is not valid. If that's the case, display a message next to the favorite choice saying No such menu number exists. (See bonus for more)

If everything is valid, save the user's preference somewhere in your client app such that you can retrieve it in another view/component/controller/etc. (Hint: think service). Once saved, display a message below the form saying Your information has been saved.

Task 2: When the user clicks on My Info button, they should be taken to another view where it shows them their "registered" information, including the favorite menu item they picked. When showing the favorite menu item, display the picture of the menu item as well as its title and description.

If the user hasn't yet "registered" through the Sign Up button, simply display a message saying: Not Signed Up Yet. Sign up Now!. The words "Sign up Now!" should be a link to the same view as the Sign Up link points to.

## [module 5 coding assignment](https://r3mkumar.github.io/SPAwithAngularjs/solution/mod5_solution/#/)
