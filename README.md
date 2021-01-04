# SEP CA2

## Setting up assignment

### Cloning to local device
```
git clone https://github.com/jonntan/SEP_CA2.git
```
### Setting up MySQL database
1. Import islandfurniture-it07.sql into MySQL and run the file.

### Running frontend
Run 'node server.js' and if error is: 
```
module.js:682
  return process.dlopen(module, path._makeLong(filename));
                 ^

Error: \\?\H:\SPY2S2\SEP\SEP_CA2\islandfurniture_ST0506\node_modules\bcrypt\lib\binding\bcrypt_lib.node is not a valid Win32 application.
\\?\H:\SPY2S2\SEP\SEP_CA2\islandfurniture_ST0506\node_modules\bcrypt\lib\binding\bcrypt_lib.node
    at Object.Module._extensions..node (module.js:682:18)
    at Module.load (module.js:566:32)
    at tryModuleLoad (module.js:506:12)
    at Function.Module._load (module.js:498:3)
    at Module.require (module.js:597:17)
    at require (internal/module.js:11:18)
    at Object.<anonymous> (H:\SPY2S2\SEP\SEP_CA2\islandfurniture_ST0506\node_modules\bcrypt\bcrypt.js:6:16)
    at Module._compile (module.js:653:30)
    at Object.Module._extensions..js (module.js:664:10)
    at Module.load (module.js:566:32)
```
Install code below and run 'node server.js' again:
```
npm i node-pre-gyp
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
