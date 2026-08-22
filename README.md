# Kapurthala Computer Care Academy Management System

A complete, professional, and production-ready Academy Management System with Admin, Teacher, and Student portals.

## Features

✅ **Complete Portal System**
- Admin Portal - Full system management
- Teacher Portal - Controlled teaching and attendance management
- Student Portal - Personal academic tracking

✅ **Excel Integration**
- Two-way Excel import/export
- Existing Excel format preservation
- Column mapping and validation
- Duplicate detection

✅ **Data Management**
- Student management with multiple statuses
- Teacher management and assignments
- Comprehensive attendance tracking
- Fee management and payment tracking
- Timetable scheduling
- Syllabus management with topics and subtopics

✅ **Advanced Features**
- Centralized notification system
- Complete backup and restore system
- Role-based access control
- Document and attachment handling
- Internship management
- Inquiry system
- Comprehensive reporting

✅ **Professional UI/UX**
- Material Design 3 principles
- Modern glassmorphism design
- Fully responsive layout
- Dark/Light theme support
- Grid/List view toggle
- Advanced search and filtering

✅ **Production Ready**
- Secure authentication and authorization
- Input validation and sanitization
- Performance optimization
- Accessibility features (WCAG 2.1)
- Comprehensive error handling
- Zero console errors

## Quick Start

### Prerequisites
- Node.js (v16 or higher)
- MongoDB (v4.4 or higher)
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/Kptsingh1/KapurthalaComputerCare.git
cd KapurthalaComputerCare

# Install dependencies
npm install

# Create .env file
cp .env.example .env

# Update .env with your configuration

# Start MongoDB
mongod

# Run the development server
npm run dev
```

The application will be available at `http://localhost:3000`

## Project Structure

```
KapurthalaComputerCare/
├── public/                 # Static files
├── src/
│   ├── components/        # React components
│   ├── pages/            # Page components
│   ├── services/         # API services
│   ├── hooks/            # Custom React hooks
│   ├── context/          # React context
│   ├── styles/           # Global styles
│   ├── utils/            # Utility functions
│   ├── data/             # Default data and templates
│   ├── App.jsx
│   └── index.jsx
├── server/
│   ├── config/           # Configuration files
│   ├── routes/           # API routes
│   ├── controllers/      # Controller functions
│   ├── models/           # Database models
│   ├── middleware/       # Express middleware
│   ├── services/         # Business logic
│   ├── utils/            # Utility functions
│   └── server.js         # Entry point
├── Excel-Templates/      # Template files
├── Documentation/        # Project documentation
└── package.json
```

## Default User Credentials

### Admin
- Email: `admin@academy.com`
- Password: `Admin@123`

### Teacher
- Email: `teacher@academy.com`
- Password: `Teacher@123`

### Student
- Email: `student@academy.com`
- Password: `Student@123`

## Available Scripts

```bash
# Development (runs both client and server)
npm run dev

# Client only
npm run client

# Server only
npm run server

# Build for production
npm run build

# Production start
npm start

# Run tests
npm test
```

## Documentation

See the [Documentation](./Documentation) folder for:
- [Setup Guide](./Documentation/SETUP.md)
- [User Guide](./Documentation/USER_GUIDE.md)
- [API Documentation](./Documentation/API_DOCUMENTATION.md)
- [Design System](./Documentation/DESIGN_SYSTEM.md)
- [Implementation Requirements](./Documentation/REQUIREMENTS.md)

## Excel Import/Export

The system supports importing and exporting data in Excel format while preserving the existing workbook structure:

**Supported Sheets:**
- Student's Record
- Teacher's Record
- Time Table
- Fees Management
- Cards
- Dashboards

**Export Options:**
- Individual records
- Filtered data
- Complete academy backup
- Role-based export restrictions

## Backup & Restore

Admin users can:
- Create full academy backups
- Create selective module backups
- Restore from backups with merge/replace options
- Preview backup contents before restoration
- Track backup history and status

## Role-Based Access

### Admin
- Full system access
- User and permission management
- System settings and configuration
- Excel import/export
- Backup and restore
- Comprehensive reporting

### Teacher
- Assigned student management
- Attendance tracking
- Syllabus management
- Note creation and management
- Student performance tracking
- Permission-restricted export

### Student
- View own profile and progress
- View course and syllabus
- Track attendance
- Check fees and payment history
- Download notes and certificates
- Submit inquiries and internship applications
- View notifications

## Security Features

- ✅ JWT-based authentication
- ✅ Password hashing with bcryptjs
- ✅ Role-based access control (RBAC)
- ✅ Input validation and sanitization
- ✅ SQL injection prevention
- ✅ CSRF protection
- ✅ Secure file uploads
- ✅ Permission-based data access

## Performance Optimizations

- ✅ Lazy loading components
- ✅ Code splitting
- ✅ Debounced search
- ✅ Pagination and infinite scroll
- ✅ Image optimization
- ✅ Efficient API calls
- ✅ Caching strategies
- ✅ Minified production build

## Accessibility

- ✅ WCAG 2.1 Level AA compliance
- ✅ Semantic HTML
- ✅ ARIA labels and attributes
- ✅ Keyboard navigation support
- ✅ Screen reader friendly
- ✅ Sufficient color contrast
- ✅ Focus management
- ✅ Reduced motion support

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Contributing

Please read our [Contributing Guide](./CONTRIBUTING.md) before submitting pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

## Support

For support, email support@academy.com or open an issue on GitHub.

## Changelog

See [CHANGELOG.md](./CHANGELOG.md) for version history and updates.
