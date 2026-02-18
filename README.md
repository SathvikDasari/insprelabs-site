# 🌐 InspireLabs Website

Welcome to the InspireLabs website repository.

This site is built using:

-   Hugo (Extended)
-   Tailwind CSS
-   GitHub Actions
-   GitHub Pages

This guide explains how to set up the website locally and test changes
before deployment.

------------------------------------------------------------------------

# 🚀 Local Setup Guide

## 1️⃣ Install Required Software

### Install Git

Download: https://git-scm.com/downloads

Verify: git --version

------------------------------------------------------------------------

### Install Node.js (LTS recommended)

Download: https://nodejs.org

Verify: node -v npm -v

------------------------------------------------------------------------

### Install Hugo (Extended Version Required)

Download: https://gohugo.io/installation/

Verify: hugo version

Make sure it says **extended**.

------------------------------------------------------------------------

## 2️⃣ Clone the Repository

git clone https://github.com/SathvikDasari/insprelabs-site.git cd
insprelabs-site

------------------------------------------------------------------------

## 3️⃣ Install Project Dependencies

npm install

------------------------------------------------------------------------

## 4️⃣ Run the Website Locally

hugo server

Open your browser and visit:

http://localhost:1313

The page will automatically refresh when you save changes.

------------------------------------------------------------------------

# ✏️ Editing the Website

Most content is inside:

content/

Examples:

-   About page → content/about/\_index.md
-   Contact page → content/contact/\_index.md
-   Programs → content/programs/

------------------------------------------------------------------------

# 🧪 Always Test Before Deploying

1.  Run hugo server
2.  Test edited pages
3.  Confirm:
    -   Text is visible
    -   Links work
    -   Layout is correct
    -   No console errors

------------------------------------------------------------------------

See DEPLOYMENT.md for how to push changes live.
