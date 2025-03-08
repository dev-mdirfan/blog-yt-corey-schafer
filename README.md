# Blog App - by Corey Schafer

A blog style application where different users can write different posts. This can be a blog posts, twitter updates, Instagram post etc.

- How to build a full-featured web application using the Django web framework in Python?
- How to work with databases?
- How to create an authentication system and accept user input from forms & send email to reset the password?

**Overview of the Web App**
   - The web application being built is a blog-style platform where users can write posts.
   - It includes features like user authentication, profile management, and CRUD operations for posts.

## Features

- **User authentication**: Register, Login, Logout, Forgot Password (Reset Password by getting email)
- **User profiles**: View Profile, Update Profile Information, Profile Picture, Resize Profile Picture if too large to save on web server
- **Blog posts**: View Posts, Update/Delete Own Posts, Asking for confirmation before deleting posts
- **Admin Page**: View all posts, Update/Delete any post, Search for posts, Pagination
- **Pagination**: Display limited number of posts per page

## Technologies

- **Django**: A high-level Python web framework that encourages rapid development and clean, pragmatic design.
- **SQLite**: A C-language library that implements a small, fast, self-contained, high-reliability, full-featured, SQL database engine.
- **Pillow**: A Python Imaging Library that adds image processing capabilities to your Python interpreter.
- **Bootstrap**: A free and open-source CSS framework directed at responsive, mobile-first front-end web development.
- **Crispy Forms**: A Django application that lets you easily build, customize and reuse forms using your favorite CSS framework.

### Functionalities

1. We use built-in `UserCreationForm` for registration.
2. Every templates resides in own app.
3. `Crispy_Forms` (third party) allows us to style our forms in bootstrap fashion.

4. **Authentication System**
   - Users can register for a new account.
   - Existing users can log in.
   - Password reset functionality is available via email.

   Example:
   - Registration: Users provide a username, email, and password to create an account.
   - Login: Existing users enter their credentials to access their accounts.
   - Password Reset: Users can request a password reset link via email.

5. **Profile Management**
   - Users can view and update their profile information.
   - Profile pictures can be uploaded, and the system resizes images.

   Example:
   - Users can change their profile picture by uploading a new image.
   - They can edit their name, bio, or other profile details.

6. **Post Handling**
   - Users can create, read, update, and delete posts.
   - Posts are organized in a user-friendly interface.

   Example:
   - Creating a post: Users write content, add images, and click "Publish."
   - Editing a post: Users can modify the content of their existing posts.
   - Deleting a post: Posts can be removed with confirmation.

7. **Learning Opportunities**
   - Building this application helps learners explore various Django functionalities.
   - Topics covered include databases, authentication, forms, email handling, and more.

   Example:
   - Learning to interact with a database to store posts and user information.
   - Implementing user authentication for secure access to the application.

8. **Accessing the Admin Page**
   - Django provides an admin page for backend management with a graphical interface.

   Example:
   - Admins can use this page to view and edit site content, including user accounts and posts.

## References

- **YouTube Channel**:  [Corey Schafer's Django Tutorials](https://www.youtube.com/playlist?list=PL-osiE80TeTtoQCKZ03TU5fNfx2UY6U4p)

