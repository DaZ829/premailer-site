### What is this?
For the best HTML e-mail delivery results, CSS should be inline. This is a huge pain and a simple newsletter becomes un-managable very quickly. This script is our solution.  
CSS styles are converted to inline style attributes Checks style and link[rel=stylesheet] tags and preserves existing inline attributes 

Relative paths are converted to absolute paths Checks links in href, src and CSS url('') 

CSS properties are checked against e-mail client capabilities Based on the Email Standards Project’s guides A plain text version is created 

A few things to note:  
Things can get messy very quickly with the * selector—be careful 
Only the screen, handheld and all media types are processed

### Premailer web interface

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

For local development, copy `.env.sample` to `.env` and update with your S3 credentials.

```
bundle install
bundle exec rackup
```

If you begin hosting a web version please let me know so I can link you from the
original Premailer site.  code [at] dunae [dot] ca.
