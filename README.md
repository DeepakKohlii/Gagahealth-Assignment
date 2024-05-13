# GagaHeath - Health Blog Platform

**GagaHeath** is a platform where users can write blogs on health topics. Users need to register and login to publish or add a blog.

## Features:
- User registration and authentication
- Ability to publish and add health blogs
- View all blogs
- View user-specific blogs
- Simple and intuitive user interface

## Setup Instructions:
1. Clone the repository to your local machine:
    ```
    git clone <repository-url>
    ```

2. Navigate to the project directory:
    ```
    cd <project-directory>
    ```

3. Create a virtual environment (optional but recommended):
    ```
    python -m venv venv
    ```

4. Activate the virtual environment:
    - On Windows:
        ```
        venv\Scripts\activate
        ```
    - On macOS and Linux:
        ```
        source venv/bin/activate
        ```

5. Install dependencies:
    ```
    pip install -r requirements.txt
    ```

6. Apply migrations:
    ```
    python manage.py migrate
    ```

7. Run the development server:
    ```
    python manage.py runserver
    ```

## Usage:
1. Open your web browser and navigate to `http://127.0.0.1:8000`.

2. Register as a new user by clicking on the "Register" link and filling out the registration form.

3. After registering, log in using your credentials.

4. Once logged in, you can:
    - Publish new blog posts by clicking on the "Add Blog" link and filling out the blog post form.
    - View your own blogs by clicking on the "View Your Blogs" link.
    - View all blogs by navigating to the homepage.
    - Click on a blog post title to view the full blog post.

5. To log out, click on the "Log out" link in the navigation bar.

That's it! You can now use the GagaHeath Health Blog Platform to write and publish blogs on health topics.
