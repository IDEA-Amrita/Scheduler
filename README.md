## Scheduler

### Abstract:
The meeting scheduler application for the university aims to streamline the process of scheduling meetings between faculty members and students. The application will have two interfaces: one for the faculty to import their timetable and view their free slots, and another for students to request meetings with faculty members based on their availability. The faculty members will have the option to accept or reject the meeting requests, and the application will provide a method of communication between the faculty and students for further coordination.


### Problem Analysis:

Problem Statement:
The current process of scheduling meetings between faculty and students is often inefficient and time-consuming. There is a need for a centralized system that allows faculty members to easily identify their free slots and enables students to request meetings based on that availability.

### Objectives:

1. Develop a meeting scheduler mobile application that imports faculty timetables and highlights their free time slots.
2. Provide a user-friendly interface for students to send meeting requests to faculty members.
3. Implement a communication method within the application to facilitate coordination between faculty and students.
4. Allow faculty members to accept or reject meeting requests based on their availability.
5. Ensure the system is secure and robust, with appropriate authentication and authorization mechanisms in place.

### Modules:

1. Faculty Interface: Importing faculty timetables and displaying available time slots.
2. Student Interface: Sending meeting requests to faculty members.
3. Communication Method: Providing a means of communication between faculty and students within the application.
4. Accept/Reject Mechanism: Allowing faculty members to accept or reject meeting requests.
5. Authentication and Authorization: Implementing secure login and access control mechanisms.

### Duration to work: 3 months

### Userbase:
The primary userbase of the application will be the faculty members and students of the university.

### Architecture:
The mobile application can be developed using the Flutter framework, allowing for cross-platform compatibility. The frontend will be built using Dart programming language and the Flutter framework. The backend can be implemented using a suitable technology stack such as Node.js, Express.js, Firebase, or Django. The database management system can be Firebase Realtime Database or Firestore. Real-time communication can be achieved using Firebase Cloud Messaging or WebSocket. Authentication can be implemented using Firebase Authentication or a custom authentication system.

WIREFRAME For Application:

[https://www.figma.com/file/T59FQ7yUEDRkDcILS6wseb/Scheduler?type=design&node-id=0-1](https://www.figma.com/file/T59FQ7yUEDRkDcILS6wseb/Scheduler?type=design&node-id=0-1)

### Deliverables:

1. Meeting scheduler mobile application with faculty and student interfaces.
2. Secure login and authentication system.
3. Communication module within the application.
4. Timetable import functionality for faculty members.
5. Accept/Reject mechanism for meeting requests.
6. User documentation and installation guide.

### System Development:

### Skills/Frameworks required:

1. Flutter: Dart programming language, Flutter framework for mobile app development.
2. Backend Development: Node.js, Express.js, Firebase, or Django for building a custom backend or utilizing BaaS platforms.
3. Database Management: Firebase Realtime Database or Firestore for data storage.
4. Communication: Firebase Cloud Messaging or WebSocket for real-time messaging and notifications.
5. Authentication: Firebase Authentication or custom authentication implementation.

### Links to research papers/articles related to the topic:

Use the developer roadmap to illustrate a timeline:

- Month 1: Requirement gathering, UI/UX design, and backend setup.
- Month 2: Frontend development using Flutter.
- Month 3: Backend development for meeting scheduling, communication, and authentication.
- Testing, bug fixing, and performance optimization can be performed simultaneously throughout the development process.

### Proposed Systems (Methodology/Wireframe/Flow of Algorithm, etc.):

1. Faculty Interface:
    - Faculty members can log in to the mobile app.
    - Import their timetable by

uploading a file or manually entering data.

- Display their free time slots with a visually intuitive interface.
- Allow faculty members to manage availability and preferences.
1. Student Interface:
    - Students can register or log in to the mobile app.
    - Browse faculty members' availability and select preferred meeting times.
    - Send meeting requests to faculty members.
    - Receive notifications for request status updates.
2. Communication Method:
    - Implement real-time messaging functionality within the app using Firebase Cloud Messaging or WebSocket.
    - Enable faculty-student communication for further coordination.
    - Provide push notifications for new messages and meeting updates.
3. Accept/Reject Mechanism:
    - Faculty members receive meeting requests.
    - Accept or reject requests based on availability.
    - Students receive notifications for request status.

### Expected Results:
The expected result is a fully functional mobile application that simplifies the process of scheduling meetings between faculty and students. The app should have an intuitive user interface, efficient timetable management, real-time communication, and push notifications for seamless coordination.

### Conclusion:
The mobile application-based meeting scheduler will provide convenience and efficiency for scheduling meetings within the university. The app's features, including timetable import, meeting requests, in-app messaging, and push notifications, will enhance collaboration and streamline the meeting scheduling process for both faculty members and students.

### Future Scope:

- The mobile app can be expanded with additional features such as calendar integration, automated reminders, location-based services, and analytics for meeting insights. Integration with other university systems, such as the university's existing databases or learning management systems, can be considered for a more comprehensive solution.
- Integrate a bluetooth beacon/geolocation other methodology to implicitly detect location of faculties within the academic block and give alerts accordingly.

In conclusion, the development of an impartial assignment algorithm for iDEA will enable the efficient mapping of student members to upcoming projects or research papers. By considering skillsets, experience levels, and peer groups, the algorithm will ensure fair and effective project assignments, fostering collaboration and maximizing project success.

The application will be a one stop destination for all progress tracking, connecting and scheduling needs of iDEA. 

The required documentation will provide an organized resource if further work has to be done on the project

### Future Scope
    1. Building the peer group mapping. Based on performance reports and history of projects completed we can build a model to group people to maximize productivity.
    2. Create a point based system for developers. Based on contributions to the club, projects successfully completed, points will 
