**Overview of the Idea**

	Below is the flow of automated platform that transforms the entire TA management lifecycle through improved efficiency, transparency, and collaboration:

<img width="940" height="505" alt="image" src="https://github.com/user-attachments/assets/9995e274-56d9-4ec4-ab1c-e111ea8d3599" />

Figure 1: Workflow of STAMP


**Flow of Interactions:**

Applicant Interactions:
TA Applicants interact with the system by registering, logging in, and signing up through the ET entity. They submit applications, view opportunities, and receive notifications. Upon account creation, they apply for TA positions and can send notifications.
Administrator Interactions:
Administrators interact with the system by providing preliminary recommendations based on available data. They handle the application process, send notifications to TA Applicants regarding outcomes, and match TA expertise with courses.

TA Committee Interactions:
Members of the TA Committee interact with the system by making decisions regarding TA assignments. They forward these decisions to Administrators for implementation and respond to notifications and application status updates.

Instructor Interactions:
Instructors interact with the system by assessing the performance of TAs in their classes. The feedback provided by instructor is sent to both Administrators and TA Committee members for future TA considerations.

TA Applicant Portal

•	Intuitive interface for creating and managing applicant profiles.
•	Upload CV (Optional: Drag-and-drop)
•	Specify prior TA experience like courses and dates TA'd at North University
•	Indicate course qualifications.
•	Automated validation checks like prompting for missing information.
•	Email confirmations
•	Proactive notifications

Applicants will be able to upload their CVs through the portal, and we will also include an optional drag-and-drop feature for CV submission to improve the user experience. This tool streamlines the procedure and increases user convenience when it comes to providing necessary documents. In order to gather comprehensive information on candidates' experience as a teaching assistant, we need to collect detailed data, and the portal will feature options for identifying details such as courses taught and corresponding dates of TA responsibilities at North University. Candidates can also use the search function to determine their course requirements.

In order to ensure that the data is both accurate and complete, certain measures must be taken, the application will use automated validation checks. These checks prompt applicants to fill in any missing information or rectify errors before final submission, maintaining the integrity of the data collected. The idea of implementing email confirmations adds another layer of communication, acknowledging successful profile creation and submission. This feature keeps applicants informed about the progress of their application, providing reassurance and maintaining transparency in the application process. Proactive notifications further enhance the user experience by keeping applicants updated on the status of their applications. Whether it's acknowledging receipt of materials, confirming application review, or notifying about any additional steps, these notifications contribute to a smooth and communicative application process, fostering a positive interaction between applicants and the portal.
NOTE: Candidates who receive offers can choose to either confirm their acceptance or decline the offers.

**Key challenges **
•	Handling walk-in applications.
•	Technical issues like server not responding. 
•	Scheduling conflicts on classes timings for courses. 
•	Security for data – Authentication (2-step)

**Key technologies **
1.	Development Platform: IntelliJ
2.	Programming Language: Java
3.	Database: MySQL
4.	Frontend: HTML, CSS, JavaScript
5.	Authentication: API Token
6.	Deployment Environment: GitHub

**Functional Requirements:**

1.	TA Applicants

1.1. User Management:
- TA applicants shall be able to register, log in (reset passwords and manage their profiles).

1.2. Application Management:
- TA applicants shall be able to submit their resume/CV and all other required information as part of their application via the form provided to them.
- TA Applicants shall note whether they have prior TA experience or not as part of their application, and the courses they have served as TA and time frame (start and completed semesters/dates) if they do.

2.	 Department Staff

2.1. Application Management:
- Department staff shall be able to view and manage all submitted TA applications.
- Department staff shall be able to forward committee selections to the TA committee members for review and finalization.

3.	 TA Committee Members

3.1. Application Management:
- TA committee members shall be able to view, review, and make selections for TA applications. 
- TA committee members shall be able to forward their selections to the department staff/admins for confirmation/implementation/finalization and assigns tasks to TA applicant accordingly.

