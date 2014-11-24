appledoc-template-jazzy
========================

Brings the look &amp; feel of Apple’s official reference documentation, post WWDC 2014 to appledoc.

Example
---

![](http://i.gyazo.com/34ecfc2ea6bd8a36db70d48022b4ebb4.png)

Installation
---

Just clone the repository.

Usage
---

```objc
appledoc --template /path/to/jazzy_template .
```

Just add `--template` argument with the path to the template.

Current Limitations
---

1. Enums are currently not supported.
2. Block Typedefs are currently not supported.
3. Hierarchy Graph in document index are not supported. (This is limitation of appledoc)
