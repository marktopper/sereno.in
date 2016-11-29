# Directory Structure

- [Introduction](#intro)
- [The Root Directory](#project)
- [The `content` Directory](#content)
  - [The `_includes` Directory](#includes)
    - [The `_assets` Directory](#resources)
  - [The `_blog` Directory](#blog)
  - [The `_docs` Directory](#docs)
  - [The `assets` Directory](#assets)

{#intro}
## [](#intro) Introduction
The default directory structure of Sereno is intended to provide a great
starting point. It includes a complete demo website with blog and docs enabled
out of the box.

{#project}
## [](#project) The Root Directory

#### The `_cache` Directory
The `_cache` directory stores temporary views used to build the website. It is
autogenerated at build time.

#### The `content` Directory
The `content` directory stores all source code of the website. We will explore
this directory in more detail soon.

#### The `public` Directory
The `public` directory, as expected, stores your website. Contents of this
directory are autogenerated at build time.

#### The `node_modules` Directory
The `node_modules` directory is created by NPM or Yarn to store javascript
dependencies.

#### The `vendor` Directory
The `vendor` directory contains your Composer dependencies.

#### Other Files

Your Composer dependencies are listed in `composer.json` and `composer.lock`.

Javascript dependencies are listed in `package.json` and `yarn.lock`.

`.gitignore` configures git to excludes unwanted files from version history.

Sereno configurations are stored in `config.php` and `config.dev.php`. We will
explore configurations in detail further.

`gulpfile.js` controls the build process of the Sereno.

`sereno` provides a command line interface for Sereno.

{#content}
## [](#content) The Content Directory
The `content` directory houses your websites code. All files (excluding `_blog`,
`_docs` and `_includes`) in this directory are treated as content for your
website.

Blade and Markdown files are rendered as pages and rest files are copied as it is.

{#includes}
#### The `_includes` Directory
The `_includes` directory contains Blade components and resources. You can tweak
these files to get a personalized look for your website.

{#resources}
##### The `_assets` Directory
The `_assets` sub-directory contains Javascript and SCSS styles.

{#blog}
#### The `_blog` Directory
The `_blog` directory provide customized rendering to produce your.

{#docs}
#### The `_docs` Directory
The `_docs` directory produces a sleek documentation for your project.

{#assets}
#### The `assets` Directory
The `assets` directory contains static files like images, scripts and styles.

<br><br><br>
- - - - - - - - - - - - -
[Edit this page on Github](https://github.com/znck/sereno.in/edit/master/content/_docs/directory-structure.md)