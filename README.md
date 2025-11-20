<p align="center">
 <img src="assets/readme/read-me-banner.png" alt="GYMXP Read Me Banner" width="100%">
</p>

# GYMXP — Gamified Fitness
## Table of Contents
- [Overview](#overview)
- [Purpose](#purpose)
- [Target Audience](#target-audience)
- [UX / UI Rationale](#ux--ui-rationale)
- [Page Breakdown](#page-breakdown)
- [Accessibility Features](#accessibility-features)
- [Responsive Design](#responsive-design)
- [External Code Attribution](#external-code-attribution)
- [Testing](#testing)
- [Bugs and Fixes](#bugs-and-fixes)
- [Version Control](#version-control)
- [Deployment](#deployment)
- [Future Improvements](#future-improvements)
- [Screenshots](#screenshots)
- [References](#references)

---

## Overview
GYMXP is a gamified fitness platform designed as a user-centered web application. It transforms traditional workouts into an engaging, interactive experience using XP progression, AI-powered virtual trainers, aura effects, achievements, and motivational behaviour-design principles.

The project demonstrates strong UX/UI decision-making, accessibility-focused design, optimised front-end performance, and a structured development workflow. By merging fitness with game-style progression systems, GYMXP aims to increase user motivation, consistency, and long-term engagement through clear goals, instant feedback, and visual reward mechanics.

Inspired by successful behaviour-driven apps like Duolingo, GYMXP targets a niche gap in the ever growing fitness market aswell as utilising the gamification trend by combining core gamification elements, AI, and gym-based training in a modern, aesthetically focused interface. The website acts a pre-launch platform and showcases the app concept through cinematic visuals, interactive avatars, and clear feature explanations providing users with a compelling preview of the full GYMXP experience. This experience, in turn, has the real prospect to attract users and potential investors interested in bringing the product to the market.
## Purpose
The purpose of this website is to clearly introduce the concept of GYMXP in a way that is simple, visual and easy for users to understand. The site acts as a gateway to information that showcases the key features of the concept, such as XP progression, the AI trainers (which are the key USP), and the overall design and theme of the app. Each page has been designed to visually engage visitors in a style similar to how professional companies and studios present their concepts. The images, videos and text have been arranged in a way that is easy for users to follow and understand without overwhelming them with too much information at once.

From a development perspective, the website is designed to demonstrate my ability to build a responsive, accessible and user‑centred front‑end project. It highlights the use of clean HTML structure, optimised images for efficient performance, Bootstrap for layout, and a consistent visual UI that fits the vision of the project while meeting best practices and accessibility standards. The main purpose of this project, within the scope of development, is to showcase my ability to design and implement a fully responsive interface using HTML5, CSS and Bootstrap.
## Target Audience
The target audience for this website are users who are interested in fitness, self‑improvement and gamified experiences. The typical age range for this demographic is between 15–35. The GYMXP website is mainly aimed at people who struggle with motivation, enjoy strong visuals and visual progress, and prefer more interactive and rewarding modes of training. This includes beginners who want structure, guidance and discipline, as well as more experienced gym users who want to track their progress in a more engaging way than traditional fitness apps currently offer.

The project is also aimed at users who respond well to visual stimuli and character driven design. The three core AI coaches—Blaze, Zaya and Shadow appeal to users who enjoy personality, narrative and digital guidance. The XP system further supports this by mirroring the type of progress users are familiar with from gaming environments. The website presents all of this information in a clear, fun and visually engaging way, with the aim of encouraging users to join the ‘Waiting List’ for early access.

Additionally, the website helps communicate the GYMXP concept to stakeholders and potential developers by clearly presenting the visuals, layout and key features of the idea.
## UX / UI Rationale
The design of the GYMXP website is based on a user‑centric approach that focuses on clarity, visual engagement and simplicity. These three core aspects guided the project from the very beginning with the aim of providing users with a user‑friendly, engaging and easy‑to‑navigate experience. The layout across the entire website was intentionally kept clean, with strong spacing, clear headings and well-structured sections to ensure users can move through the site without confusion or information overload.

Dark backgrounds combined with bright accents and coloured text were chosen to complement and match the energetic, anime‑inspired theme of the project. All of these visuals were implemented while still maintaining readability and accessibility. The use of large visuals, bold typography and subtle animated imagery reflects the core concept behind the website and the product itself, helping to emphasise personality and aesthetic identity.
<p align="center">
  <img src="assets/readme/anime-graphic.png" width="40%" alt="example of banner in the AI trainers page to showcase visual and anime inspired identity ">
</p>
<p align="center"><em>Visual in AI Trainers page showcasing the visual and anime‑inspired brand identity and how it it fits with the theme of the page and navigation.</em></p>

Each page of the website has been designed to highlight one idea at a time. For example, the AI Trainers page focuses on showcasing the three coaches, the Waiting List page provides a clear and simple form for users to register interest, and the About page uses a video supported by text to explain the core app concept. This approach was deliberately chosen to simplify navigation and prevent cognitive overload, allowing users to absorb information at their own pace. The flow of media and text avoids clutter and ensures the overall experience remains accessible and easy to use.

The targeted demographic (ages 15–35) was also considered throughout the design process. Users in this age group typically prefer fast, visual and straightforward interfaces, so the structure, visuals and pacing of information delivery were designed to match these expectations. This design caters specifically to those users while still being friendly for others. Users also tend to skim through websites rather than fully read all the content, so the UX/UI was created with this behaviour in mind—keeping it simple yet aesthetically pleasing, with clear headers and sections laid out in a way that avoids clutter.
<table>
  <tr>
    <td align="center">
      <img src="assets/readme/header.png" width="80%" alt="screenshot of header <h1> on trainers page">
      <br>
      <em>Example of header</em>
    </td>
    <td align="center">
      <img src="assets/readme/spacing.png" width="80%" alt="image showing spacing of <h> elements and <p> element.">
      <br>
      <em>Example of spacing between <H> and <p> elements</em>
    </td>
  </tr>
</table>

The navigation bar was intentionally kept clean and thin to provide more of an aesthetic and modern sleek look. This was placed at the top of each page as most websites improving usability. The GYMXP logo also doubles as a home button which follows best practice and improves flow for the user. On mobile screens, the navigation collapses into Bootstrap’s hamburger menu. This keeps the layout clean and prevents the navigation links from overcrowding the screen. By collapsing the links into a menu, it avoids clutter and allows the logo and design elements to remain visually balanced. This mobile adaptive behaviour ensures the navigation is kept simple and easy to use.
<table>
  <tr>
    <td align="center">
      <img src="assets/readme/desktop-nav.png" width="80%" alt="image of desktop navigation">
      <br>
      <em>Desktop navigation bar</em>
    </td>
    <td align="center">
      <img src="assets/readme/mobile-nav.jpg" width="80%" alt="image of mobile hamburger navigation">
      <br>
      <em>Mobile hamburger navigation bar</em>
    </td>
  </tr>
</table>
The use of Bootstrap classes was chosen to handle majority of the spacing and layout. this was achieved by implementing the Bootstrap responsive grid system to ensure a consistent and clean layout. It kept spacing and layout balanced across all pages and prevented elements from appearing unbalanced or shifted. The Bootstrap framework also allowed the website to scale appropriately on mobile, desktop and tablet without the need for extra code. Using Bootstrap allowed faster development without compromising on a high design standard. Ultimately, Bootstrap helped achieve a polished and aesthetic design that aligned with the core concepts of clarity, visual engagement and simplicity. In addition to Bootstrap's grid system, custom CSS media queries were used to adjust spacing, typography and image sizing. This ensured the layout scaled appropriately on different types of devices thus demonstrating the use of an advanced technique.
<table>
  <tr>
    <td align="center">
      <img src="assets/readme/spacing-two.png" width="80%" alt="example of grid system for text">
      <br>
      <em>Bootstrap grid system example for text</em>
    </td>
    <td align="center">
      <img src="assets/readme/grid-example.png" width="70%" alt="example of grid system for images">
      <br>
      <em>Bootstrap grid system example for images </em>
    </td>
  </tr>
</table>

The design implements three well known established UX laws to support clear interaction.Hick’s Law was implemented as the the use of simple layouts and minimal options per page, which i have applied, reduces user decision time in theory. Fitts’s Law has also been applied through the use of large and easy to tap buttons and links especially with the hamburger menu on mobile devices. Lastly Cognitive Load was implemented through the strategic design of breaking information into smaller sections with spacing and a clear hierarchy, preventing cognitive overload. With all this, no UX rules were deliberately broken and my design choice and features ensures a smooth user experience.

### Wireframe
Below are wireframe diagrams used to guide the design and layout of the website.
  <table> 
    <tr>
     <td align="center">
       <img src="assets/readme/wireframe.png" width="80%" alt="wireframe for home and trainer page">
       <br>
       <em>Wireframe diagram for Home and Trainers pages</em>
     </td>
     <td align="center">
       <img src="assets/readme/Wireframe-2.png" width="80%" alt="wireframe for about and waitinglist page">
      <br>
       <em>Wireframe diagram for About and Waiting List pages</em>
     </td>
  </table>

## Page Breakdown

### Home Page
The Home Page serves its purpose as the landing page and main introduction to the GYMXP Concept. It is designed to communicate the core idea of the platform. The hero section of the home page features a cinematic fullscreen background taking up the width of the page, with a bold headliner, subheader and a charcter animation to the right. The background image has had a fade applied to it from the bottom so it blends in well with the complimenting black background. This dynamic design was intended to set the visual identity and tone for the rest of the project.

The structure of text was intentionally designed to allow visitors to understand the purpose of the app quickly. The brand message ("Transform your workout into XP") is reinforced visually through the use of strong and bold typography and text underneath. Two buttons ('Register Interest' and 'LEARN MORE') are positioned directly below the hero text with sufficient spacing to maintain clarity. This spacing creates a more balanced, aesthetic layout and prevents the text and buttons from appearing cluttered, while still allowing the background image to remain clearly visible and unobstructed. The buttons also follow Fitts’s Law by using high-contrast colours, large tap-friendly sizing and clear labelling to improve usability and accessibility.

Below the her section, three key features are displayed in bootstrap three column layout ('Track your XP', 'Unlock Achievments', Level Up On Your Training'). This design uses minimal text, clear spacing and short and concise desciptions to prevent cognotive overload, helping the visitor to quickly understand the three core aspects of the product. Each feature follows a consistent design, spacing, maintaining readability across various different screen sizes.

A preview of the three AI trainers is included below the features section. This Avatar section introduces three familiar faces users will see across the site - Blaze, Zaya and Shadow. These are the main characters of the app/product. This section is intended to highlight the personality driven aspect of the GYMXP concept. The layout, once again borrowed from Bootstrap, centres the avatars visually and uses spacing thus helping the section feel connected and consistent with the rest of the page and grid system.

To enhance user experience, the Home page makes the subtle use of  UI enhancements such as fade-in animations on text, images and videos as well as smooth hover interactions on the AI avatar previews. This includes  a zoom in effect as well as a character attributed glow to each avatar image to highlight and support the visual and character driven aesthetic of the GYMXP concept.

The Home Page layout adopted the use of Bootstrap's responsive grid system, allowing it smoothly adapt to different screen dimensions. For example, the hero section's two column layout transforms to a single column on mobile and this ensures the hero text and video remain readable. The three column features section as well as the AI avatar previews stack on top of each other on mobile devices, preventing clutter and maintaining readability and clarity. Utilities such as img-fluid, mx-auto and text-md-start were used to maintain spacing and alignment that is consistent no matter the device.

Accessibility was implemented in the design of the Home Page through the use of Alt text on images, ARIA labels on the navigation bar and the use of high contrast buttons that meet expected readability standards. Buttons use high contrast and large sizing to support both mouse and touch input.

### About Page
### AI Trainers Page
### Waiting List Page

## Accessibility Features

## Responsive Design

## External Code Attribution

## Testing

## Bugs and Fixes

## Version Control

## Deployment

## Future Improvements

## Screenshots

## References