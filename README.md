Project Description:

For this automation system, I chose Visual C# as the programming language and MS SQL Server as the database. 
The topic is a Hospital Appointment and Management System, and I developed the project using a Windows Form Application.

Content: I started the project by creating tables in SQL Server. These tables include:

Patients
Doctors
Secretaries
Appointments
Announcements
Specialties
I created a total of 6 tables. Then, I focused on 3 main modules and created interfaces using Windows Form Application. These modules are:

Doctor
Patient
Secretary
The users can log in through these modules. Once logged in, the information stored in the database is used for authentication.

After a successful login, users can perform operations through detailed pages added to each module. 
If a patient tries to log in and is already registered, they can log in directly; if not, they can click on the "Sign Up" option,
fill in their details, and become a registered user. After that, they can return to the login screen and log in to the system.

Doctors and secretaries are already registered, so they do not have sign-up forms.

When logged in as a patient, they can create appointments, view past and active appointments, and edit personal information.

When logged in as a doctor, they can view their appointments and details, update their information, check announcements created by the secretary, 
and log out of the system.

When the secretary logs in, they can see the list of specialties and doctors, create appointments for patients, create new announcements, 
and view a list of announcements they created. The secretary can also add, delete, or update doctors and specialties.

Result: In this project, I used a total of 14 forms. The transitions between forms were managed using various SQL commands, 
based on the data retrieved from the database. By actively utilizing the database, my goal was to create an application that provides both visual and functional benefits to the user. With the designed interfaces, users can easily perform all operations within the system.
