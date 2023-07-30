# freecodecamp-responsive-web-design
Certification projects are done for Responsive Web Design Certification on freeCodeCamp.

In order to receive the certification, I had to complete all the projects listed below (to fulfil the given user stories and pass all the tests). I gave a personal style to each project.

## Certification Projects:
- [x] Survey Form
- [x] Tribute Page
- [x] Technical Documentation Page
- [ ] Product Landing Page
- [ ] Personal Portfolio Webpage



### Survey Form

**Objective:** Build an app that is functionally similar to https://survey-form.freecodecamp.rocks

**User Stories:**

1. You should have a page title in an `h1` element with an `id` of `title`.
1. You should have a short explanation in a `p` element with an `id` of `description`.
1. You should have a `form` element with an `id` of `survey-form`.
1. Inside the form element, you are required to enter your name in an `input` field that has an `id` of `name` and a `type` of `text`.
1. Inside the form element, you are required to enter your email in an `input` field that has an `id` of `email`.
1. If you enter an email that is not formatted correctly, you will see an HTML5 validation error.
1. Inside the form, you can enter a number in an `input` field that has an `id` of `number`.
1. The number input should not accept non-numbers, either by preventing you from typing them or by showing an HTML5 validation error (depending on your browser).
1. If you enter numbers outside the range of the number input, which are defined by the `min` and `max` attributes, you will see an HTML5 validation error.
1. For the name, email, and number input fields, you can see corresponding `label` elements in the form, that describe the purpose of each field with the following ids: `id="name-label"`, `id="email-label"`, and `id="number-label"`.
1. For the name, email, and number input fields, you can see placeholder text that gives a description or instructions for each field.
1. Inside the form element, you should have a `select` dropdown element with an `id` of `dropdown` and at least two options to choose from.
1. Inside the form element, you can select an option from a group of at least two radio buttons that are grouped using the `name` attribute.
1. Inside the form element, you can select several fields from a series of checkboxes, each of which must have a `value` attribute.
1. Inside the form element, you are presented with a `textarea` for additional comments.
1. Inside the form element, you are presented with a button with `id` of `submit` to submit all the inputs.


### Tribute Page

**Objective:** Build an app that is functionally similar to https://tribute-page.freecodecamp.rocks

**User Stories:**

1. Your tribute page should have a `main` element with a corresponding `id` of `main`, which contains all other elements
1. You should see an element with an `id` of `title`, which contains a string (i.e. text), that describes the subject of the tribute page (e.g. "Dr. Norman Borlaug")
1. You should see either a `figure` or a `div` element with an `id` of `img-div`
1. Within the `#img-div` element, you should see an `img` element with a corresponding `id="image"`
1. Within the `#img-div` element, you should see an element with a corresponding `id="img-caption"` that contains textual content describing the image shown in `#img-div`
1. You should see an element with a corresponding `id="tribute-info"`, which contains textual content describing the subject of the tribute page
1. You should see an `a` element with a corresponding `id="tribute-link"`, which links to an outside site, that contains additional information about the subject of the tribute page. HINT: You must give your element an attribute of `target` and set it to `_blank` in order for your link to open in a new tab
1. Your `#image` should use `max-width` and `height` properties to resize responsively, relative to the width of its parent element, without exceeding its original size
1. Your `img` element should be centered within its parent element


### Technical Documentation Page

**Objective:** Build an app that is functionally similar to https://technical-documentation-page.freecodecamp.rocks

**User Stories:**

1. You can see a `main` element with a corresponding `id="main-doc"`, which contains the page`s main content (technical documentation)
1. Within the `#main-doc` element, you can see several `section` elements, each with a class of `main-section`. There should be a minimum of five
1. The first element within each `.main-section` should be a `header` element, which contains text that describes the topic of that section.
1. Each `section` element with the class of `main-section` should also have an `id` that corresponds with the text of each header contained within it. Any spaces should be replaced with underscores (e.g. The section that contains the header "JavaScript and Java" should have a corresponding `id="JavaScript_and_Java"`)
1. The `.main-section` elements should contain at least ten `p` elements total (not each)
1. The `.main-section` elements should contain at least five `code` elements total (not each)
1. The `.main-section` elements should contain at least five `li` items total (not each)
1. You can see a `nav` element with a corresponding `id="navbar"`
1. The `navbar` element should contain one `header` element which contains text that describes the topic of the technical documentation
1. Additionally, the navbar should contain link (`a`) elements with the class of `nav-link`. There should be one for every element with the class `main-section`
1. The `header` element in the `#navbar` must come before any link (`a`) elements in the navbar
1. Each element with the class of `nav-link` should contain text that corresponds to the `header` text within each section (e.g. if you have a "Hello world" section/header, your navbar should have an element which contains the text "Hello world")
1. When you click on a `navbar` element, the page should navigate to the corresponding section of the `#main-doc` element (e.g. If you click on a `.nav-link` element that contains the text "Hello world", the page navigates to a `section` element with that `id`, and contains the corresponding header)
1. On regular sized devices (laptops, desktops), the element with `id="navbar"` should be shown on the left side of the screen and should always be visible to the user
Your technical documentation should use at least one media query
