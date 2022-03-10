# Propel

Propel is an open-source Object-Relational Mapping (ORM) for PHP5. 

**This fork includes several updates to introduce support for PHP >= 7.4 for legacy systems which may not be able to upgrade to newer versions of Propel.**

## Usage

To use this version of Propel locally, simply update the `composer.json` to reflect this repository, update the package to point
to master, and run `composer install`.

```json
{
  "require": {
    "propel/propel1": "dev-master"
  },
  "repositories": [
    {
      "type": "vcs",
      "url": "https://github.com/dfalkcreative/propel.git"
    }
  ]
}

```