# 100 Days Of Code - Log

## Day 0: March 27, 2020
**Today's Progress**: Created the Github repository for `build-my-app`. Drafted an initial plan for the application.

**Thoughts**: I am once again having a little bit of analysis paralysis. For the frontend of the app, I am looking at Flutter, VueJS and React. Neither of them are ideal for me at the time I suppose. Flutter uses Dart, which would be a completely new language for me. Next to that, web development support is currently still in beta. React has been used for quite some time, but I always heard it is quite difficult. Lastly, I've used VueJS before in the past, but didn't have the time to learn it decently, so I'm not sure if I want to use this one. The struggles! Hey, but at least I started :) .

**Link to work:** [Build my app](https://github.com/bverhoeve/build-my-app)

## Day 1: March 28, 2020
**Today's Progress**: Read a [re-introduction to JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/A_re-introduction_to_JavaScript) on MDN to rediscover how JavaScript works, and new quirks that were added since ES6. Worked through the [React tutorial](https://reactjs.org/tutorial/tutorial.html#why-immutability-is-important) to teach myself React by doing. It went well, and React seems like a decent framework as it was quite fun to work with and made sense all the way. I'll use React for the frontend of the app.

**Link to work**: No code was written for `build-my-app` today :(

## Day 2: March 29, 2020
**Today's Progress**: Started the boilerplate for the frontend of `build-my-app` using Create React. I added React-Bootstrap to my application as well to have some better visuals. I want to include a bootstrap theme to give the website a little bit more charm. So, the rest of my time went to looking at possible Bootstrap themes. One that I liked in particular is the [Lazy kit](https://technext.github.io/lazy-kit), which I'm probably going to use. I still need to add it in to the application though.

**Link to work:** [Build my app](https://github.com/bverhoeve/build-my-app)

## Day 3: March 31, 2020
**Today's Progress**: I successfully added the [Lazy kit](https://technext.github.io/lazy-kit) to the application! Then I wrestled a bit with React Router to figure out how to add my own home page. But in the end, I managed to create a new default route to my own page and redirect the Lazy kit routes to other URLs.

**Thoughts**: I feel a bit guilty about skipping on yesterday. I started out for a couple of minutes, but then a friend called and I forgot about coding until it was too late to get started even. I do feel that I made quite a bit more progress today than I did the previous days. Although the `build-my-app` is still in boilerplate mode, more and more of the foundations are being laid to work further on.

**Link to work**: [Build my app](https://github.com/bverhoeve/build-my-app)

## Day 4: April 1, 2020
**Today's Progress**: Added a logo for Build My App. I added a navigation bar to the homepage. The layout isn't that nice yet but I'll fix it in the coming days.

**Thoughts**: I only started working on the application late in the evening but I still managed to get some stuff done.

## Day 5: April 8, 2020
**Today's Progress**: I started working on a smaller project and put Build My App on hold for now. The reason for this is that the smaller project is in the context of aiding people in need for COVID-19, which I do find important. The project I started is called `viper`, where I'll implement a Battlesnake in order to compete in the Battlesnake competition for the Food Banks in Canada (https://play.battlesnake.com/)

**Thoughts**: It has been a while that I've continued coding. I underestimated starting to work full time and still being able to commit to the challenge. I'll try again with the Battlesnake initiative!

**Link to work**: [viper](https://github.com/bverhoeve/viper)

## Day 6: April 12, 2020
**Today's Progress**: Continued work on my Battlesnake. I've successfully deployed the app to the Heroku platform, which was challenging! I also started working on the API, but realized I'll need to test the app as well, so I've started working on testing with `pytest`.

**Thoughts**: I quite underestimated how rusty coding has become for me. I am a bit overwhelmed by all the things I once again need to learn, but I'll get there.

**Link to work**: [viper](https://github.com/bverhoeve/viper)

## Day 7: April 13, 2020
**Today's Progress**: I continued to work on the Battlesnake. I started to work together with a friend on the app. The Battlesnake now has a functioning API and can play games against the Battlesnake engine. Next to that, the engine can now also run locally allowing to simulate games.

**Thoughts**: Today I started working on the Battlesnake together with a friend, which was a very good idea! We actually coded a lot longer than one hour, in fact it was the better part of the afternoon. It was fun to feed of each others energy, and we both could bring knowledge to the table.

**Link to work**: [viper](https://github.com/bverhoeve/viper)

## Day 8: April 18, 2020
**Today's Progress**: Worked on my own on the Battlesnake. Implemented a basic collision detection algorithm that identifies the possible directions a snake can go in without dying.

**Thoughts**: It feels good to work on something.

**Link to work**: [viper](https://github.com/bverhoeve/viper)

## Day 9: April 19, 2020
**Today's Progress**: Worked on the Battlesnake with [sanderdewilde](https://github.com/sanderdewilde) We fixed an issue in production and added an algorithm that finds food based on the Euclidian distance.

**Thoughts**: After deploying our snake and entering it into the global arena, it actually performed quite well! I'm happy to see the progress and I'm excited to see what will happen on game day.

**Link to work**: [viper](https://github.com/bverhoeve/viper)

## Day 10: May 8, 2020
**Today's Progress**: I've started a new side project called 'wolk' It'll be a website that will help me more easily compare virtual machines across cloud providers, since this is an issue that I often have during my day job.

**Thoughts**: I feel a bit bad to continue on day 10, given that it has been so long that I've actually progressed with the 100 days of code. After the Battlesnake competition, I wasn't really motivated on working on the build my app project anymore
and I didn't feel like starting a new project. The other project just had a bit too large of a scope, so I've trimmed it down quite a bit with `wolk`. I hope by doing this that I can stick with the challenge better!

**Link to work**: [wolk](https://github.com/bverhoeve/wolk)

## Day 11: May 9, 2020
**Today's Progress**: Didn't have a lot of time, so I've just added bootstrap and a button linking back to my Github repository to the website.

**Thoughts**: I'm hungry!

**Link to work**: [wolk](https://github.com/bverhoeve/wolk)

## Day 12: May 12, 2020
**Today's Progress**: I've made the top of the website a bit prettier, adding a navigation bar to the three main pages and the Github button.

**Thoughts**: I've decided to get up a little bit earlier than other days, so I could start the day with a 'quick win' by working on the site for about an hour. It feels pretty good having created something before my workday even started!

**Link to work**: [wolk](https://github.com/bverhoeve/wolk)

## Day 13: May 14, 2020
**Today's Progress**: I've started to work on the main table of the homepage using Bootstrap 4 tables and a for loop in Jinja2. I've also restructured the codebase a bit to make it easier once the app starts to become larger.

**Thoughts**: Implementing a basic table with Flask and Bootstrap was actually a lot easier than I thought!

**Link to work**: [wolk](https://github.com/bverhoeve/wolk) [wolk app](https://wolk.herokuapp.com/)

## Day 14: May 17, 2020
**Today's Progress**: Added a second page to the website and reworked the web app so pages can inherit from the base page that contains the navigation bar.

**Thoughts**: I struggled a bit with a fairly simple bug on which I spent a good amount of time on. In the end, I was looking way too far since it was just a simple routing issue.

**Link to work**: [wolk](https://github.com/bverhoeve/wolk) [wolk app](https://wolk.herokuapp.com/)

## Day 15: May 19, 2020
**Today's Progress**: Scraped and stored the data for the AWS EC2 instances from EC2Instances.info. Also added a coming soon message to my other pages.

**Thoughts**: I coded a fair bit longer than other days, because I couldn't really quit when solving an issue. I should time myself a bit better if I'm to continue this coding marathon.

**Link to work**: [wolk](https://github.com/bverhoeve/wolk) [wolk app](https://wolk.herokuapp.com/)

## Day 16: May 23, 2020
**Today's Progress**: Fixed the navbar height issue, added all the columns for the AWS page.

**Thoughts**: I ran into a couple of issues today. First off, the data on the Github repository of EC2.instances.info app apparently hasn't been updated in 5 months, leaving me to suspect that they store their data elsewhere. This also implies that I can't use the data from that repository, as it isn't up to date. This means that I'll have to scrape the data myself. Luckily, the repository is open source, so I should be able to use the code as a starter. Furthermore, I discovered that storing data on the ephemeral storage of Heroku is apparently not that straightforward nor practical. With the Heroku dynos being Docker images, persisting data is a bad idea anyways, so I'll have to store the data elsewhere. Since I need AWS credentials for the scraping anyways, I'll probably store the data in an S3 bucket, since it's cheap/free anyways. Making production apps is a lot harder than I thought!

**Link to work**: [wolk](https://github.com/bverhoeve/wolk) [wolk app](https://wolk.herokuapp.com/)

## Day 17: May 24, 2020
**Today's Progress**: The site now gets up to date data from the S3 bucket `www.ec2instances.info`. Scraped data can also be uploaded to my own S3 bucket now

**Thoughts**: I am feeling a bit frustrated today, as I haven't added a lot of code, and the code that I did add, looks like shit. At least I'm still working on the app.

**Link to work**: [wolk](https://github.com/bverhoeve/wolk) [wolk app](https://wolk.herokuapp.com/)

## Day 18: May 26, 2020
**Today's Progress**: Moved the app to the eu region and created a nightly job to load in the data. Wanted to work on the local caching, but that's apparently not working.

**Thoughts**: At first, coding went well. Then I ran into a very frustrating issue with the AWS `boto3` library that I can't seem to figure out yet.

**Link to work**: [wolk](https://github.com/bverhoeve/wolk) [wolk app](https://wolk.herokuapp.com/)

## Day 19: May 30, 2020
**Today's Progress**: Fixed the download from AWS S3.

**Thoughts**:

**Link to work**: [wolk](https://github.com/bverhoeve/wolk) [wolk app](https://wolk.herokuapp.com/)

## Day 20: May 31, 2020
**Today's Progress**: Added a landing page and started presenting the data on the AWS page.

**Thoughts**: I coded a lot longer today than I usually do, but I made good progress on the site.

**Link to work**: [wolk](https://github.com/bverhoeve/wolk) [wolk app](https://wolk.herokuapp.com/)

## Day 21: June 1, 2020
**Today's Progress**: Added all the price data to the AWS page using Jinja2 macros. Added a `region` argument to the HTTP request on the AWS page that
selects the region for which data is to be presented.

**Thoughts**: This is a lot more work than I thought it would be.

**Link to work**: [wolk](https://github.com/bverhoeve/wolk) [wolk app](https://wolk.herokuapp.com/)

