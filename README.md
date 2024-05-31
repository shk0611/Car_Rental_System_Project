<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>

<!-- PROJECT SHIELDS -->
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/github_username/repo_name">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Car Rental Booking and Management System</h3>

  <p align="center">
    A comprehensive system for managing car rentals, bookings, clients, and insurance options.
  </p>
</div>

<br><br>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

The Car Rental Booking and Management System is a comprehensive application designed to streamline the management of car rentals, bookings, clients, and insurance options. This system is built using JavaFX and CSS for the user interface and MySQL for the database backend, providing a robust and scalable solution.

#### Key Features:

 ###### User Interface (UI) Applications:
  * Modern UI with JavaFX, enhanced with CSS for styling and FXML for layout.

 ###### MYSQL Database:
  * Store and retrieve data reliably with support for transactions.

 ###### Management:
  * Add, Update, Delete vehicle, client, reservation information
  * Display details with dynamic updates

 ###### Thread Safety and Preventing Race Conditions:
  * Synchronized methods, ExecutorService, Transaction management, Scheduled tasks

 ###### Design Patterns:
  * MVC, DAO, Strategy

#### Built With

* [Java](https://www.java.com/)
* [JavaFX](https://openjfx.io/)
* [MySQL](https://www.mysql.com/)
* [Maven](https://maven.apache.org/)
* [SceneBuilder](https://gluonhq.com/products/scene-builder/)

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

You will need the following software installed:
* Java 11
* Maven
* MySQL

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/github_username/repo_name.git
   ```
2. Install Maven dependencies
   ```sh
   mvn install
   ```
3. Set up the database
   ```sh
   mysql -u root -p < create_table.sql
   mysql -u root -p < rental_project_schema.sql
   ```
4. Run the application
   ```sh
   mvn javafx:run
   ```

<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples, and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<!-- ROADMAP -->
## Roadmap

- [ ] Implement additional features for managing car rentals
- [ ] Enhance the user interface with more interactive elements
- [ ] Integrate additional payment methods
- [ ] Add support for more insurance options

<!-- CONTACT -->
## Contact

Email - shyke0611@gmail.com

Project Link: [https://github.com/shyke0611/Car_Rental_Project.git](https://github.com/github_username/repo_name)

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [othneildrew - Best README Template](https://github.com/othneildrew/Best-README-Template)
* [Maven Repository](https://mvnrepository.com/)
* [Img Shields](https://shields.io)
* [Font Awesome](https://fontawesome.com)
* [Font Awesome Cheatsheet](https://fontawesome.com/v4/cheatsheet/)

<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo_name.svg?style=for-the-badge
[contributors-url]: https://github.com/github_username/repo_name/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo_name.svg?style=for-the-badge
[forks-url]: https://github.com/github_username/repo_name/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo_name.svg?style=for-the-badge
[stars-url]: https://github.com/github_username/repo_name/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo_name.svg?style=for-the-badge
[issues-url]: https://github.com/github_username/repo_name/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo_name.svg?style=for-the-badge
[license-url]: https://github.com/github_username/repo_name/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/linkedin_username
[product-screenshot]: images/screenshot.png