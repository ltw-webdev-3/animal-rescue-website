---
summary: 'Re-design an animal rescue website by applying everything learned this term.'
time: '10 hour'
deliverables: '3 HTML files, 4 CSS files, images'
---

# Animal rescue website

## Overview

- *Fork this repository.*
- Completely re-design an animal rescue website that you find online that’s not currently designed very well.
  <br>Here are some examples of local rescues whose websites could use an update:
  - [Birch Haven](http://www.birchhaven.org/)
  - [Loyal Rescue](http://www.loyalrescue.com/)
- Create a 3-page website: Home, List of Available Rescues & Adopt a Rescue
- *It should have real text content*—**that you have written yourself.**
- It should be completely designed, with real images, real colours—and it should look amazing.
- **Don’t steal images**—[use properly licensed images](https://cg.algonquindesign.ca/topics/stock.html). If the image requires that you credit the author use a [`humans.txt`](https://learn-the-web.algonquindesign.ca/topics/search-engine-optimization/#humanstxt) file. ([See an example `humans.txt` file](https://github.com/acgd-webdev-3/modularity-mindfulness/blob/gh-pages/humans.txt)).
- Don’t start writing code without first doing everything as expected in your IxD class: target audience analysis, website goals, competitive analysis, sitemap, wireframes, etc.
- *The website should obviously be fully responsive: working on screensizes from `320px` all the way to `~2500px`.*
- *Run it through Markbot and make sure it passes all the checks.*

---

## Details

We are only concentrating on making these 3 pages—**but the navigation should absolutely suggest the rest of the pages exist on the website.**

### `index.html` — Homepage

The homepage of the rescue website should accomplish the goals for the target audience you’ve researched when doing your UX.

- Consider the goals of the website.
- Consider the responsiveness.
- Consider your performance budget.
- Consider accessibility concerns.

### `rescues.html` — List of Available Rescues

The Rescues page is the page that lists all the available animals, giving details about each animal and photos of what they look like.

- You don’t need to go overboard listing an excessive number of animals, just show ~5 examples, giving the idea of what the completed page would look like.
- Consider the responsiveness.
- Consider your performance budget.
- Consider accessibility concerns.

### `adopt.html` — Adopt a Rescue

The Adopt page is the *huge* form that users fill out to adopt a rescue animal. Look at some examples like [Loyal Rescue](http://loyalrescue.com/application.php).

- You don’t have to do every single form field, but it should be a significant enough amount to represent what the form would look like upon completion.
- Consider the responsiveness.
- Consider your performance budget.
- Consider accessibility concerns.

---

## Deliverables

There are a few different things that will be checked throughout the process:

1. [Animal rescue website UX](https://learn-the-web.algonquindesign.ca/courses/web-dev-3/week-13/#animal-rescue-website-ux)
  <br>— **Due week 13**
  <br>(checked for completion, graded with final website)
2. [Animal rescue website check-in](https://learn-the-web.algonquindesign.ca/courses/web-dev-3/week-14/#animal-rescue-website-check-in)
  <br>— **Due week 14**
  <br>(checked for completion)
3. [Request for grade](https://learn-the-web.algonquindesign.ca/courses/web-dev-3/week-15/#request-for-grade)
  <br>— **Due week 15**
4. [Final animal rescue website redesign](https://learn-the-web.algonquindesign.ca/courses/web-dev-3/week-15/#animal-rescue-website)
  <br>— **Due week 15**

---

## Teacher’s expectations

This website is to prove that you—by yourself—can do everything we covered in class. Look back over all the assignments from the term, determine what kernel of knowledge they were trying to teach you, and see if you can implement it in this website.

There should be a significant example of everything we’ve learned this term in this website. **Leave the impression that you’ve confident with what we’ve learned and can apply everything.**

---

## Markbot’s expectations

Markbot has a bunch of expectations on the code of your website. *But luckily for you **no** screenshot checking.*

### General expectations

- Proper naming conventions are followed
- Minimum 10 commits that follow best practices

### All HTML files

Name the HTML files: `index.html`, `rescues.html` & `adopt.html`

- `header`, `header nav`, `header nav li`, `header nav a`, `main`, `section` or `article`
- `modules.css`, `grid.css`, `type.css`, `main.css`
  And many of the expected classes: `.grid`, `.unit`, `.xs-`, `.s-`, `.m-`, `.l-`, `.pad-`, `.push`, `.gutter`, `.list-group`, *font size classes*
  *Remember to choose only the modules that are necessary*
- A `color` or `background-color` hover state on the navigation
- A unique `<title>` & `<h1>` for everything HTML page
- Proper focus states for navigation and main content links
- Fits within the [standard performance budget](https://learn-the-web.algonquindesign.ca/topics/performance-checklist/)
- Passes all [accessibility checks](https://learn-the-web.algonquindesign.ca/topics/accessibility-checklist/) including skip links and ARIA landmark roles
- *Google Fonts are optional—you may decided they have too much of a performance impact.*

### CSS files

- CSS requirements are really open—just make sure the CSS is valid & indented properly.

### Images

- All images should be smushed, with a maximum file size of `250kB` and maximum dimensions of `2500px`
- Proper favicons, `favicon.ico` & `favicon-196.png`

---

## Browser & accessibility testing

In class, week 15, we will be doing lots of peer testing—most of the website needs to be complete by then.

Each person will be assigned a tool and will be required to test everybody’s websites.

- [Accessibility testing](https://learn-the-web.algonquindesign.ca/courses/web-dev-2/accessibility-testing/)
- [Browser testing](https://learn-the-web.algonquindesign.ca/courses/web-dev-1/browser-testing/)

---

## Marking rubric

Below is the rubric of expectations for this project. **You will be assigned a letter grade based on your standing within the rubric.**

| | 0 points | 1 points | 2 points | 3 points |
| --- | --- | --- | --- | --- |
| **Knowledge** | Poor understanding of material | Partial understanding of material | Demonstrates full understanding of material | Demonstrates excellent understanding of material |
| **Professionalism** | Poorly done, rushed, incomplete | A good start but needs much more effort & time | Well done, but could use more refinement | I would steal this and use it myself |
| **UX** | Incomplete or missing | Rushed & too generic | Specific but obviously lacking research | Specific and appropriate, with good details |
| **Wireframes** | Incomplete or missing | Missing important pieces or poorly executed | Complete but not detailed enough | Complete, detailed, and a good representation to code from |
| **Responsiveness** | Not responsive | Works on some screens | Responsive but with lots of awkwardness | Looks great on all screen sizes |
| **Semantics** | Very little HTML | Basic HTML tags chosen | Good variety and appropriate HTML tags chosen | Excellent demonstration of HTML tags and correct use |
| **Design** | Very little design | Basic design implemented | Cohesive design implementation | Excellent design implementation |
| **Modularity** | Modular CSS not used | Some basic modular CSS used | Lots of modular CSS | Modular CSS used to its full potential |
| **Accessibility** | Not accessibile | Some accessibility but doesn’t work well with certain situations | Some minor accessibility problems | Works really well under all the standard accessibility tests |
| **Performance** | Doesn’t come close to passing the performance budget requirements | One or two performance budget requirements are not met | Just passes the performance budget requirements | Surpasses the performance budget requirements |
| **Forms** | No form | Non-functioning form | Functional but ugly form | Good looking and functional form |
| **Home page** | Missing or incomplete | Started but severely lacking | Complete but with poor text or bad responsiveness—not quite perfect | Complete, amazing content, responsive, designed well—amazing |
| **Rescues page** | Missing or incomplete | Started but severely lacking | Complete but with poor text or bad responsiveness—not quite perfect | Complete, amazing content, responsive, logical—fantastic |
| **Adopt page** | Missing or incomplete | Started but severely lacking | Complete but with poor text or bad responsiveness—not quite perfect | Complete, amazing content, responsive, good use of forms—super |
| **Code quality** | Missing or incomplete | Poorly done, rushed, no semantics, bad accessibility | Decent: semantics, indentation & accessibility | Perfect: semantics, indentation & accessibility |
| **Git & commits** | Bad commit messages | Decent messages | Good messages | Excellent and descriptive commit messages |
| **Markbot** | Not handed in with Markbot | — | — | Handed in with Markbot |

---

## Hand in

Drop this folder into your Markbot application. Make sure to fix all the errors. And submit for grades using Markbot.

**When you submit to Progressinator, you’ll see a grey checkmark that shows the project was handed in.** You’ll still have to write a *Request for Grade* and the teacher will still be grading it personally.
