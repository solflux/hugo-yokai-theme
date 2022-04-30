# Yokai

Simple theme for team docs, decisions and a blog. Built using Tailwind and loosely inspired by the default theme from the GitLab Pages starter.

## Installation

    $ mkdir themes
    $ cd themes
    $ git clone https://github.com/solflux/hugo-yokai-theme.git yokai

See [the Hugo documentation](http://gohugo.io/themes/installing/) for more information.

## Quirks

For whatever reason with Hugo, in List views single item summaries will not render properly as Markdown **unless** you add a "more" tag into the Markdown content.

As such, be sure to add `<!--more-->` into the markdown files to force them to render correctly on the list views. All Architypes provided by this theme include "more" tags to force this behaviour and remind you to use them.