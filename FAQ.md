### What is reSRC.io and how should I use it ? [whatisit]
#### A brief history
reSRC stands for *resource* (programmers often abbreviate source to *src*).

It came to birth because I could not find a website
displaying both quality curated lists and tag-sorted learning resources
(articles, books, tutorials, documentations, blog posts, ...).

Whenever I found an interesting article or a tutorial on a subject I wanted to
investigate, I ended up bookmarking it, together with curated lists laying here
and there.

Programmers sometimes need lists of links on a specific programming topic, be
it a technology, a framework, a language, ... Programmers sometimes want to
create such lists but don't know where to go to keep them and share them.

Non programmers sometimes want to do that kind of stuff too and it's alright.

On reSRC, you are free to create your own lists or to pull the list you already
have on GitHub or anywhere else. But most of you will probably be more
interested by discovering great resources from great lists.

#### How reSRC works

There are two kinds of entities on reSRC, both allowing comments and upvotes, and
both owned by someone.

The first one is link, links are pretty straightforward : add their URL, give them
some tags and you're done. You are now the owner of the link (the entry in reSRC, not
what the URL points to) and are the only one who can edit it. Other members can
still submit modifications, but they can only be accepted by an administrator for now.
When an administrator validate a modification, the link's owner is not informed.

Lists are hardly harder to understand. A list is basically a Markdown file with a
special handling of links. Links that have already been added to reSRC are displayed
with a nice little blue link symbol on their left. If you click the link like you would
normally do, you are sent to its reSRC page and can view upvotes, comments and stuff. If
you click the link symbol, you are directly redirected to the URL. On the other hand if
the link isn't published on reSRC yet, an "add" button is displayed on its right. You can
click it to become the reSRC owner of the link if you feel like doing so.


### How to format my lists?

Use Markdown. The syntax is easy to learn and can be found
[here](https://en.wikipedia.org/wiki/Markdown#Example)
or [here](http://daringfireball.net/projects/markdown/syntax).

### How to import a list from an external website?

First, the list **must** be a Markdown file. Second, create a new list and
indicate the URL pointing to the **raw** Markdown file.

For example, if you want to create a list from
[this file on GitHub](https://github.com/vhf/resrc/blob/master/FAQ.md), the URL
you'll have to give reSRC is
[this one](https://raw.githubusercontent.com/vhf/resrc/master/FAQ.md).

### Should I add links to reSRC first and then create an external list, or vice versa ?

Vice versa. First, create your list with all your beautiful links. Then add it
to reSRC, either by copy/pasting the Markdown or by creating an "external" list
 using the URL field. Only then will you be able to easily add the links on
reSRC : a nice "add" button will appear next to each link that is not on reSRC yet.

### I found a poorly tagged link, how can I modify it ?

Next to the tags, there's an **edit** button. It lets you suggest modifications
to any fields of a link.
