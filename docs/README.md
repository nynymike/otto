OTTO Working Group Documentation
================================

Install virtualenv if necessary:

```
$ sudo pip install virtualenv
```

Create a local python enviroment and install the version of mkdocs we used to make our custom theme:

```
$ virtualenv env
$ env/bin/pip install -r requirements.txt
```

For more information see their website: http://www.mkdocs.org

To generate the documentation:

     $ env/bin/mkdocs build

This will create a directory called `site` which has the `index.html`
for viewing in your browser.

To run the server locally:

     $ env/bin/mkdocs serve

The home repository for this project is:

- [https://github.com/nynymike/otto](https://github.com/nynymike/otto)
