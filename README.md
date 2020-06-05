# My First Fork
* **Objective** - To fork a project, `add`, `commit`, and `push` a single change upstream.
* **Objective** - To familiarize with basic `git` commands

### Part 1 - Forking the Project
* To _fork_ the project, click the `Fork` button located at the top right of the project.


### Part 2 - Navigating to _forked_ Repository
* Navigate to your github profile to find the _newly forked repository_.
* Copy the URL of the project to the clipboard.

### Part 3 - Cloning _forked_ repository
* Clone the repository from **your account** into the `~/dev` directory.
  * if you do not have a `~/dev` directory, make one by executing the following command:
    * `mkdir ~/dev`
  * navigate to the `~/dev` directory by executing the following command:
    * `cd ~/dev`
  * clone the project by executing the following command:
    * `git clone https://github.com/MyUserName/my-first-fork.git`

### Part 4 - Opening _cloned_ project
* from a text editor (i.e. - Visual Studio Code), select:
  * `File` > `Add Folder to WorkSpace`
    * select the `dev` directory 
  * from the text editor, in the `dev` directory, locate the newly cloned project
    * expand the project from the _project explorer_
    * modify the `my-details.txt` file to include your full name, college-classification, major, and minor
  
 ### Part 5 - _Pushing_ new changes to repository
 * from a _terminal_ navigate to the root directory of the _cloned_ project.
  * from the root directory of the project, execute the following commands:
    * add all changes
      * `git add .`
    * commit changes to be pushed
      * `git commit -m 'I have added my name to the text file!'`
    * push changes to your repository
      * `git push -u origin master`

### Part 6 - Submitting assignment
* from the browser, navigate to the _forked_ project from **your** github account.
* click the `Pull Requests` tab.
* select `New Pull Request`

### Part 7 - Ensuring project has been submitted
* Upon submission, your name, and a link to your project should be made available by clicking [here](https://github.com/CodeDifferently/git.my-first-fork/pulls)
