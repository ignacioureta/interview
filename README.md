# Welcome

Welcome to the Dealsyte Visit. we hope you're having a great time.

# Your Task

This is the code challenge and it is intended to do it in peer programming, 10m each side. This repo is going to guide you through the process. Each time you complete a commit from this repo, proceed to the next.

## First task

Setup a public React repo that you can share with us at the end.

## Second task

The repo should be able to read a list of Questions and it's answers. The questions, answers and users that should be used are attached in their respective files.

## Third task

We changed the styles of the Question and answer, and now we have to render the date and who did the last change in the question. the events are as follows: creation, edition, publish, submission, closing, in that order. We also updated the answers and questions jsons AND the mockup

## Fourth task

Add a select at the top of the page with all the users. When you select a user, you're "logged in" as that user. I've added the `organization` attribute to the `users`. If the organization of the logged in user doesn't match the one from the user that did an action, you should render the organization name instead of the user name in that question/answer

## Fifth task

Add comments to the system. They should have the same behaviour as the Q&As, but they always display the createdAt attribute. Comments should only be visible for the users of the same organization as the creator.

## Sixth task

Add tests to all the previous.

Note: We're not testing speed, but quality of the code and the use of good practices.
