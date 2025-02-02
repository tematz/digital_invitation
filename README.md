Below is the translated README for the event management project with digital invitations:

---

# Digital Event Management and Invitations System

## Description

A complete platform for managing events with a focus on digital invitations and attendance tracking. The application provides validated forms with error handling, generates unique invitation links, creates administrative links secured by passwords, and produces QR codes for mobile event access. An administrative dashboard enables efficient event management, attendance confirmation, and companion tracking.

## Features

- **Validated Forms:** Interactive forms with error handling to ensure data quality.
- **Digital Invitation Generation:** Unique links to invite people to events.
- **Secure Admin Link:** Password-protected access to the admin dashboard for event management.
- **Mobile QR Codes:** Automatic generation of QR codes for seamless mobile check-in.
- **Administrative Dashboard:** Manage events with insights on attendance confirmations and companions.
- **Camera Integration:** Use the mobile device camera to scan QR codes for quick check-in.

## Technologies

- **Turborepo:** Monorepo management for organizing modules (web, API, and mobile).
- **Next.js:** Development of a responsive web interface.
- **NestJS:** Creation of a scalable and modular API.
- **React Native:** Development of a native mobile application.
- **Prisma ORM:** Database management and migrations.
- **QR Code Libraries:** For generating and reading QR codes.

## Prerequisites

- Node.js (LTS version)
- npm or yarn
- Mobile development environment (Android Studio/Xcode)
- A database (e.g., PostgreSQL or MySQL)

## Installation and Setup

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/digital_event_invitations.git
   cd digital_event_invitations
   ```

2. **Install Dependencies:**

   ```bash
   npm install
   # or
   yarn install
   ```

3. **Database Setup:**

   - Update the `.env` file with your database credentials.
   - Run Prisma migrations:

     ```bash
     npx prisma migrate dev
     ```

4. **Running the Application:**

   - **API (NestJS):**

     ```bash
     cd apps/backend
     npm run start:dev
     ```

   - **Frontend (Next.js):**

     ```bash
     cd apps/frontend
     npm run dev
     ```

   - **Mobile (React Native):**

     ```bash
     cd apps/mobile
     npx react-native run-android  # for Android
     npx react-native run-ios      # for iOS
     ```

## Contribution

Contributions are welcome! To contribute:

1. Fork the project.
2. Create a branch (`git checkout -b feature/your-feature-name`).
3. Commit your changes.
4. Push your branch (`git push origin feature/your-feature-name`) and open a Pull Request.

## Contact

Questions or suggestions: [matvno@gmail.com](mailto:matvno@gmail.com)

---