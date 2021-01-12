# SEP CA2

## Setting up assignment

### Cloning to local device
```
git clone https://github.com/jonntan/SEP_CA2.git
```

### Setting up MySQL database
1. Open MySQL. 
2. Open [Administration] panel on the left hand.
3. Select [Data Import/Restore]
4. Select [Import from self-contained file] and chose SQL file.
5. Start import
6. Open new SQL tab and run code
```SQL
ALTER USER 'root'@'localhost' IDENTIFIED BY 'root1234';
```

### Nodejs
Uninstall current nodejs version in computer. Reinstall nodejs with the one in Misc folder.

### Running website
Run these code in VS Code **first!**
```node
npm i node-pre-gyp
```

Run these dependencies if needed...
```node
npm init
npm install mysql
npm install body-parser
npm install express
npm install request
npm install nodemailer
npm install bcrypt
npm install stripe
npm install @fortawesome/fontawesome-free
npm install pretty-checkbox
npm install jsonwebtoken
npm install multer
npm install forever -g
```

Run project code
```node
forever server.js
```

### Debugging
When debugging, open an issue. Then create a new branch and push your solution of code there. If it is approaved, it will be merged to the main branch.  
To create a new branch and switch to it:
```git
git checkout -b <branch_name>
```
Push the codes into this new branch and change back to main branch
```git
git checkout main
```

## Assignment Requirements

### Project timeline
Project commences on 4th Jan 2021 and ends on 1st Feb 2021, 2359 hrs.

### Team
Scrum Master: Jonn Tan  
Team members: Tenia, Anna Yap

### To be done
1. Create a prodect backlog.
2. Monitor progress using burndown chart.
3. Create 3 test cases.
   - View “Retail Products” category (this is the last option of “ALL
DEPARTMENTS”) (1 test case)
   - View Retail Product Details (for “Retail Products” option only) (1 test case)
   - View “Sales History” option (1 test case)
4. For each test case that has a Fail status, fix the bug.
5. Using sequence diagram, document the exchanges of messages by the objects in each of the above functions:
   - View “Retail Products” category (this is the last option of “ALL DEPARTMENTS”)
   - View Retail Product Details (for “Retail Products” option only)
   - View “Sales History” option
6. Follow proper change-request process to check out source code for the bug fix and commit the tested working code back to Github.

## Deliverables
- [x] 1 product backlog (use the template in appendix D for the estimation of effort).
- [x] 1 burndown chart for the whole CA2 (you may use any software e.g. Word, Excel, Trello for the scrum board). Provide 3 screenshots for your scrum board (1 for the starting state, 1 for showing status of progress at midway point, and 1 for the ending state of your scrum board).
- [x] 3 test cases.
- [x] 2 screen shots of Github (1 screen shot at the start before committing any changes, 1
screen shot to show all the commits at the end of the project).
- [x] 3 sequence diagrams.
- [x] Bug fixes (if any). Submit only those program files that are amended.
