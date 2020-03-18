# Giving and Receiving Code Review
You wrote the code! Well, some code. Now you’d like for someone else to look at it and see if it could be better. Or, alternately, someone else wrote code and needs your help. This process is called code review. Here, we’ll look at what code review is, why developers use it, and how it works. 

## What is code review, and why do people use it?  
First things first! 

What code review generally is:
Presenting clean, properly-formatted, polished block of code for feedback on a specific question, usually in regard to code quality, readability, correctness, or security.
Reading and offering clear feedback on someone else’s code.

What it generally isn’t: 
Sharing an early draft of unformatted code, and/or asking reviewers to check for *anything* wrong with it.
Sharing a final *project* and asking for feedback on the project itself (instead of a piece of the underlying code).
Rewriting or marking up someone else’s code outside of their specific request.

Many resources on code review are specific to a particular coding language or to a work environment. See if you can identify the common principles in the overview articles below.  

* **Article:** [Code Review Best Practices](https://medium.com/palantir/code-review-best-practices-19e02780015f)

This post is a high level overview of why Palantir does code reviews, how to prepare code for review, and how to perform code reviews, as well as examples of a few different types of fixes. It’s a good intro to the topic as a whole.  

* **Article:** [A quick guide to peer code review](https://www.netguru.com/blog/a-quick-guide-to-peer-code-review)

This article outlines Netguru’s code review flow and highlights the tool that they use. Again, note the common principles with other companies and tools, and don’t feel obligated to use the tool this post mentions. 

* **Article:** [Code Review: Why It’s Important](https://wishdesk.com/blog/why-code-review-important)

This article covers why businesses and organizations like to conduct code review and peer review of code. To be clear, including this piece here is not an official endorsement of the product by Codecademy.

Finally, we refer you to this list from the [Wikipedia article on code review](https://en.wikipedia.org/wiki/Code_review) for this helpful list of purposes for code review. 

* *Better code quality*  – improve internal code quality and maintainability (readability, uniformity, understandability)
* *Finding defects*  – improve quality regarding external aspects, especially correctness, but also find performance problems, security vulnerabilities, injected malware, etc.
* *Learning/Knowledge transfer*  – help in transferring knowledge about the codebase, solution approaches, expectations regarding quality, etc; both to the reviewers as well as to the author
* *Increase sense of mutual responsibility*  – increase a sense of collective code ownership and solidarity
* *Finding better solutions*  – generate ideas for new and better solutions and ideas that transcend the specific code at hand.
* *Complying to QA guidelines*  – Code reviews are mandatory in some contexts, e.g., air traffic software


## How to review code
As with almost everything you learn with us, process is an important part of this … process. In order to maximize both the reviewer’s time and the efficacy of the review itself, there are several guidelines to follow in reviewing code. We’re presenting this section before the “asking for code review” section because we think that grasping what the reviewer will be doing and looking for will help you prepare your own code for review and better understand what to ask for. 

Start with [this Codecademy video](https://www.youtube.com/watch?v=TlXy_i27N3w&feature=youtu.be) on how to review others’ code, and then take a look at the articles below.   

* **Article:** [How to Do Code Review](https://google.github.io/eng-practices/review/reviewer/)

This is a well-organized, comprehensive look at code review best practices. Not surprising, since it comes from Google’s Engineering team! We recommend reviewing this article now and consulting it again later on to make sure you’re still on track with the principles of conducting code review.

* **Article:** [Best Practices for Peer Code Review](https://smartbear.com/learn/code-review/best-practices-for-peer-code-review/)

A practical, tactical guide to reviewing code. Once you’ve reviewed the principles above, this guide will help you outline how you actually _do_ the review, with tips on everything from how many lines of code to review at a time to building a positive peer review culture. As a bonus, there’s a link at the bottom of the page to a webinar on the “Best Kept Secrets of Code Review.” 

* **Article:** [How To Quickly And Effectively Read Other People’s Code](https://selftaughtcoders.com/how-to-quickly-and-effectively-read-other-peoples-code/)

This also falls into the “tactical guide” category of resources, as one developer walks you through his method of efficiently reviewing others’ code. 

* **Article:** [How To Comment Your Code Like A Pro](https://www.elegantthemes.com/blog/wordpress/how-to-comment-your-code-like-a-pro-best-practices-and-good-habits)

How to write your comments on the code that you are reviewing is an important skill, and this article provides great examples of what to do (and some advice on how to deal with naysayers).

* **Article:** [Mastering Issues](https://guides.github.com/features/issues/)

The "issues" feature in GitHub is incredibly useful for providing feedback on certain parts of a code base.

## Asking for code review
Ah! This is what you’ve been waiting for! How to get your own code reviewed! 

Following the guidelines of [the code review section](https://www.reddit.com/r/learnprogramming/wiki/index#wiki_asking_for_a_code_review) of the /learnprogramming reddit FAQ is a good place to start. Its do’s and don’ts can be applied almost anywhere that you ask for help, especially if you ask in a public forum. There are online communities where you can ask for code review, but as you can imagine, they most often respond to people whose code and request come across as prepared and mindful of the reviewer’s time. Again, we've found that the most pertinent advice here is to be specific with what you want to be reviewed – don't just send over your entire site and repo and ask for general feedback, point people to smaller parts of your work or isolatable things that you're trying to accomplish.  After all, code review in the workplace doesn't involve reviewing code for an entire project, they're split up in smaller, digestable chunks like pull requests.

On that note, with a multi-person project you can create a [Pull Request](https://youtu.be/HW0RPaJqm4g) on Github and ask for review there. Note that you’ll create a Pull Request to ask a specific person to review your code on Github.  You can also post your code for strangers to review on [Reddit](https://www.reddit.com/r/learnprogramming/), provided you follow the guidelines above. You or ask on the Stack Exchange [forum](https://codereview.stackexchange.com/) specifically created for code review. Of course, you've also got the [Premium community on Slack](https://codecademypremium.slack.com/)!  Something particularly useful may be to spend a portion of your [pair-programming](https://github.com/codecademy-coaches/premium-supplemental-repo/blob/master/group-coding-how-to/pair-programming-guide.md) time performing and practicing code review on one-another's projects before jumping into a challenge or even pairing through a problem that you have (or have discovered) with your project material.  Finally, you've got your mentor time, but again be extra mindful of being efficient with the time as your mentor only has so much time to be able to spend with you (whether it's a 1-on-1 booked conversation or particularly during group office hours on Slack).  If you're asking your mentor for code review, be sure to flag it well in advance, by bringing it up in a meeting that you'd like code review next time, and then filling out your learner journal.  Your mentor always reads your learner journal while prepping for your meeting and this will give them a head-start with reviewing.

If you’re a beginner, we’d recommend sticking to the above locations at first. If you’re a more experienced coder who already has been active on Stack Overflow, that may also be a good place to ask for a review.


## Finally, some tools for code review
These lists are by no means exhaustive, but if you’d like to familiarize yourself with some of the tools that developers use for code reviews, you can find some [here](https://codegeekz.com/15-best-code-review-tools-for-developers/), [here](https://github.com/marketplace/category/code-review), and [here](https://en.wikipedia.org/wiki/List_of_tools_for_code_review)! 
