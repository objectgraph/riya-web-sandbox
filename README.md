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
- Created my own website and uploaded it to github pages
  - Used HTML and CSS to design and style it
  - Used `@ media querys` to make the design responsive for mobile
- Implemented JavaScript to add some reactive elements to the demo inquiry form
- Created a dark mode using localStorage so the preference is kept when refreshed or when the page is changed
- Created a new inquiry form with Bootstrap 5
  - Added validation
-

## What I've Used

### Tools

- [Visual Studio Code](https://code.visualstudio.com/)
  - LiveServer Extension
  - GitLens Extension
  - Prettier Extension
- [Figma](https://www.figma.com/)
- [Bootstrap 5](https://getbootstrap.com/)
- [Java Script Fiddle](https://jsfiddle.net/)

### Tutorials

- [W3Schools](https://www.w3schools.com/css/default.asp)
- [24 Minute Figma Tutorial](https://www.youtube.com/watch?v=FTFaQWZBqQ8)
- [HTML with Mosh](https://www.youtube.com/watch?v=qz0aGYrrlhU)
- [Dark Mode Guide](https://css-tricks.com/a-complete-guide-to-dark-mode-on-the-web/#toggling-themes)
- [Bootstrap 5 Forms Video](https://www.youtube.com/watch?v=dKVX22GR7zQ)

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

#### Git Stash

When you are working on a branch and don't want to commit your changes until you've merged to another branch, you can use something called `git stash`

- This command will enable you to "stash" away your changes until you are merged with onto another branch.
- Once you merge using `git checkout branch-name` and `git pull` you can use the command `git status` to see that you are working on a clean directory
- Once you see that, you can apply the command `git stash apply` to bring your changes to the current branch.
