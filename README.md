# Responsive Sign In and Sign Up Landing Page

This project involves the creation of a responsive landing page with sign-in and sign-up functionalities. The design focuses on providing a seamless user experience across different devices, leveraging Tailwind CSS for styling and minimal custom JavaScript for handling user interactions. The landing page is tailored for a hypothetical fashion-related website named "JannahWear."

## Features

- Responsive Design: The layout is fully responsive, adapting to various screen sizes from small mobile devices (320px width) to larger screens (900px and above).
- Dynamic Page Switching: The page includes two main sections: a sign-in (login) page and a sign-up (registration) page. Users can switch between these sections dynamically without a page reload.
- Custom Fonts and Icons: The project uses custom Google Fonts (Inter and Anek Devanagari) and icons from Material Icons and Font Awesome to enhance the visual appeal.
- Tailwind CSS Configuration: The project utilizes a customized Tailwind CSS configuration to extend the default styles with additional font families, shadows, colors, and screen breakpoints.

## Files and Structures

- HTML (index.html): The primary structure of the landing page, including the sign-in and sign-up forms, as well as placeholders for images and text content.
- Tailwind CSS: Tailwind CSS is integrated via a CDN, with custom configurations defined within a script block in the HTML head.
- Custom JavaScript: Basic JavaScript is included to handle the visibility of the sign-in and sign-up forms, ensuring that only one is visible at a time based on user interaction.

## Key Sections

- Sign In Page
  - Contains a welcoming message and a form for users to enter their email and password.
  - Includes a button to switch to the sign-up form if the user does not have an account.
  - Features a responsive design with hidden elements on smaller screens and visible elements on medium to larger screens.
- Sign Up Page
  - Includes a form for new users to register with their email, password, and confirmation password fields.
  - Provides links to switch back to the login form if the user already has an account.
  - Contains a visually engaging background and introductory text on medium to large screens.

## Usage Instructions

<ol>
  <li> Initial Setup: </li>
    <ul>
      <li> Open index.html in a web browser to view the landing page.
      <li> The login page will be displayed by default when the page loads.
    </ul>
  <li> Switching Pages: </li>
    <ul>
      <li> Use the "Register" link on the login page to switch to the sign-up form.
      <li> Use the "Login" link on the sign-up page to return to the login form.
    </ul>
  <li> Customization: </li>
    <ul>
      <li> Images: Replace the placeholder image (muslimah.png) with your own.
      <li> Content: Update the text within the login and registration sections as needed.
      <li> Styling: Modify the Tailwind CSS configuration or add custom styles in the  block for further customization.
    </ul>
</ol>

## Dependencies

- Tailwind CSS: Integrated via CDN for utility-first CSS styling.
- Google Fonts: Inter and Anek Devanagari for typography.
- Icons: Material Icons and Font Awesome for user interface icons.

## Contributing

Feel free to fork this repository and submit pull requests if you have suggestions for improvement or want to contribute additional features.
