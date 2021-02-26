# Pintrest Image Scraper
Flask rest api is used.
chrome webdriver  and the selenium automated web testing tool is used.
To fetch images from the pintrest user needs to provide  input to search, email and passowed. if any of the field is blank then the error message is shown on sceen.

If the user is authenticated then the search is perform. We have added the limit on number of images to be fetch to 10. You can change it by assigning your own values to it and you also need to make changes to the webpage scrolling in downloadurl function.
after that the images are stored in the static folder and loaded on the web page.
