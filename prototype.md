visual style: follow design3.html, make the design approachable to a housewife / people less familiar with tech

1.implement a website page where we can search and see some possible discount from certain companies, there are also “suggested” discounts
details:
create a list of dummy restaurants first (x20 of different food styles(find 3 different food styles) with immediately recognisable food style from name), and then the specific restaurants are marked as suggested in the food styles 
the discounts should be capped at (20%) and there are different types, e.g. $20 off, 20% off, buy 2 get 1 free
place the restaurant names and discounts in .json files, and create an html file that uses those .json files as dependency
implement a simple search function that ranks the restaurants by relevance, but always top 1 ‘suggested’ restaurant in that particular category; when the user search for a particular restaurant, also place a relevant similar restaurant that is marked as suggested on top


2.implement a mobile page where we can see a demonstration of a shopping page and a notification pops up when the user is at the checkout page
details:
design a webpage that has a screen in the middle that is of a similar scale to most mobile phone, 20:9
the webpage starts at a list of possible goods to buy, make a list of daily items (e.g. toothbrush, trousers…) and put that list into a .json file as dependency
in the html file, create specific pages for the different daily items, and in those specific pages, display what a normal checkout page will look like, e.g. a dummy address of the user, a display of the factories address, a checkout button, the price of the item, the shipping price of the item, the expected shipping time of the item
design an icon of daibuy app first according to design3.html
when the users presses into that page, a notification pops up with the icon of daibuy app, and states clearly a cheaper alternative exists; the notification should include 1. the cheaper alternative source 2. the cheaper price
visuals: use iphone style notifications
