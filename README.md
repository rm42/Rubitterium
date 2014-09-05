A very simple ruby script that can post to twitter.

Installation/Guide/Whatever:

$ sudo apt-get install ruby
$ gem install bundler

clone repo
cd into it

$ bundle update

Go to https://apps.twitter.com/
Create an app. Name, website, etc doesnt really matter
Go to Permissions, set to Read And Write
Go to API Keys and generate API Keys, copy key/secret into consumerKey/consumerSecret in config.yml
Generate Access Token, copy token/token secret into accessKey/accessSecret in config.yml

You're all ready to go.

$ bundle exec ruby rubitterium "My Tweet Goes Here"

