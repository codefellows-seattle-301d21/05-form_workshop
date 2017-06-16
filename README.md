![CF](https://i.imgur.com/7v5ASc8.png)  Workshop/Lab 05: New Article Creation
=======
[Code of Conduct](https://github.com/codefellows/code-of-conduct)

## Submission Instructions
When you are finished with lab, follow these steps to submit your work. Create one Pull Request (aka: "PR") from your Forked repo to the CF repo with your changes, and you'll each submit that same PR link in Canvas.

1. Ensure that all your local changes are committed, and pushed to your origin repo.
1. Visit the origin repo on github.com, and ensure that all of your completed work has been merged to master via Pull Requests within your repo.
1. Create a new PR from your Fork to the CF repo and ensure the branches look correct.
1. Fill in the template based on the text box prompts:
  1. Write a good descriptive summary of your changes:
    1. Be sure to include how much time you spent on it, and who you worked with.
    1. Briefly reflect on and summarize your process.
1. When you create the PR, it will have a unique URL. Copy this link, share with your partner, and paste it into the assignment submission form in Canvas. Both the driver and the navigator will submit the same PR link.
---

## Learning Objectives
* Recap the primary concepts discussed throughout the week.
    * Ask the students "What have you learned so far?"
    * Ask "What has been challenging?"
    * Ask "What has been helpful?"
* Build out a form to provide both a preview *and* a JSON string export of a new blog article.
* Implement 3rd party library integration for dynamic code highlighting and markdown creation.

---

## Resources  
[HighlightJS Docs](https://highlightjs.org/)
[MarkedJS Docs](https://github.com/chjj/marked)

---

## Feature Tasks  
1. Focus on the functionality of adding a new article through a form submission by completing the TODOs in articleView.js.
1. Review the image `preview.png` in the lab directory to get an idea of what we will be building.
1. We now have two pages in our blog app, each of which need different initialization. There is a skeleton of a method in articleView.js to get this started for the new page; be sure to examine how this is now being done for the index page.
1. The new page with the form will need event handling and a template. Where should these pieces go in the code?
1. The new page should not display any other articles; how to manage this?
1. The new page with the form should provide a JSON string which can be copy/pasted into the data file to add articles to the blog.
1. *Reminder: use template literals rather than string concatenation where applicable*

#### Stretch Goals
1. We have two new libraries that we can add: HighlightJS (provides syntax highlighting of code blocks) and MarkedJS (allows use of Markdown format text). Link to (or include) these two libraries and implement them.

---

## Rubric  
Criteria | Pts
---|---
Meets all Assignment Reqs | 6
Uses idiomatic code style | 3
Follows proper Git workflow | 1
**Total** | **10**
