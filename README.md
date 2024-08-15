# Dashboard Application

This is a dashboard application built using React, Material-UI, and react-pro-sidebar. The application provides various features such as managing team members, viewing contacts, handling invoices, and displaying different types of charts including bar, line, pie, and geography charts.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/dashboard-app.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd dashboard-app
   ```

3. **Install dependencies:**

   ```bash
   npm install
   ```

## Usage

1. **Start the development server:**

   ```bash
   npm start
   ```

2. **Open your browser and navigate to:**

   ```
   http://localhost:3000
   ```

## Features

- **Dashboard Overview:** A summary of key metrics such as revenue, emails sent, sales, and traffic.
- **Team Management:** Add, view, and manage team members.
- **Contacts Information:** Manage and view contact details.
- **Invoices:** Keep track of invoices and payments.
- **Charts:** View different types of charts including bar, line, pie, and geography charts.
- **Customizable Themes:** Toggle between dark and light modes with a customized color scheme.

## Customization

### Changing Colors

You can customize the color theme of the application by modifying the `tokens` function in the `theme.js` file. The application supports both dark and light modes.

- **Dark Mode:** The primary colors are `#1E042F` and `#12021C`.
- **Light Mode:** The primary colors are `#FFF5FB` and `FCE3F2`.

### Sidebar

The sidebar is built using `react-pro-sidebar`. You can customize the items and links by modifying the `Sidebar.jsx` file.

### Adding New Pages

To add new pages, create a new component in the `scenes` directory and add a corresponding route in the `App.js` file.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure your code adheres to the existing coding standards and includes relevant tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
