![CF](https://i.imgur.com/7v5ASc8.png)  Lab 05: New Article Creation
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
<!-- the learning objectives from the corresponding class number -->
* Recap the primary concepts discussed throughout the week.
    * Ask the students "What have you learned so far?"
    * Ask "What has been challenging?"
    * Ask "What has been helpful?"
* Work through a form-based inputs to build out a JSON string export of a new blog article.
* Implement 3rd party library integration for dynamic code highlighting and markdown creation.

---

## Resources  
<!-- a list of links if any are necessary for the assignment-->
[HighlightJS Docs](https://highlightjs.org/)
[MarkedJS Docs](https://github.com/chjj/marked)

---

## Feature Tasks  
<!-- a list or description of the feature tasks you want the students to implement -->
1. We have two new libraries that we'll be working with today; highlight.js and marked.js
1. Focusing on the functionality of adding a new article through a form submission, complete the TODOs in articleView.js.
  * The body field of your form should be able to accept formatting via Markdown syntax, including code blocks and snippets.
1. *Reminder: use template literals rather than string concatenation where applicable*

## Stretch Goals

- We will not do anything with the tab navigation on **new.html** in the workshop; if you want, get this navigation working as either show/hide like we did on the **index.html** page, or have it work with an anchor tag that will scroll down to the preview when that is selected.
- Rather than simply making copy-paste JSON readily available, have the new articles created with the form populate into the rawData array when the "Publish" box is clicked. Think carefully about how to make this user-friendly; it might require rethinking or refactoring how the "Publish" box works, or perhaps adding another button.

---

## Rubric  
<!-- a list of grading requirements with associated points, scaling to 10pts possible -->
Criteria | Pts
---|---
Meets all Assignment Reqs | 6
Uses idiomatic code style | 3
Follows proper Git workflow | 1
**Total** | **10**

<!-- links -->
