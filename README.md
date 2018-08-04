# FaDoe codesniffer

## About

This is the base coding standard for my projects. I use the default coding standards. Additionally I add the ```PHPCompatibility``` standard.

## Installation

To use this coding standard add this repository to your ```composer.json```:

```
{
    ...
    "repositories": [
        {
                "type": "git",
                "url": "https://github.com/fadoe/codesniffer.git"
        }
    ],
    ...
}
```

Now you can use codesniffer when you run this from command line:


```
composer.phar require fadoe/codesniffer:dev-master
```

## Show installed coding standards

View all installed coding standards:

```
vendor/bin/phpcs -i
```

## Usage

TBW


