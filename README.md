[![Stories in Ready](https://badge.waffle.io/backbee/backbee-standard.png?label=ready&title=Ready)](https://waffle.io/backbee/backbee-standard)
# BackBee CMS Standard Edition

## Overview ##

BackBee CMS is an open-source content management system. Because it incorporates HTML5 programming to an unprecedented extent, its usability and design flexibility surpasses all other content management systems that we know of.

All changes in content – adding, deleting or changing text, images or new page elements – can be made directly on the page. Just click and type, or drag and drop. No back office. No shuttling back and forth between the back end and a “preview” page that often fails to match the final page display.

BackBee CMS offers what we like to call WYSIWYRG, What You See Is What You Really Get. And because it automatically saves different page versions, there’s no fear of losing changes along the way. If only everything in life could be this easy and secure.


:speech_balloon: If you want to have more information about the project progression you can take a look at the actual [Roadmap](https://waffle.io/backbee/backbee-standard).

## Features ##

* Powerful and easy to use content system
* Multiple websites
* Custom themes
* Custom pages
* Advanced block system
* Users/Groups management

## Documentation ##

:book: Documentation for api is available, and you can also follow BlogBee, a tutorial to help you make a complete website with BackBee CMS.

 - **[Developer PHP Api docs](http://developers.backbee.com/api)**
 - **[Video tutorials](http://developers.backbee.com/get-started/video-tutorials)**

If you want to generate some fake categories and articles, you can use this command:

    $ ./backbee fake:data:generate --article-limit 20 --category-limit 5

## Ask for help ##

:speech_balloon: If you need help about this project you can [post a message on our gitter room](https://gitter.im/backbee/BackBee)

## Contributing

Pull requests are welcome.

Please take a look to our CONTRIBUTING.md file

First of all, **thank you** for contributing, **you are awesome**!

Here are a few rules to follow in order to ease code reviews, and discussions before
maintainers accept and merge your work.

You MUST follow the [PSR-1](http://www.php-fig.org/psr/1/) and [PSR-2](http://www.php-fig.org/psr/2/). If you don't know about any of them, you should really read the recommendations. Can't wait? Use the [PHP-CS-Fixer tool](http://cs.sensiolabs.org/).

* You MUST run the test suite.
* You MUST write (or update) unit tests.
* You SHOULD write documentation.

Please, write [commit messages that make sense](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html), and [rebase your branch](http://git-scm.com/book/en/Git-Branching-Rebasing) before submitting your Pull Request.

One may ask you to [squash your commits](http://gitready.com/advanced/2009/02/10/squashing-commits-with-rebase.html) too. This is used to "clean" your Pull Request before merging it (we don't want commits such as `fix tests`, `fix 2`, `fix 3`, etc.).

Also, while creating your Pull Request on GitHub, you MUST write a description which gives the context and/or explains why you are creating it.

### Workflow

When you create a Pull Request ("PR"), if it's component related you can prefix it by the component name.
You can also use plus or minus to describe if you globally add or remove something, and reference it to an issue.

For instance, this is a PR valid label: ``[Rest] #42 + Updated & completed PageController tests``.

When you want to take an issue, create your PR prefixed by a [WIP]("Work in progress") and add a "in progress" label.
This way, we know you are working on it and we can give you some advices if needed.

When you have finished your PR, you can update the PR label to replace [WIP] by [RFR]("Ready for review") prefix.

Consider your PR finished if:

* You have written a test with a new feature;
* All tests pass;
* The build is all green;
* You (may) have introduced a little documentation;
* Your PR respects project formatting rules (see above);

### Sync a fork

Github dev team has already described the [right way to do](https://help.github.com/articles/syncing-a-fork/).

```bash
$ git fetch upstream
$ git checkout master
$ git merge upstream/master
```

### Formatting

We use [php-formatter](https://github.com/mmoreram/php-formatter) to manage your file headers and the way the use statements should be added to the classes.

Before submit your Pull Request, don't forget to apply this commands:

```sh
    ~$ php-formatter formatter:header:fix .
    ~$ php-formatter formatter:use:sort .
```
You need to install php-formatter before.

### Deciders & mergers

BackBee CMS have a core team who have rights on repositories.
* Only mergers can merge your work on master branch;
* If one of the deciders gives a ``:-1:`` on your suggestion, the pull request won't be merged until he changes his mind;

Current mergers are @eric-chau and @crouillon, current deciders are @ndufreche and @fkroockmann, @hbaptiste, @mickaelandrieu.

All the core team is here to help you if you want to improve BackBee CMS, we love contribution :)


Thank you!

note: this ``CONTRIBUTING`` file is proudly inspired from [Hateoas' one](https://github.com/willdurand/Hateoas/blob/master/CONTRIBUTING.md)


Thanks to [everyone who has contributed](https://github.com/backbee/backbee-standard/graphs/contributors) already.

---

*This project is supported by [Lp digital](http://www.lp-digital.fr/en/)*

**Lead Developer** : [@crouillon](https://github.com/crouillon)

Released under the GPL3 License

