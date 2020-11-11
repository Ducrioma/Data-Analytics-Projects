# Data Analytics Projects

## TO DO
## Phase 2 : Shiny Application
### Instruction list

 - [ ] Write a shiny app with a Readme.md
 - [ ] Deploy the app on the local server
 - [ ] Share server and ui codes on github
 - [ ] Write a 5 slides pitch using RMD presentation.
 - [ ] Add the presentation in the repo

### App features

 - [ ] Some form of input (widget: textbox, radio button, checkbox, ...)
 - [ ] Some operation on the ui input in server.R
 - [ ] Reactive output displayed as a result of server calculations
 - [ ] User friendly
 - [ ] Shiny doc only

### Remote repo organisation

 1. App directory (Shiny)
 2. Presentation directory
 3. Scripts directory (includes all other types of scripts such as the preprocessing scipt)

### App Organisation
![Sketch](/img/sketch.png)

## Phase 1 : Core Analysis
### Part 1

 - [X] Find the "average availability over 30 days" of listings per each city.
 - [X] Find the "average revenue of over 30 days" of listings per each city.
 - [X] Compare the distribution of estimated availability for the next 30 days of listings per each city.
 - [X] Compare the distribution of estimated revenue for the next 30 days of listings per each city.
 - [X] Compare the distribution of estimated revenue for the next 30 days of listings per each city & for each house size (# of bedrooms). --> **remove NaN**
 - [ ] Compare the distribution of estimated revenue for the next 30 days of listings per each city & for each room type (room_type). --> **élargir les viz**

### Part 2
For each city :

 - [X] What is the proportion of each room type?
 - [X] What is the proportion of each house size (# of bedroom)?
 - [X] What is the proportion of each neighborhood?
 - [ ] What is the average availability over the next 30 days for each room type / house size / neighborhood? -> Metric
 - [ ] What is the average revenue over the next 30 days for each room type / house size / neighborhood? -> Metric
 - [X] What is the distribution of availability over the next 30 days for each room type / house size / neighborhood? -> Distrib plot
 - [ ] What is the distribution of revenue over the next 30 days for each room type / house size / neighborhood? -> Distrib plot

### Bonus :
For each city :
- [X] Fetch the price of squaremeter in each city : fixed cost
- [X] Fetch the price of the electricity and water in each city : variable cost
- [X] Compute the breakeven point in days and in € : Fixed Cost / (Income-variable cost)
