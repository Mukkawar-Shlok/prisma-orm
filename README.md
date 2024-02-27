# Prisma-orm trial

trying out basic functionalities of prisma orm.

## Installation

1. **Clone the repository:**

    ```bash
    git clone <repository_url>
    cd project-directory
    ```

2. **Install dependencies:**

    ```bash
    npm install
    ```

3. **Set up Environment Variables:**

    Create a `.env` file in the root directory of the project and add the following environment variables:

    ```plaintext
    DATABASE_URL="your_database_connection_url"
    ```

    Replace `"your_database_connection_url"` with the URL of your database connection.

## Database Migration

To apply database migrations, run the following command:

```bash
npx prisma migrate dev
