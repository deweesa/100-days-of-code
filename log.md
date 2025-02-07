# 100 Days Of Code - Log

### Day 1: August 27, Friday

**Today's Progress**: 
    - Created new repo for development on my personal site. Was in git hell 
      trying to git the locally created react app on branch `master` to the 
      remote branch `main`. 
    - Just made a simple landing page. Think I am going to use bootstrap moving
      to bootstrap has messed with the styling of the page a little bit. 

**Thoughts**: Moved pretty slow today. WIsh I was better at more advanced git 
          features so that I could have gotten out of git hell sooner. Also 
          wish that I had some more experience with web development and front
          end technologies. 

**Link(s) to work**
1. [Initial Commit](https://github.com/deweesa/Portfolio-Site/commit/10590ce939480d1ac0d5b8d0ab10e805e7cd2955)
2. [GitHub Repo](https://github.com/deweesa/Portfolio-Site) 

### Day 2: August 28, Saturday

**Today's Progress**:
    - Didn't get any coding done today. Was out all day celebrating Papa's birthday

### Day 3: August 29, Sunday

**Today's Progress**:
    - Missed Day

### Day 4: August 30, Monday

**Today's Progress**:
    - LeetCode p868
    - Got some work in on the chess app. Started pulling out the movement logic
      from the board componenet. Working on creating functions to remove the 
      really repetitive code from piece logic. Like breaking out row/col/diag 
      highlighting into their own functions that a piece handler can call.

**Thoughts**:
    Had some issues with javascript today, and was kind of distracted the while
    working on stuff. Had an issue where I didn't decompose a piece, so I was 
    looking at a whole piece trying to just get it's type, and it would crash
    the app. Took a bit of head scratching and snooping to figure out where it 
    went wrong. Maybe this is a situation where typescript shines, not just 
    grabbing things willy-nilly. Want to get more stuff done tomorrow. 
    
### Day 5: August 31, Tuesday

**Today's Progress**:
    - Got the PieceHandler object mostly finished. It handles all the basic 
      movement for each of the pieces. Very close to where you could play a
      whole chess game on the same computer with someone. 

**Thoughts**:
    Had fewer js frustrations today, or moreover have a better feel for what
    some of the finer details of js. Also made the movement stuff way cleaner
    than it was when it was still in the board. Nice to have stuff feeling 
    cleaner. 
    
**Link(s) to work**:
    -[Commit of PieceHandler](https://github.com/deweesa/boardgames/commit/09b8284016e390dad970a6a3ba22c500a879cd33)
    
### Day 6: September 1, Wednesday

**Today's progress**:
    - Worked on Back End/APIs exercises from freeCodeCamp

**Thoughts**:
    I like the way that FCC handles their exercises. Compared to the other 
    express tutorials I've looked at so far this is the easiest to follow 
    along with. Feel like I have a better understanding of of the different
    express methods and how to use them. 

**Link(s) to work**:
    - [npm work](://github.com/deweesa/boilerplate-npm)
    - [express work](https://github.com/deweesa/boilerplate-express)

### Day 7: September 2, Thursday

**Today's progress**:
    - Worked on mongodb/mongoose exercises from FCC

**Thoughts**:
    So far working with mongodb w/mongoose is a lot like working with 
    sqlalchemy. It has a similair feature of chaining queries, but the 
    structure of having a `done()` method is something new. Still adjusting 
    to the use of callback functions with js.

**Link(s) to work**:
    - [MongoDB and Mongoose Exercises](https://github.com/deweesa/boilerplate-mongomongoose)

### Day 8: September 3, Friday

**Today's progress**:
    - Completed tiemstamp microservice from FCC

**Thoughts**:
    It was a pretty straightforward assignment, fairly simple. Hardest part
    was some mistakes I was making with the Date object. 

**Link(s) to work:
    - (Timestamp Microservice)[https://github.com/deweesa/boilerplate-project-timestamp]

### Day 9: September 4, Saturday
**Today's progress**:
    - Off day

### Day 10: September 5, Sunday
**Today's progress**:
    - Completed headerparser from FCC

**Link(s) to work**:
    - [Header Parser](https://github.com/deweesa/boilerplate-project-headerparserhttps://github.com/deweesa/boilerplate-project-headerparser)

### Day 11: September 6, Monday
**Today's progress**:
    - Off day

### Day 12: September 7, Tuesday
**Today's progress**:
    - Worked on the URL shortener, now validates the url (if no protocol is specified)
      and just sends back the IP address from `dns.lookup()`. 
    
**Thoughts**:
    - Had some trouble figuring out the settings for the `dns.lookup()` and figuring out
      that if the url has `http(s)` in it it would error out the lookup. but now I know 
      next steps are to get it hooked to mongodb and be able to parse out the `http(s)`
      before feeding it to `lookup()`

**Link(s) to work:
    - [URL Shortener MS](https://github.com/deweesa/boilerplate-project-urlshortener)
