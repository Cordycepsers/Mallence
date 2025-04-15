# RFP Monitoring System

A comprehensive web application for monitoring Request for Proposals (RFPs) and other funding opportunities across multiple websites.

## Features

- **Automated Monitoring**: Automatically searches for RFPs and funding opportunities across 25+ websites
- **Custom Search**: Monitors for specific service keywords like video, photo, multimedia, design, etc.
- **User-Friendly Dashboard**: Visual statistics and metrics for monitoring activity
- **Opportunity Management**: Track, save, and manage discovered opportunities
- **Email Notifications**: Get alerts for new opportunities matching your criteria
- **Export Functionality**: Export results to CSV for further analysis
- **User Authentication**: Secure multi-user access with role-based permissions
- **Mobile Responsive**: Works on desktop, tablet, and mobile devices

## Technology Stack

- **Frontend**: React.js with Material-UI
- **Backend**: Node.js with Express
- **Database**: MongoDB
- **Search API**: Google Custom Search API
- **Deployment**: Docker and Docker Compose

## Getting Started

### Prerequisites

- Node.js (v14+)
- MongoDB
- Docker and Docker Compose (for production deployment)

### Development Setup

1. Clone the repository
2. Install backend dependencies:
   ```
   cd backend
   npm install
   ```
3. Install frontend dependencies:
   ```
   cd frontend
   npm install
   ```
4. Set up environment variables:
   - Create a `.env` file in the backend directory based on the example
   - Set your Google Custom Search API key and Search Engine ID
5. Initialize the database:
   ```
   cd backend
   npm run init-db
   ```
6. Start the development servers:
   - Backend: `npm run dev` in the backend directory
   - Frontend: `npm start` in the frontend directory

### Production Deployment

See [DEPLOYMENT.md](DEPLOYMENT.md) for detailed production deployment instructions.

## Default Credentials

After initializing the database, you can log in with:

- **Admin User**:
  - Email: admin@example.com
  - Password: admin123

- **Regular User**:
  - Email: user@example.com
  - Password: user123

**Important**: Change these passwords immediately after first login.

## Configuration

The system monitors the following types of websites:
- UN and international organizations
- Development banks and funds
- NGOs and humanitarian organizations
- Development platforms
- Other specialized organizations

It searches for opportunities containing service keywords like:
- video, photo, film, multimedia, design
- visual, campaign, podcasts, virtual event, media
- animation, animated video, promotion, communication, audiovisual

## License

This project is proprietary and confidential.

## Support

For support, please contact the development team.

