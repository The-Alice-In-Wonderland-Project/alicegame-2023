Note: Updated Tuesday, October 03, 2023.
## Welcome to Wonderland!

👍🎉 First off, thanks for taking the time to be part of The Alice in Wonderland Project! 🎉👍

### About The Alice in Wonderland Project

A better way to learn GitHub

The Alice in Wonderland Project seeks to do the seemingly impossible - give new developers real world experience being part of a remote software development team before they have a software development job.

It also gives developers with work experience the opportunity to level up their leadership skills by being co-team leads (maintainers) for groups of up to 6 new devs.

---
## How to Get Involved

To keep things organized there's an application process. The current form will be linked from our project website at: [https://www.aliceproject.dev](https://www.aliceproject.dev) Applications from groups underrepresented in software development are strongly encouraged to apply!

Teams are organized geographically, and the number of teams depends on several factors including how many team leads are available. 

Devs who are accepted into the project will get an email and/or discord message from  the founder and/or one or both of their team leads.

---
## Getting Started

### Co-Team Leads/ Maintainers

Team leads/maintainers will have access to a private discord server. An invitation will be sent via email or Discord DM. Instructions will be shared in our private discord server.

### New Devs/ Contributors

Once you've been contacted and accepted into this year's project follow these steps to get set up. Depending on your team and your previous experience, one or both of your team leads may walk you through this process.

1. Fork the repo into your own GitHub account
2. Make sure you have a folder set up on your computer as a place for this project
3. Open VS Code
4. In VS Code: clone the GitHub repo from the url (web address) of the fork in your account.
5. Save it in the project folder on your computer.

---
## Environment

You will need three applications on your computer:

1. [VS Code](https://code.visualstudio.com/): Used to write code
2. At least one browser. 
	1. [Firefox Developer edition](https://www.mozilla.org/en-CA/firefox/developer/) and/or 
	2. [Google Chrome](https://www.google.com/intl/en_ca/chrome/) are recommended
3. [Obsidian](https://obsidian.md/) Used to write markdown including documentation. While you can write markdown in VS Code, it's a much better experience using an application designed for documentation. It's also another skill to add to your resume.

### VS Code Extensions

There are some VS Code extensions that will be very handy for completing this project. Here's a list of some. This list will be added to by maintainers.

1. [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
2. [Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)
3. [ES Lint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
4. [Rainbow Brackets](https://marketplace.visualstudio.com/items?itemName=2gua.rainbow-brackets)

### Browser Dev Tools

content to be added

### Obsidian

Obsidian docs and help are online here: [https://help.obsidian.md/Home](https://help.obsidian.md/Home)

---
## Branches

Contributors create branches using the project's branch naming convention (see below) in VS Code on their computer. This is then pushed to GitHub and a pull request (PR) is done to merge their changes from their branch to the project's dev branch.

#### Branch Naming Convention

- One issue per branch. 
- Issues are assigned. 
- Issues have numbers up to 9999. 
- Leading zeros are kept. e.g. issue 10 is numbered i0010
- All contributors have issue numbers in their branch names.
- At times maintainers, especially the founder will not have an issue number in her branch names. Instead ixxxx will be used.

branches are named the following way:

dev-yyyy-mm-dd-i0001-ABCDE-usergithubname

##### Example of naming a branch

- A developer with the user name of adalovelace 
- Has been assigned issue 42
- This issue adds a button. The short name is addbtn
- The date is 2025-12-10: December 10, 2025.
- She names her branch:
dev-2025-12-10-i0042-AddBtn-adalovelace

ABCDE  is a short name for the issue.

A maintainer who's doing administration and organization may name a branch like this:
dev-2023-10-03-ixxxx-ORG-gingerkiwi

### Main vs Master Naming

We use the modern naming of "main" for our main (production) branch, and not the older term "master". This [blog post on Tech Target](https://www.theserverside.com/feature/Why-GitHub-renamed-its-master-branch-to-main)explains why the change occurred.

### Dev and Main Branches

The site https://alicegame.app is set up with CI/CD (Continuous Integration/Continuous Deployment) and deploys automatically when the main branch is updated.

All PRs are merged into the dev branch. At least twice a week the dev branch is merged into main and project contributors and maintainers can see their code updates go live! We're doing it this way to both control potential costs, and also to simulate real world production and development branches.

---
## Pull Requests

### Your First PR

Your first PR will be to follow the instructions in the issue assigned to you. You will have to copy a block of text from Alice's Adventures in Wonderland on Gutenberg.org and paste them properly formatted into your cloned copy of Book-Alices-Adventures-in-Wonderland.md in Obsidian on your computer.

We do this because:
1. It's a low stakes way of getting new devs used to: 
	1. writing branch names, 
	2. writing markdown, 
	3. using Obsidian, 
	4. using git locally, 
	5. pushing up to GitHub, 
	6. creating a PR.
2. Having a copy of the book is a great resource for our project! (It's not just a "make work" PR)

---


