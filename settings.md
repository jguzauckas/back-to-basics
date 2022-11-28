In the extensions section, search for and install the "Black Formatter" for Python (should have a Python logo).

Once you've installed it, go to File -> Preferences -> Settings and open up the `settings.json` by clicking the button at the top right.

Paste the following into your `settings.json` on a new line:

```json
"[python]": {
        "editor.defaultFormatter": "ms-python.black-formatter",
        "editor.formatOnSave": true
    },
```

In the settings menu, search for "autosave".

Change the `Files: Auto Save` dropdown to `afterDelay`.

Now your files should periodically autosave (helping to eliminate loss of work), and when you save a Python file, it will automatically format it (adding in extra lines where necessary, fixing spacing, etc.).
