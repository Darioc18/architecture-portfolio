# Portfolio Project 1 - HTML/CSS Essentials

## DC Architecture Portfolio

![Responsive Mockup](assets/images/readme-files/multi-device.jpg)

## Live Site

[Dario Covella - Architecture Portfolio](https://darioc18.github.io/architecture-portfolio/architecture.html)

## Repository

[https://github.com/Darioc18/architecture-portfolio](https://github.com/Darioc18/architecture-portfolio)

## Brief

The goal of this project is to create a portfolio-style website showcasing the projects I have worked on as an architect. My main aim is to demonstrate my competence in HTML and CSS by developing a visually appealing and user-friendly static front-end application.

It is important to note that this portfolio is not intended for professional use; rather, it serves as a showcase to highlight my skills and competence with CSS and HTML.

## Goal

The primary goal of creating this website is to showcase my architecture portfolio, featuring the projects I have worked on. By presenting my professional accomplishments and showcasing my design skills, I aim to:

- Provide potential clients, employers, and collaborators with a comprehensive overview of my architectural expertise;
- Include information about me, allowing visitors to gain insights into my background, qualifications, and design philosophy;
- Include a contact section to enable interested parties to reach out to me directly, providing a platform for communication and potential opportunities.

Overall, this website would serve as a dynamic platform to exhibit personal architectural achievements, establish a professional online presence, and foster connections within the industry.

## User Experience (UX)

### As a Target User, I want

- To easily find information about the architect's experience, qualifications, and relevant certifications to assess their expertise and credibility;
- The website to showcase a diverse range of project types (residential, commercial, etc.) to gauge the architect's versatility and adaptability;
- To highlight any collaborative efforts or notable partnerships the architect has engaged in, demonstrating their ability to work effectively with a team;
- The website to provide a gallery or portfolio section showcasing high-quality images that highlight the architect's attention to detail and craftsmanship;
- The website to offer a way to easily request additional information or schedule a meeting with the architect to discuss specific project needs.

### As a First-Time User, I want

- To easily navigate the website to understand its purpose and content quickly;
- To be able to view the site on wide range of devices;
- To explore the projects in the architecture portfolio and view detailed information about each project;
- To learn more about the architect by accessing their profile or bio section;
- To have a clear understanding of how to contact the architect through the website's contact section;
- The website to provide a visually appealing and intuitive interface that encourages further exploration.

### As a Returning User, I want

- The website to provide regular updates on new projects or achievements by the architect.
- To have a seamless experience when contacting the architect through the website, ensuring my message reaches them successfully.

## Design

In designing this website, my intention was to keep the colors and layout minimalistic. This approach allows the projects showcased in the portfolio to take center stage, each having its unique style and color palette. By adopting a simple design, the goal is to create a visual environment where the projects can truly stand out and captivate the viewer's attention.

### Wireframes

Displayed below are a set of wireframes illustrating the various pages of the portfolio. The elements in red indicate some specific features that I intend to incorporate in future revisions.

![Wireframes](assets/images/readme-files/wireframes.jpg)

### Colours

In line with the principle mentioned above, I aimed to adhere to a minimalistic color palette, consisting of black, white, and two distinct shades of grey. This deliberate choice allows for a clean and understated aesthetic, ensuring that the focus remains on the projects themselves while maintaining a cohesive and visually appealing design. I created a visual palette by using [coolors.co](https://coolors.co).

![Color palette](assets/images/readme-files/color-palette.jpg)

## Typography

In order to maintain a clean aesthetic, I opted to utilize a single font imported from [Google Fonts](https://fonts.google.com/): Raleway. This font choice complements the overall design by providing a clean and elegant typography style that enhances the readability and visual consistency of the website.
was used to import Raleway used throughout the website

## Imagery

As the central focus of the website, Dario's personal portfolio will prominently feature imagery. To optimize the loading times, many of the images, which are typically large files, will be compressed. By using a compression tool [compressjpeg.com](https://compressjpeg.com/), the images will be resized and optimized without compromising their quality.

For the home page, I selected a visually pleasing image with neutral and clear colors to align with the minimalistic character of the entire website. The arrangement of the images will be thoughtfully organized to showcase a variety of projects effectively, allowing visitors to explore and appreciate Dario's diverse body of work.

## Features

### Existing Features

- #### Home Page

  - The home page of the website follows a minimalistic design, featuring only a name and a hero image. Upon clicking the name, a smooth transition occurs where the navigation bar appears, and the hero image gracefully disappears. This transition creates a seamless user experience, allowing the navigation bar to show up.
  - Once the navigation bar is visible, a white canvas is revealed, providing a clean backdrop for the display of projects. By clicking on the _architecture_ option, the projects related to architecture will be showcased on this white canvas. This approach ensures a focused and uncluttered presentation, allowing visitors to explore your architectural projects without any distractions.

![home age transition](assets/images/readme-files/homepage-transition.gif)

- #### Navigation bar

  - Featured on all three pages, the full responsive navigation bar includes links to the Gallery (_architecture_), _info_, _contact_, and _home_ page and is identical in each page to allow for easy navigation.
  - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button;
  - For screens larger than 920px, the navigation bar is designed to have no solid background. This intentional choice allows the images to scroll freely without being obstructed by a solid header.

    ![navbar transparent background](assets/images/readme-files/navbar-transparent.gif)

  - On screens smaller than 920px, a white background is applied to the navigation bar. This adjustment is made to prevent any clashes between the scrolling images and the navigation bar items. However, on the home page, the navigation bar is intentionally designed withn no solid background. This decision ensures that the hero image can span the entire screen size, creating a visually impactful impression and allowing the image to be fully visible even on smaller screens.

    ![navbar solid background](assets/images/readme-files/navbar-solid.gif)

- #### Architecture Gallery

  - The _architecture_ page serves as a platform for users to explore the designer's work, which is presented through a series of boxes. Initially no text is displayed maintaining a clean appearance. However, upon hovering over each box, the name of the project elegantly fades in, providing additional information and context for the user. This interactive feature enhances the user experience by enabling them to discover the project names and engage more deeply with the designer's portfolio.

    ![architecture page](assets/images/readme-files/architecture-page.jpg)

  - On smaller screens, the website's responsive design ensures optimal user experience by adapting the layout of the _architecture_ page. Specifically, the boxes containing project information are designed to stack on top of each other, creating a vertical arrangement. This stacking arrangement allows for easy scrolling and improved readability on smaller screens, ensuring that users can comfortably explore the projects even with limited screen space. By adapting to different screen sizes, the responsive design provides a seamless and user-friendly browsing experience across a range of devices.
  - On screens smaller than 920px, a white background is applied to the navigation bar.

    ![architecture page mobile](assets/images/readme-files/architecture-page-mobile.jpg)

- #### Info Page

  - The info page provides a brief introduction of myself, showcasing my achievements and my experiences and showing a picture of me.

    ![info page](assets/images/readme-files/info-page.jpg)

  - The info page is fully responsive, with the text and picture stacking on smaller screens for optimal viewing.

    ![info page mobile](assets/images/readme-files/info-page-mobile.jpg)

- ### Contact Page

  - The contact page provides users with the ability to easily get in touch with the artist for various purposes, such as project inquiries or sharing opinions about previous work.
  - All fields in the contact form are set as required. This means that the form cannot be submitted unless all necessary information, including names, message and valid email addresses, are provided.

    ![contact page](assets/images/readme-files/contact-page.jpg)

### Features left to implement

- Expand the _architecture_ page: add more projects to showcase a wider range of the designer's work.
- Individual project pages with navigation arrows: implement the feature depicted in the [Wireframes](#wireframes), allowing users to navigate between individual project pages using arrows. These arrows should be placed in a way that allows users to easily move to the next or previous project. Additionally, consider including a small preview of the upcoming or previous project above the arrows, providing a glimpse of what's to come.
