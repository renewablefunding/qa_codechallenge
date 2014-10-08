Renewable Funding: QA Automation Challenge
=======================

Hi there!  We're ecstatic that you're interested in working for Renewable Funding's QA team.  To get a better idea of your current automation skills, we'd like for you to complete a code challenge - build automation according to a set of requirements.  The actual requirements are listed further down, but here are the general tech requirements:

1. Write your code in Ruby.
1. Make sure your app is runnable on Mac OS X or Linux.
1. Do not require any for-pay software.
1. Include instructions for setting up and running your application.

Feel free to email me at [kiisu@renewfund.com](kiisu@renewfund.com) if you have any questions.

## Submission Instructions

1. Clone this repository.
1. Create (and switch to) a new branch in your local repository:

  ```bash
  % git checkout -b new-branch-name
  ```

1. Complete the project as described below within your local repository.
1. Create patches from your commits, and place them in a directory:

  ```bash
  % git format-patch master -o submission_patches
  ```

1. Create a .zip file with the contents of the patches directory:

  ```bash
  % zip -r submission_patches.zip submission_patches
  ```

1. Email the .zip file to [kiisu@renewfund.com](kiisu@renewfund.com), and put the position you are applying for in the email's subject.

If you have any questions about this submission process, feel free to email me.

#### Why can't I just fork, and submit a pull request?

Unfortunately, Github no longer allows you to fork a public repo and make it private, so your submission would be visible to the entire world.  We'd love to keep this fair and not give the last responders a possible unfair advantage (since they'd be able to see all prior submissions); hence the patch method.

## Project Description

Imagine that Renewable Funding has just acquired a new company, that provides walking directions and we want to compare our walking directions to directions provided by Google.  We may at some point want to compare different starting and ending points so we need automation to obtain this data reliably.  Your automation script should enter a starting address (400 SW 6th Ave #902, Portland, OR 97204), obtain the walking directions to an ending address and output them into a standard csv file.

Here are the automation requirements.

1. The automation must run via the UI within a browser, as future requirements may include a screenshot.
1. Your solution must output the data into a csv file `directions_data.csv` with details for each step on one line.

#### Bonus options:

If you're feeling inspired, bonus points for:

* allowing for data driven tests pulling addresses from an external file.  (csv, or yml)
* obtain a screenshot of the map with the route for a "future requirement".

## Evaluation

Reviewers will assess your familiarity with standard libraries, and with object-oriented programming.

1. Did your automation fulfill the basic requirements?
1. Did you document the method for setting up and running your automation?
1. Did you follow the instructions for submission?
