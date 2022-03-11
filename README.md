# Draft and prototyping CMS for Code for Tucson
## Description

Working out the kinks to make NetlifyCMS friendly enough to use for this specific site. Design to be changed later.
Planning on re-building with Wordpress if time permits as the CMS functions are more robust, but speed and hosting are more of a challenge.

## Usage Guide
A collection can be added to a page by selecing "Has Collection List" then specifying a tag to use to populate the collection.

By default Projects are given the "project" tag and blog posts are given the "post" tag. Additional tags can be added during creation.

Posts or projects given the "highlight" tag will be placed on the homepage.

## Todo
- [x] Format navbar
- [x] Add logo and hero to homepage
- [x] Create feature collection and add it to homepage
- [x] Get Projects page to mimic blog but using the projects collection instead
- [x] Figure out why hero does not show on other pages
- [x] Get projects summary on homepage by pulling it from an existing page
- [x] Finish combining post/project/feature lists .njk files into collectionList.njk
- [ ] Make hero modular by adding to its own component
- [ ] Delete remaining content and add content from existing page
- [ ] Validate that all no links are broken
- [ ] Fix mobile styles and add styles to support larger screens
    - [ ] Add .js to make hero and features scroll
- [ ] Test page and post creation and build todo for CMS

# Eleventy Netlify Boilerplate

### Click the button below to try it out!

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/danurbanowicz/eleventy-netlify-boilerplate&stack=cms)