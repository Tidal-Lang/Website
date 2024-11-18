# Tidal Website

This repository contains the source code for the Tidal Programming Language website. The website provides information about the Tidal language, its features, documentation, and download links for past releases.

## Table of Contents

- [Tidal Website](#tidal-website)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
  - [Project Structure](#project-structure)
  - [Getting Started](#getting-started)
  - [Deployment](#deployment)
  - [License](#license)

## Overview

The Tidal website is built using HTML, CSS, and JavaScript, with Vue.js for dynamic content rendering and Tailwind CSS for styling. The website is hosted on Firebase Hosting and includes automated deployment workflows using GitHub Actions.

## Project Structure

- **main/**: Contains the main HTML, CSS, and JavaScript files for the website.
- **.github/workflows/**: Contains GitHub Actions workflows for automated deployment.
- **firebase.json**: Firebase configuration file.
- **.firebaserc**: Firebase project configuration.
- **.gitignore**: Specifies files and directories to be ignored by Git.
- **LICENSE**: License file for the project.

## Getting Started

To get started with the Tidal website locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/PranavVerma-droid/Tidal.git
   cd Tidal
   ```
2. Open the main/index.html file in your browser to view the website locally.

## Deployment
The website is deployed to Firebase Hosting. The deployment process is automated using GitHub Actions. There are two workflows:

**firebase-hosting-merge.yml**: Deploys the website to the live channel on merge to the main branch.
**firebase-hosting-pull-request.yml**: Deploys a preview of the website for pull requests.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.