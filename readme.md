# Readme file for this bookdown 

Instructions

To know if you have git or not

Go to terminal, type "git" (without quotation).
If you don't have git, download and install it
Go to your github profile, settings, navigate to SSH/GPG keys, give it title and enter RSA Key (generate this key from Rstudio, under tools>global options> Git/SVN> create RSA Key, view the public key and copy it to github account and paste there). Save the SSH keys

Now, 

1. Download this template
2. Set your github settings and page.
3. Clone the repo code
4. Load your Rstudio, create a new project> Version control> paste the cloned url
3. Edit the _bookdown, _output, and index and save them.
4. Once you're done editing, then render the book,

## How to create bookdown without using template

1. Create a repository on github, clone it and repeat number 4 under instructions (opening Rstudio)
2. Create README.md file in RStudio and edit. Add index.Rmd, create and edit _bookdown.yml and _output.yml in RStudio
3. To add more chapters , create empty R Markdown and save it accordingly. N.B- Index is the 1st chapter.

Once you're done, render the book, commit and push to github and voila- you're done.

### Render the book

 1. Install bookdown with install.packages("bookdown"). If you already have it, update to the [latest version](https://CRAN.R-project.org/package=bookdown).

 2. Render locally with bookdown::render_book("index.Rmd").

 3. Use browseURL("docs/index.html") to view your book locally (or just open index.html in a browser).

 4. If it looks good, commit and push all changed files to GitHub.

(You will need to repeat steps 2 and 4 every time you wish to update the book online.)


## If you're using the terminal command
git commit git push -u origin master git push -f origin master (force changes to the server with the local repo)

To get back to the github repo, use the code : usethis::browse_github().


PS: If you use my template here, I will appreciate if you acknowledge it when building your book. You could write a line or two, such as - This book was developed using the template [available here version](https://github.com/drhammed/bookdown_workshop)


Some helpful resources while building this book - 

1. https://github.com/jtr13/bookdown-template
2. You may consult the official guide to bookdown: https://bookdown.org/yihui/bookdown
