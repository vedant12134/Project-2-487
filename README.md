# Project-2-487
**1. Project Title**
Apartment Maintenance Request System
**2. Project Description**
This system allows tenants to submit maintenance requests, which can be viewed and managed by staff and the property manager. The system supports functionality for adding, moving, and deleting tenants, along with submitting maintenance requests. Requests can be filtered by apartment number, problem area, and submission date, and their status can be updated.
**3. Features**
Tenant Features:
Submit maintenance requests by entering apartment number, problem area, description, and photo.
Staff Features:
View submitted maintenance requests.
Filter requests by apartment number, area, and date range.
Update request status (mark as complete).
Manager Features:
Add, move, and delete tenants.
View tenant details such as name, phone, email, and apartment number.
Responsive Design:
The layout is responsive and adapts to different screen sizes.
**4. Technologies Used**
Frontend:
HTML, CSS (Responsive design with flexbox).
JavaScript (for Firebase interaction and dynamic content rendering).
Backend:
Firebase Firestore (for storing and retrieving requests and tenant data).
Firebase Authentication (if implemented for user management).
**5. Firebase Configuration**
Firebase is used for backend services, including storing maintenance requests and tenant data in Firestore. You'll need to configure Firebase with your project-specific credentials (API key, project ID, etc.) to make the app functional.
**6. How to Run**
Clone this repository.
Create a Firebase project and add Firestore to your project.
Replace the Firebase config object in the script with your own Firebase credentials.
Open index.html in a browser to view and use the application.
**7. Functionality Overview**
Submit Request:
Tenants can submit a request with the apartment number, area, description, and a photo (if needed).
View Requests:
Staff can view, filter, and mark requests as completed.
Tenant Management:
Managers can add, move, or delete tenants. They can also fetch a list of tenants and their details.
Database Interaction:
The app uses Firebase Firestore to handle data storage and retrieval for both maintenance requests and tenant information 
