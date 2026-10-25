# How to Create an E-Portfolio (GitHub Website)

## Introduction

This page will show you how to create an e-portfolio using GitHub Pages. E-portfolios are a great way to showcase your education, experince, projects, and skills in a resume style.  These are the steps for the `Minimal` theme template, however you can take similar steps for the `Minimal Mistake` theme, which creates a more polished porfolio. 

## Step 1: Create a Repository on GitHub

Create a GitHub account, if you do not already have one. First, I created a repository `<your_github_name>.github.io` which will store the files that you can download from the theme. 

## Step 2: Download the Theme
Download the [`minimal`](https://github.com/pages-themes/minimal) theme template. Add it to the repository that was just created. 

To download the [`minimal`](https://github.com/pages-themes/minimal) theme:
1. Open `Minimal` theme repository.
2. Click the green **Code** button.
3. Click **Download ZIP**
4. Extract the downloaded ZIP file. 

## Step 3: Add the Downloaded Theme to the Repository

Clone the portfolio repository to the computer and open it in VSCode to make changes. 

Next, move the extracted theme files into the local portfolio repository. Commit the changes and push them to GitHub. 

## Step 4A: Set Up the Theme

In the `_config.yml` edit the title, logo, and description. 

![screenshot](/assets/img/config_ss.png)

## Step 4B: Replace the Stock Logo with a Headshot

The theme includes a stock image, and you should replace with a headshot. 

1. Save the headshot as `logo.png` to replace the orginal logo with the headshot. 
2. Ensure the logo:`____` in `_config.yml` matches the name assigned to the headshot in the `img` folder. 

## Step 5: Write the Homepage

Open the main `index.md` file included in the `minimal` package, and replace the sample writing with your information. 

It is a markdown page so you can use markdown syntax to format text to your liking.

*Examples*: 
- `# Heading`: for a level one heading. 
- `## Heading`: for a level two heading. 
- `### Heading`: for a level three heading. 
- `**bold**`: for bold tetx.
- `*italic*`: for italizied text. 
- `- item` for a bullet point list. 
- and much more. 

## Step 6: Commit Changes and Publish the Portfolio

After making customizations to the `_config.yml` and `index_md` files, save the entire folder. Then, commit the changes through the source control section in VSCode, and push them to GitHub. 

Open the GitHub Pages repository in GitHub, navigate to the "Actions" tab and confirm you see a successful "pages build and deployment".

Then, navigate to the e-portfolio page to confirm the logo and text are in correct formatting. 

## Final E-Portfolio
The completed e-portfolio is a great place to showcase education, experience, projects, and anything else you may want to add. It can be linked in a resume, on LinkedIn, and shared in job applications so potential employers can easily navigate examples of your work. 

You can easily add new projects and new experiences by repeating Step 5 and Step 6. 

## References

Markdown cheat sheet | markdown guide. (n.d.). Www.Markdownguide.Org. Retrieved October 25, 2026, from https://www.markdownguide.org/cheat-sheet/

 Minimal Theme | GitHub Pages. Www.Markdownguide.Org. Retrieved October 25, 2026, from https://github.com/pages-themes/minimal