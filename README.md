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

### Running website
Before running the project, install following code:
```
npm i node-pre-gyp
npm install bcrypt --save
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
- [ ] 1 product backlog (use the template in appendix D for the estimation of effort).
- [ ] 1 burndown chart for the whole CA2 (you may use any software e.g. Word, Excel, Trello for the scrum board). Provide 3 screenshots for your scrum board (1 for the starting state, 1 for showing status of progress at midway point, and 1 for the ending state of your scrum board).
- [ ] 3 test cases.
- [ ] 2 screen shots of Github (1 screen shot at the start before committing any changes, 1
screen shot to show all the commits at the end of the project).
- [ ] 3 sequence diagrams.
- [ ] Bug fixes (if any). Submit only those program files that are amended.
