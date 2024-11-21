# SunnyCo - Solar Panel Company Website

Welcome to the SunnyCo website, where we offer innovative solar energy solutions to power homes and businesses sustainably. This repository contains the HTML structure for the SunnyCo website, designed to showcase our products, services, career opportunities, and more.

## Table of Content

1. [Project Overview](#Project-Overview)
2. [Structure of the Website](#Structure-of-the-Website)
3. [Technologies Used](#Technologies-Used)
4. [Process Breakdown](#Process-Breakdown)
5. [Installation](#installation)
6. [Contributing](#contributing)
7. [Deployment](#Deployment)
   - [Set Up Hosting on Niagahoster](#1-set-up-hosting-on-niagahoster)
   - [Register Netlify](#2-register-netlify)
   - [Connect Your Repository in Github to Netlify](#3-connect-your-repository-in-github-to-netlify)
   - [Connect a Custom Domain](#4-connect-a-custom-domain-optional)
8. [License](#license)

## Project Overview

SunnyCo provides high-efficiency solar panels to customers looking to reduce their energy costs and environmental impact. Our website serves as an informational and service platform for those interested in adopting solar energy solutions. The site offers:

1. Information on solar energy products and services
2. Career opportunities at SunnyCo
3. Contact details for inquiries and support

## Structure of the Website

1. Hero Section
   - Features a bold introduction about the company's core values: simplicity, smart technology, and sustainability.
   - A call-to-action (CTA) button that guides users to get started with solar energy.
2. About Section
   - Describes the mission of SunnyCo, how we help clients transition to solar energy, and our dedication to offering reliable and affordable solutions.
   - Includes a carousel showcasing images related to solar energy projects.
3. Product Section
   - Displays the different solar energy solutions offered by SunnyCo, including:
   1. Ground Mounted Solar Power
   2. Industrial Rooftop Solar Power
   3. Residential Rooftop Solar Power
   4. Solar Power for Telecommunication
   5. Solar Street Lighting
   - Each product includes an image, brief description, and key benefits.
4. Career Section
   - Highlights available job openings at SunnyCo, such as Solar Energy Consultant, Installation Technician, Project Manager, Marketing & Communications Specialist, Sales Representative, and Customer Support Associate.
   - Provides a contact form for individuals to apply directly, with fields for name, email, phone number, and a message.
5. Contact Section
   - Displays SunnyCo’s address and contact information.
   - Provides links to our social media channels (email, Instagram, Twitter, LinkedIn).
     Includes an embedded Google Maps view of our office location.
6. Footer
   - Provides copyright information and a footer note.

## Technologies Used

1. HTML5: The backbone of the website structure.
2. CSS3: Used for styling the webpage and ensuring responsiveness.
3. Feather Icons: For sleek and modern icons throughout the site.
4. Google Fonts (Poppins): For consistent and easy-to-read typography.
5. JavaScript: Used for functionality like the hamburger menu toggle and form submission.

## Process Breakdown

1.  Step 1: Planning and Design<br>
    Identify key features: product information, career opportunities, and a call-to-action for prospective customers.
    Create wireframes and design the layout for user-friendly navigation.
2.  Step 2: Development (HTML Structure)<br>
    Develop the HTML structure to ensure proper layout for desktop and mobile viewing.
    Use semantic HTML5 tags for better SEO performance and accessibility.
3.  Step 3: Styling (CSS)<br>
    Design and apply styles to enhance the visual appeal of the website.
    Make use of a responsive design approach to ensure compatibility across various screen sizes.
    The site uses the Poppins font and integrates Feather icons for a modern, clean interface.
4.  Step 4: Content Creation<br>
    Write content for each section, ensuring clarity and concise information about solar products, services, and career options.
    Optimize content for SEO by using relevant keywords like "solar panels," "renewable energy," and "solar solutions.
5.  Step 5: Image and Media<br>
    Select and add high-quality images to illustrate the products and services.
    Add a carousel component for image sliders in the "About" section.
    Ensure all images are optimized for fast loading.
6.  Step 6: Testing<br>
    Test the website across different browsers and devices to ensure responsive design.
    Validate the contact form to ensure data is captured correctly when submitted.
    Verify all links, buttons, and CTAs are functional.
7.  Step 7: Launch<br>
    Upload the final code to a live server for public access.
    Promote the website to potential customers through online channels.

## Installation

1. Clone this repository to your local machine:

   ```
   git clone https://github.com/revou-fsse-oct24/milestone-1-anggreinipra.git
   ```

2. Open the index.html file in your browser to view the website locally.

3. Customize the content to fit your company’s branding (e.g., change the company name, logo, contact details).

4. Upload the files to your preferred hosting service for public access.

## Contribution

If you'd like to contribute to this project, feel free to fork the repository, make changes, and submit a pull request. Contributions are welcome, whether it's fixing a bug, adding new features, or improving documentation.

## Deployment

In this guide, we'll walk you through the process of migrating your website from **NiagaHoster** to **Netlify**. Whether you're transitioning from traditional shared hosting to a more modern, scalable solution, or simply looking to leverage Netlify’s powerful features like automated deployments and serverless hosting, this tutorial covers everything you need. We'll guide you through preparing your site, setting up hosting on NiagaHoster, deploying it to Netlify, and configuring DNS settings to ensure everything runs smoothly. Let's get started!

### 1. Set Up Hosting on Niagahoster

To deploy your website to NiagaHoster, you need to set up a hosting account and access cPanel.

- Log in to your Niagahoster account.
- Go to cPanel.
- Make sure you have a domain or subdomain ready to host your website.If you haven't set up a domain yet, you can use a temporary subdomain that NiagaHoster provides. If you need a new domain or subdomain; in cPanel, go to the Domains section ther add a new domain or subdomain to associate with your website files.

### 2. Register Netlify

- Go to Netlify by **visit : https://www.netlify.com**
- Click **"Sign Up"** on the top of the right corner.
- Choose GitHub Option: Select the **"Sign up with GitHub"** option. You'll be redirected to GitHub’s authentication page.
- **Authorize Netlify**: GitHub will ask you to authorize Netlify to access your GitHub account. Click Authorize to allow the connection.
- **Grant Permissions**: Choose whether to grant Netlify access to all your repositories or only specific ones, depending on your preferences.

### 3. Connect Your Repository in Github to Netlify

- Select the repository you want to deploy.
- Click **Deploy Site**. Netlify will pull the files from your GitHub repository, build the site if needed, and deploy it.
- After deployment, Netlify will provide a preview URL **(e.g., https://your-site-name.netlify.app/)**.

### 4. Connect a Custom Domain (Optional)

Once your site is live on Netlify, you can connect your own custom domain by update DNS settings.

- In your Netlify dashboard, go to your site’s settings then set up a custom domain.

  <img src="./asset/img/01. setup custom domain.png" alt="setup custom domain" width="350" />

- Add custom domain

  <img src="./asset/img/02. add custom domain.png" alt="Add custom domain" width="350" />

- Add domain alias

   <img src="./asset/img/03. add domain alias.png" alt="Add domain alias" width="350" />

- Verify set up Netlify to DNS

   <img src="./asset/img/04. Verify set up Netlify to DNS.png" alt=" Verify set up Netlify to DNS" width="350" />

- Nameserver changed

  <img src="./asset/img/06. Nameserver changed.png" alt="Nameserver changed" width="350" />

- Awaiting Netlify DNS<br>Netlify is waiting for DNS settings to be updated or propagated before your website can go live on your custom domain. This process may take up to 24 hours or less.<br>

  <img src="./asset/img/07. Awaiting Netlify DNS.png" alt="Awaiting Netlify DNS" width="350" />

- Check the website regularly

   <img src="./asset/img/08. Check the website regularly.png" alt="Check the website regularly" width="350" />

- DNS Verified<br>DNS changes have been successfully propagated across the internet, and Netlify can now properly associate your custom domain with your website hosted on their platform.

  <img src="./asset/img/09. DNS verified.png" alt="DNS verified" width="350" />

- Your Website is Ready!<br>Now you can visit the website by follow the link (e.g., https://anggreinipra.com/)

   <img src="./asset/img/10. Go-live.png" alt="Go Live" width="350" />

## License

_Used for submission Assigment Project Milestone 2, RevoU FSSE Program._

---

© 2024 SunnyCo. All Rights Reserved.
Created by [@anggreinipra](https://www.linkedin.com/in/anggreinipra)
