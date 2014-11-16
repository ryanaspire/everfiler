Everfiler
=========

A bash script to automate the filing of documents to Evernote via email including Mac OS X tags.

## General Notes
- I'm a scripting novice. This is the result of **days** of googling + trial and error.
- Designed to be used with Hazel (http://www.noodlesoft.com/hazel.php) and/or Apple's Automator
- Mutt is used to send from Gmail to avoid ISP issues with port 25
- Credit to James Berry for Tag utility (https://github.com/jdberry)


## Installation
- Install Tag (https://github.com/jdberry/tag) (I use Homebrew)
- Install Mutt mail client (http://www.mutt.org/)
- Open the script and edit the following:
  - The Notebook you'd like the document to be filed to
  - Your private Evernote email address
  - Your Pushover credentials (optional)


## Help Wanted
- I'm having trouble running this as a Shell script from Hazel. When I run it as an Automator script via Hazel, it works. More details to come
- My home ISP blocks port 25 so [mail] doesn't work. Setting up Mutt is a pain. Would love to find a simpler solution
- Currently the Pusherover notification fires a success notification unconditionally. Would be great to have a success/error notification. 
