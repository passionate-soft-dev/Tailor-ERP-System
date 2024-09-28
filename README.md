# Tailor ERP System

This is a Tailor ERP system built using **CodeIgniter**, designed to manage and automate processes in a tailor shop, including order management, inventory management, and more.

## Table of Contents
1. [Requirements](#requirements)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Folder Structure](#folder-structure)
5. [Features](#features)
6. [Troubleshooting](#troubleshooting)
7. [Contributing](#contributing)
8. [License](#license)

## Requirements

Before you begin, ensure you have met the following requirements:
- **PHP**: >= 7.2
- **MySQL**: >= 5.6
- **Apache/Nginx**: Installed and running
- **Composer**: For dependency management
- **Node.js/NPM**: For front-end assets if needed

## Installation

1. Clone the repository:
   ```bash
   git https://github.com/passionate-soft-dev/Tailor-ERP-System.git
   cd Tailor-ERP-System


## Usage

1. **Start the local development server (or configure with Apache/Nginx):**
   ```bash
   php spark serve
   ```
   Visit the application at http://localhost:8080.

2. **Default Admin Credentials:**
- **Username:** admin
- **Password:** admin123

## Folder Structure
   ```bash
   /application
       /controllers
       /models
       /views
   /public
       /assets
       /css
       /js
   /database
       erp_db.sql
   .env.example
   composer.json
   package.json
   README.md
   ```
   - application/ - Contains the core CodeIgniter framework files and custom logic.
   - public/ - Public assets and index file.
   - database/ - Contains the initial SQL schema.

## Features
   - Order Management
   - Inventory Management
   - Customer Management
   - Tailor Assignment
   - Reporting & Analytics

## Troubleshooting

### Common Issues:

   1. 500 Internal Server Error:
      - Check file permissions for /application/cache and /application/logs.
      - Ensure Apache/Nginx points to the public/ directory.

   2. Database Connection Error:
      - Double-check your .env file for correct database credentials.
   3. Missing Dependencies:
      - Run composer install and npm install to ensure all packages are installed.

## Contributing
If you would like to contribute to this project, please fork the repository and submit a pull request. Contributions are welcome!

## License
This project is licensed under the MIT License.

**Thank you for using the Tailor ERP System platform! If you like this project, please give it a ⭐ on GitHub.**