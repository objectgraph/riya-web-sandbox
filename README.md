# riya-web-sandbox

## What I've Learned

- Watched a YouTube vidoe by Mosh that gave a basic rundown of HTML
  - How to debug using Google developer tools (inspect)
  - How to validate a HTML file and CSS file using an online validator
    - This is a tool to help see where your code may have issues or incorrect formatting
  - Learned the basics of tag, classes, adding images, and modifying layout
- Started to create my own inquiry form
  - Desgined a basic wireframe in Figma
  - Used W3Schools to learn more about HTML forms and dropdown menus
  - Also used W3Schools to figure out CSS and design elemenets

## The tools I've Used

- [24 Minute Figma Tutorial](https://www.youtube.com/watch?v=FTFaQWZBqQ8)
- [HTML with Mosh](https://www.youtube.com/watch?v=qz0aGYrrlhU)
- Visual Studio Code
  - LiveServer Extension
- Figma
- [W3Schools](https://www.w3schools.com/css/default.asp)

## How to use Git

Git is a powerful version control system used by programmers to keep track/record changes to files.

### Git with VSCode

- Within a new VSCode window, click clone from repository
- Copy and paste the repository URL into the prompted box
- You can commit by either using the GUI or the terminal
- To use the terminal, first open a new terminal pane
- Type the command `git status`
  - This will let you see the status of your github repo
- Then type the command `git add .`
  - This will add all the changes
  - This does not mean it is committed however
- Then type the command `git commit -m ""`
  - This will commit the changes and the `-m ""` means that inbetween the quotes you can add a message
    - It is improtant to add a meaningful message so you can look back at changes you made during the commit
    - This is extremely helpful for debugging and testing
- The final command is `git push`
  - This will push your code to the github repo and the changes will all be synced.
- To use the GUI the steps are pretty simliar
- Open the side panel called source control
- Under the changes pane click the + icon to add all the changes
- Once that is done, click the checkmark icon to commit the changes and add a message in the box
- Finally click sync which will push all the changes to the github repo

### Branches and Pull Requests

Branches are used to work on current code without affecting the main/other branches in the repo
Reasons why branches are created:

- To develop new features
- To fix bugs

In order to merge the branches with the main branch, a pull request is created.
It will tell others about the changes you made, and once reviewed can be merged with the main branch

Branches and pull requests are an extremely valuable tool used my many developers and teams to effectively work with code

#### Branches with Git and VScode

- To create a branch in the terminal use the command 1`git checkout -b name-of-branch`
  - Dont' use uppercase or spaces, instead use kebab case
- To switch to a branch use the command `git checkout name-of-branch`
- Finally to merge the changes to your computer use the command `git pull`
  - This will pull all the changes from the merge to your VSCode
