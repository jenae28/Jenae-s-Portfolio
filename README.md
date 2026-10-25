Portfolio Website Instructions

This Project

This is my personal portfolio website using HTML and CSS.

The website has:
- Home
- About Me
- Technical Skills
- Education and Work Experience
- Projects
- Contact Me
- Footer

HTML is used to add the content to the website.

CSS is used to add the colors, stlye, fonts, spacing, and layout.

1. How to Create the Files in VS Code

 Step 1: Create a Folder

1. Go to your Desktop or Documents.
2. Right-click an empty space.
3. Select New, Folder.
4. Name the folder
5. Press Enter.

This folder will have your code.

Step 2: Open Visual Studio Code

1. Open Visual Studio Code.
2. Click File at the top of the screen.
3. Select Open Folder.
4. Find the `my-portfolio` folder.
5. Select Folder.

Your folder should show on the left side of the screen.

Step 3: Create the HTML File

1. Find the panel on the left, near folder.
2. Click New File.
3. Type `index.html`. exactly like this

The HTML file is website's words, pictures, links, and sections.

Step 4: Create the CSS File

1. Again, Click the New File icon
2. Type `style.css`. Eaxctly

The CSS file controls how your website looks and style.

Step 5: Connect HTML to CSS

1. Open `index.html`.
2. Find the head section near the top.
3. Add the stylesheet link inside the head section.

The line should look like this:

    <link rel="stylesheet" href="style.css">

This tells the browser to use the styles from `style.css`.

Step 6: Add Your Profile Picture

1. Choose a picture you want to use.
2. Rename it `profile.jpg` if it is a JPG image.
3. Copy it into your `my-portfolio` folder.
4. Make sure your HTML image tag uses the correct filename.

Example:

    <img src="profile.jpg" alt="My profile picture">

Your project folder should contain:

    my-portfolio/  
        index.html
        style.css
        profile.jpg
  README.md

The README.md file contains these instructions.

Step 7: Save Files

Press Ctrl + S to save

2. How to Open the Website in a Browser

There are two ways to open your website.

1. Open the HTML File

Live Server helps you preview your website.

1. Open VS Code.
2. Click the Extensions icon on the left. It looks like a cube
3. Search for Live Server.
4. Find Live Server by Ritwick Dey.
5. Install.
6. Open `index.html`.
7. Right-click inside the file.
8. Select Open with Live Server.
~Your website will then open in browser.

3. How to Replace Placeholder Information

Change Name

1. Open `index.html`.
2. Press Ctrl + F.
3. Search for `NAME`.
4. Replace the name with your preferred name..

Change Your Profile Picture

1. Choose a new picture.
2. Place it in your `my-portfolio` folder.
4. Find the image tag in `index.html`.
5. Update the filename after src tag.

Change Your Skills

1. Open `index.html`.
2. Press Ctrl + F.
3. Search for `skills-container`.
4. Find the skill cards.
5. Change the skill names and descriptions.

Change Your Education

1. look for `education-section`.
2. Find the education cards.
3. Replace the information.

Exmaple:
- School or institution name
- Degree or certification
- Graduation date or expected graduation date

Example:

    <h3>Software Engineering</h3>
    <h4>Your College Name</h4>
    <p>Expected Graduation: May 2028</p>

Work Experience

1. Find the work experience card.
2. Replace the example workplace name.
3. Add job title.
4. Add employment dates.
5. Add your responsibilities and achievements.

Use accurate information about your experience.

Change Your Projects

1. Search for `projects-container`.
2. Find the project cards.
3. Change the project titles.
4. Change the descriptions.
5. Update the GitHub links.

ChangeSocial Media Links

Find the Contact and Footer sections.

Replace the example links with your own.

Email example:

    <a href="mailto:youremail@example.com">
        Email Me
    </a>

The mailto link opens an email application.


4. CSS Color

CSS controls the colors used on your website.
A CSS variable is a way to give a color a name.
makes it easier to change the same color in different places.

Step 1: Open Your CSS File

1. Open VS Code.
2. Click `style.css`.
3. Go near the top of the file.

Step 2: Add Color Variables

Add these variables near the top of your CSS file:

    :root {
        --background-color: #0f172a;
        --card-color: #1e293b;
        --accent-color: #38bdf8;
        --text-color: #ffffff;
    }

### Step 3: The Colors

- background-color: Dark navy background
- card-color: Lighter navy used for cards
- accent-color: Bright blue used for highlights
- text-color: White used for text

### Step 4: Use the Variables

Instead of typing the color code every time, use var().

Example:

    body {
        background-color: var(--background-color);
        color: var(--text-color);
    }
    
    Step 5: Change a Color

If you want to change the blue accent color:

1. Find `--accent-color`.
2. Replace its color code.
3. Save `style.css`.
4. Refresh the website.

5. How to Another Project Card
Step 1: Open Your HTML File

1. Open `index.html`.
2. Press Ctrl + F.
3. Search for `projects-container`.

Step 2: Find the Project Cards

Look for the project cards inside the projects container.

Each starts with:

<div class="project-card">

Step 3: Copy a Project Card

1. Find the last project card.
2. Highlight the card.
3. Include the opening and closing div tags.
4. Press Ctrl + C.

Step 4: The New Card

1. Click after the last project card.
2. be sure you are still inside the projects container.
3. Press Ctrl + V.

Step 5: Change the Information

Change:
- Project title
- Project description
- Project icon
- GitHub repository link

Step 6: Save Changes

1. Press Ctrl + S.
2. Open your website in the browser.
3. Refresh the page.
4. Check that your new project card appears.

6. Desktop Testing Checklist
Check:

- [ ] My website opens correctly.
- [ ] My name looks correct.
- [ ] My profile picture is there.
- [ ] The navigation menu works.
- [ ] The Home section looks cohesive.
- [ ] The About Me section is easy to read.
- [ ] My Skills cards display correctly.
- [ ] My Education information is accurate.
- [ ] My Work Experience information is accurate.
- [ ] My Project cards are evenly spaced.
- [ ] My GitHub links work.
- [ ] My LinkedIn link works.
- [ ] My email link works.
- [ ] My Contact form displays correctly.

## 7. Mobile Testing Checklist
Mobile View

1. Open your website
2. Press F12.
3. Find phone and tablet icon.
4. Click the icon.
5. Select a phone screen size.
6. Check the website.

Mobile Checklist

- [ ] My website fits on a phone screen.
- [ ] The text is easy to read.
- [ ] My navigation links are accessible.
- [ ] My profile picture fits correctly.
- [ ] My About Me cards stack properly.
- [ ] My Skills cards fit the screen.
- [ ] My Education cards fit the screen.
- [ ] My Project cards stack vertically.
- [ ] My Contact form fits the screen.

## 8. Final Checklist
check the following:

- [ ] Save index.html.
- [ ] Save style.css.
- [ ] Make sure profile.jpg is in the project folder.
- [ ] Replace any placeholder names.
- [ ] Update your education information.
- [ ] Update your work experience.
- [ ] Update your skills.
- [ ] Update your projects.
- [ ] Update your GitHub links.
- [ ] Update your LinkedIn link.
- [ ] Update your email address.
- [ ] Check spelling and grammar.
- [ ] Test the website on desktop.
- [ ] Test the website on mobile.
- [ ] Check the copyright year.
