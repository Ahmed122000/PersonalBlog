
# SAH Blog

SAH Blog is a simple and modern blog website that allows users to read and share technical posts related to software development, artificial intelligence, and coding tips. The site offers a clean interface with navigation, search functionality, and a grid of blog posts.

## Project Overview

This project is a static blog site built with HTML, CSS, and FontAwesome. The homepage introduces users to the blog, allows for easy navigation, and showcases several blog posts in a grid format. Each post contains a brief description, and users can click to read more. 

The project includes:
- Homepage with post grid and brief descriptions.
- Navigation bar with links to the home, about, and subscription sections.
- Search bar for filtering content.
- Footer with social media links and subscription options.

## Features

- **Homepage**: 
  - Displays a welcoming message and the blog's name.
  - Includes a grid of blog posts, each with a cover image, title, date, description, and "read more" button.
  
- **Search Bar**: 
  - Allows users to search for posts using a simple search bar.
  
- **Post Cards**:
  - Each post is represented as a card with a cover image, title, date, description, and link to the full article.
  - 
- **Responsive Design**: The layout adjusts to different screen sizes using CSS Grid, Flexbox, and media queries.

- **Author Info Section**: Displays the author's avatar, name, and bio.

- **Social Media Sharing**: Fixed social media icons for easy sharing, hidden on small screens for better usability.

- **Footer**:
  - Contains an "About" section describing the blog's focus on software and AI.
  - Social media links (Facebook, Google Plus, GitHub, LinkedIn).
  - Subscription button to allow users to subscribe to the blog.

## File Structure

```bash
SAH Blog/
│
├── blog.html             # Blog page with post grid
├── article.html          # Template for full blog articles
├── css/
│   └── article.css        # style for the blog articles
│   └── blog.css          # Styles for the blog page
│   └── content.css        # style for the content of the blog page
│   └── footer.css 	   # style for the footer of the website
│   └── header.css        # style for the header of the website
│   └── social-icons.css   # style social media icons
│   └── social-share.css        # style the social share bar
├── assets/
│   └── images/           # Folder for images like cover.jpeg
├── README.md             # This file
└── LICENSE               # License for the project
```

## Technologies Used
- **HTML5**: Structure of the webpage.
- **CSS3**: Styling for the page, including grid layout, flexbox, and media queries.
- **Font Awesome**: For the icons used in the search bar and social share buttons.
  
## How to Use

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/sah-blog.git
    ```
2. Open the `index.html` file in any web browser to view the blog.
3. Navigate to the blog page using the provided navigation bar to see all posts.

## Dependencies

- [FontAwesome](https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css): For icons used in the project.
  

## Responsive Design

The article page uses **CSS Grid** and **Flexbox** to adapt the layout across different screen sizes. Here's how the page behaves on various devices:
- On **larger screens** (desktops/laptops), the content is centered with a maximum width of 1200px.
- On **tablets and smaller devices**, the layout adjusts to fit the screen width, and elements like the social share buttons are hidden for better usability.

### Media Queries

This project uses media queries to enhance responsiveness:
```css
@media (max-width: 768px) {
    /* Adjustments for smaller screens */
}
```
