# Assignment 2

For the final project in this class you will be building a website that models which women will present with late stage breast cancer.  That site will have many "tabs" that show different things.  For example, there will be a tab that describes the data, another tab will have a logistic regression model, another will have a summary of a kNN analysis, another will show a CART model, etc.  This assignment asks you to build the content that will go into the descriptive page.  

You will be working gently modified REAL data from a live project run by an surgical oncologist, [Dr. Goel](https://doctors.umiamihealth.org/provider/Neha+Goel/764301), who is collaborating with Ray and Layla.  For this assignment, you can collaborate with others in the class (and your instructors and Dr. Goel).  Keep in mind that you will be able to show this work to potential employers and because this is on GitHub they will be able see what **you** (vs. your collaborators) did and when you did the work.  Do not procrastinate.... it will look bad if they see all your commits piling up in the 3 hours before the steps were due.

Throughout all the assignments you will see instructions like "Modify the .gitingore file to include a data directory".  That means do that step, save, stage, commit and push the file.

## Tasks
### Setup the project
0. Figure out who you want on your team for the rest of the final project.
1. AS A TEAM...Build a private repo on GitHub.  Include a README and an R .gitignore file. Make sure all team members are collaborators on repo.
1. Invite Ray and Layla to be collaborators.
1. Clone the repository to your local machine.

### Deal with data
1. Make a data directory in the local repository.
1. Modify the .gitignore to include that data directory.
1. Look on GitHub and confirm that the .gitignore file was updated.

### Add the data
1. Download the data from Blackboard and put it into the data directory.

### Describe the data
1. Download the draft tables.
1. Identify which variables are missing from the dataset
1. Make an R Markdown document called Summary.Rmd.
1. Add a section that lists the variables that are missing.
1. Use the table 1 package to approximate table 1 and table 2.
1. Make a pretty plot showing the age at diagnosis by the 3 race groups.
