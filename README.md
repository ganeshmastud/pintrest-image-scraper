# pintrestiamgescrapper
Flask rest api is used.
chrome webdriver  and the selenium automated web testing tool is use to perform fetch iamges.
To fetch images from the pintrest user needs to provide  input to search, email and passowed. if any of the field is blank then the error message is shown on sceen.

If the user is authenticated then the search is perform. We have limit the number of images fetch to 10 you can change it by assigning your own values to it and you also need to make changes to the webpage scroling in downloadurl function.
after that the images stored in the static folder.and load on web page.
