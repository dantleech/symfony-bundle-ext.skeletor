Symfony Bundle Skeleton
=======================

Skeleton for a basic Symfony bundle with an extended file structure (i.e. with
`src` and `tests` directories).

It also has a built in example application:

```bash
$ php example/bin/console --version
```

Install using [Skeletor](http://dantleech.github.io/skeletor/).

```bash
$ skeletor install dantleech/symfony-bundle-ext.skeletor
$ skeletor generate
```

Generate the project:

```
./bin/skeletor generate
Choose a skeleton:
  [0] dantleech/symfony-bundle-ext.skeletor
 > 1
Install to [symfony-bundle-ext.skeletor]: example
package.name [my-vendor/my-package]: acme/example
bundle.name [BundleNameWithoutTheSuffix]: Example 
bundle.namespace [My\\Project]: Acme\Bundle\Example
bundle.description [Description about my project]: My Acme Bundle
author.name [Anonymous]: Daniel Leech
author.email [anonymous@example.com]: daniel@dantleech.com
Generating symfony-bundle-ext.skeletor skeletor in example:
...
```

Enjoy:

```bash
$ tree . -a --dirsfirst
.
├── src
│   ├── DependencyInjection
│   │   ├── Configuration.php
│   │   └── ExampleExtension.php
│   └── ExampleBundle.php
├── tests
├── composer.json
├── .gitignore
├── LICENSE
├── phpunit.xml.dist
├── README.md
├── .styleci.yml
└── .travis.yml

3 directories, 10 files
```
