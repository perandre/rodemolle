# Quick prototyping using Bootstrap + Jekyll
## Install stuff
1. Install Xcode from the Mac App Store, then go to Preferences and download Command Line Tools (if haven't done it already).
2. Install Jekyll: `$ gem install jekyll`

## Grab the code
Clone this repo: `$ git clone git@github.com:front/proto.git`

## Do stuff
1. Go to your project in the Terminal and start Jekyll `$ jekyll --server --auto`
2. Duplicate a post in the /_posts/ folder, and give it a name according to the pattern: [date]-[url].html
3. In Your Favorite Browser, go to localhost:4000/
4. Yay!

## Misc
- To edit the master page, hack away at /_layout/default.html
- In /_posts/ you can use both .html and .markdown files. You do however need to start the file with a YAML header (see existing files)
