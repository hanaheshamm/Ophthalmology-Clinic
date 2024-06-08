# OptiCare Connect: Ophthalmology Clinic Information System

Welcome to **OptiCare Connect**, an advanced Ophthalmology Clinic Information System designed to streamline the management of clinic operations, enhance patient care, and optimize workflow efficiency.

## Features

### Doctors Management
- **View Doctors List**: A comprehensive list of all doctors in the clinic.
- **Add Doctor**: Form to add a new doctor to the system with necessary details.
- **View Doctor Information**: Detailed information for each doctor, including specialty, contact information, and availability.
- **Edit Doctor Information**: Update the existing information of doctors as required.
- **Search Doctor**: Search for specific doctors by name, specialty, or other criteria.

### Patients Management
- **View Patients List**: A complete list of all registered patients.
- **Add Patient**: Register new patients and automatically send an email notification with login credentials.
- **View Patient Information**: Detailed information for each patient, including medical history, contact information, and appointment history.
- **Edit Patient Information**: Update patient records with new information.
- **Search Patient**: Search for patients by name, ID, or other criteria.
- **Email Notifications**: Upon creating a new patient record, an email is sent to the patient with their username and password for the portal.

### Appointments Management
- **View Appointments**: A list of all scheduled, completed, and canceled appointments.
- **Mark as Scheduled/Canceled**: Update the status of appointments as scheduled or canceled.
- **Appointment Details**: View detailed information about each appointment, including patient and doctor involved, date, time, and status.

### Services Management
- **Add New Service**: Admin can add new services offered by the clinic, including details and pricing.

### Dashboards
- **Admin Dashboard**: Provides a comprehensive overview and management tools for clinic administrators. Includes metrics, recent activity, and quick access to various management functions.
- **Patient Portal**: Allows patients to log in, view their medical records, reserve appointments, and manage their personal information.

## Technologies Used

- **MongoDB**: A NoSQL database for storing patient records, appointment data, billing information, and inventory details.
- **Express.js**: A web application framework for building robust and scalable backend APIs to handle CRUD operations.
- **React.js**: A frontend JavaScript library for building interactive user interfaces and managing client-side application logic.
- **Node.js**: A JavaScript runtime environment for running server-side code and managing the backend logic.

## Screenshots
- *Login window in which admin and patient can access their dashboard according to their emails and password.*

  ![Doctors List](https://github.com/hanaheshamm/Ophthalmology-Clinic/assets/115111861/c5910c96-2ff9-4a17-afba-03f04b81a6c6)

<br />

- *Displays statistics of patients' information, including the number of patients, doctors, and appointments. Provides visual analytics on service usage and patient demographics.*

![Doctor Information](https://github.com/hanaheshamm/Ophthalmology-Clinic/assets/115111861/98ac3d81-5b03-4b49-b6af-d372eebbe39b)

<br />

- *View of the patients list.*

![Patients List](https://github.com/hanaheshamm/Ophthalmology-Clinic/assets/115111861/47079ae7-f803-449c-bdfd-fdeb6d02d2a8)

<br />

- *View of the doctors list.*

![image](https://github.com/hanaheshamm/Ophthalmology-Clinic/assets/115111861/1b103ff2-98f0-4a67-879d-906f0496eb0a)


<br />

- *View and manage appointments.*                                                                 
  ![image](https://github.com/hanaheshamm/Ophthalmology-Clinic/assets/115111861/b72a4550-952b-413a-89aa-40c037ef8de9)

<br />

- *Form to add a new service.*

  ![Appointments Management](https://github.com/hanaheshamm/Ophthalmology-Clinic/assets/115111861/f9023e5f-de8d-4ab7-a999-e80f5129eea4)

<br />   


- *the email that is sent to the patient of his username and password to access the patient portal*
![image](https://github.com/hanaheshamm/Ophthalmology-Clinic/assets/115111861/86a32a19-ae2c-49b4-921e-9b5f15b3a823)

<br />   
                                                                                     
## Getting Started

To get a local copy up and running, follow these simple steps:

1. **Clone the repository**:
    ```sh
    git clone https://github.com/hanaheshamm/Ophthalmology-Clinic.git
    ```

2. **Install dependencies**:
    ```sh
    cd Ophthalmology-Clinic
    npm install
    ```

3. **Run the application**:
    ```sh
    npm run dev // on Backend folder
    npm start // on Frontend folder
    ```

4. **Open the application in your browser**:
    ```sh
    http://localhost:3000
    ```

## Contribution

Contributions are what make the open source community such an amazing place to be. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature`)
3. Commit your Changes (`git commit -m 'Add some Feature'`)
4. Push to the Branch (`git push origin feature`)
5. Open a Pull Request


---

Thank you for using **OptiCare Connect**. We hope this system greatly enhances your clinic's operations and patient care.

