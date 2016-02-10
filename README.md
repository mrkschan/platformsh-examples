# Example configurations for Platform.sh

This repository is a collection of various example configurations demonstrating 
the flexibility of `Platform.sh`.

## Examples

Each example is a specific branch that you can use as a starting point for your 
[Platform.sh](https://platform.sh) project.

### PHP

#### Drupal

[DEPRECATED] The Drupal examples have moved to the [platformsh-example-drupal](https://github.com/platformsh/platformsh-example-drupal) GitHub repository.

#### Magento

[DEPRECATED] The Magento examples have moved to the [platformsh-example-magento](https://github.com/platformsh/platformsh-example-magento) GitHub repository.

#### Symfony

[DEPRECATED] The Symfony examples have moved to the [platformsh-example-symfony](https://github.com/platformsh/platformsh-example-symfony) GitHub repository.

#### WordPress

[DEPRECATED] The WordPress examples have moved to the [platformsh-example-wordpress](https://github.com/platformsh/platformsh-example-wordpress) GitHub repository.

## NodeJS

Some NodeJS examples can be found in the [platformsh-example-nodejs](https://github.com/platformsh/platformsh-example-nodejs) GitHub repository.

### Misc

* [custom-php/minimal](https://github.com/platformsh/platformsh-examples/tree/custom-php/minimal)
* [custom-php/hhvm](https://github.com/platformsh/platformsh-examples/tree/custom-php/hhvm)
* [double-mysql](https://github.com/platformsh/platformsh-examples/tree/double-mysql)
* [multiapp/drupal-symfony](https://github.com/platformsh/platformsh-examples/tree/multiapp/drupal-symfony)
* [sonata/2.4](https://github.com/platformsh/platformsh-examples/tree/sonata/2.4)

## How to use

Clone one of the example branch you want to start from:

    $ git clone --branch=BRANCH-NAME git@github.com:platformsh/platformsh-examples.git my-project
    $ cd my-project

If you start from a new [Platform.sh](https://platform.sh) project, choose the 
`start with an existing repository` option and copy the `remote add` command. It
will look like this:

    $ git remote add platform PROJECT-ID@git.eu.platform.sh:PROJECT-ID.git

Paste this command into your newly created folder and push it to your 
[Platform.sh](https://platform.sh) project:

    $ git push -u platform HEAD:master

To work with your new application it would be simpler for you to use the CLI or
git to clone the remote repository into another "clean" directory without all
of the other branches.

That's it!
