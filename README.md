## Curriculum Vitae

My name is Tuan. I'm a developer. I'm a blogger, too.

Why do I want to be a developer? Doing everything manually is kind of boring, so I figured out what if I can automate them. That's the reason why I became a developer.

Why do I want to be a blogger? Because I want to be self-assertion. Write my experience down, help me and everyone wanting to learning not to repreat my mistakes.

### Personal information

- Name: Tuan Nguyen
- Birthday: 1993-08-07
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

### Experience

#### Isentia (March 2018 - Now)

**Position:** Fullstack Developer, DevOps

**Responsibility:** I'm a lead of Crawler Team. We buit a platform allow listen all reponse from user on almost chanels such as: Social (Facebook, Youtube, ...), Forum, News, ... To serve a hundred million requests per days, store a gigabyte data per hour, we use some techniques

- Elasticsearch: We store almost data on this engine. With ability to scale up data per day, just begin with a minimum equipment, with flexible format (JSON), we could sovle our problem - store terabytes of data, distributed search and analytics data (message of user)
- MongoDB: We need a hidden layer to store config and data before push to Elasticsearch
- Docker: One environment for development, testing and production. We can serve a platform run on NodeJS v0.12.x and v8.x on one server. And we can scale apps up with a file - docker-compose.yml
- Nginx: A reverse proxy. Serve HTML site, React application and load balancing
- CI/CD tools: I use CI/CD tool on Gitlab to auto build new package and put it to npm.com

The best thing I had been did is upgrade old platform from Node v.12.x to v8.x. I changed many things to make sure our platform is working with new policy from our chanels. This is a way I did it

- Learned a bussiness logic by deploy and runing it on real server
- Write TDD test case by the logic I learned above and implement it
- Cleanup the unit test and code I wrote
- Repeat these steps over, over and over until no more code to upgrade
