# Registration Form Web Application

## Overview
This project is a simple web application designed to provide a registration form along with a table that pre-populates user submissions. The form collects basic user information (first name, last name, email, password), includes a checkbox for terms and conditions, and has a register button for form submission. The table displays previously submitted data with email links. 

### Key Features:
1. **Responsive Registration Form**: A well-structured registration form to capture user details.
2. **Pre-populated Submissions Table**: Displays previously submitted user data.
3. **Images Section**: Includes responsive images with different display styles.
4. **Responsive Buttons**: Buttons that show/hide based on screen size using Bootstrap's utility classes.

---

## Technologies Used:
- **HTML**: For structure and content.
- **CSS (Bootstrap 5.3)**: For styling and responsive design.
- **JavaScript (Bootstrap Bundle)**: For interactive elements such as the navbar toggle.

---

## How It Works

### HTML Structure

1. **Navigation Bar**:
    - Contains a simple navigation menu with links to Home, About, and Contact.
    - The navbar is responsive, collapsing into a hamburger menu on smaller screens.
    - Navbar is styled using Bootstrap's built-in classes.

2. **Registration Form**:
    - The form consists of:
        - **First Name** and **Last Name** fields.
        - **Email** and **Password** fields.
        - A checkbox to agree to the terms and conditions.
    - Each input field has the `required` attribute to ensure data is entered before submission.
    - The form is responsive and adapts to different screen sizes, with two columns for larger screens and a stacked form on smaller screens.
  
3. **Pre-populated Submissions Table**:
    - Displays a list of user submissions with their name and email.
    - The email column is clickable, allowing users to easily send an email by clicking the mailto link.

4. **Images Section**:
    - The first image is displayed as a standard image, while the second is shown in a circular frame using Bootstrap's `rounded-circle` class.
    - The images are made responsive using the `img-fluid` class, ensuring they adjust according to the screen size.

5. **Buttons Section**:
    - Two buttons: one is visible on all screen sizes, while the second is hidden on smaller screens (using Bootstrap's `d-none d-md-block` class).
    - The buttons are placed in a flex container to ensure proper alignment.

### Bootstrap Integration

This project uses **Bootstrap 5.3** to leverage the power of responsive grids, built-in styling, and utility classes. It ensures the layout adapts to various screen sizes, providing an optimal experience for mobile, tablet, and desktop users.

1. **Responsive Grid System**: 
    - The form layout utilizes Bootstrap's grid system (`row` and `col-md-6`) to create a two-column layout for medium and large screens. On smaller screens, the columns stack.
  
2. **Navbar**:
    - The `navbar-expand-lg` class makes the navbar responsive, transforming it into a collapsible menu on smaller screens.

3. **Buttons**:
    - The `btn` class is used to style buttons, and responsive visibility classes (`d-none`, `d-md-block`, etc.) are used to show or hide elements based on screen width.

---

## How to Use

1. **Clone the repository** or **Download the code** to your local machine.

2. **Directory Setup**:
    - Place the HTML file in your desired location.
    - Ensure the images are correctly placed in the `/images` directory.

3. **Opening the File**:
    - Simply open the `index.html` file in a web browser to view the registration form and table.
  
4. **Form Submission**:
    - The current implementation is static, and form submissions do not trigger any backend logic.
    - To make the form functional, you would need to add backend handling for form submission (e.g., PHP, Node.js, or a similar server-side technology).

---


## Conclusion

This project demonstrates how to build a simple, responsive registration page using HTML, CSS (Bootstrap), and JavaScript. The code is modular, easy to understand, and provides a foundation for extending features such as user authentication, data storage, and improved UI/UX elements.

For future improvements, you can integrate backend technologies, enhance the form functionality, and improve the overall styling of the application to make it more visually appealing and interactive. 

---

## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://github.com/Dub5991/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dustin-snellings-8385ba274/)
