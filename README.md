### Group-5_CSCI4710-6710_Final-Project
  - Jacob Turnage (turnagej19@students.ecu.edu)
  - Sandhya Kodem (kodems21@students.ecu.edu)
  - Alejandro Cruz-Bautista (cruzbautistaa17@students.ecu.edu)

# DentistAppointmentScheduler System
A fully-working dentist appointment scheduler system which is written in Python using Flask web development, powered by Bootstrap, using MySQL to manipulate data. It's based on a statement of work, developed first its own database and then application. Its database has much quite enough good mock data.

## Main page of the system
![Index page](https://user-images.githubusercontent.com/90139084/232938179-4131bf71-7679-4a82-873d-5204e35d0baf.png)

# DentistAppointmentScheduler System - Patient Perspective
DentistAppointmentScheduler System allows patients to:
1. Register to the system,
2. Use the system after adding address and telephone information,
3. Add chronic disease information if any,
5. Search for an appointment and book appointments after search,
6. Look for past appointments (treatments if patient has been gone to the appointment), upcoming appointments,
7. And of course change their information like email, password, telephone, address, chronic disease information.

## Patient Registration
![Patient registration](https://user-images.githubusercontent.com/90139084/232938419-6c59af1e-1e00-431b-b149-9bfd4bc2fae8.png)

## New User Login
Users have to add address and telephone information to use the system.
![New user page](https://user-images.githubusercontent.com/90139084/232945025-d17b1765-ae36-469d-aa85-0b3084c9efd3.png)

## Profile Page
Users can easily change their email, password, address and phone information in the profile page. But there are some restrictions like patients cannot delete their phone and address number if they only have only one.
![Profile page](https://user-images.githubusercontent.com/90139084/232945166-b1d1578a-ef78-4ea9-ae15-f93e054ff3a3.png)
![Restriction example](https://user-images.githubusercontent.com/90139084/232945309-f8c81514-d7e5-4620-a6b2-34071384200a.png)
![Changing password](https://user-images.githubusercontent.com/90139084/232945492-6c1b1666-e061-4071-a0d3-e702d4d58c62.png)
![Adding address information](https://user-images.githubusercontent.com/90139084/232945682-e9e6d288-4339-4bb5-b51f-2c250a375898.png)
![Activating account](https://user-images.githubusercontent.com/90139084/232945877-8e732a11-7176-40f9-be34-a6b098862767.png)
## Patient Login
![Patient login page](https://user-images.githubusercontent.com/90139084/232946055-2ffa8078-47b9-4609-8c1e-993024eb5d73.png)

## Booking An Appointment
![Booking an appointment](https://user-images.githubusercontent.com/90139084/232946290-c55cbee6-1a6e-4155-b2ab-5de30b5dcb3a.png)

## My Appointments Page
![My appointments page](https://user-images.githubusercontent.com/90139084/232946373-2978272d-c3ce-41ed-a24d-8575f4579e8c.png)

# DentistAppointmentScheduler System - Dentist Perspective
DentistAppointment system allows dentists to:
1. See the upcoming appointments,
2. Look for every single patient's profile and see their handy information,
3. Look for today's appointments and add treatment information to them,
4. Look for past treatments (and appointments if patient didn't come to the treatment), and search for past treatments by date,
5. Add holiday information, and of course to view upcoming and past holidays,
6. Look for interesting statistics in the system, that can be either dentist statistics or patient statistics.

## Dentist Login
![Dentist Login](https://user-images.githubusercontent.com/90139084/232946528-a0c37925-3ca9-4c61-b5ba-50272d0227df.png)

## Upcoming Appointments
![Upcoming appointments](https://user-images.githubusercontent.com/90139084/232946721-c65a719f-ffc2-4d24-b1b0-6758efc49018.png)

## Today's Appointments
![Today's appointments](https://user-images.githubusercontent.com/90139084/232946938-c000ba7d-ae04-423e-a842-4290556af117.png)
![Adding treatment](https://user-images.githubusercontent.com/90139084/232947134-ea16e2a9-afb4-4f51-b8c9-a8405aa2302c.png)
### Note: Dentists can only add treatments (or medicines) to appointments which only booked for today.
![Medicines](https://user-images.githubusercontent.com/90139084/232947271-3514a954-6109-4d17-93a0-93115a51a797.png)

## Past Treatments
![Past treatments](https://user-images.githubusercontent.com/90139084/232947416-c27b6c0e-534b-439c-97c3-9986579f89b5.png)
![Searching treatments](https://user-images.githubusercontent.com/90139084/232947577-8d6d6942-6182-485d-b3e7-1585837196f3.png)

## Holidays
![Holidays](https://user-images.githubusercontent.com/90139084/232947729-a26f065f-2d96-446a-b011-f5584c523f62.png)
![Adding holiday](https://user-images.githubusercontent.com/90139084/232947885-7a0b16bf-7510-4181-98ad-e8b24c9f2f26.png)

## Patient profiles
![Patient profile](https://user-images.githubusercontent.com/90139084/232948116-4986a140-24bd-4a30-b38f-64db5b6077b4.png)

## Patient & Dentist Statistics
![Patient statistics](https://user-images.githubusercontent.com/90139084/232948326-d97ad145-d6d9-4ca9-951b-acfcbb08fff1.png)
![Dentist statistics](https://user-images.githubusercontent.com/90139084/232948450-94a40548-2ca0-467f-bd08-4a694828a210.png)

## How to use DentistAppointmentScheduler System?
If you want to use DentistAppointmentScheduler System with its all things: 
- Create a database named 'dentist_management_system',
- And import the file in the github main directory named 'dentist_management_system.sql'.
After that you are almost ready to go, just download the release or clone the repository. Don't forget to make necessary database configuration if you need to do in dentistAppointment.py. And then run dentistAppointment.py.

System should be working on http://127.0.0.1:5000/.

![Running dentistAppointment.py](https://user-images.githubusercontent.com/90139084/233229900-5ba70f89-170d-4f19-ab3e-ae75684ca418.png)

If you want to edit or improve somethings just fork the repository.

Since the system is fully working, you don't have to use the demo credentials, but just in case:

### Demo person credentials:

Email: demoperson@gmail.com

Password: tzesh

### Demo patient credentials:

Email: demopatient@gmail.com

Password: tzesh

### Demo dentist credentials:

Email: demodentist@gmail.com

Password: tzesh
