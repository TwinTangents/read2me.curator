# Read2Me Curator

This repository provides tools and processes for parsing books into a format our system can use. Each project has it's own Jupyter Notebook so that it's final results can be recreated and the parsing steps can be modified and updated as needed in the future without a full rewrite. The goal is to eventually turn most of this processing (at least level 1 and most of level 2) into an automated step that can simply be audited. Until we know how most books are processed, each book will be done individually in it's own notebook.

### To get started
You will need a Jupyter Notebook with Javascript kernel installed. Run yarn install from the root of the repository to make sure you have all the tools necessary to start parsing a new book. Create a folder for your book under the projects/ folder and copy Template.ipynb into that folder. Rename the notebook to match the book's name. Happy parsing!