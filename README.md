# Attendance Tracker for AWS re/Start

## Project Overview
This project aims to streamline the attendance process for AWS re/Start Cohorts using facial recognition and automated metadata extraction. The solution involves a mobile app and a web-based admin dashboard to eliminate manual check-ins and enhance efficiency.

## Features
- **Facial Recognition**: Automatically detect and verify learners' faces.
- **Metadata Extraction**: Determine the time and location from the image metadata to ensure learners are physically present.
- **Admin Dashboard**: Manage cohorts, onboard learners, and generate detailed attendance reports.
- **Mobile App Interface**: Learners can take a picture and submit it for attendance upon arrival.

## Technologies Used
- **Frontend**: React for web dashboard, React Native for mobile app.
- **Backend**: Node.js with Express for API, MongoDB as the database.
- **Facial Recognition**: Python using deep learning models like Inception for facial feature extraction.

## Development Approach
- **DevOps Culture**: Integration with CI/CD pipeline using GitLab to streamline development, testing, and deployment.
- **Security Hardening**: CIS benchmarks applied to improve overall system security.

## Project Outcome
- Developed a robust attendance tracking solution, successfully deployed, and evaluated in a Kubernetes cluster environment.
- Achieved a final project grade of 19/20.

## Future Work
- Add first-time login feature and implement liveness detection to further enhance security.
