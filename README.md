# SkillGig_Freelancer_Portal

## Project Overview
This is a SkillGig Freelancer Website that allows clients to post jobs and projects, and freelancers can apply to them. The platform includes features like job postings, project listings, talent showcasing, contact forms, payment integration, sign-in/signup functionality, and workshops for skill development. The backend is developed using Java for handling business logic, database interaction, and server-side operations.

## Project Structure

- **Jobs/**: Contains files related to job postings where clients can post jobs, and freelancers can browse available opportunities.
  
- **Projects/**: Contains files for project management, allowing clients to list projects and manage applications from freelancers.

- **Talent/**: This directory showcases the profiles of freelancers, highlighting their skills and portfolios.

- **contact/**: Handles contact forms where users can get in touch with the support team or administrators.

- **images/**: Contains images used across the website, such as user profile pictures, project images, or website logos.

- **payment/**: Implements the payment gateway for transactions between freelancers and clients.

- **signin_signup/**: Manages user authentication, including login, registration, and password recovery functionalities.

- **workshops/**: Contains content for skill development workshops, where freelancers can improve their skills or learn new ones.

- **LICENSE**: The license governing the use and distribution of this project.

- **README.md**: Provides an overview and instructions for this project.

- **index.html**: The main landing page of the website that provides an introduction to the platform and its features.

- **script.js**: Contains the JavaScript functionalities used for interactive elements on the website, such as form validation, dynamic content, and more.

- **style.css**: The main CSS file responsible for styling the entire website, including layout, colors, fonts, and responsive design elements.

## Installation

### Backend (Java)

1. Ensure you have Java Development Kit (JDK) installed on your system.
2. Clone the repository:
   ```bash
   git clone https://github.com/your-username/freelancer-website.git
   ```
3. Navigate to the backend source directory:
   ```bash
   cd freelancer-website/backend
   ```
4. Build the project using Maven or Gradle (depending on your build tool).
   ```bash
   mvn clean install
   ```
   Or with Gradle:
   ```bash
   gradle build
   ```

5. Run the backend server:
   ```bash
   java -jar target/freelancer-website-backend.jar
   ```

### Frontend (HTML/CSS/JavaScript)

1. Navigate to the frontend directory:
   ```bash
   cd freelancer-website
   ```
2. Open `index.html` in your browser to view the website.

## Features

- **Job Posting**: Clients can post job listings and specify the required skills.
- **Project Listings**: Clients can manage projects and receive applications from freelancers.
- **Freelancer Profiles**: Freelancers can showcase their skills, portfolios, and availability.
- **Secure Payments**: Integrated payment gateway for safe transactions.
- **User Authentication**: Sign up and login functionality with secure password encryption.
- **Workshops**: Skill development workshops for freelancers to enhance their abilities.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Java, Spring Boot
- **Database**: MySQL for managing user and project data
- **Build Tool**: Maven or Gradle
- **Deployment**: Can be deployed on any Java-compatible application server like Apache Tomcat or using Spring Boot's embedded server.

## Usage

1. Clients can post jobs and projects by signing in and navigating to the respective sections.
2. Freelancers can create profiles and apply to projects.
3. Payments are securely processed through the integrated payment gateway.

## Contributing

If you'd like to contribute to this project, please fork the repository and submit a pull request with detailed changes.

## License

This project is licensed under the terms of the [MIT License](LICENSE).

---

This `README.md` file now includes instructions for running the backend in Java along with the frontend. 
