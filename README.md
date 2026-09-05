# resumes-index

The public front page for my CV work: [thimiraperera.github.io/resumes-index](https://thimiraperera.github.io/resumes-index/)

It lists **names only**. Nothing else is published here.

## Why this is a separate repository

GitHub visibility is set **per repository, not per branch**. There is no way to
publish one branch and keep the others private — making a repository public
publishes every branch in it, including its whole history.

The CVs themselves live in the private [`resumes`](https://github.com/thimiraperera/resumes)
repository, one branch per person, and those branches hold real personal data:
national identity card numbers, dates of birth, home addresses, referees'
private telephone numbers, and scanned signatures.

So the index lives here instead. `resumes` stays private permanently; this
repository never contains anything but names.

## Adding a person

Add one line to the list in `index.html`:

```html
<li><span class="n">02</span><span class="who">Their Name</span></li>
```

Commit and push — GitHub Pages redeploys on its own.

## Rule

Never copy a document, a photograph, a contact detail or a date of birth into
this repository. Names only.
