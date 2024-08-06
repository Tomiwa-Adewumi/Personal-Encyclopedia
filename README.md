# Encyclopedia Rails Application

## Overview

Welcome to the Encyclopedia Rails Application! This project offers a platform for users to create, view, edit, and delete articles. It features robust search functionality to help users find relevant articles quickly. The application implements CRUD (Create, Read, Update, Delete) operations for articles and includes comprehensive testing to ensure functionality.

## Features

- **Create Articles:** Users can add new articles with relevant content.
- **View Articles:** Users can access detailed information about individual articles.
- **Edit Articles:** Users can update existing articles.
- **Delete Articles:** Users can remove articles no longer needed.
- **Search Functionality:** Users can search for articles using keywords.

## Getting Started

To get started with the Encyclopedia Rails Application, follow these steps:

1. **Clone the Repository:**

   ```bash
   git clone <repository_url>
   ```

2. **Install Dependencies:** Navigate to the project directory and run:

   ```bash
   bundle install
   ```

3. **Run Database Migrations:** Apply any pending database migrations:

   ```bash
   rails db:migrate
   ```

4. **Seed the Database:** Populate the database with initial data:

   ```bash
   rails db:seed
   ```

5. **Run the Application:** Start the Rails server:

   ```bash
   rails server
   ```

   Open your browser and navigate to `http://localhost:3000` to see the application in action.

## Testing

The project includes a suite of tests to validate the core functionality.

1. **Review Tests:** Open `article_test.rb` in the `test/models` directory to understand the test cases.

2. **Run Tests:** Execute the tests locally to ensure everything is functioning correctly:

   ```bash
   rails test
   ```

   This will execute all the test cases and provide feedback on the application's functionality.

## Resources

Here are some helpful resources for your development work:

- [Ruby on Rails Guides](https://guides.rubyonrails.org/) - Comprehensive documentation on Ruby on Rails.
- [Ruby Style Guide](https://rubystyle.guide/) - A style guide for consistent Ruby code.
- [Git Documentation](https://git-scm.com/doc) - Official documentation for Git.
