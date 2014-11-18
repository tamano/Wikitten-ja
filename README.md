# Wikitten

Wikitten is a small, fast, PHP wiki, and the perfect place to store your notes, code snippets, ideas, etc.

**This repository is a fork of Wikitten.**

Check out the **[project website](http://wikitten.vizuina.com)** for more details and features.

[![Wikitten](http://wikitten.vizuina.com/screenshot.png)](http://wikitten.vizuina.com)

## Requirements

* PHP `5.3+`
* The Apache webserver (with `mod_rewrite`)

## Installation

* [Download](https://github.com/nicosomb/Wikitten/archive/master.zip) the latest version or clone the [repository on GitHub](https://github.com/nicosomb/Wikitten)
* After extracting the archive, drop the files somewhere in your DocumentRoot, or make a separate Apache [VirtualHost](http://httpd.apache.org/docs/2.2/mod/core.html#virtualhost) (this is the way I currently use it myself)
* That's it. There's a `library` directory in the installation folder. Everything you place in there will be rendered by the wiki. If there's an `index.md` file (such as the one you are reading now) in that folder, it will be served by default when accessing the wiki.

  You don't have to use the `library` directory if you don't want to, you can configure Wikitten using
  the `config.php` file. Simply copy the `config.php.example` file found in the site root to `config.php`,
  and change the values of the constants defined inside.

## Special thanks go to:

* [Victor Stanciu](http://victorstanciu.ro/), the main developer of Wikitten
* [Michel Fortin](http://michelf.ca/home/), for the [PHP Markdown parser](http://michelf.ca/projects/php-markdown/).
* [Marijn Haverbeke](http://marijnhaverbeke.nl/), for [CodeMirror](http://codemirror.net/), a JavaScript code editor.
* Twitter, for the [Bootstrap](http://twitter.github.com/bootstrap/) CSS framework.
* All Vectors, for the [free cat vector](http://www.allvectors.com/cats-vector/) silhouette I used in making the logo.

## What I've modified
What I have added/deleted from the [original](https://github.com/nicosomb/Wikitten) repo.

- Theme is now responsive and be better looked at smartphones.
- Basic Auth.