4.	 Instructors

4.1. Evaluation Management:
- Instructors shall be able to send feedback on TA applicant if previously worked with the instructor. 
- Evaluations to the correct applicants, who are applying again having already been a TA at the university will be sent to TA committee members and Department Staff.

**Non-Functional Requirements:**

5. Performance:
- The application shall be responsive and have low latency, even under high load, ensuring a smooth user experience.

6. Security:
- The application shall implement robust security measures, including data encryption, secure authentication, and role-based access control to protect sensitive information.

7. Reliability:
- The application shall be available and fault-tolerant, with mechanisms for data backup, disaster recovery, and error handling.

8. Scalability:
- The application architecture shall support horizontal and vertical scalability to accommodate growing user bases and increased data volume.

9. Usability:
- The application shall have an intuitive and user-friendly interface, with support for accessibility and localization to cater to diverse user needs.

10. Compatibility:
- The application shall be compatible with a range of devices, browsers, and operating systems, adhering to web standards and accessibility guidelines.

11. Maintainability:
- The application shall be well-documented, modular, and designed with clean code to facilitate ease of maintenance, updates, and future enhancements.


**UML Diagram**

<img width="940" height="637" alt="image" src="https://github.com/user-attachments/assets/19380bb0-4133-4f35-a901-47a92b1e9459" />

**Test Case and Related Screen-shots**

Below Screenshot shows the 4 Entities : TA Applicant, TA Committee Member, Department Staff Member and Instructor 

<img width="940" height="493" alt="image" src="https://github.com/user-attachments/assets/22c42f11-4e37-4445-8437-55efd2293b1f" />

Screenshot shows fau email ID verification:
 
<img width="940" height="493" alt="image" src="https://github.com/user-attachments/assets/5a55c1c1-9163-47ba-bd15-34f3bf4a28cf" />


Screenshot shows Courses to be added by Department Staff /Administrator:
 
<img width="940" height="493" alt="image" src="https://github.com/user-attachments/assets/82ad9d89-035a-4d5e-bfe7-2daf79a6a1cd" />


Screenshot represents Logging out of Department Staff and showing the choice that can be made by them: 

<img width="940" height="493" alt="image" src="https://github.com/user-attachments/assets/9a08603b-e927-43dc-a135-81a0f7f5f97c" />


Registration form of TA Applicant and followed by below is the Summary :  

<img width="940" height="493" alt="image" src="https://github.com/user-attachments/assets/599f3cbe-c0c9-42b5-929d-3cdca7f39feb" />

<img width="940" height="493" alt="image" src="https://github.com/user-attachments/assets/baa46d3d-db83-454a-9691-845783e0b05e" />


Represents Sign In page of TA Applicant and below is profile:  

<img width="940" height="493" alt="image" src="https://github.com/user-attachments/assets/0b7be650-ee1c-455b-a251-6191ba317ef2" />

<img width="940" height="489" alt="image" src="https://github.com/user-attachments/assets/bd43e123-ba29-4c77-907e-3d70612ee1bb" />


Logged out of Applicant and below is Department Staff Login Page:  

<img width="940" height="489" alt="image" src="https://github.com/user-attachments/assets/a5a369ba-981d-4167-8c0d-efce2c5f33d0" />

<img width="940" height="489" alt="image" src="https://github.com/user-attachments/assets/451cfcc3-10d9-422d-a127-222f02ac6c4f" />

TA Committee Members login and below is Instructors pages :   

<img width="940" height="489" alt="image" src="https://github.com/user-attachments/assets/03a58c8d-5955-4803-b647-71181315d35c" />

<img width="940" height="489" alt="image" src="https://github.com/user-attachments/assets/36a46330-52e0-4a0f-9691-eeb4bdf842e6" />

<img width="940" height="489" alt="image" src="https://github.com/user-attachments/assets/738a6618-ac70-440b-bcc8-5a81b342a29f" />

