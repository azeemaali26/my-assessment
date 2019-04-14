# my-assessment
Code assessment - Azeema Ali 

Main.html
•	Using the bootstrap library I was able to create a responsive website. (https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.5/css/bootstrap.min.css)
•	By including the CDN I was able to use start using jQuery on this website. (https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js) 
•	Rather than having all the data saved in only an array I decided to use sessionStorage, which is a global object that maintains the storage area. It allows to save key/value pairs in a web browser. Once the sessionStorage is not empty, reset the value of the shopping cart by parsing it into useable object in a string value. 
•	I made a formatMoney function which will convert the amount into 2 decimal places. 
•	There’s a shopping cart function in this class. When you click on it, a pop of the shopping cart is presented with list of items, quantity, and price. There is also a remove button which is used if the user does not wish to buy the item. 


Checkout.html
•	This page is being integrated to Paypal. When the user is ready to. Check out they can go over to paypal to make the payment. 
•	Paypal has hidden HTML variables which are copied to my code so it can be integrated. 
•	Using the same Jquery library from Main.html i was able to format this page in the way it was required.
•	There is an option for adding or subtracting the quantity of the item. 
•	There is a function that makes sure that if the user reaches 0 or lower in quantity, then to delete the item from the chart and not to charge the user. 
	
