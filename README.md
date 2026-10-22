# Student Portfolio Website

A responsive, minimalist four-page student portfolio built using only **HTML** and **CSS** (no JavaScript). Created as part of the Day-1 Mini Challenge.

## Pages

| Page | File | Description |
|------|------|-------------|
| Home | `index.html` | Name, profile photo, short introduction, course, branch, semester, year of study and social links |
| About | `about.html` | Personal introduction, education, areas of interest, skills and hobbies |
| Projects | `projects.html` | Project cards with title, description, technologies used and GitHub links |
| Contact | `contact.html` | Email, phone number, GitHub/LinkedIn links and a simple contact form |

## Features

- Consistent navigation menu on every page
- Minimal dark theme: soft white text (`#F1F5F9`) on deep navy (`#0F172A`)
- Responsive layout using CSS Flexbox, adapting to desktop, tablet and mobile screens
- Profile image displayed without stretching (`object-fit: cover`)
- Hover effects on links, buttons and project cards
- Skills section highlighted in its own panel
- Footer with a closing message, social links and copyright notice
- Colours defined as CSS variables in `style.css` for easy customisation

## Project Structure

```
portfolio/
├── index.html
├── about.html
├── projects.html
├── contact.html
├── style.css
├── photo.jpg
└── README.md
```

## How to Run

1. Clone the repository:
   ```
   git clone https://github.com/your-username/portfolio.git
   ```
2. Open the folder and double-click `index.html` (or open it in any browser).

No installation or build step is needed.

## Customisation

- Replace `photo.jpg` with your own profile photo.
- Update your name, links, phone number and email in the HTML files.
- Change the colour scheme in the `:root` block at the top of `style.css`.

## Note

The contact form is for interface practice only. It opens the visitor's email app and does not send or store messages on a server.

## Technologies Used

- HTML5
- CSS3 (Flexbox, media queries, CSS variables)
- Git & GitHub

## Author

**Your Name**
B.Tech Computer Science, Your College Name
[GitHub](https://github.com/your-username) | [LinkedIn](https://www.linkedin.com/in/your-username)
