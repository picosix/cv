## Curriculum Vitae

My name is Tuan. I'm a developer. I'm a blogger, too.

Why do I want to be a developer? Doing everything manually is kind of boring, so I figured out what if I can automate them. That's the reason why I became a developer.

Why do I want to be a blogger? Because I want to be self-assertion. Write my experience down, help me and everyone wanting to learning not to repreat my mistakes.

### PDF

If you are looking for my CV on PDF format, you can find it at [[Tuan Nguyen] - Backend Developer](./%5BTuan%20Nguyen%5D%20-%20Backend%20Developer.pdf)

### Personal information

- Name: Tuan Nguyen
- Birthday: 1993
- Mail: tuan.nguyen930708(at)gmail.com
- Skype: tuan.nguyen930708(at)hotmail.com
- Curriculum Vitae: [Curriculum Vitae](https://picosix.github.io/cv/)
- Github: [Picosix](https://github.com/picosix)
- Blog: [Node++](http://nodeplusplus.com/)
- LinkedIn: [Tuan Nguyen](https://www.linkedin.com/in/tuan-nguyen-p6/)

### Mindset

Before doing anything, I'm always think about how user interact with my application. How does my application solve their problem, make their job more interesting and make they feel comfortable. In short, **think for user** is the key of successful.

### Highlight

- 2+ experience on position `Full stack developer`
- Backend - NodeJS
- Frontend- ReactJS
- GraphQL
- Docker ([Personal hub](https://hub.docker.com/u/picosix/) with NodeJS, Nginx images)
- Create clean code or make code to be clean
- Write unit test (TDD)

### Projects

#### 2018

- [Node++](https://nodeplusplus.com/vi/)

#### 2017

- [Amazon Seller Toolbox](https://amzsellertoolbox.com/index.html)
- [Hilton - Sertahospitality](https://hilton.sertahospitality.com/index.html)
- [Serta](https://serta.com/)

#### 2016

- [Mangvieclam](https://mangvieclam.com/)

#### 2015

- [Xehoiviet](https://xehoiviet.com/)

### Experience

#### Isentia.boomerang (March 2018 - Now)

**Position:** Fullstack Developer, DevOps

**Responsibility:** I'm a lead of Crawler Team. We buit a platform allow listen all reponse from user on almost chanels such as: Social (Facebook, Youtube, ...), Forum, News, ... To serve a hundred million requests per days, store a gigabyte data per hour, we use some techniques

- Elasticsearch: We store almost data on this engine. With ability to scale up data per day, just begin with a minimum equipment, with flexible format (JSON), we could sovle our problem - store terabytes of data, distributed search and analytics data (message of user)
- MongoDB: We need a hidden layer to store config and data before push to Elasticsearch
- Docker: One environment for development, testing and production. We can serve a platform run on NodeJS v0.12.x and v8.x on one server. And we can scale apps up with a file - docker-compose.yml
- Nginx: A reverse proxy. Serve HTML site, React application and load balancing
- CI/CD tools: I use CI/CD tool on Gitlab to auto build new package and put it to npm.com

A best thing I had been did is upgraded old platform from Node v.12.x to v8.x. I changed many things to make sure our platform is working with new policy from our chanels. This is a way I did it

- Learned a bussiness logic by deploy and runing it on real server
- Write TDD test case by the logic I learned above and implement it
- Cleanup the unit test and code I wrote
- Repeat these steps over, over and over until no more code to upgrade

#### Tagrem Corp (September 2016 - March 2018)

**Position:** Fullstack Developer

**Responsibility:** I'm maintain a ecommerce and a CRM platform to server our client - Serta.com, hilton.sertahospitality.com, ...

A best thing I had been did is worked with small team to create a Automatic Escalation System. The purpose of this project is to automatically create an escalation (ticket) from an email sent by a customer and assign it to right staff. We used Yii Framework, FlightJS and VueJS in this project.

My main responsibilities is:

- Help teammates configure webpack base on manager's requirements. I had to make it reuseable to the next project.
- Build components by VueJS (Alert, Form Validation).
- Learn about CRM system of Indition platform.

Finished that project, we processed more than 100 email a week to help generate more than 30 escalations.

#### Caribe Tech (October 2015 - July 2016)

**Position:** Fullstack Developer

**Responsibility:** I'm maintain a marketplace platform with a small team.

A best thing I had been did is released our beta version on time in time with techniques

- Elasticsearch for our search function, autosuggest and autocomplete keywords
- Redis to cache information of logged user, static data, ...
