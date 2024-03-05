# Bootcamp Challenge 01 - HTML, CSS and Git: Code Refactor

On-the-job ticket challenge to refactor starter code for a mock-marketing agency website.

## Description

Horeiseon marketing agency have requested their website be refactored to meet current accessibility standards so that:

1. People with disabilities can access the site using assistive technologies, and
2. The site can rank higher on Google and other search engines

The [User Story](#user-story) and [Acceptance Criteria](#acceptance-criteria) are below.

I describe the process for completing the challenge and my learnings in the [Process & Learnings](#process-learnings) section.

(just learned how to do a Markdown anchor :raised_hands: & emoji syntax too! :raised_hands:).


<a id="user-story"></a>
## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```


<a id="acceptance-criteria"></a>
## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```
<a id="process-learnings"></a>
## Process and Learnings

In Week 1 of Bootcamp one of our learnings was Git, including how to initialise local repositories. Challenge files were already pulled (git pull) from our coursework repo on Gitlab. The files include starting assets (images & CSS) and an index.html. I created my README.md file locally too.

1. Create local directory
```
mkdir ~/bootcamp/challenges/01-html-css-git-code-refactor/
```

2. Copy challenge files to new directory + create new README (this one)
```
cp assets -R ~/bootcamp/challenges/01-html-css-git-code-refactor/
cp index.html ~/bootcamp/challenges/01-html-css-git-code-refactor/
touch README.md
```

3. Initialise local Git repo
```
git init
```
Not to mention using the following pretty much after every git command:
```
git status
```
Which in this case outputs:

![git status screenshot with untracked files](./assets/images/git-status-untracked.png "git status example")

(just learned how to add an image to a markdown file :raised_hands:)

4. Add untracked files to staging for the next commit
```
git add README.md index.html assets/
```

5. Then commit changes to the local repo
```
git commit -m "initial commit"
```

6. 