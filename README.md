# LiveToTravel - Interactive Travel Tracking Application

LiveToTravel is an interactive web application that allows users to track and visualize countries they've visited on a world map. Built with Node.js, Express, and PostgreSQL, it features user authentication and a dynamic SVG-based world map interface.

## 🌟 Features

- **Interactive World Map**: Click or tap on countries to mark them as visited
- **User Authentication**: Secure login and registration system
- **Personalized Tracking**: Each user can track their own visited countries
- **Custom Color Schemes**: Users can choose their own color for marking visited countries
- **Responsive Design**: Works on both desktop and mobile devices
- **Real-time Updates**: Instant visual feedback when marking countries
- **Country Count**: Track the total number of countries visited

## 🛠️ Technologies Used

- **Backend**: Node.js, Express.js
- **Database**: PostgreSQL
- **Authentication**: JWT (JSON Web Tokens), bcrypt
- **Frontend**: EJS, SVG, Vanilla JavaScript
- **Styling**: CSS3 with custom animations
- **Container**: Docker support

## 🚀 Getting Started

### Prerequisites

- Node.js (v20 or higher)
- PostgreSQL
- npm or yarn

### Installation

1. Clone the repository: git clone https://github.com/yourusername/livetotravel.git -> cd livetotravel
2. Install dependencies: npm install
3. Create a `.env` file in the root directory with the following variables:
  DB_HOST=your_database_host
  DB_NAME=your_database_name
  DB_PASS=your_database_password
  JWT_SECRET=your_jwt_secret
4.Start the application: node index.js

To run the application using Docker: docker build -t livetotravel . -> docker run -p 3000:3000 livetotravel


## 📱 Usage

1. Register a new account or login with existing credentials
2. Click/tap on countries you've visited on the world map
3. Watch your travel statistics update in real-time
4. Customize your visited countries' color in the settings

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the ISC License - see the [LICENSE](LICENSE) file for details.

## 👥 Authors

- Your Name - Initial work - [YourGitHubUsername](https://github.com/YourGitHubUsername)

## 🙏 Acknowledgments

- World map SVG data
- Node.js community
- Express.js team
- PostgreSQL community

