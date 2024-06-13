# ECS-14-Team-Project

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



<img width="57" alt="image" src="https://github.com/ganesh-uofg/ECS-14-Team-Project/assets/107865375/627c2d80-5187-42be-9578-b6018faad4a4">

If you are running it for the first time, you are required to run the **test.py file first** in order to create the database and set it up with default data to be able to visualize the application more easily.

<img width="71" alt="image" src="https://github.com/ganesh-uofg/ECS-14-Team-Project/assets/107865375/f973f774-f93c-4f54-8514-af8be589d897">

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

WattWheels a software system to support an electric vehicle share programme. It is a functional end-to-end prototype that supports all the detailed functional requirements for a vehicle renting application. It focuses on clean and minimalistic UX while ensuring the safety and security of data for users.

You must use Python for your implementation, with a user interface written in Tkinter. Your system must include a database to store the details of the vehicles, charging points, city locations, customers, and any other data as needed by your implementation. You must include at least two vehicle types, for example electric scooters and electric bikes; you can also include more vehicle types if you want to.

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
  - Generate reports showing all vehicle activities over a defined time period, using appropriate data visualisation techniques.

You may want to consult similar real-world systems such as Lime (https://li.me/) or Voi (https://www.voiscooters.com/) to help with your system design. Note that it is not expected that you exactly duplicate the functionality of these systems.

## What to submit
Each group must submit the following (through Moodle):

- A report describing the functionality that was implemented, explaining any design decisions that were made. The report should also include a summary of how each team member contributed to the design and implementation, as well as to the report. Templates will be provided on Moodle.
- A video presentation of your system, up to 10 minutes long.
  - All members of the team must speak on the video (cameras not required)
  - The video must include a live demo of all  the system, as well as a discussion of all design decisions.
- All of the source code involved in the system, along with any other resources required to run it. You should also include a README file describing exactly how to run your software.

