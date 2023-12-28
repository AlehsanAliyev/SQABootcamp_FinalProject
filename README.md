# Bank Application Testing

This repository contains a set of manual and automation test cases for a banking application. The tests cover various functionalities, including user authentication, transactions, customer management, and more. Both manual and automated test cases have been included in order to provide extensive report.

## Test Cases

### Login 

- **Case 1: Verify Successful Login**
  - Objective: Ensure users can successfully log in with proper credentials.


- **Case 2: Verify Customer Selection**
  - Objective: Confirm that users can select their customer name during login.

  - **Case 3: Verify Deposit Functionality**
 
  - **Case 4: Verify Withdrawal Functionality**
 
  - **Case 5: Verify Authentication for Bank Manager Login**
 
  - **Case 6: Verify Validation on Add Customer Fields**
    
  - **Case 7: Verify Opening an Account**
 
  - **Case 8: Verify Customer Search Functionality**
 
  - **Case 9: Verify Customer Deletion**



## Performance testing

Performance Testing Report
Overview

This repository contains the results of a comprehensive performance testing initiative conducted on our application using JMeter. The goal was to assess the robustness and scalability under different user load scenarios.
Test Scenarios
400 Users

    Home Page Request:
        Some users experienced errors due to scalability challenges.
        Optimizations initiated to improve performance.
    Transactions and Bank Manager Login:
        Generally stable performance observed.
    Generic Login:
        Connectivity issues addressed to mitigate errors.

400 Users

    Home Page Request:
        Continued scalability issues addressed with optimizations.
    Transactions Request:
        Errors identified, optimizations implemented for enhanced database performance.
    Bank Manager Login and Generic Login:
        Authentication and authorization optimizations applied to improve performance.

Common Observations

    Network Issues:
        Connectivity challenges resolved to improve reliability.
    Server Unavailability:
        Monitored and addressed intermittent server unresponsiveness.

Recommendations

    Optimization Measures:
        Continued optimization efforts for the home page and overall system performance.
    Monitoring:
        Implement robust server and network monitoring solutions.
    Scalability Testing:
        Consider additional scalability testing for comprehensive performance evaluation.

Screetshots of errors

Include screenshots or pictures depicting errors encountered during the tests:
Home Page requests (400 Users)

![image](https://github.com/rashad2001/FinalProject/assets/60662650/1588551f-e519-4ba6-adfe-9f16fc1fdf5c)

Transactions requests (400 Users)

![image](https://github.com/rashad2001/FinalProject/assets/60662650/d319e5bf-5726-4547-a07a-abf3edba862d)

Bank Manager Login requests (400 Users)

![image](https://github.com/AlehsanAliyev/SQABootcamp_FinalProject/assets/149327636/859f01af-1c27-4676-a85b-476f8a47b718)


Add Customer requests (400 Users)

![image](https://github.com/rashad2001/FinalProject/assets/60662650/0d35f515-d1a8-4be9-bdfd-3b6a025857c6)

Conclusion

The performance testing initiative provided valuable insights, leading to targeted optimizations and enhancements. Ongoing monitoring and optimization efforts are crucial for ensuring optimal performance under varying conditions.

For more details, refer to the detailed Performance Testing Report.

## User Stories


A set of user stories has been created to outline the requirements and expectations from the banking application:

    As a User, logging in to the banking application with a valid customer name so that I can access my account information easily.
            I should be able to select my customer name from the dropdown.
            After logging in, I expect to see relevant information on the post-login page.

    As a User, I want to perform transactions seamlessly to manage my account efficiently.
            I should be able to navigate to the transaction page after logging in.
            Transaction details should be displayed accurately, and the process should be smooth.

    As a Bank Manager, I want to log in securely with valid credentials to access administrative features.
            I should be prompted for valid Bank Manager credentials during login.
            Access should be restricted without proper authentication.

    As a Bank Manager, I want to add new customers to the system easily.
            The system should allow me to input customer details such as first name, last name, and post code.
            Customer information should be stored accurately, and the process should be validated.

    As a Bank Manager, I want to open accounts for customers efficiently.        
          The system should provide a smooth process for opening accounts for customers.
          Account creation should not allow invalid characters or data.

    As a Bank Manager, I want to search for customers by name to access their information quickly.
            The system should allow me to search for customers using their names.
            Search results should display relevant customer details.

    As a Bank Manager, I want to delete customer records securely when necessary.
            The system should prompt for confirmation before deleting a customer record.
            Deleted customer records should no longer be accessible.

    As a User or Bank Manager, I want to log out of the application securely with a click of the home button.
            Clicking on the "Home" button should log me out securely, and I should be redirected to the home or login page.

    As a User, I want to navigate through the application easily, ensuring a responsive and user-friendly experience.
            The application should be responsive on different devices and browsers.
            Navigation buttons should work correctly without breaking the application.

## Conclusion
I tried to implement all my knowledge obtained in bootcamp, thanks to my instructor and my groupmates I completed this. If there are problems please let me know!
