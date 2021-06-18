# Readme file for this bookdown 

Instructions
To know if you have git or not

Go to terminal, type "git" (without quotation).
If you don't have git, download and install it
Go to your github profile, settings, navigate to SSH/GPG keys, give it title and enter RSA Key (generate this key from Rstudio, under tools>global options> Git/SVN> create RSA Key, view the public key and copy it to github account and paste there). Save the SSH keys
Start RStudio>New project>Version control> paste the cloned url Edit index, bookdown, output

then render the book,


### Render the book

 1. Install bookdown with install.packages("bookdown"). If you already have it, update to the [latest version](https://CRAN.R-project.org/package=bookdown).

 2. Render locally with bookdown::render_book("index.Rmd").

 3. Use browseURL("docs/index.html") to view your book locally (or just open index.html in a browser).

 4. If it looks good, commit and push all changed files to GitHub.

(You will need to repeat steps 2 and 4 every time you wish to update the book online.)

git commit git push -u origin master git push -f origin master (force changes to the server with the local repo)

To get back to the github repo, use the code : usethis::browse_github()

Some helpful resources while building this book - 

1. https://github.com/jtr13/bookdown-template
2. You may consult the official guide to bookdown: https://bookdown.org/yihui/bookdown
