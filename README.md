# BookstoreSpringJMS

In this project, we use Spring JMS to publish book order request from Bookstore Front End to an ActiveMQ queue. The JMS message is read by Warehouse which publishes ackonwledgement message to a queue and sends updated inventory to a durable topic

Backend: SpringBoot
