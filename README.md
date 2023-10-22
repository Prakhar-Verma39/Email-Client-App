# Email Client App - Outlook Clone

This is a React and Redux-based email client app designed to emulate the features and functionalities of Outlook. The application allows users to view, manage, and interact with their emails. It utilizes the provided APIs for fetching emails and email bodies.

## Features

### Email List View

- The app provides an email list page, displaying a list of emails sent to the user.
- Each email item in the list includes details such as sender (from), subject, a short description, date, and time.
- The avatar (circular logo) in each email item is populated with the first character of the sender's first name from the API response.

### Email Body View

- Clicking on any email item in the list splits the screen into a master-slave (left-right) layout. The master section (left) displays the email list with the selected email item, while the slave section (right) displays the body of the email.
- The email body view includes the email subject, email body content, and email date and time.

### Mark as Favorite

- Users can mark a specific email as "favorite" by clicking on an email item and then using the "Mark as Favorite" button in the email body section.

### Read and Unread Emails

- The app visually distinguishes between read and unread emails using different CSS styles.

### Filter Emails

- The app allows users to filter emails by various criteria, including "favorites," "read," and "unread."


## API Sources

- Email List APIs (Not Paginated): [https://flipkart-email-mock.now.sh/](https://flipkart-email-mock.now.sh/)
- Email List APIs (Paginated): [https://flipkart-email-mock.now.sh/?page=<pageNumber>](https://flipkart-email-mock.now.sh/?page=<pageNumber>)
- Email Body API: [https://flipkart-email-mock.now.sh/?id=<email-item-id>](https://flipkart-email-mock.now.sh/?id=<email-item-id>)

## Getting Started

### Prerequisites

Before you begin, make sure you have the following software installed on your machine:

- Node.js (v18 or higher)
- npm (v7 or higher)

### Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/Prakhar-Verma39/Email-Client-App.git

2. Change to the project directory:
   ```bash
   cd Email

3. Install the project dependencies:
    ```bash
    npm install

### Development

To start the development server, run the following command:
```bash
    npm run dev

This will start a development server, and your app will be available at `http://localhost:3000`.

### Building for Production

When you're ready to build your application for production, use the following command:
```bash
    npm run build
    
## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This project was created with React and Redux.
- Email List and Email Body APIs provided by [flipkart-email-mock](https://flipkart-email-mock.now.sh/).

