# Dadole_StudentProfile

## 1. Project Description

This is my Student Profile application made using Apache Cordova, HTML,
and CSS. I updated my previous single-page profile into five pages:
Profile, About, Skills, Projects, and Contact.

The goal of the project is to present information about me, my skills,
the projects I have worked on, and ways to contact me. I also kept the
design simple, responsive, and easy to navigate.

## 2. Application Pages

-   **Profile (`index.html`)** --- The homepage. It shows my profile
    picture, complete name, short introduction, and a brief description
    about me.
-   **About (`about.html`)** --- Contains more information about me, my
    interests, education, organizations, and goals.
-   **Skills (`skills.html`)** --- Shows my skills and areas of
    expertise, including programming, web development, mobile
    development, UI/UX design, database management, and version control.
-   **Projects (`projects.html`)** --- Shows some of the projects I have
    worked on with short descriptions and project links when available.
-   **Contact (`contact.html`)** --- Contains my contact information and
    a contact form layout where visitors can enter their name, email,
    subject, and message.

## 3. Navigation

I used regular HTML links for the navigation. All five pages have the
same bottom navigation menu:

`Home / About / Skills / Projects / Contact`

The active page is highlighted in the navigation so it is easier to know
which page I am currently viewing. I also added a back link on the other
pages that leads back to the Profile page.

## 4. Responsive Design

The website uses a mobile-first layout and adjusts to different screen
sizes.

-   The layout is designed to work on mobile, tablet, and desktop
    screens.
-   The navigation stays at the bottom of the screen.
-   The skill cards adjust into columns on larger screens.
-   The content uses flexible widths to avoid unnecessary horizontal
    scrolling.
-   Spacing and text sizes adjust on larger screens to keep the pages
    readable.

## 5. UI/UX and Accessibility

I kept the design simple and consistent throughout the five pages.

-   **Consistency** --- The same red and blue color scheme, cards,
    spacing, and navigation are used across the pages.
-   **Visual hierarchy** --- Headings and important information use
    different sizes and weights to make the content easier to scan.
-   **Usability** --- The bottom navigation makes it easy to move
    between the five pages.
-   **Readability** --- The layout gives the content enough space and
    keeps paragraphs easy to read.
-   **Accessibility** --- The pages use semantic headings, descriptive
    image alt text, visible focus states, and a skip-to-content link.

## 6. How to Run

1.  Make sure Node.js and the Cordova CLI are installed.
2.  Open the project folder in the terminal.
3.  Add the Android platform if it is not already added:

``` text
cordova platform add android
```

4.  Make sure the website files are inside the `www` folder.
5.  Build the project:

``` text
cordova build android
```

6.  Run the application using an emulator or connected device:

``` text
cordova run android
```

7.  Check each page and make sure the navigation links work properly.

## 7. Application Screenshots

Screenshots of the following pages can be added here before submitting:

-   Profile
-   About
-   Skills
-   Projects
-   Contact
