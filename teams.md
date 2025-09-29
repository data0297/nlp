# Assignment & presentation workflow

## General

- We have 14 students in the class, which will divide into 4 (3+3+4+4) teams. 
- Each team has been assigned a team lead. 
- Assignment and due date will be posted on Canvas, but you will be directed to the [GitHub repo](https://github.com/Tufts-University/NLP-course-fall2024/tree/main/HWs) main branch for the Jupyter Notebook. [^1]
- Each person must create their own branch on the GitHub repo and only work from that branch. 
- The grading will be based on the final status of the code in your individual branch. 
- You are allowed to discuss the homework with your team before you submit. 
- Each team will present one code review in class (which means going over the code and results in your assignment).
- Each team will also be assigned to present one research paper in class.

[^1] Please send me your github username so I can add you to the repo. 

## Code
- When you start your assignment, follow the instructions on the GitHub repo and write the code independently. Work within your own branch.  
- As you iterate through your code, make commits and push to the GitHub repo on your branch. 

## Meet
- The team lead can call a meeting to discuss homework assignments prior to the due date. This is an optional meeting where you can get together to discuss the homework before you submit it.
- If a homework requries group discussion or code review from your team, then the team lead will call a meeting to discuss, in which case it is a mandatory meeting. 

## Submit
- Please do not push any of your code to the remote (GitHub.com) until the due time on the due date. Otherwise your solution will be available for others to copy at any time. you can do that when you come to class, or right before the class. 

## Present (code review)
- The team will be presenting a 10-15 minute code review explaining your team's implementation of the assignment in class, and any challenges you faced, any analytical insights you derived. This is to get on the same page about the homework, and also an opportunity for sharing your unique insights and your learnings with the class. 
- Prior to the code review, every student will ask at least one question about the homework (or anything related to the homework in the class) on the platform Sli.do (links to follow). The team code review will need to make sure to address all of these questions in the presentation.
 
## Teams
Team leads are responsible for guiding the discussions of the assignment during team meetings and organizing the presentations. 

- Team A: Emma Virnelli (Lead), Caleb Deitch, Bichen Tang, Geneva Yang

- Team B:  Jingwen Feng(Lead), Maida Raza, Luodingyi Huang, Qingzhu Zhao

- Team C: Matthew D Soto(Lead), Harrison Chang, Xiaoheng Zhou

- Team D: Allen Wu (Lead), Evelyn Sun, Ella Zhou, Kyle Ng

## Useful Github commands and resources
0. You set up github on your command line in your terminal on your computer. You can Google how to do this, but here is a place to start: [link](https://git-scm.com/downloads)
1. First, you clone the course homework git repository onto your local computer in the terminal using `git clone` below. 
2. Second, you must create your own branch, and work within your own branch on the homework. (see below)
3. Third, after you edited your code and homework, you can use `git add` and `git commit`. You can do it every time you made progress and want to save the progress, you don't have to wait until you completed everything to add and commit. 
4. Finally, when you are very cloe to the deadline (like 15 mins), you can do `git push` to the git remote (github.com) so that you are submitting your homework. Don't push your code early or other people will see it way before the deadline. 


```bash
# clone the repo either using ssh or https
git clone url/of/the/repo

# to create your own branch, first send your GitHub username to the professor or team lead for authentication
git checkout -b branch_name

# to look at which files are being tracked now and check the status of your repo in your terminal 
git status

# to add your file for staging after it's been edited
git add hw2-1.ipynb

# after you added your file, check `git status` again to see which files are staged for committing now.
# to commit locally
git commit -m 'first submission' 

# to push to remote (wait until 10 mins before the dealine)
git push 

# to pull/merge the latest updates from the remote
git pull

## if you encounter an error message from git, read it carefully and follow the instructions to debug that. 
## it's a good practice to check the online repo (remote) to see that you actually successfully pushed your commits. 
```
### other git resources
- [comprehensive github tutorial](https://www.youtube.com/watch?v=tRZGeaHPoaw)

### last resort
Using git on the command line in your terminal is the correct way. However, for whatever reason, if you cannot make this work, you can also click download zip from github.com to download the assignment, and after you finished your assignment, you can click to upload files onto github.com directly (must be into your branch still, not the main branch) on the website. This way is the shortcut which is a set of operations that can be completed by clicking things on github.com website only without using git on your command line. It is not recommended but can be used as a last resort if you cannot get the command line to work and are short on time. 

An intermediate option is to use the GitHub Desktop , which is a GUI version of the git command line. I use it sometimes and it is very convenient. 