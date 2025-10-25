TuToR App
Description
TuToR is a student-tutor matching app designed to connect students with qualified tutors based on their course needs and availability. The app includes safety features like user verification, a review system, and in-app messaging to ensure secure and convenient interactions between students and tutors.

The app is built using React Native for the frontend and Firebase for the backend. It offers seamless navigation through various sections, such as finding a tutor, booking sessions, and chatting with tutors directly. Our goal is to simplify the process of finding help in academic subjects and make quality education more accessible.

Features
User-friendly interface: Easily navigate through the app to find tutors or manage sessions.
Profile customization: Upload and manage your profile photo, visible throughout the app.
Course search: Find tutors by searching for UCT courses.
In-app chat: Secure communication between students and tutors.
Booking system: Schedule and manage tutoring sessions directly in the app.
Tutor review system: Leave reviews for tutors after sessions.
Secure payment processing: Payments are processed securely, with automatic refunds for declined requests.
Installation
To get started with the TuToR app locally:

Clone the repository:
bash
Copy code
git clone https://github.com/LethaboCodes/TuToR-App.git
cd tutor
Install the dependencies:
bash
Copy code
npm install
Set up Firebase:
Create a Firebase project and configure the necessary services for authentication, database, and storage.
Add your Firebase credentials in the environment file.
Run the app:
bash
Copy code
npm run android  # For Android development
npm run ios      # For iOS development (requires macOS)
Usage
Home Screen: Displays available features like "Find Tutor," "Sessions," and "Chat."
Find Tutor: Search for tutors based on courses and availability. Once a tutor is found, you can request a session.
Sessions: View all your scheduled tutoring sessions.
Chat: Communicate directly with tutors in real time to clarify session details or discuss academic queries.
Roadmap
Planned future updates include:

Enhanced notification system.
Expanded payment options.
Advanced tutor filtering based on reviews and subject specialties.
Contributing
We welcome contributions! If you'd like to contribute:

Fork the repository.
Create your feature branch (git checkout -b feature/AmazingFeature).
Commit your changes (git commit -m 'Add some AmazingFeature').
Push to the branch (git push origin feature/AmazingFeature).
Open a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.
