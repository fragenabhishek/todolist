# To-Do List Web Application

## Introduction
This is a simple To-Do List web application built with Node.js, Express, and MongoDB. The application allows users to create, read, update, and delete to-do items. Users can also create custom lists with their desired names.

## Prerequisites
Before running the application, ensure that you have the following installed:
- Node.js (https://nodejs.org)
- MongoDB (https://www.mongodb.com)

## Installation
1. Clone the repository to your local machine using the following command:
 git clone https://github.com/your-username/to-do-list.git
2. Change into the project directory:
cd to-do-list
3. Install the required npm packages:
npm install

## Usage
1. Start the MongoDB server on your machine.
2. Run the application using the following command:
node app.js
3. Open your web browser and navigate to `http://localhost:3000` to access the To-Do List application.
4. To create a new to-do item, simply type the task in the input field and click the "Add" button.
5. To view or manage your to-do items, click on the list with the title "Today."
6. To create a custom list, append the desired list name to the URL (e.g., `http://localhost:3000/your-list-name`) and press Enter.
7. To delete a to-do item, click on the checkbox next to the item and then click the "Delete" button.

## Database
The application uses MongoDB to store the to-do items. The connection string for MongoDB Atlas is provided in the `app.js` file. Replace `<username>` and `<password>` with your MongoDB Atlas credentials to connect to your database.

## Technologies Used
- Node.js
- Express.js
- MongoDB
- EJS (Embedded JavaScript) for templating
- lodash (for string manipulation)

## Author
[Your Name](https://github.com/your-username)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
