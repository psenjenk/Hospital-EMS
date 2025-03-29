# Hospital Management System

A comprehensive Hospital Management System built with Node.js and MySQL, designed to streamline hospital operations and improve patient care.

## Features

### Core Functionalities
- **Staff Management**
  - Employee registration and profile management
  - Role-based access control
  - Staff attendance tracking
  - Performance monitoring

- **Patient Management**
  - Patient registration and records
  - Emergency patient handling
  - Medical history tracking
  - Appointment scheduling

- **Room Management**
  - Room allocation and tracking
  - Bed management
  - Room status monitoring
  - Room type categorization

- **Medical Records**
  - Digital patient records
  - Treatment history
  - Prescription management
  - Medical reports

- **Appointment System**
  - Online appointment booking
  - Appointment scheduling
  - Reminder notifications
  - Calendar management

- **Complaint Portal**
  - Patient feedback system
  - Complaint tracking
  - Resolution management
  - Analytics dashboard

- **Hardware Management**
  - Medical equipment inventory
  - Maintenance scheduling
  - Equipment allocation
  - Status tracking

- **Billing System**
  - Patient billing
  - Insurance integration
  - Payment tracking
  - Financial reports

- **Communication**
  - Email notifications
  - SMS alerts
  - Internal messaging
  - Patient communication

## Technology Stack

### Backend
- Node.js
- Express.js
- MySQL Database
- Passport.js (Authentication)
- bcrypt (Password Hashing)

### Frontend
- HTML5
- CSS3
- JavaScript
- Bootstrap
- EJS (Template Engine)
- SweetAlert2 (Notifications)

### Additional Tools
- Nodemailer (Email Service)
- Express Validator
- Express Session
- Connect Flash

## Prerequisites

- Node.js (v12 or higher)
- MySQL (v5.7 or higher)
- npm (v6 or higher)
- Modern web browser

## Installation

1. Clone the repository:
   ```bash
   git clone [repository-url]
   cd Hospital-Management-System
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up the database:
   - Create a MySQL database named 'hms'
   - Import the database schema:
     ```bash
     mysql -u [username] -p hms < database.sql
     ```

4. Configure the application:
   - Open `controllers/db_controller.js`
   - Update the database connection details:
     ```javascript
     host: 'localhost',
     user: 'your_username',
     password: 'your_password',
     database: 'hms'
     ```

5. Set up email service (optional):
   - Add your email server details in the database:
     ```sql
     INSERT INTO server VALUES('<email>', '<password>', '<proxy:port>');
     ```

6. Start the application:
   ```bash
   node main.js
   ```

7. Access the application:
   - Open your browser and navigate to `http://localhost:3000/home`

## User Roles

1. **Manager**
   - System administration
   - Staff management
   - Financial oversight
   - Report generation

2. **Doctor**
   - Patient management
   - Medical records
   - Prescription writing
   - Appointment handling

3. **Nurse**
   - Patient care
   - Room management
   - Medical assistance
   - Record updates

4. **Receptionist**
   - Patient registration
   - Appointment scheduling
   - Front desk operations
   - Query handling

5. **Maintenance Staff**
   - Equipment management
   - Room maintenance
   - Hardware tracking
   - Facility upkeep

## Security Features

- Password hashing with bcrypt
- Session-based authentication
- Role-based access control
- Input validation
- SQL injection prevention
- XSS protection

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the GNU General Public License v3.0 (GNU GPL v3) - see the [LICENSE](LICENSE) file for details. This license ensures that:

- The software remains free and open source
- Any modifications or distributions must also be open source
- Users have the right to:
  - Use the software for any purpose
  - Study how the software works
  - Modify the software
  - Distribute the software
  - Distribute modified versions of the software

For more information about the GNU GPL v3, please visit: https://www.gnu.org/licenses/gpl-3.0.txt

## Support

For support, please contact the system administrator or create an issue in the repository.

## Acknowledgments

- All contributors who have helped shape this project
- The open-source community for the tools and libraries used
- The healthcare professionals who provided valuable feedback



