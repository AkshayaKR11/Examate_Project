# Examate_Project
A next js and django project
The EXAMATE System is a comprehensive web application designed to facilitate the
creation, management, and administration of exams for organizations. The system serves
two primary user roles. Admins, known as Solution Providers, are responsible for system
administration and exam content creation. They access an administrative dashboard for
setting up and managing questions, accommodating different types such as Single Answer
(SA), Multiple Answer (MA), and Free Answer (FA). For FA questions, admins mark the
correct answer, and the system facilitates manual evaluation by organizations. Configuration
options include required and exclusive options for MA questions. Strong passwordrequirements are enforced for admin accounts, and JWT token generation ensures secure
navigation within the admin interface.
On the other hand, Consumer Organizations register with the system, providing details such
as institution name, valid address, contact number, email ID, and password. Account
creation involves email validation, and passwords are securely hashed and stored. The
purchase of tickets is required for exam creation, ensuring a sustainable business model.
Organizations can create exams with customizable parameters, including different difficulty
levels, question count, and exam time duration. Candidates are invited via email to
participate in exams and an active link available 15 minutes before the exam. Organizations
have the ability to disable, deactivate, or activate exam links for enhanced security. Manual
evaluation of FA questions is performed by organizations. Result viewing and distribution
functionalities are available for organizations.
The End User, representing individual participants, utilizes the system to attend exams. Their
main actions involve accessing exams through provided links, submitting answers.
The system integrates with email services for sending invitations and result notifications.
Security measures include the secure hashing and storage of passwords, JWT tokens for
secure user authentication, email validation for user registration, and options for link
deactivation and regeneration to control exam access. The user interface features intuitive
dashboards for both admins and organizations, with a responsive design for a seamless
user experience across devices. The system ensures secure storage and retrieval of
exam-related data, with logging and auditing features for monitoring system activity.
