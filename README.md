# Form-Builder-JS

This impressive full-stack form builder application serves as a showcase of your skills in modern web development. Built with a combination of popular technologies, it offers a user-friendly interface for creating and managing forms.

## Table of Contents

- [Features](#features)

- [Installation](#installation)

- [Prerequisites](#prerequisites)

- [Clone the Repository](#clone-the-repository)

- [Configuration](#configuration)

- [Build and Run](#build-and-run)

- [Contributing](#contributing)

- [License](#license)

## Features

List the key features and functionalities of Form-Builder-JS:

- Registration: Users can easily create accounts using Clerk, ensuring secure access.

= Drag-and-Drop Form Builder: DND-Kit empowers users to build forms by dragging and dropping various form elements (text fields, dropdowns, etc.).

- Form Preview: Users can instantly visualize the created form, allowing for iterative design and testing.

- Subdomain-Based Form Hosting: Each form is potentially hosted on a unique subdomain using its ID, offering a clean and accessible way to share custom forms.

- Data Analytics Dashboard: Users can access a personalized dashboard displaying insights and analytics about their forms' activity.

## Installation

Follow these steps to install and run Form-Builder-JS on your system.

### Prerequisites

Before you begin, ensure you have the following dependencies and tools installed:

- [Node.js](https://nodejs.org/en)

- [React](https://react.dev/)

- [Next.js](https://nextjs.org/)

- [Prisma](https://www.prisma.io/)

- [Clerk](https://clerk.com/)

- [DND-Kit](https://dndkit.com/)

- [Tailwind CSS](https://tailwindcss.com/)

### Clone the Repository

1. Open your terminal or command prompt.

2. Use the following command to clone the Form-Builder-JS repository:

git clone https://github.com/Rae-Nelvin/Form-Builder-JS.git

### Configuration

1. Change your working directory to the cloned repository:

cd Form-Builder-JS

2. Install dependencies by running:

npm install

3. Clone and create .env the .env.example by running:

cp .env.example .env

4. Register a Clerk Account and get the credentials for the authentication

5. Run the initialize configuration for prisma by running:

npx prisma generate

6. Fills out the required fields into the .env

7. Run the following command to migrate to prisma db:

prisma migrate --dev

### Build and Run

1. To build and run the project, use the following command:

npm run dev

npx prisma studio

This will build the project and install it on your connected device or emulator.

## Contributing

Since it's just a self-learning project, I don't expect any contributions to Form-Builder-JS.

Thank you for choosing Form-Builder-JS! If you encounter any issues or have suggestions for improvements, please don't hesitate to create an issue. We look forward to your feedback.

## License

I don't own any license for the YouTube Crash Course Tutorial Form Builder. Form-Builder-JS is licensed under the [MIT License](LICENSE). [https://github.com/Kliton/yt_pageform/?tab=MIT-1-ov-file]

Thank you for choosing Form-Builder-JS! If you encounter any issues or have suggestions for improvements, please don't hesitate to [create an issue](https://github.com/Kliton/yt_pageform/issues). We look forward to your feedback and collaboration.
