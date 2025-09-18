# Gitflow instructions

## Main  
The main branch should be mostly untouched, hotfixes can go through to make for a better
progress without upsetting future releases. Stable releases only can move on to the main
branch after careful testing  

## Gitflow structure  
 - Develop branch set up to house most of the working code
 - Features branch set up up from Develop branch, this is where most of the major features will be made
 - Releases branch set up from the Develop branch, this is for the larger releases
 - Hotfixes branch set up from main to quickly push through small errors in text and code

### What is gitflow?
Gitflow is an alternative Git branching model that involves the use of feature branches and multiple primary branches. It was first published and made popular by Vincent Driessen at nvie. Compared to trunk-based development, Gitflow has numerous, longer-lived branches and larger commits. Under this model, developers create a feature branch and delay merging it to the main trunk branch until the feature is complete. These long-lived feature branches require more collaboration to merge and have a higher risk of deviating from the trunk branch. They can also introduce conflicting updates.

source: https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow