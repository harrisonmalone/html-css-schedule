## HTML and CSS

### Tuesday (12/03)

Morning challenge 
- Building upon what you learnt with Figma, try to get a high score on this design challenge game
- [Can't Unsee](https://cantunsee.space/)
- What are some websites that you think have great design? List 5 of them out
- Using the developer tools built into your browser of choice (i recommend firefox) inspect the source code, what html tags do they use?

10 - 11.15
- Aaron doing unit on how internet works
- HTTP requests 
- Protocols

11.30 - 12
- Harrison taking HTML fundamentals 
- Reiterate from this point on you'll always need HTML, you might think that this content is easier BUT it's so incredibly useful, people are hired as HTML/CSS experts
- Break down second part of morning challenge, developer tools, looking at inspector 
- The cornerstones of the world wide web
- HTML CSS and JavaScript
- HTML = structure / content
- CSS = layout / style
- JavaScript = behavior / make website dynamic
- JavaScript can be front end or back end (with Node), don't worry about JavaScript for now, let's get good at writing clean HTML and CSS for the next week and a half
- Live server VSCode extension
- Using my website as an example of basic HTML, very minimal CSS going on, lets try to build it, we want you to be able to write clean HTML so it works well together with your CSS
- HTML files and how that creates a URL, localhost replaced with whatever I have as a domain name, directories and how that works with HTML files
- Shortcut in VSCode with ! + tab, what this generates
- Talk about the head vs body, refer to `head.html`
- [Halt and catch fire](https://www.youtube.com/watch?v=mi_fKu9WTAE)

12 - 3 (lunch break 1 - 2)
- Harrison talking about HTML elements
- Developing my website [harrisonmalone.com](http://harrisonmalone.com)
- HTML5 vs older HTML
- HTML5 introduced things like `<nav>` and `<footer>`, these are the two most important ones, can use other stuff but no real need to unless there's a use case (svg, html media)
- I'm happy for you to `<div>` it up

3 - 5
- Challenge on Canvas (under HTML basics)
- For those that finish early direct to [HTML quiz](https://www.w3schools.com/html/html_quiz.asp)

### Wednesday (13/03)

Morning challenge
- Form challenge

10 - 11
- Basic CSS, create what my website actually is (fonts, margin, classes and ids, using ids to link to days)
- Introduction to class and id
- Styling a specific element within a class `.content p`
- Emphasize class is for many things id is for one thing
- External stylesheets (can also use style tag in head but don't)
- Looking at box model, padding is fat being added to organs, border is skin, margin is space you're away from me
- Preventing default margin set by browser
- Can override elements with certain box model attributes on them
- Introduction to unsplash
- Different values (px, vh, vw, %)
- Google fonts, font awesome
- [Different displays](https://stackoverflow.com/questions/9189810/css-display-inline-vs-inline-block) (inline, inline block, block)

11 - 1
- Challenge to create a landing page
- Will need to research background images, setting height for background, difference between margin and padding
- Challenge to create a website that has a fixed nav, with links that allow you to jump to different points on the page
- Create a page with a fixed scrollable sidebar, similar to [bootstrap website](https://getbootstrap.com/docs/4.3/components/alerts/)

2 - 2.30
- What is a component, it's a single piece of your website, making things modular is much cleaner, also kind of how react works
- CSS components (using import)
- Build some components (buttons, cards, badges, labels)
- Pseudo-class (hover) to create box shadow effect on button
- For cards show off position relative and absolute
- [Box shadow generator](https://www.cssmatic.com/box-shadow) or just use figma
- Quick intro to media queries
- Creating something in figma, implementing it in css, digital color meter, searching for inspiration, link to [figma buttons](https://www.figma.com/file/LckcJY0YPxYty3MAYVOXMHwl/buttons), link to [inspiration](https://material.io/design/components/buttons.html)

2.30 - 5
- Challenge to create multiple button, card, badge and label components, create a reusable library
- At mobile view have just one item in navbar, a logo thats centre aligned and links somewhere, at bigger view have navbar that has 4 different links, have logo left aligned and 4 different links right aligned
- Dropdown menu that uses hover pseudo-class

### Thursday (14/03)

Morning challenge
- [Zen garden challenge (ongoing throughout day)](http://www.csszengarden.com/)

10 - 11
- [CSS variables](https://codepen.io/harrisonmalone/pen/jJYEWE?editors=1100), grab color scheme from [coolers](https://coolors.co/)
- What the [root element](https://css-tricks.com/almanac/selectors/r/root/) actually is 
- Opening vscode
- Show how annoying it is to vertically align a box in the middle of a page (2 containers and then vh)
- Now use flex box 
- Understanding on that tweet, what kinds of things are one dimensional (buttons, navbars, forms)
- When to use and when to use flexbox [example](https://twitter.com/rachelandrew/status/1088827732874747910?s=12)
- Run through example of moving elements within flexbox to the 9 different positions, pretty much take class through [docs](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- Talk about different displays we've done thus far again (mention display none, inline, block, inline-block)

11 - 12.30
- Create a centred box (500px by 500px) in the middle of full width page using flexbox 
- Create a row of 4 boxes 200px by 200px using flexbox, test out different ways to justify them (center, flex-end, space-around)
- Build similar navbar with flexbox, add that to component library
- Create a page with a navbar and a full height container (100vh) underneath the navbar, you'll need to look up CSS calc for an elegant solution

1.30 - 2
- - Create a box type layout, [what i did with java](https://gist.github.com/harrisonmalone/41e4d0ebb8f7ff1c5223ae3a851f816b)

2 - 5
- Redo landing page with flexbox
- Build a form column layout with flexbox
- Build an inbox email style layout with flexbox
- Build a products page with flexbox, using the box type layout
- Build a page with items on left that's scrollable and sticky map on the right (need to use google maps api), similar to airbnb design
- Recreate a website with [parallax scrolling](https://www.w3schools.com/howto/howto_css_parallax.asp) 

### Friday (15/03)

Morning challenge
- Continue on with something you didn't finish yesterday

10 - 11
- Introduction to grid
- Again reference that [tweet](https://twitter.com/rachelandrew/status/1088827732874747910?s=12), grid is for more than one column and more than one row, multi dimensional 
- You might think then why not just use grid for everything, that is never the case, it's using a combo of block, flexbox and grid to achieve nice design
- Create a dashboard type of layout, show how i can target specific parts of the grid, [run through docs](https://css-tricks.com/snippets/css/complete-guide-grid/) 

11 - 12.30
- Create a dashboard layout using css grid, recreate these 3 examples: [health dashboard](https://dribbble.com/shots/1340306-Rolodex-Dashboard), [price dashboard](https://dribbble.com/shots/1464920-Basic-Dashboard-Design), [sales dashboard](https://elements.envato.com/bracket-responsive-bootstrap-admin-template-QHCFTF?irgwc=1&clickid=360yQf247xyJTJk0GIyI522MUkl0dQz073ja0U0&iradid=298927&utm_campaign=elements_af_78798&iradtype=ONLINE_TRACKING_LINK&irmptype=mediapartner&utm_medium=affiliate&utm_source=impact_radius&mp=Speckyboy%20Design%20Magazine)

1.30 - 5
- Re-do some kind of card component with css grid
- Challenge to recreate this website https://www.fortherecord.simonfosterdesign.com/

### Monday (18/03)

Morning challenge
- What's in repo

Schedule
- CSS review
- More challenges
- Deployment with netlify or github pages
- Introduction to assignment
- Go to the park to get bio profile done on each other, questionnaire

## Design resources 

Some links to design guidelines:
- [iPad human interface guidelines (from 2007)](https://www.hung-truong.com/blog/wp-content/uploads/2010/06/iPadHIG.pdf#page17)
- [Google material design](https://material.io/design/foundation-overview/#)
- [Human centred design](http://d1r3w4d5z5a88i.cloudfront.net/assets/guide/Field%20Guide%20to%20Human-Centered%20Design_IDEOorg_English-ee47a1ed4b91f3252115b83152828d7e.pdf)