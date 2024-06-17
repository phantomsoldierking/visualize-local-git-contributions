Run go install and

gogitlocalstats -add /path/to/folder will scan that folder and its subdirectories for repositories to scan
gogitlocalstats -email your@email.com will generate a CLI stats graph representing the last 6 months of activity for the passed email. You can configure the default in main.go, so you can run gogitlocalstats without parameters.
Being able to pass an email as param makes it possible to scan repos for collaborators activity as well.

reference
-https://gist.github.com/flaviocopes/bf2f982ee8f2ae3f455b06c7b2b03695

-https://github.com/codecrafters-io/build-your-own-x  
