This is an Android application created as a group assignment by six students over the course of three weeks.

Named "The Invisible Cart", it allows customers and store owners to create accounts, for owners to list products, for customers to place orders, and for owners to fulfill those orders.

It is written in Java, uses Firebase as its database, and has unit testing performed with JUnit.

(All filenames below found in the directory "app/src/main/java/com/example/b07_final_project/" unless otherwise specified)

I (Alex Russell) was responsible for the following parts:
- I was Scrum Master for the team. The development was performed over three one-week Scrums.
- I designed the layout of the database, and was solely responsible for interfacing with it. I wrote the helper/FirebaseModel.java class.
- I also wrote the following helper/ classes: IDobj, Customer, Order, Owner, Product, & Store. These allow various classes to be saved to and pulled from the database without redundant code.
- I setup the Model-Presenter-View structure, including the interfaces. I helped rework other team members' contributions to work with each other using this structure.
- I wrote the first roughly-a-third of the helper/Singleton.java class, and guided others in how to continue adding to that class.
- I wrote the first roughly-half of the unit test file (app/src/test/java/com/example/b07_final_project/LoginPresenterTester.java)

The project worked as intended, and we received a mark of 98% for our work.
