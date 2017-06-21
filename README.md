# Adelie Git Project 
## Phase One: Basics
1. Go to the [Issues page for the project](https://github.com/adelieco/biographies/issues) and find the Issue number for you.
2. Clone the repository:
```
git clone git@github.com:adelieco/biographies.git
```
4. Check out a new branch like so:
  - `git checkout -b feature/add-kevin-bio`
5. While on the branch above, add a file to the `src` folder as per the convention: `src/yourfirstname-yourlastname.md`.  If either your first or last name has special characters like an apostrophe (like `O'Malley`)  or a hyphen (like `Robert Lee-Jones`), omit the character.
6. In the folder, write a paragraph of 3-5 sentences with the following information. (#2 and #3 can be in whatever order, but start with #1).
  - Quick description of you
  - Fun fact
  - Current goal as a developer.
7. For example, you might write:
  - Kevin is a Front-End Developer at Nulab NYC. He is currently studying machine learning and the AWS platform. He has a fat cat named Bernie and secretly really enjoys fidget spinners.
8. Add a high-quality photo of yourself to the `/assets` folder, as `yourfirstname.jpg`. Crop it to the shape of a square (if you don't, I will at my own discretion). If you really don't want a photo of yourself on the Adelie site later, then you can omit this step, but please share a photo if you can!
9. Add your changes to the stage.
```bash
# Adds all your files to the stage
git add -A
```
10. Commit your change with a descriptive message
```bash
# Make sure your commit message includes your issue number
git commit -m "#1 Added personal bio for Kevin Oh"

# More detailed syntax might be something like this:
git commit -m "#1 Added Kevin's bio

* Added kevin-o.bio.md
* Edited some other thing 
* Did some other junk
```
11. Push your changes to the repository.
```bash
git push origin name_of_your_branch

# For me, my branch name from earlier was feature/add-kevin-bio, so:
git push origin feature/add-kevin-bio
```
12. Tag Kevin on the `#projects` channel of the Adelie Slack and let him know that you’ve done your task. His ID is:`@adelie-ko`.

## Phase Two: Pull Requests (PR)
1. Do not start this Phase until everyone is on the same page. On Github, create a “Pull Request” to merge your feature branch into the `development` branch.
2. Assign it to the dev below you in the chart at the bottom of this document. (If you’re at the bottom, do the first person).
3. You will get a PR assigned to you. 

## Phase Three: Review
1. Review the PR that has been assigned to you.
2. (THIS SET OF INSTRUCTIONS IS DELIBERATELY LEFT INCOMPLETE. KEVIN WILL LET YOU KNOW WHAT TO DO LATER.)


#adelie

---

# Project Roster

Developer|Phase One| Phase 2|Phase 3|
----|---|---|
Kevin Oh|
Irma Mesa|
Matthew Sweeney|
Diomedes Lajara|
George Escobar|
Ivan Prunier|
Adam Akers|
Drew Hill|
Mary Chapman|
Seth Jones|
Marce Mar|
Maryellen M|