# A Markdown Blog


This is a Hugo blog project built with a focus on modern web development technologies. It leverages TypeScript for type safety, Sass for advanced CSS, and Hugo's powerful Go backend for its built-in pagination and speed.

## Features

- Built with Hugo (static site generator)
- Leverages TypeScript for type safety and maintainability
- Employs Sass for enhanced CSS features and maintainability

### Project Structure

    markdown-blog/
        ├── archetypes/   # Content templates for different post types
        ├── content/     # Markdown files containing your blog posts
        ├── layouts/     # HTML templates for different page layouts
        ├── public/      # Output directory for the generated static site
        ├── static/      # Project-wide static assets (images, fonts, etc.)
        └── config.toml  # Hugo configuration file

## Getting Started

    Clone the repository:
    Bash

    git clone https://github.com/your-username/your-project-name.git

    Utilisez ce code avec précaution.

### Hugo Setup
[Follow the official Hugo quick start guide](https://gohugo.io/getting-started/quick-start/)

#### Key commands
Regenerate the static site in /public ```hugo```

Run development server ```hugo server```

    This will start a development server and open your blog in the default web browser (usually http://localhost:1313/). Any changes you make to your content or templates will be automatically reflected in the browser.

Add a new page using the default template ```hugo new content```


## Development Notes

The project is currently in development, and some features are still on the to-do list

    Implement a working search system
    Migrate from CSS to Sass for enhanced styling capabilities
    Fully convert the project from JavaScript to TypeScript for improved type safety

## Credits

    This project is a derivative of https://github.com/safak/markdown-blog. It leverages the same basic structure but introduces additional technologies (TypeScript, Sass) for an enhanced development experience.

Feel free to customize this README.md with your specific project details and instructions.