# e-commerce-back-end

## Description

For this challenge I was tasked with building the back end for an e-commerce site. I took a working Express.js API and configured it to use Sequelize to interact with a MySQL database. 

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Questions](#questions)

## Installation

The following steps are needed install and interact with the project: 
1. Clone the repo: https://github.com/vpratnicki/e-commerce-back-end.git
2. Install the following packages: 
- [MySQL2](https://www.npmjs.com/package/mysql2) and [Sequelize](https://www.npmjs.com/package/sequelize) to connect your Express.js API to a MySQL database 
- [dotenv](https://www.npmjs.com/package/dotenv) to use environment variables to store sensitive data, like MySQL username, password, and database name.

## Usage

Once the required packages are installed (see section above) follow these steps to interact with this app:
- Create an .env file and enter the database name, user and password. 
- Use the schema.sql file in the db folder to create your database using MySQL shell commands.
- Run 'npm run seed' to seed data to your database (in the package.json file, make sure "seed": "node seeds/index.js" is listed under scripts)
- Run 'npm start' and test the API endpoints. View the videos below for a walkthroughs.

### [Walkthrough that demonstrates the functionality of the e-commerce back end](https://watch.screencastify.com/v/RTvIuSTKzEDCYMNxmbd0)

### Walkthrough of GET, PUT, POST and DELETE for Category

https://user-images.githubusercontent.com/18556546/197418966-0267de06-e237-4509-bc70-3180cf4270f4.mp4

### Walkthrough of GET, PUT, POST and DELETE for Tag

https://user-images.githubusercontent.com/18556546/197418944-9674ed2a-6bf2-43b9-8a4a-20f130daaf84.mp4

### Walkthrough of GET, PUT, POST and DELETE for Product

https://user-images.githubusercontent.com/18556546/197418834-0421444e-cb03-47e5-a0d3-c51217c0f662.mp4

## Contributing 

Contributions are greatly appreciated! In fact, they are what makes this open source community such a wonderful place to learn, develop, and create. I welcome all suggestions that would make this project better, please fork the repo and create a pull request. Additionally you can open an issue with the tag "enhancement". 

Fork the Project: 
1. Create your feature branch (git checkout -b feature/awesome-feature).
2. Commit your changes (git commit -m 'Add some awesome feature'). 
3. Push to the branch (git push origin feature/awesome-feature).
4. Open a Pull Request.

## Questions

Have any questions about this project? Please reach out! 

- GutHub username: vpratnicki
- Link: [https://github.com/vpratnicki](https://github.com/vpratnicki)
- Email: vanessa@pratnicki
