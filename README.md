# School of Code Learning Audit - Day 25

## Ratings system - Red, Amber, Green

🔴 Red - Topics that I feel lost on and need to work on
🟠 Amber - Topics that I remember the gist of but would struggle with syntax and specifics or i was rocky on
🟢 Green - Topics that I have a decent conceptual understanding of and could bash out some code that mostly works or a topic i can explain in depth

## Learning topics confidence evaluation

## Overarching mindset and soft skills
  - Myers briggs, cognitive styles,
  - growth mindset
  - assertive enquiry - teamwork and 3 fallacies

### On-boarding

- Learning, competency, and behaviour topics, including
  - Non-Sleep deep rest NSDR - havent done much but get it 🟠
  - High performance routines - sleep is better, walks regular,🟢
  - Team programming - we do this regularly🟢
  - Computational thinking - pretty step by step🟢
  - 7 Steps programming - i haven't tended to write things out on paper, rather say them or pseudocode🟠
  - Agile thinking and Agile manifesto - could put into better use, mvp etc🟠
  - Disney Ideation - blue sky, realist, critic make sense!🟢
  - Git and GitHub confident with basic workflow and fixing issues when i have them, e.g. reset, stash stuff i've tinkered with - still don't fully appreciate better ways to use it and branch with others or be more efficient🟠


### Software engineering

- Minimum viable product (MVP) 🟠
- GitHub project management, including
  - Projects - board and link to issues🟢
  - Milestones - epics 🟢
  - Issues - user stories🟢
  - Tasks - break it down🟢
- JavaScript fundamentals, including
  - Data types
    - number 🟢
    - string - letters🟢
    - boolean - true false🟢
    - undefined 🟢
    - null 🟢
    - array [] index positions 0 onwards, organised🟢
    - object {} json etc🟢
    - symbol not used 🟠
    - bigInt haven't used, but cryptography / unique id related? 🟠
  - Variables no var, only let const 🟢
  - Operators
    - Mathematical operators like +, -, \*, / - basic maths🟢
    - Logical operators OR (||), AND (&&), NOT (!) - typically used in our conditional if statements🟢
    - Rest and spread operators - have used spread to bring object contents to same nest level as a new object, not used rest to condense🟠
  - Conditionals - if and else statements  - list of conditions to check before doing a thing🟢
  - Loops - for, while, and do loops - concept i get, but havent used many, but it's just repeating a thing or function until a condition is satisfied🟠
  - Functions -i still feel a bit shaky on arrow function shorthand and syntax for a callback 🟠
  - Objects 🟢
  - Arrays 🟢
- JavaScript Debugging - havent used the fancy debuggers to step through code as it runs and see where it stops, but i'm alright at seeing where we have issues anyway🟠

### Front-end engineering

- Semantic HTML - shaky on interaction b/w html blocks and css and what style is applied where, especially flex/grid arranging since i was winging it with airbnb🔴
- Basics of CSS layouts 🔴
- DOM selectors using dot and # notation for class/id etc to target - need refresh before using it again🟠
- Event listeners - button clicks, form submits, etc. concept ok, implement is meh 🟠
- Fetch - just get data from api, right?🟠
- Async JavaScript and JavaScript promises 🟠
- Async/Await  - i have used these, but still not fully clued up on how and why they work🟠
- .then as alternative, not that we shold use it much now anyway
- using postman to interact with API and make requests 🟢

- UNSURE HOW MUCH OF THIS IS BECAUSE IT WAS WEEKS AGO VS ACTUALLY LOST

### Back-end engineering

- Server vs client 🟢
- Node as a foundation🟢
- NPM use and install stuff - didn't touch on using for different version of node though🟢
- JavaScript modules - exporting and importing code from other JavaScript files - mighty useful! 🟢
- APIs / REST - HTTP methods/verbs good at get,post, put, delete, didnt do as much patching as wanted 🟢
- Common node packages, including
  - Express - excellent for making an app as a basis🟢
  - Helmet - middleman prot 🟢
  - Nodemon - auto update when changed🟢
