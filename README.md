# Greenwood-library-website
Adding book reviews and updating events page on the greenwood community library website.

## Cloning a repository and working with branches in Git.

> Create a repository names 'greenwood-library-website' and clone.

![cloning](./img/1.%20Cloning.png)

> The website aims to be more engaging and informtive for visitors. I am creating files in my main branch to aid this, they are ;

- home.html

- about_us.html

- events.html

- contact_us.html

![files](./img/2.%20Create%20Files.png)

> Contents have been added to each file, files need to be staged, but first we will check the status of the file with command `git status`.

![status](./img/3%20check%20status.png)

> Files have not been staged yet, to stage file command `git add` plus each file name was used.

![](./img/4.%20staging.png)

> All files have been staged

![staged](./img/5.%20all%20files%20staged.png)

> To commit chnages, command `git commit -m "This is my first commit` was used.

![commit](./img/6.%20Commit.png)

> To push main branch to git hub command `git push origin main` was used.

![push](./img/7.%20push.png)

## Adding contributors and their work to website.

> The team has decided to add a **Book Reviews** and update the **Events** page to feature upcoming community events. To create a branch for the frist contibutor (morgan), command `git checkout -b add_book_reviews` was used.

![add_book_reviews](./img/8.%20Add%20branch%20for%20morgan.png)

> Morgan has created her file *book_reviews.html* and added contents to it, this file now needs to be staged with command `git add book_review.html`

![stage book review](./img/10.%20stage%20add%20book%20review.png)

>Commit changes using command `git commit -m "add-book-reviews`

![Commit](./img/11.%20commit%20add%20book%20review.png)

> Push add-book-reviews branch to github with command `git push origin main`.

![push](./img/12.%20push%20add%20book%20review.png)

> Raise a pull request and merge megan's work to main.

![PR merge](./img/13.%20pull%20and%20merge%20add%20book%20review.png)

> Jamie, the second contributor is working on updating the event feature on the website. A new branch called 'update-events' will be created and the latest chanages from the main branch will be pulled using `git pull origin main`  .

>To create a new branch, we must first go to the main branch using `git checkout main` command, to create new branch `git checkout -b update-events`. 

![update event](./img/14.%20create%20add%20event%20branch%20and%20pull%20main.png)

>Jamie has created his file *update_event.html* and added contents to it, this file now needs to be staged with command `git add update_event.html`.

![stage](./img/15.%20cretae%20update%20event%20file%20and%20stage.png)

>Commit changes using command `git commit -m "Add book reviews section`. Push changes using command `git push origin update-events`.

![commit](./img/16.%20Commit%20and%20push%20update%20events.png)

> Raise a pull request and merge Jamie's work to main.