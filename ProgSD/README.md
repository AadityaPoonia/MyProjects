# This project was a part of my Programming & Systems Development coursework in my Master's program at UoG 2023-24.

## E-Vehicle Share System

### Application startup guide
For the application environment to be initialized properly, make sure the following requirements are satisfied.
 - Install python (preferably python3) https://www.python.org/downloads/
 - Make sure the environment variables are set for both Python and PIP during installation.
- The application requires additional libraries to be installed on the device, namely **pandas, matplotlib,** and **Argon2**.

  To download these dependencies, simply enter the following commands in the terminal one by one.

  ``pip install jupyter`` For Argon2 and its dependencies. <br>
  ``pip install pandas``<br>
  ``pip install matplotlib``<br>

------------


If you are running it for the first time, you are required to run the **test.py file first** in order to create the database and set it up with default data to be able to visualize the application more easily.

Starting the application afterward is very simple. Running the **mainApp.py file in the outermost folder** will open the main window and from then the user is free to use the functions described in the report.

#### Test Data

To be able to fully explore all the core functionalities, here are the log-in credentials for each type of user with pre-defined randomized data for visualization

##### **Customer**

```
Email: user1@ecs14.com
Password: password
```

##### **Operator**
```
Email: op1@ecs14.com
Password: password
```
##### **Manager**
```
Email: manager1@ecs14.com
Password: password
```

------------

### Description and Problem Statement

WattWheels is a software system to support an electric vehicle share programme. It is a functional end-to-end prototype that supports all the detailed functional requirements for a vehicle renting application. It focuses on clean and minimalistic UX while ensuring the safety and security of data for users.

You must use **Python** for your implementation, with a user interface written in **Tkinter**. Your system must include a **database** to store the details of the vehicles, charging points, city locations, customers, and any other data as needed by your implementation. You must include at least two vehicle types, for example, electric scooters and electric bikes; you can also include more vehicle types if you want to.

The detailed functionality of the system is up to you, but it should include at least the following capabilities:

- Customers should be able to:
  - Rent a vehicle at any location in the city, as long as there is a working vehicle available at that location.
  - Return a vehicle to any location. When a customer returns a vehicle, their account is charged depending on how long the vehicle rental was and what type of vehicle was used.
  - Report a vehicle as defective.
  - Pay any charges on their account.
- Operators should be able to:
  - Track the location of all vehicles in the city.
  - Charge a vehicle when the battery is depleted.
  - Repair a defective vehicle.
  - Move vehicles to different locations around the city as needed.
- Managers should be able to:
  - Generate reports showing all vehicle activities over a defined time period, using appropriate data visualization techniques.



