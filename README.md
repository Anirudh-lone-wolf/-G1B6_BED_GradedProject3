# G1B6_BED_GradedProject3
* **Problem Statement : You are required to create a CRUDS (Create, Read, Update, Delete, Search) functionality for a ticket tracker application.**
* This project is created using Spring Boot and Thymleaf (a server side view template). The Spring Boot autoconfiguration registers and configures the DispatcherServlet automatically. Therefore, we have not included the web.xml file or registered DispatcherServlet manually. The only xml file in this project is the project POM file (Maven is the build tool used here).
* The main package is com.glearning.Project which contains the Driver class of the Application There are 5 sub-packages :
    * com.glearning.Project.model - conatains the 'Ticket' entity class
    * com.glearning.Project.doa - contains a 'TicketRepository' interface which extends JpaRepository for database related operations in spring
    * com.glearning.Project.service - contains a 'TicketService' Interface and an implementation class. Here the JpaRepository methods are used for                                                               different CRUD operations required by the use case
    * com.glearning.Project.controller - which will have url mappings to perfom different CRUDS functionalities in the UI
* The UI is created using Thymeleaf view template
