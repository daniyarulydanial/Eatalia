# EATALIA
## Structure of our project
In our website we have 8 pages:
* Main page
* About
* Menu
* Location
* Register
* Login
* User profile
* Admin panel
## Contributions to our project
Design part was done by Taslima Raimkulova with animations and connections between pages and js logic was done by Daniyaruly Danial.
## Design of our project
## Logic of our project
### Main page
When main page is downloaded it is save the info about admin account into the local storage with key "adminInfo". Then it gets the item form local storage "active" where i store information about active account. If it is empty it returns empty object and you can see register and login pages. If it is not empty then it will show in navigation bar "Hi! 'username'". In main page there are two functions. First called checkAccount() where we check is there any active account which is logged in to go the user page. Second called checkLogin() to check if the user active and give him permission to go the menu page. That is why if not logged in then you cannot go to the user page or menu to make an order.
### About
In this page nothing knew. You again have two functions checkAccount() and checkLogin().
### Menu
In menu page we give for the user ability to choose one product out of nine. User can order only one product at a time. New function there would be makeOrder(prodname, prodprice) which takes two arguments (product name and product price).
## Links
