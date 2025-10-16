# Mergington High School Activities

A comprehensive web application that allows teachers to manage student registration for extracurricular activities at Mergington High School.

## Features

### Activity Management
- View all available extracurricular activities with detailed information
- Filter activities by multiple criteria:
  - **Category**: Sports, Arts, Academic, Community, Technology
  - **Day of the week**: Monday through Sunday, including weekend activities
  - **Time of day**: Before School, After School, Weekend
- Search activities by name or description
- View activity details including:
  - Schedule and meeting times
  - Maximum participants
  - Current participant list
  - Activity descriptions

### Teacher Authentication
- Secure teacher login system
- Session management
- Role-based access (Teacher and Admin roles)

### Student Registration
- Register students for activities (requires teacher authentication)
- Unregister students from activities (requires teacher authentication)
- Real-time participant tracking
- Email-based student identification

### Technology Stack
- **Backend**: FastAPI (Python)
- **Database**: MongoDB
- **Frontend**: Vanilla JavaScript, HTML5, CSS3
- **Authentication**: Argon2 password hashing

## Development Guide

For detailed setup and development instructions, please refer to our [Development Guide](../docs/how-to-develop.md).
