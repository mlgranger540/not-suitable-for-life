# Not Suitable for Life Blog

Not Suitable for Life is a personal blog where I can share my thoughts and experiences around navigating a world where everything just is not designed for people like you. By which I mean, people with anxiety, introverts, highly sensitive people, people with any form of neurodivergence... When the world expects everyone to be everything you are not, it's a constant struggle just to make it through each day without having all the energy drained out of you.

This blog hopes to both allow me the space and freedom to write about these things, because writing is often the best way for me to process and deal with my feelings - as well as hopefully offering a sense of companionship and compassion to anyone else who, like me, finds the world to be a too loud, too much, too difficult place. Perhaps even helping other lost souls to figure out why they have always felt out of step with the world. But also, hopefully, shining light on the perspective that it's not us that is wrong, it's just that the world isn't set up to accommodate people like us. And maybe that's something that needs to change.

## Design

I visualised a couple different possible designs for the homepage using wireframes to help make a decision on the look of the site.

<img alt="Home Wireframe V1" src="./readme-images/home-wireframe-v1.png" width="50%"><img alt="Home Wireframe V2" src="./readme-images/home-wireframe-v2.png" width="50%">

I'm still somewhat torn but leaning more towards version 2. Though I'm planning to add some decoration to the corners of the page, as I like the minimalist mostly white design but also don't want to have too much blank space.

## Features

### Recent

The homepage of the blog is the Recent page, which will display the most recently posted entries, newest first.

### All Posts

The second page will contain all the entries posted to the blog, displayed in a compact way to make navigating easier (probably title, date and brief description).

There will ideally be a way to either filter entries or sort by categories/tags in order to find posts on particular topics, or show entries in a given time frame etc.

### Stats

Then of course I will have to have a stats page, because I'm a nerd and obsessed with stats ;P That could include number of entries, word counts, list of categories/tags with number of entries posted in each - both overall and in a given time frame.

### About

Finally, an about page which will just be a brief overview of me and the blog.

Maybe that could include contact information too. But I may need to set up a new email for that, unless I just use one of my normal ones.

### Features to Add

It would be nice eventually to have a way for visitors to create an account, so that they could respond to blog posts with some form of like feature and leave comments, maybe bookmark their favourite articles etc.

A calendar feature would be nice as well, to get an overview of how many entries were posted in each month/year etc.

Probably a contact form too so people can easily send in questions/messages/articles they'd like to see etc.

Also eventually it would be good to have a 'sign up for updates' feature where people could then get emails when I post.

## Content Management System

[Prismic](https://prismic.io/), a headless content management system, is used to create, manage and publish the blog posts to the site. In Prismic I have defined a Blog Post repeatable type which includes an ID number, title, content, date created and tags. I enter this information for each blog post in Prismic where it is saved and stored. Once published, this data is then converted into JSON to be accessible in my code, and then displayed as HTML on my webpages.

## Deployment

The site is hosted on [Google Firebase](https://firebase.google.com/). The live site can be found [here](https://not-suitable-for-life.web.app/) or [here](https://not-suitable-for-life.firebaseapp.com/).

## Technologies

### Languages

- HTML5
- CSS3

### Frameworks, Libraries, Programs, External Stylesheets etc

- [Git](https://git-scm.com/) for version control
- [GitHub](https://github.com/) to store the project repository and back up git commits
- [Bootstrap v5.3](https://getbootstrap.com/docs/5.3/getting-started/introduction/) to assist in the structure and design of the site
- [Prismic Headless CMS](https://prismic.io/) to manage my blog content
- [Google Fonts](https://fonts.google.com/) for the blog title and date fonts
- [Justinmind](https://www.justinmind.com/) to create the wireframes

## Known Bugs

None... so far ;)

## Credits

### Code

[This stackoverflow post](https://stackoverflow.com/questions/24749399/centering-an-hr-tag) helped with centering my hr tag.

[This post](https://stackoverflow.com/questions/1643320/get-month-name-from-date/18648314#18648314) helped to format my dates with the full month name, and [this one](https://www.w3resource.com/javascript-exercises/javascript-date-exercise-23.php) helped with adding ordinal suffixes to the day number.

[This one](https://stackoverflow.com/questions/4820230/display-multiple-spaces-in-html) helped with adding multiple white spaces to HTML.

### Content and Media

All written content on the website was created by myself.

The Google Font [Patrick Hand](https://fonts.google.com/specimen/Patrick+Hand) was used for the title, and [Diphylleia](https://fonts.google.com/specimen/Diphylleia) for the blog entry dates.
