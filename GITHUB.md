
## Git and Github   
#### For further  detail visit [Github](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
#### For tutorial see Harvard YT video [Git CS50](https://www.youtube.com/watch?v=NcoBAfJ6l2Q)
#### Presentation [Slides](https://cdn.cs50.net/web/2020/spring/lectures/1/lecture1.pdf)

| Command | Description | Example |
| --- | --- | --- |
| `git clone <url>` | Clones the repository | git clone https://github.com/midsu/Portfolio.git |
| `ls` | List the folders in the directory | ls |
| `cd` | Change directory | cd hello |
| `touch` | Create folder in the directory | touch hello.html |
| `code.` | Opens text editor | code. |
| `git add <filename>` | Adds the file to track/saved | git add hello.html |
| `git commit -m "message"` | Save and commit the changes w/ a note | git commit -m "added a line" |
| `git status` | See what's currecntly happening in the repository | git status |
| `git push` | Publish your current local commit | git push |
| `touch` | Create folder in the directory | touch hello.html |
| `git commit -am` | add and commit in a single step | git commit -am "Added more" |
| `git pull` | Download the latest version from github to local version(opposite of git push) | git pull |
| `git log` | Keep track of all the changes/commits you've made in the repository | git log (shows commit,author,date,commit msg) |
| `git reset` | Revert back to previews update (--hard resets everything, --hard origin/master resets local to whatever the github version is) | git reset --hard <commit hash> OR git reset --hard origin/master |

#### Branching
Feature
Master
Head - points to which branch you're working on
Merge

| Command | Description | Example |
| --- | --- | --- |
| `git branch` | Tells what branch you're currently on & which branch exist | git branch |
| `git checkout -b style` | Creates new branch called style | git checkout -b style |
| `git checkout` | switching branch | git branch master |
| `git merge style` | merge "style" branch to master (running git from master already) | git merge style |
| `git commit -am` | add and commit in a single step | git commit -am "Added changed and merge" |


#### Merge Conflict

| Description | Example |
| --- | --- | 
| Local version and github version conflicting on same line of changes | <<<<< HEAD a=2 ===== b=0 >>>>> 7656c636f6d65207 c=3 |



