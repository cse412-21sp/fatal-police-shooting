# CSE412 Final Project Template (Idyll)

## IMPORTANT NOTE:
**Planning of the final website is in file `rought draft.pdf` under directory docs.**

## Team Members

Tim Li, Chris Chen, Yuchen Sun

### Contribution Statements

Tim Li worked on maintaining consistency on the Github repo, creating some visualizations via Tableau, and facilitating discussions.

Chris Chen was responsible for writing the most of the narrative, creating some of the visualizations via Tableau, and arranging meetings.

Yuchen Sun worked on creating most of the visualization via D3 and Vega-lite, designing the general layout of the website, and recording the demo video.

## Project Proposal Abstract

As the topic of police brutality continues to gain heat on social media, more and more people started to realize that the racial discrepancy still exists in our society and movements like Black Lives Matter garner social presence. We also seek to gain some insight about this social phenomena, hence we will use this project to examine the latest trends in US fatal police shooting. Are there any patterns in police shootings such as location hotspots, time series, etc. We use two datasets from the past six years, one dataset will be the police shooting dataset from kaggle, the other one will be the demographic distribution in the United States from the world bank. This project aims to deepen the discussion in the currently popular topic of racial discrimination and police brutality. This is the first analysis of its type to drill down on city-level datasets. We are used to national level reports on police brutality that often ignores the specific context of local communities. This project hopes to explain why some cities have higher tendencies of fatal shootings than others.


## Getting Started

This template is a starting place for your project. Update the header information to include the relevant details for your project, and then feel free to mix and match the visualization and layout techniques introduced here for your own narrative.

Think about how the narrative structure draws readers into the story you are telling and how the visualizations interact with the text (and with each other). The narrative should help ensure that the page as a whole is greater than just the sum of it's parts. When designing your page, decide on particular layouts that enhance the reader's experience and understanding of the topic.

### Required Software

You must have Node.js installed. You can get it directly from https://nodejs.org/en/.

### Installation

- Clone and open your project repo on your own computer.
- Make sure you have `idyll` installed (`npm i -g idyll`).
- Run `npm install` to install project-specific dependencies.

npm is the node package manager. If you're curious how this works and what the project dependencies are, open up `package.json` to see where these are listed.

You can install custom dependencies by running `npm install <package-name> --save`. Note that any collaborators will also need to download the package locally by running `npm install` after pulling the changes.

### Developing a post locally

Run `idyll` from the command line. Your post will appear at [http://localhost:3000/](http://localhost:3000/). When the server is running, any local change that you make will be deteched and your webpage will auto-update with the new changes. Your local changes will not be visible to your team members until you push the changes to your repository. These changes will not be reflected in the final website unless you run the build script and push the updated docs folder (see below).

### Building a post for production

Run `idyll build`. The output will appear in the top-level `build` folder. To change the output location, change the `output` option in `package.json`.

### Deploying

Make sure your post has been built, then commit the `docs` folder to your project repository. It will be available at [cse412-21sp.github.io/your-repo-name/](). For example, you can view the sample embedded Tableau, vega-lite, and d3 charts at [https://cse412-21sp.github.io/Final-Project-Template](https://cse412-21sp.github.io/Final-Project-Template).

#### Acknowledgements

This template was adapted from the initial Scrollytelling template for Idyll. The code and visualization examples were adapted from the [final project template](https://github.com/cse412-21w/project-demo) created for a previous offering of CSE 412.
