# Engineering E-Book Store

A static storefront for engineering textbooks, organised by branch. Built as a web
technology coursework project in plain HTML and CSS — no JavaScript, no framework, no
build step.

## Pages

```
webtechnology/
  homepage.html        landing page and navigation
  cataloguepage.html   full catalogue
  csepage.html         Computer Science and Engineering titles
  ecepage.html         Electronics and Communication Engineering titles
  eeepage.html         Electrical and Electronics Engineering titles
  mechpage.html        Mechanical Engineering titles
  loginpage.html       login form
  registerpage.html    registration form
  style.css            one shared stylesheet, 126 lines
```

Every page links to the same `style.css`, so the visual language is defined in exactly
one place and a change to the palette or type scale propagates across all eight pages.

## Running it

No tooling required — open `webtechnology/homepage.html` in a browser. To serve it
over HTTP instead:

```bash
cd webtechnology
python -m http.server 8000
```

Then visit `http://localhost:8000/homepage.html`.

## Scope

This is coursework, and it is honest about what it is. The login and registration
forms are markup only: there is no backend, no validation and no persistence behind
them. The catalogue is hand-authored rather than data-driven.

Kept in its original form as a record of early work.
