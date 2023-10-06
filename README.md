
# BidHub- An Bidding Portal

BidHub portal is an online platform that facilitates the process of auctioning or bidding on various items or services over the internet. BidHub designed to bring together buyers and sellers, allowing them to participate in competitive bidding processes.




## Modules
The system has two major Modules

    1. User Module

    2. Admin Module

The Users are divided into

    1. Sellers (add products)

    2. Bidders (Bids for the products)

There is basic user registeration where user can register themselves as seller or Bidders
You either register a new user or use the following credential

    User Login as Seller

    Username: preetam
    password: 1234

    User Login as Bidder
    Username: preetam@123
    password: 1234

Basic CURD operations is done for all users including change password,edit,profile etc.

    Admin Module:
    username: admin
    password: 1234
 
The admin can view all the biddings, products,users of the system,auction status and winners.
Basically admin will add category of product like type of a product eg: Antiqques,vehicle etc.
The seller adds the product while choosing the respective category of product into the system and admin approves the product for bidding using its ID.

Admin can set start date(session date) of the auction and duration of the auction(session time).
Once the bidding is done and the end time is passed the Highest amount raised for a particular product wins the auction,the winner can be viewed in results section of admin dashboard.






## Technology Used
BackEnd:	 	Python

Framework: 		Django

Database: 		SQLite

Frontend Language: HTML, CSS, JavaScript and  BootStrap
Editor: Any (VS Code Preffered).
You can run the project in vs code prerequiste Django must be installed use command py manage.py runserver 
