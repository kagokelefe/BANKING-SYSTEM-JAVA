#BANKING SYSTEM
A Java banking system developed using a layered architecture. The application separates the user interface, business logic, data access and data models to keep the code organised and maintainable.
##PROJECT STRUCTURE
java/
├── app/          # Application entry point and navigation
├── controller/   # Handles user actions and screen logic
├── dao/          # Data access operations
├── model/        # Banking entities, such as customers and accounts
├── service/      # Business rules and banking operations
└── util/         # Shared utility classes

resources/        # FXML views, CSS, and other application resources
    
##Main Features
-Customer registration and login
-Account management
-Savings account support
-Cheque account support
-Investment account support
-Viewing account details and balances
-JavaFX user interface built with FXML
-Separation of concerns using Model, DAO, Service, and Controller layers

##Technologies used
-Java
-JavaFX
-FXML
-CSS
How to Run
1.Clone the repository:
  git clone https://github.com/kagokelefe/BANKING-SYSTEM.git
2.Open the project in IntelliJ IDEA or another Java IDE.
3.Configure the JavaFX SDK in the project.
4.Run the main application class:
   MainApp.java

Author
Kago Kelefe
