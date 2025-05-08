# Guilherme Teixeira's Portfolio

This project (guilhermeteixeira.dev) is a personal portfolio website showcasing the projects developed by Guilherme Teixeira. The site is designed to highlight technical skills, certifications, and professional experience, while providing detailed information about individual projects.

The portfolio includes:
- A homepage with featured projects.
- A dedicated page for all projects.
- An "About" page with information about the author.
- A "Contact" page with a form and links to social media.

## Table of Contents
1. Features
2. Technologies
3. Project Structure and Content
4. How to Run
5. Author

## Features

- **Dynamic Project Showcase:**
  - Displays featured projects on the homepage.
  - A dedicated "All Projects" page lists all portfolio projects with descriptions and links to detailed pages.

- **Detailed Project Pages:**
  - Each project has its own page with a description, features, and repository links.

- **Contact Form:**
  - A functional contact form for visitors to send messages.
  - Links to GitHub, LinkedIn, and WhatsApp for direct communication.

- **Responsive Design:**
  - Fully responsive layout for desktop, tablet, and mobile devices.

- **SEO Optimized:**
  - Meta tags for Open Graph (Facebook, LinkedIn) and Twitter cards.

## Technologies

### **Front-end:**
- HTML5
- CSS3
- JavaScript
- Google Fonts

### **Build and Deployment:**
- GitHub Actions

### **Cloud:**
- AWS S3
- AWS CloudFront

This portfolio website is hosted in the AWS Cloud, leveraging a serverless architecture with AWS S3 (Simple Storage Service) for static content hosting and AWS CloudFront distributions for global content delivery and caching. The deployment process is automated through GitHub Actions CI/CD pipeline, which updates content in the S3 bucket whenever changes are committed to the repository. The infrastructure also utilizes Security Groups, Policies and Roles of AWS IAM (Identity and Access Management) for secure access control, and ACM (AWS Certificate Manager) for SSL certificates ensuring encrypted connections. This approach provides a highly available, scalable and cost-effective solution for hosting static websites without the need for traditional server infrastructure.

## Project Structure and Content

The portfolio is organized into the following sections:

### **Homepage (index.html)**
- Presents featured projects with images, titles, and descriptions.
- Provides direct links to detailed pages for each project.

### **All Projects (allprojects.html)**
- Displays a complete list of all portfolio projects.
- Each project contains a title, concise description, and link to its detailed page.

### **About (about.html)**
- Highlights the author's qualifications and experience:
  - Technical skills: Java, Python, Spring, DBMS, Git, Maven, SQL, JPQL.
  - Certifications: AWS and Google Data Analytics.
  - Personal interests: Family, barbecue, and volunteer work.

### **Contact (contact.html)**
- Offers an interactive form with fields for name, email, and message.
- Includes direct links to:
  - GitHub
  - LinkedIn
  - WhatsApp

### **Individual Project Pages**
Each project has a dedicated page with detailed information:

- **Ecommerce with Spring Boot and JPA** (posts/Ecommerce-with-Spring-Boot-and-JPA.html)
  - Java back-end application implementing business logic for an e-commerce system.
  - Technologies: Spring Boot, Spring MVC, Spring Data JPA, PostgreSQL...
  - Repositories: [Back-end](https://github.com/gamtcode/ecommerce-spring-boot-jpa-backend), [Front-end](https://github.com/gamtcode/ecommerce-spring-boot-jpa-frontend)

- **JDBC and MySQL Operations** (posts/JDBC-and-MySQL-Operations.html)
  - Study project demonstrating CRUD operations using JDBC and MySQL.
  - Technologies: JDBC, MySQL, Factory and DAO design patterns...
  - Repository: [JDBC and MySQL Operations](https://github.com/gamtcode/jdbc-and-mysql-operations)

- **JPA Learning System** (posts/JPA-Learning-System.html)
  - Study project demonstrating CRUD operations using JPA.
  - Technologies: JPA, Java, PostgreSQL...
  - Repository: [JPA Learning System](https://github.com/gamtcode/jpa-learning-system)

Additional projects will be added to the portfolio in the future as new development work is completed. The site is designed to be easily expandable to showcase ongoing learning and professional growth.

## How to Run

The portfolio is available online at: [guilhermeteixeira.dev](https://guilhermeteixeira.dev)

To clone and run this portfolio locally, you'll need Git and a web browser.

### **Steps:**
1. Clone the repository:
   ```bash
   git clone https://github.com/gamtcode/guilhermeteixeira.dev
   ```

2. Navigate to the project folder:
   ```bash
   cd guilhermeteixeira.dev
   ```

3. Open `index.html` in your browser to view the homepage.

## Author

This portfolio was developed by Guilherme Teixeira, a Systems Developer Analyst with Full Stack skills and AWS certification. Some JavaScript effects and UI components were inspired by or adapted from Webflow. If you have any questions or would like to collaborate, feel free to [get in touch](https://www.guilhermeteixeira.dev/contact.html) or connect via [GitHub](https://github.com/gamtcode) or [LinkedIn](https://www.linkedin.com/in/dev-guilherme-teixeira/).