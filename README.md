# website.io

A clean, responsive personal website with a modern design.

## Features

- Responsive design that works on mobile, tablet, and desktop
- Clean and minimal aesthetic with Inter font
- Organized sections for your profile, education, experience, and projects
- Skills display with categorized tags
- Contact form with clean styling
- Social media integration

## CSS Structure by HTML Pages

### Common Elements (Used across all pages)
* **Font & Basic Styling**: Uses Inter font with a white background and dark text
* **Container**: Centers content with max-width of 800px
* **Header & Navigation**: Consistent header with site title and navigation menu
* **Footer**: Simple footer with copyright information
* **Responsive Design**: Adjustments for different screen sizes (mobile, tablet, desktop)

### Home Page (index.html)
* `.hero`: Creates a prominent welcome section with your title/subtitle
* `.about`: Centers paragraphs with a max-width for readability
* `.links`: Horizontal layout for social media links
* `.introduction` with `.profile`: For displaying your photo alongside intro text
* `.educations` and `.experiences`: Timeline-based sections with vertical blue line
* Improved social media icon styling with consistent sizes

### Projects Page (projects.html)
* `.projects-grid`: Card-based layout that changes columns based on screen size
* `.project-card`: Clean cards with subtle hover effects
* Responsive grid that shows 1, 2, or 3 columns depending on screen width

### Skills Page (skills.html)
* `.skills-container`: Container for all skill categories
* `.skill-category`: Section for each type of skill
* `.skills-list` and `.skill-tag`: Tag-based layout for skills display

### Contact Page (contact.html)
* `.contact-form-container`: Centered form with left-aligned inputs
* `.form-group`: Consistent form field styling
* Button styling with hover effects
* `.contact-info`: Additional contact information

## Difficulites
* Using rem based on html at the top due to difficulty in unifying letters
* Difficulty in organizing common pages and individual pages, so the header and footer perform common tasks and try to organize the main part for individual pages
