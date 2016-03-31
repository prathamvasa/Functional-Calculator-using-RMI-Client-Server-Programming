•Tools and technologies used:
Java, Remote Method Invocation paradigm, Eclipse IDE.

•The goal of this project is to implement a Client/Server Java objects running on different machines. The Client object invokes methods on the Server objects through Java IDL capability. 

•This project aims at building a simple “Calculator” server (S) and a Client agent (C) Java objects. The client agent object reads input command/arithmetic operation from the user (U), invokes the calculate() method on the server IDL interface, gets the result back and passes it back to the User.

•The interactions between the User, Client Agent, and the “Calculator” Server are synchronous, i.e, the user has to wait to receive the response to the calculation operation request before responding by another request.

•Basic arithmetic operations of addition, subtraction, division, multiplication etc were implemented through this calculator. The calculator was implemented using the RMI (Remote Method Invocation) paradigm.
