The Spring Boot application uses both REST and MVC controllers. Thymeleaf templates are used for the admin and doctor dashboards while REST APIs serve all other modules. The application
interacts with two databases. MySQL for patient, doctor, appointment and admin data and Mongo DB (for prescriptions). All controllers route requests through a common service
layer which in turn delegates to the appropriate repositories. MySQL uses JPA entries while MongoDB uses document models. 


1. User accesses AdminDashboard or Appointment pages.
2. The action is routed to the appropriate Thymeleaf or REST controller.
3. The controllers call the service layer which in turn call the repositories either MySql repository or MongoDB repository.
4. MySQL repositories accesses MySQL database through models.
5. Mongo DB accesses the database through MongoDB models.