- Express, including
  - Spinning up an Express server, setting scripts to run start up modules🟢
  - Middleware - still nto sure what morgan is, could look into JEST for testing🟠
  - HTTP request handlers, a.k.a. routes 🟢
  - Error handling - understand codes and basic errors, but these were basic handlers, not extensive. look into the modules that do error handling?🟠
- Working with files 🟢

### Database engineering

- Database management systems - what are they and the most common types/ones 🟢
- High-level SQL language and writing SQL statements
  - Data Definition Language (DDL) 🟢
  - Data Manipulation Language (DML) 🟢
  - Data Control Language (DCL) (in theory) 🟢
- SQL joins - just remember what we define as left and right tables and what that means for which columns are incl🟢
- SQL self-joins - didn't really use, but understand concept with employee/boss each with employee ID 🟢
- SQL sub-queries - used in our sql games, but not really🟢
- Entity relationship diagram (ERD), including
  - Attributes (properties or traits) 🟢
  - Relationships 🟢
  - Cardinalities concepts, probably familiarise with lingo, though self explanatory🟠
  - Primary keys 🟢
  - Foreign keys 🟢
  - Composite primary keys - wombo combo values to make a new key when a single column/value isn't enough to specify 1 record🟢
  - Bridge tables 🟢
- Online ERD creation tools - aware of lucid chart, used mermaid and chatgpt code to make ERD🟢
- Node environment variable (.env) - security, and gitignore ( also for dependencies so not into github)🟢
- Cloud-based PostgreSQL database creation and hosting using the Render (render.com) cloud
- Node PostgreSQL client (pg) npm package
  - Installation 🟢
  - Implementation in a Node/Express server to retrieve data from a cloud-hosted PostgreSQL database 🟢
  - Converting SQL into API function and handlers - mostly ok

## Learning plan and priorities

Focus on the sections where you have more 🔴 and 🟠, in this case, front end. Rebuilding the quiz app from scratch probably a good place to start since it covers a lot of those things of layout as well as async functions, fetch, api interaction, DOM and JS interactivity with event listeners. Maybe we could even make it so we choose different difficulties and genres using the online API endpoints?
### 1. Front end is sketchy cos it was all done by winging it

- DOM selectors are a bit rusty, but in theory mostly dot notation and similar to other methods of select
- I don't know how to properly use flexbox and grid to style my containers and what best practices are around wrappers and structure the html so i don't have to hardcode stuff.

### 2. Async JavaScript and JavaScript promises

- I have a basic understanding of asynchronous JavaScript and JavaScript promises, but I struggle to retrieve values/data from resolved promises.
- I need to fill in the gaps in my knowledge of JavaScript promises and what they return when they resolve, reject, or error out.
- And how to access the values/data inside those resolved/rejected/errored promises.

### 3. Async/Await

- I understand the basic concepts behind async/await asynchronous JavaScript functions.
- However, syntax is a faff and promise chaining inside async/await functions isn't super clear, esp how to avoid callback hell type situations. keep code clean and clear

## Learning resources and completion tracking

- **Frontend is a pain** 
    - Flexbox froggy and css diner and grid garden and remaking the front end of the quiz app since i was less hands on with Jakub and Jin.
- **Async JavaScript and JavaScript promises**

  - Javascript.info - The Modern JavaScript Tutorial - Promise basics - https://javascript.info/promise-basics
  - Javascript.info - The Modern JavaScript Tutorial - Error handling with promises - https://javascript.info/promise-error-handling

- **Async/Await**
  - Javascript.info - The Modern JavaScript Tutorial - Async/await - https://javascript.info/async-await
  - Async + Await YouTube video by Wes Bos - https://www.youtube.com/watch?v=9YkUCxvaLEk
  
- **Doing more planning and thinking about agile and mvp and all that in next project** 