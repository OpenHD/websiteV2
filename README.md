# OpenHD Website V2

Welcome to the OpenHD Website V2 repository. This project contains the source code for the OpenHD website.

## Table of Contents

- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Contributing](#contributing)

## Overview

The OpenHD Website V2 is a modern, responsive website built to provide information and resources about the OpenHD project. The website is designed to be user-friendly and accessible, providing a seamless experience across different devices and screen sizes.

## Technologies Used

The project uses the following technologies:

- **HTML**: Markup language for creating the structure of the website.
- **CSS**: Styling language for designing the look and feel of the website.
- **JavaScript**: Programming language for adding interactivity and dynamic content.
- **Ruby**: Used for specific backend functionalities.
- **Jekyll**: A static site generator used to build the website.

## Getting Started

To get a local copy of the project up and running, follow these steps:

### Prerequisites

Make sure you have the following software installed:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/)
- [Ruby](https://www.ruby-lang.org/en/)
- [Jekyll](https://jekyllrb.com/)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/OpenHD/websiteV2.git
   cd websiteV2
   ```

2. Install dependencies:

   ```bash
   npm install
   bundle install
   ```

3. Build the site and start the Jekyll server:

   ```bash
   bundle exec jekyll serve
   ```

4. Open your browser and navigate to `http://localhost:4000` to view the website.

## Project Structure

The project structure is organized as follows:

```
OpenHD/websiteV2/
├── .github/           # GitHub-related files
├── _data/             # Data files
├── _includes/         # Include files for Jekyll
├── _layouts/          # Layout files for Jekyll
├── assets/            # Static assets (images, CSS, JS)
├── changelogs/        # Changelog files
├── downloads/         # Downloadable files
├── .gitignore         # Git ignore file
├── Gemfile            # Ruby gem dependencies
├── Gemfile.lock       # Lock file for Ruby gems
├── _config.yml        # Configuration file for Jekyll
├── checks.json        # Configuration for checks
├── index.md           # Main index file
├── privacy.md         # Privacy policy file
```

## Contributing

We welcome contributions to improve the OpenHD website. If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.

### Steps to Contribute

1. Fork the repository.
2. Create a new branch: `git checkout -b my-feature-branch`
3. Make your changes and commit them: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-feature-branch`
5. Open a pull request.
