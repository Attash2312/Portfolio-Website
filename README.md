# Mobile Portfolio (Non-Responsive)

This is a **mobile-specific** version of my personal portfolio website, built to provide an optimal experience for mobile devices with a screen width of **375px**. This version focuses solely on delivering a polished user interface for mobile devices and does not include responsiveness for larger screens like tablets or desktops.

## Table of Contents

- [Mobile Portfolio (Non-Responsive)](#mobile-portfolio-non-responsive)
  - [Table of Contents](#table-of-contents)
  - [Features](#features)
  - [Technologies Used](#technologies-used)
  - [Setup](#setup)
    - [Prerequisites](#prerequisites)
    - [Steps](#steps)
  - [File Structure](#file-structure)
  - [Notes](#notes)
  - [License](#license)

## Features

- **Mobile-First Design**: Specifically designed for mobile devices, with a width of 375px.
- **Project Display**: Projects are showcased with images, descriptions, and the technologies used.
- **About Me Section**: Includes a brief introduction and a biography about myself as a software developer.
- **Contact Form**: Allows visitors to easily reach out via a simple form.
- **Social Media Links**: Links to my social media profiles for networking and connection.

## Technologies Used

- **HTML5**: For structuring the content.
- **CSS3**: For styling the page and maintaining the mobile layout.
- **JavaScript (Optional)**: Used to add interactivity where necessary.

## Setup

### Prerequisites

- A modern web browser like Google Chrome, Firefox, or Safari that supports HTML5 and CSS3.

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/mobile-portfolio.git
   ```

2. Navigate to the project directory:

   ```bash
   cd mobile-portfolio
   ```

3. Open the `index.html` file in your mobile browser or use a mobile emulator:

   ```bash
   open index.html
   ```

4. (Optional) Serve it locally using a simple HTTP server:

   ```bash
   npx http-server .
   ```

## File Structure

```
mobile-portfolio/
│
├── images/                  # All image assets used in the portfolio
│   ├── menu-icon.png
│   ├── pr1.png
│   ├── pr2.png
│   ├── social-media-icons.png
│   └── ...
│
├── style.css                # Main CSS file with mobile-specific styles
├── index.html               # Main HTML file for the portfolio
└── README.md                # This README file
```

## Notes

- This portfolio is intended **only for mobile devices** with a 375px width. If opened on larger screens, it will not display correctly without adjustments.
- A fully responsive version for other devices can be built by extending the current CSS and adding media queries.

## License

This project is open-source and is licensed under the [MIT License](https://opensource.org/licenses/MIT).