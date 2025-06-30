Dental Center Management Dashboard 

Setup

Clone the repository.

Run npm install to install dependencies.

Start the app with npm run dev (or npm start).

App runs locally on http://localhost:3000.

Architecture

React Functional Components with React Router for navigation.

Context API manages global state including users, patients, and appointments.

localStorage persists all data (users, patients, incidents, files).

Tailwind CSS used for responsive, clean styling.

Known Issues

Calendar view UI currently minimal.

Basic file preview; advanced viewer not implemented.

No backend validation (per assignment requirement).

Technical Decisions

Chose Context API over Redux for simplicity given app size.

Used localStorage for data persistence to meet 'no backend' constraint.

Tailwind for rapid, consistent responsive design.

Hardcoded initial user list to simulate authentication.

