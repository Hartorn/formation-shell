# Creating a new formation

## Create Github repository
To create a new formation, first, create a public github repository

Then, clone it locally

## Initialize the formation
Simply run the following commands

``` bash
sudo apt update && sudo apt install -y wget unzip
wget https://github.com/hakimel/reveal.js/archive/master.zip && unzip -o master.zip -d . && rm -rf master.zip reveal.js-master/css  reveal.js-master/js reveal.js-master/test reveal.js-master/examples reveal.js-master/.github
rm -rf docs/ && mv reveal.js-master/ docs/
```

This will create the base formation template
Then, add, commit and push all the files

## Host it online

To host and setup online, go to settings on your repo, to Pages category.
Activate it on branch main, for folder docs, and Save it