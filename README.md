# hugo-mock-landing-page-autodeployed
Created a Github Action workflow for my website. 
The Github Action is called 🏗️ Build and Deploy GitHub Pages.
The workflow is trigged when we push to the repository in the main branch.
When it runs, it:
    Checks out your code
    Sets up Hugo
    Runs the Hugo build command (hugo -D --gc --minify)
    Publishes the result to GitHub Pages
