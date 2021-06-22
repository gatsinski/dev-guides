# Code style

Sections covered:

* [Python](#Python)
* [JavaScript](#JavaScript)
* [HTML, Angular templates and JSX](#HTML-Angular-templates-and-JSX)
* [CSS, Less and Sass](#CSS-Less-and-Sass)
* [JSON, YAML and Markdown](#JSON-YAML-and-Markdown)
* [Kotlin](#Kotlin)
* [Groovy](#Groovy)
* [Other languages](#Other-languages)

## Python

Python as a language has its own officially adopted style guide specified by the [PEP8](https://www.python.org/dev/peps/pep-0008/). In order to follow all the rules described in the proposal and standardize the ones that are not explicitly specified, use [Black](https://black.readthedocs.io).

All python developers should have Black installed and configured on their systems. Black has integrations for all popular editors including Vim, PyCharm, Visual Studio Code and Sublime. More about the topic can be found [here](https://black.readthedocs.io/en/stable/editor_integration.html).

Most of our Python projects are written with Django which offers its own set of [rules](https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/coding-style/) which in most cases doesn't conflict with PEP8 and are responsible for Django-specific code. Follow them whenever possible but don't argue with Black. No one should argue with Black.

## JavaScript

JavaScript is a problematic language due to its lack of official style guide. Instead, multiple large companies or group of enthusiasts published their own style guides adopted by many but still very far from official widespread adoption. In order to counter these problems, use [StandardJS](https://standardjs.com/) and its default rules to lint and format code.

Possible replacement - [Prettier](https://github.com/prettier/prettier).


## HTML, Angular templates and JSX

HTML can be written in many ways. This causes a lot of confusion and often makes the code harder to read. To standartize HTML code the use of [Prettier](https://github.com/prettier/prettier) is recommended.

This formatter is also suitable for Angular templates and JSX code.

To integrate Prettier with your editor of choice follow this [guide](https://prettier.io/docs/en/editors.html). It supports all but Notepad. Please, don't use notepad.

## CSS, Less and Sass

[Prettier](https://github.com/prettier/prettier)

## JSON, YAML and Markdown

[Prettier](https://github.com/prettier/prettier)

## Kotlin

Kotlin offers nice and descriptive code style guide as part of its official [documentation](https://kotlinlang.org/docs/reference/coding-conventions.html) you should strictly follow these rules. In order to prevent any deviation from the canon all Kotlin developers should use [ktlint](https://github.com/pinterest/ktlint) to properly format their code before commit.

## Groovy

Follow the official [style guide](http://groovy-lang.org/style-guide.html). In addition, you can use [groovy-lint](https://github.com/nvuillam/npm-groovy-lint).

## Other languages

If the language you are looking for is not listed here, there are two possible scenarios.

* The language has a supporting role in the project - In that case, you should follow the official style guide for that specific language. If such is missing, gather the rest of the team and agree upon a community-driven effort or quickly develop your own, whichever makes more sense.
* A huge part of the project is going to be coded with that language - Call all team members and discuss which code style to implement for the current project and all future projects that are going to use the same language or technology. And don't try to sneak out with cheap excuses such as "There will be no future projects". There are always future project and we shoud be prepared for that. Don't forget to update this document.
