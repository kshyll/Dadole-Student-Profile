## Dadole Student Profile | Activity 3

1. Project Description
The product is in partial fulfillment of my output for ITCC 41 - Mobile Development Activity 3. This project is a student profile using apache cordova containing my personal, education, and technical information. The current application was improved with the instructions provided from activity 3 applying responsive design and UI/UX principles from module 4.

3. Application Structure
The application is organized into the following main sections:
Header - displaying profile picture, complete name, subtitle, current learning status
Navigation Menu - Provides links to about and skills section of the application
About Section - information about my education, interests, organizations, career goals, and personal interests
Skills Section - technical skills with short description
Footer - copyright information, name, and current year level

3. Responsive Design
My student profile uses responsive design techniques so that the layout will adjust accordingly to any device such as tablet, desktop, and smartphone.

The following Module 4 responsive techniques were applied:

- Flexible layouts using Flexbox and CSS Grid.
- Media queries to adjust the layout at different screen sizes.
- Responsive images using flexible width and height.
- Flexible typography using responsive font sizing.
- Mobile-first layout where content is arranged vertically on smaller screens.
- Two-column layout for larger desktop screens.
- Small-screen adjustments to improve spacing and readability on smaller devices.
- Responsive navigation with large enough links for touch interaction.

4. UI/UX Principles Applied
Principles I applied in Module 4 includes:
- **Responsive Layout**: The layout adjusts from a single-column design on mobile devices to a two-column design on larger screens.
- **Mobile-Friendly Spacing**: Proper spacing and padding are used to make the content easier to read and interact with on smaller screens.
- **Appropriate Typography**: Different font sizes and font weights are used to make headings and text clear and easy to read.
- **Clear Visual Hierarchy**: Different sizes, weights, and spacing help users easily identify the most important information.
- **Usable Controls**: Navigation links and clickable elements have enough size and spacing for easier interaction.
- **Basic Accessibility**: Semantic HTML, alternative text, organized headings, focus indicators, and a Skip to Main Content link are included. Has a clear skip to main content compared to activity 2.
- **Consistent Design**: Consistent colors that does not overpower the content, typography, spacing, borders, and card styles are used throughout the application.

5. Navigation
The about and skills navigation links allows users to move directly to corresponding sections.

The links use HTML anchor links (because it is in the same page only) with section IDs:
  - #about: about section
  - #skills: skills section

6. How to Run
- Open Terminal
- Navigate to the project folder: cd "path/to/DadoleStudentProfile"
- Install the project dependencies: npm install
- Add the Android platform if it is not already installed: cordova platform add android
- Build the Android application: cordova build android
- Start an Android emulator
- Run the application: cordova emulate android

8. Application Screenshots
Your README must include screenshots demonstrating all three layouts:

#Desktop
<img width="1028" height="699" alt="Screenshot 2026-09-02 at 11 10 07 PM" src="https://github.com/user-attachments/assets/a9482a71-1643-414f-953e-14754ebc16f4" />

#Tablet
<img width="1028" height="699" alt="Screenshot 2026-09-02 at 11 13 04 PM" src="https://github.com/user-attachments/assets/d63a197d-e1fc-421a-8769-9a3893af47fd" />
<img width="1028" height="699" alt="Screenshot 2026-09-02 at 11 13 29 PM" src="https://github.com/user-attachments/assets/02e33c88-423e-4567-a9c8-a79c18c83a4d" />


#Mobile
<img width="947" height="506" alt="Screenshot 2026-09-02 at 11 00 00 PM" src="https://github.com/user-attachments/assets/4eabdfaa-8d7d-4333-a862-64e3e0405b73" />
<img width="947" height="506" alt="Screenshot 2026-09-02 at 11 00 12 PM" src="https://github.com/user-attachments/assets/a84961bb-3268-4a95-a355-ace416f53086" />
<img width="478" height="890" alt="Screenshot 2026-09-02 at 10 59 17 PM" src="https://github.com/user-attachments/assets/8e78b740-2c87-4621-8daf-4a9a6145bc0d" />

