#  😷 Remote startup handbook - COVID-19 edition 

Hello everyone 👋 

In this hard time we hope everyone is safe.

This is a small guide we wrote at Shieldfy to manage our work during the COVID-19 virus outbreak. We thought to opensource the guide it may benefit any other company.

> Note: This guide is far from complete, it's just some tips and tricks we learned, so feel free to contribute and improve this guide.

## Table of contents

* [Founders guide](#-founders-guide)
* [Team leader guide](#-team-leaders-guide)
* [Developer guide](#-developers-guide)
* [Tools & Services](#-tools--services)


## 👨‍💻 Founders guide

As a founder, it's very scary to imagine how the entire team can collaborate completely remotely. 
It's not an easy task but it's achievable, here are some tips for you.

1. **Embrace the pros more than the cons.**
   
    It's very important for your team to feel that you are on board with the idea of being work remotely. 
    This will give them the feeling that you trust them and gives them a sense of responsibility.


2. **Re-organize your goals & KPIs**.
   
    You have to rewrite your goals to be fit in short periods.

    You must be very sharp on what you need to accomplish. It needs to be specifically measured with numbers (KPI).

    Also, it's very important to communicate these numbers and KPIs with your team, they must understand how their work contributes to company growth.

    `Tools used:` [Trello](https://trello.com)

3. **Your employees are your real capital, don't lose them**.

    I know it's a hard time, You may have to cut your costs to extend your runway. 

    The obvious choice will be layoff employees. Believe me, that is the most terrible choice you will have to make.

    This will harm your employees in these hard times, and make the remaining employees feel insecure and feels betrayed by you. Their bond with each other is much stronger than your bond with them.

    > Stand with your employees not against them.

    Instead, you can cut your costs from other resources (office, online/offline services .. etc). Also, you can communicate with your employees to reduce their salaries in this period instead of letting some of them go and they will be rewarded later.


4. **Be transparent.**

    Transparency in this specific time is needed more than ever. Your team already knows that we are facing a hard time. So communicate with them, explain your plan and company situation. Ask for their help and they will respond, It's their company too.

## 👨‍💻 Team leaders guide

1. **Communicate, communicate and communicate.**

    Communication is the key, You have to communicate regularly with your team ( at least 2 times a day ). This will keep you sync with your team, who's working on what.

    It depends on your methodology, but you can start the day with a standup meeting, and you can have a 1:1 catchup call with your team and ending the day with a quick recap.

    > important note: Keep the meeting short (10-15 min) unless you have a good reason to make it long. 

    `Tools used:` [Google Meet](https://meet.google.com), [Slack](https://slack.com)


2. **Understand the anatomy of working at home.**

    Working from home is boring, distracting. You have to understand that to give your team reasonable tasks to finish.

    Perfect tasks are the one that well written short stories

    Don't calculate the working time as a bulk. No one will set down for 6-8 hours straight even at the office. 

    Instead, define a time ( 1-2 hours) that all the team should be online together and the rest of the day make it flexible for them. 

    Express to your team that it's ok if the kids' sounds appear in the meetings. Don't push your team members to be angry ( Family always first ).

3. **More carrots, less stick.**

    It's very normal to see a drop in  productivity, especially in the first week or two. Please don't rush and punish your team for that. 

    Instead, try to award them for good work. It's always paid off to show them how you appreciate their hard work.

    `Tools used:` [Slack](https://slack.com), phone, be creative 😉 .

4. **Automate everything.**

    As said before, the productivity is dropped. and human errors will be much higher. So to maintain the quality of your product, you must automate everything that can be automated.

    Automate your code review: You can use tools like `code linters` and services like `Sonarqube` and `Shieldfy` to automate the code review for you. This helps you to identify problems fast and improve your workflow.

    Automate your deployment: If you don't have that yet, please do it fast. Make it Push to deploy for your test, development or staging environment. Allow developers to deploy their code without getting back to you.

    `Tools used:` [Github actions](https://github.com/features/actions), [Sonarqube](http://sonarqube.org/), [Shieldfy](https://shieldfy.io)


5. **Create developer handbook**

    Create a handbook and describe all the processes of the development, QA and deployment.
    Try to describe everything in steps. This allows developers to act fast without asking you about everything.

    `Tools used:`  [Github](https://github.com), Markdown


## 👨‍💻 Developers guide

1. **You are not at home, you are at work inside your home.**

    The first thing to do is to define a corner at your home and set up your disk, chair, and PC. 

    It's important to make it organized and looks like a professional desk like you what have at work.

    > Don't ever make your default work from bed or couch

    Tell your family that you are at work and you need to focus. And reward them later with quality fun time with them, they deserve it.

2. **Communicate, communicate and communicate.**

    Communicate with your team leader and your fellow developers regularly.

    `Tools used:` [Google Meet](https://meet.google.com), [Slack](https://slack.com)


3. **Divide your time, but still be connected.**

    Don't imagine that you will spend 6-8 hours on your PC, this is home at the end. Instead, be realistic and take a break with your family (ex: 15 min every 2-3 hours). 

    But don't turn the notification off during these short breaks. Always be connected.


## 🔧 Tools & Services

> note: we didn't list everything here, there is a lot of tools in the market, we just listed the tools we used and one or more similar product.

> In communications: we are using `Zoom`, `Google meet`, `Slack`, `Clubhouse`, `Trello` and `Loom`.

> In technical automation: we are using `Github`, `Github action`, `Shieldfy`, `SonarQube`, `Sentry`.

1. Visual Communication (Meetings)
    - [Zoom](https://zoom.us)
    - [Google Meet](https://meet.google.com)
2. All-day communication
    - [Slack](https://slack.com)
3. Task management
    - [Jira](https://www.atlassian.com/software/jira)
    - [Clubhouse](https://clubhouse.com) 
    - [Asana](https://asana.com)
    - [Trello](https://trello.com) 
4. Visual Feedback 
    - [Loom](https://loom.com) 
5. Source Code management
    - [Github](https://github.com) 
    - [Gitlab](https://gitlab.com)
    - [Bitbucket](https://bitbucket.org)
6. CI/CD
    - [Github Actions](https://github.com/features/action) 
    - [CircleCI](https://circleci.com) 
7. Code review
    - linters 
    - [Code Climate](https://codeclimate.com)
    - [Codacy](https://codacy.com)
    - [SonarQube](http://sonarqube.org)
7. Security review
    - [Shieldfy](https://shieldfy.io) 
    - [Snyk](https://snyk.io)
9. Code coverage
    - CLI based code coverage 
    - [Codecov](https://codecov.io)
    - [Coveralls](http://coveralls.io)
10. Error tracking
    - [Sentry](https://sentry.io) 
    - [Rollbar](http://rollbar.com)


## 🤝 Contributing

Contributions, issues, and feature requests are welcome.
You can open Issue first to have your suggestion discussed before you create a PR.


## 🙏 Stay Home, Stay Safe