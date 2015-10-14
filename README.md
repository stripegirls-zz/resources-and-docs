# Resources and Docs

This repo will combine resources to help you get started with coding. StripeGirls focuses on PHP and the SilverStripe platform, so resources about those topics will be the main focus of this collection.

Think of this document as a repository of knowledge. Just like any other knowledge-base, it will grow and be addd to when our members find more cool things! If you spot something helpful online that you'd like to share, open up an issue or a pull request and we'll add the resource here!

## Table of Contents
[Contributing](#contributing)
[Text Editor](#text-editor)
[Git](#git)
[Apache, PHP and MySQL or MariaDB](#apache-php-and-mysql-or-mariadb)
[Composer](#composer)
[SilverStripe](#silverstripe)
[General Learning Resources](#general-learning-resources)

## Contributing

If you'd like to add a new resource via a pull request, please make sure it's formatted similarly to the other resources here and is placed in the correct category to make it easier for other people to find.

If it's a general learning resource, please write a sentence or two about what it is/does and why it's helpful, as well as a link and an author if possible.

This ReadMe doc is written using GitHub flavoured Markdown. You can read more tips and tricks on how to use Markdown by reading [this handy document by Adam Pritchard](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)!

## Text Editor

We write code in a text editor, which can easily be just about any program that lets you type in un-formatted text. Your computer will already come with a few of these that can be suitable, such as Notepad. However, some text editors were made specifically for coders and will detect the language you are using, highlight names of classes or functions, and do a whole bunch of other useful stuff. Here are some popular ones you can download:

* [Sublime Text](http://www.sublimetext.com/)
* [Atom](https://atom.io/)
* [Notepad++](https://notepad-plus-plus.org/)
* [Komodo Edit](http://komodoide.com/komodo-edit/)

You can also use something called an IDE (Independant Development Environment), which can give you lots of other helpfu hints.

*[PhpStorm: A PHP IDE](https://www.jetbrains.com/phpstorm/)

WARNING: Do not use a text editor that puts out formatted text, such as Microsoft Word or Pages. The formatting on the text (eg font, font size, bold, italics) will prevent it being able to be interpretted as code and your projects will break.

## Git

Here's a list of learning resources and helpful links to get you started with git!

* [GitHub git from the command line cheat sheet](https://training.github.com/kit/downloads/github-git-cheat-sheet.pdf)
* [Youtube tutorial series by 308tube](https://www.youtube.com/watch?v=mYjZtU1-u9Y&list=PL1F56EA413018EEE1)
* [Interactive git cheatsheet](http://www.ndpsoftware.com/git-cheatsheet.html)
* [Learn git from the series 'Learn X in Y minutes'](http://learnxinyminutes.com/docs/git/)

## Apache, PHP and MySQL or MariaDB

### Apache
To run your new PHP sites locally (on your machine), you will need to run a local server. We will be using Apache as our local server, although there are many others. If you are using a Mac, your computer might aleady come with some of this stuff installed, so if you're struggling with installing any of the stuff below, have a chat to somebody at the next meetup about how to best set up your environment for developing.

An easy way to get all the stuff you need is to install it as a bundle. Bundles come with a whole bunch of technologies you need to get started right away. The common ones are XAMPP, WAMP, LAMP and MAMP. They all come with the same technologies, but you will need a different one based on your operating system. The first letter of the bundle will tell you which one suits you. Click on the one that suits you below and follow the installation instructions on their site.
* [XAMPP](https://www.apachefriends.org/index.html) — X for Cross-platform (available on Windows, Linux and Mac), MySQL, PHP, and Perl.
* [WAMP](http://www.wampserver.com/en/) — Windows, Apache2, MySQL, PHP.
* [LAMP](https://help.ubuntu.com/community/ApacheMySQLPHP) — Linux, Apache, MySQL, PHP.
* [MAMP](https://www.mamp.info/en/) — Mac and Windows, Apache, MySQL, PHP.

### PHP
PHP is the language we will be using. If you've installed one of the bundles above, you should already have it. Many computers also come with an install of PHP. You can check if you have PHP already installed on your computer by going to your command line (Terminal app on Mac / Command Prompt on Windows) and typing the following:
* Windows and Mac: php -v
* Linux: php --version

If PHP is installed on your computer, you should get back 3 lines of text. The first one will say PHP 5.5.2 (or whatever version number you have installed), and the next 2 will contain some copyright information.
If you do not have PHP installed, it will come back with something like "command not found".

### MySQL or MariaDB
Lots of websites need a database. Think of the database like a series of tables that stores information about the things on the site. For example, a database might store all the users who are registered to use the site, or all the products available for sale on that website. We will be working with either MySQL or MariaDB. These two databases were created by the same people and are very similar. Some people prefer MariaDB because that project is committed to remaining Open Source. 

However, there are other databases people use too.

MySQL and MariaDb are relational databases. This means that you can set up relationships between different tables and records. For example, if you're making a blogging site, you might want to set up tables for users and comments. A user might then have a one-to-many relationship with comments, meaning every comment will be attributed to only one user, but every user can have a whole bunch of different comments.

If you installed one of the bundles above, you will already have MySQL installed on your computer. 

## Composer

Composer is a dependancy manager for projects written in PHP. Why do you need a dependancy manager? Imagine you are working on a project with a group of people. Somebody makes a change to the project that depends on a specific library having been downloaded. The other members of the project don't know about this and when they pull down the changes, their app no longer works. To avoid this happening, we use Composer. It will keep track of all the dependencies in a project for us, and allow every person to keep their project's list of dependencies and their correct versions up to date with everyone else automatically.

* [Composer installation guide for Windows and Linux](http://www.dev-metal.com/install-update-composer-windows-7-ubuntu-debian-centos/)
* [Composer installation guide for Mac](http://www.abeautifulsite.net/installing-composer-on-os-x/)

## SilverStripe

Now that you have Composer installed, you can use it to get a basic install of SilverStripe, which is the platform we will be using in StripeGirls.

[Install SilverStripe basic recipe with Composer](https://docs.silverstripe.org/en/3.1/getting_started/composer/#create-a-new-site)

There are other ways to install SilverStripe too, but we'll stick with this one for now.

## General Learning Resources

This section is for programming tips and tricks that will help us all become awesome coders.

* [PHP: The Right Way](http://www.phptherightway.com/) — This resource comes with a bunch of PHP tips and explanations and can teach you a lot about the land of PHP.







