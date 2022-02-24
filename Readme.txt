/*
Author: 	Shwetank Singh
Roll No.: 	MT2021133
Date: 		30/10/2021

Project Title:	Create a Railway ticket booking system  using socket programming and locking mechanisms
*/

Functionalities of our system:
1: Admin
	a: Manage Train (add,update,delete)
	b: Manage Users (delete agent/customer)

2: Agent
	a: can login from multiple systems
	b: view/book tickets
	c: manage tickets (update/cancel)

3: Customer
	a: can login only from single system
	b: book tickets
	c: manage tickets (update/cancel)
	d: view/update bookings


Steps to run the MyTrain System:

Run database.sh to create essential database files:
$ sh database.sh 

Run compile.sh to create object file of server and client:
$ sh compile.sh

//we are running our server and client on port: 14523

run the server:
$ ./server

run the client:
$ ./client [ip_address of server]
if ip_address of server is not given as command line argument then we have used loopback address 127.0.0.1 as server's IP address


Note: Initially, signup as a admin using secret key "root".

Happy booking.......!!!
