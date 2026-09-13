<img width="1200" height="3830" alt="4f852565-de89-41f3-b18e-ad88f83a5a98" src="https://github.com/user-attachments/assets/abc7c4de-4899-4ddb-8b6a-30c809f4e680" /># Dadole_StudentProfile

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

-   Profile
<img width="1200" height="2685" alt="4bde107b-9850-47c7-a487-f741abfc1144" src="https://github.com/user-attachments/assets/e27137c3-fc18-4ab9-a916-850bd0f27610" />

-   About
<img width="1122" height="4095" alt="2449ddb3-f91c-43c4-8ea8-542b782657fb" src="https://github.com/user-attachments/assets/0aa0d009-4e45-4530-b01c-e9459afb4100" />
  
-   Skills
<img width="794" height="4094" alt="43ef8900-88ed-46f0-949e-5cc098179acb" src="https://github.com/user-attachments/assets/7509ea0e-1a4c-4f3c-9bd6-d52214156399" />

-   Projects
<img width="900" height="4099" alt="1e79dc7d-9c01-47b1-9c71-24eff393eb56" src="https://github.com/user-attachments/assets/5a6d8669-4fb9-49bb-956f-c585e85822a2" />

-   Contact
<img width="1200" height="3830" alt="4f852565-de89-41f3-b18e-ad88f83a5a98" src="https://github.com/user-attachments/assets/1cf67554-749b-4ae5-b5d6-9b0c7b57135d" />

