# Sphinx Demo

## How to run & edit

Everything is set up in a docker project, just run `docker-compose up` and go to http://localhost:7000 to view the documentation.

Feel free to edit any needed part (pages are in `./sphinx/source/pages`).
The docker image is set up to automatically listen to changes, so you should see them immedietly.

## Sphinx

The engine behind this project is the [Sphinx](https://www.sphinx-doc.org/en/master/index.html) library.

Make sure to read the [Get Started](https://www.sphinx-doc.org/en/master/index.html#get-started) page in order to understand how everything works, and mainly go over the [reStructuredText](https://www.sphinx-doc.org/en/master/usage/restructuredtext/index.html) page as this is the format the pages are written in.
