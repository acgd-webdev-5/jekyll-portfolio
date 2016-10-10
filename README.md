---
summary: 'Move the interactive wireframes for you portfolio website to Jekyll and start building out the pages.'
time: '4 hours'
deliverables: 'Jekyll website files'
---

# Jekyll portfolio

## Overview

- Set up your portfolio website to use Jekyll—making the `_config.yml` file.
- Create a default layout that contains the header and footer of your website—and anything else common like the navigation.
  *(I know this doesn’t totally make sense for single-page websites, but it’s still good practice.)*
- Start breaking apart your interactive wireframes to reduce code duplication as much as possible.
- Populate the website with all your portfolio pieces—it’s okay to have fake images still.

### For single-page websites

- Make a loop to generate all the portfolio pieces onto your page.
- You could get the data for the loop from `_data`, `_posts` or maybe even collections.

### For multi-page websites

- Create HTML files for each portfolio piece—use the layout to add the header and footer.
- Figure out a way to reduce the duplication of code for each portfolio piece: includes, nested layouts, etc.

**Ideally there should be no code duplication.** But if you’re doing lots of custom case-studies (like you should be) there will definitely be some duplication.

---

## Hand in

Show teacher for marks during next class.

Continue to add commits to your `portfolio` repo—and make sure the website works on GitHub at portfolio URL:

```
https://username.github.io/portfolio/
```
