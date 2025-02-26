# hugo-mock-landing-page

Mock landing page for a (currently nonexistent) personal styling app. Includes a Github Actions workflow. 

## Workflow Description

The Github Actions workflow in this repository automates the process of building a Hugo website and deploying it to Github Pages whenever a change is pushed to the main branch. At a high level, it checks out the repository (including submodules), installs and initializes Hugo, builds the static site using Hugo, and deploys the site to the gh-pages branch.   
