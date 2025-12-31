# MediMitra - Because every dose matters
♾️Try MediMitra by clicking on the link :
https://medi-mitra-two.vercel.app/

MediMitra is a premium, web-based health application designed to help users manage their medication schedules with ease and precision. Built with a "Mobile-First" philosophy, it offers a seamless experience across all devices, featuring real-time alerts, cloud synchronization, and a clean, modern UI.

🚀 Features:-

▪️Personalized Medication Tracking: Easily add medications with dosage details, specific times, and color-coded categories.
▪️Real-time Notifications: High-visibility alarm system that alerts users exactly when it's time to take their medicine.
▪️Smart Dashboard: Instant overview of daily progress, showing percentage of completion and remaining tasks.
▪️Cross-Device Sync: Securely access your schedule from any device using a personal identification key.
▪️Responsive Design: Optimized for mobile, tablet, and desktop with a persistent navigation system.
▪️Secure Authentication: Built-in login/signup flow to keep health data private and localized.

🛠️ Technical Stack:-

▪️Frontend: HTML5, Tailwind CSS (Styling), Lucide-React (Icons)
▪️Framework: Vanilla JavaScript (ES6+)
▪️Backend/Database: Firebase Firestore (Real-time NoSQL database)
▪️Authentication: Firebase Auth (Anonymous & Custom logic)
▪️Typography: Plus Jakarta Sans (Google Fonts)

📂 Project Structure:-

▪️index.html: The core single-file application containing all logic, styling, and structural components.
▪️CSS (Tailwind): Utilizes utility classes for responsive layouts and "Glassmorphism" UI effects.
▪️Firebase Integration: Manages two main data collections:
▪️public/data/users: Stores user credentials.
▪️users/{uid}/meds: Stores private medication schedules.

⚙️ Setup & Installation

Since MediMitra is built as a portable single-file application, setup is minimal:

Clone the project:

git clone [repository-url]


Configuration:
Open index.html and locate the firebaseConfig object inside the <script type="module"> tag. Replace the placeholder values with your own Firebase Project credentials.

Run:
Open index.html directly in any modern web browser or use a local development server like Live Server (VS Code extension).

🛡️ Security Rules (Firestore)

To ensure data integrity, the following rules should be applied to your Firestore database:

Users can only read/write to their own users/{userId} path.

Public data path is restricted to credential verification only.

♾️Try MediMitra by clicking on the link below:⏬
https://medi-mitra-two.vercel.app/

# MediMitra-"Your Health, Our Mission" by: Sheetal Bajaj .
