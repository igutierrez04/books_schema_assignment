# books_schema_assignment

YOUR TASK: Create and ERD to represent the database for an application
    that tracks users, books, and user's favorite books.

    Each book should have an id, title, and eeach user should be able
    to save their favorite books.

    Use the MySQL Workbench for creating this databse.

    - Create a new model (ERD)
    - Name the schema books_schema
    - Create a table called users
    - Add the fields to the users tablee including:
        id
        name
        created_at
        updated_at
    - Create a table called books
    - Add fields to the books table including:
        id
        title
        num_of_pages
        created_at
        updated_at
    - Create a many to many relationship between users and books and rename the
        joining table to favorites
    -Change the field names to the singular pronoun. ie. users_id and book_id
