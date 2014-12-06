# SSD S5 Presentation Template

Use this template to make more S5 presentations.  Use this README to describe your presentation when you're done.

This is an S5 presentation.  There is a printer-friendly version.

## How To Make a New SSD Presentation
1. Become a SSD member.
1. Teach a class or hold an event, such as a Meetup event.
1. Download this repository as a Zip.
1. Edit your presentation.
1. The HTML source code shows how to make more slides.  Just copy the Slide <div> as many times as you need and edit.  You don't need the notes, and sound is disabled here by default.
1. Besides adding styles, avoid messing with the S5 CSS.  Try to stick to the presentation constraints.  If that won't work then then next best option is to force printer friendly with the 'defaultView' setting in slides.js.  If that isn't acceptable then Free says, "You'll need to know your CSS - I have a prototype that scrolls and has a TOC, ask me about it".

When you're done editing, upload your repo to the SSD Github as a Github Pages website.  Here's how:

1. Become a member of SSD
1. Get access to the SSD Github repo
1. Create a new Github repo.
1. Now, almost follow the steps to init an _existing_ repo as provided on Github.com, except:
1. git init .
1. git checkout -b gh-pages
1. create/edit README.MD
1. git add .
1. git commit -m "first commit"
1. git push origin gh-pages

To get the URL of your presentation go to the Github repo's settings -- the 'gear' icon/button on the Github.com right-side toolbar.

## Contribute
S5 is one of the original single page applications (SPA) for the web.  Code for the web often stops working on modern browsers after 10+ years, but S5 still works.  The day S5 stops working is the day browsers no longer support CSS2.  Other SPA frameworks can do the same and more than S5 (in fact, they are descendants of S5) but trade power for elegance, SEO, and accessibility.  S5 could use some CSS3 updates, more themes are usually welcome, and features like embedded maps, movies, or SVG would be cool -- there are ways to do these tasks in S5-style.  The theme here is scala_utf, how about modifying it for the SSD brand?