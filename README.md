## google cloud php sublime snippets

Clone this repo in your `<Sublime Directory>/Packages` folder.

### Snippets:

* Add copyright and base namespace to file.

    ````
    copy<tab>
    ````

* Add group annotation to testcase

    ````
    group<tab>
    ````

* Create test case template

    ````
    testcase<tab>
    ````

* Create Snippet test case template

    ````
    snippettest<tab>
    ````

* Add an `@expectedException` annotation (default to InvalidArgumentException)

    ````
    expect<tab>
    ````

### Key Bindings

To wrap a selection in `@codingStandardsIgnore<start|end>` annotations, add a
key binding to your keymap file:

```
  {
    "keys": ["ctrl+shift+i"],
    "command": "insert_snippet",
    "args": {"name": "Packages/GoogleCloudPlatform/coding-standards-ignore.sublime-snippet"}
  }
```
