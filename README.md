# Intranet Wiki Guidelines

> without clarity of speech man is only a garden gnome (German pop music band "Element of Crime" in the song "Alle vier minuten")

I maintain Intranet Wikis for fun and provit. I like:

* [Single Source of Truth](https://en.wikipedia.org/wiki/Single_source_of_truth)
* [Canonicalization](https://en.wikipedia.org/wiki/Canonicalization)
* [Hyperlinks](https://en.wikipedia.org/wiki/Hyperlink)

With the following text I would like to share my findings with you. This is my best practices sharing.

# What is an Intranet Wiki?

* An Intranet Wiki is a tool is a knowledge base on which users collaboratively edit content.
* This content is available for all employees in a company and not visible on the world wide web.
* One term is explained on one page. This page is accessible via [a canonical URL](https://en.wikipedia.org/wiki/Canonicalization#URL).

Every company has its terminology. For new employees, it is very helpful to have a definition of the terms which
are custom.

But a central Wiki is useful to improve the communication between departments. Because the terminology between departments differs.

# Difference between an Intranet Wiki and Wikipedia

Wikipedia pages are often very detailed. Usually, it makes no sense to explain every detail in an Intranet Wiki.

An Intranet Wiki should provide an overview. Historical details should be removed to focus on the current state.

# Which Wiki Software?

There are several open source wikis: [DokuWiki](https://www.dokuwiki.org/dokuwiki), [MediaWiki](https://www.mediawiki.org/wiki/MediaWiki), [XWiki](https://www.xwiki.org/xwiki/bin/view/Main/WebHome), ... See [Comparison of wiki software](https://en.wikipedia.org/wiki/Comparison_of_wiki_software)

I worked with DokuWiki, MediaWiki and Confluence. Today I would choose DokuWiki, but before I would have a look at modern alternatives. 

This text is about how to use a wiki system for a intranet knowledge base.

# #contact-channel

It is feasible to publish a #contact-channel on every wiki page. If a reader of the page has a question that is not answered on this page, he should know where he can ask his questions.

This could be a chat-channel, an email address or a role. It is feasible to avoid particular people, since they can be on holiday, busy or [hit by bus](https://en.wikipedia.org/wiki/Bus_factor).

# Default permissions

The default should be: Everybody can create/update/delete pages. Only a few pages should be restricted.

# Delete/Undelete

If you delete a page, you should be able to undelete it. 

This is no possible in Confluence. Deleting a page is not allowed for most users. And undelete is not possible, too. You need to be space-admin to undelete the page you deleted.

# Avoid Spaces

Most Wiki systems allow you to create several spaces. This sounds feasible in the beginning. 
This way department D1 can create
pages in space-D1 and department D2 can create pages in space-D2 and there will be peace since these spaces don't overlap.

No, please avoid spaces. Sooner or later Term "X" will get explained twice. Once space-D1 and once space-D2. Now an employee of department D3 wants to learn about "X". What should he do?

This "peace" you get with spaces, will lead to [information silos](https://en.wikipedia.org/wiki/Information_silo).

Next argument against spaces: Imagine you are new at the company and you realize that there is no page up to now for "foo".

You want to add value to the wiki and you want to create a page about "foo". Now you are faced with the question "Which space should I use?". Likely, the new and motivated employee can't get an answer to this question soon. Then it is Friday evening, then the weekend, and on Monday there are so many different things, that he will forget to create a page for "foo".

Without spaces, it is easier to create new pages.

The big benefit of a central intranet wiki is that you have **one** place for the single source of truth. If you use spaces, then this gets lost, because you don't have one source anymore, you have several sources. Each space has its own "world".
That's why I prefer to work with exactly one space.

# Only send email notifications if requested.

Some Wiki engines love sending mails. As soon as you edited a page one time, you always get an email notification if someone else updates the pages. 

This slows down the process.

Imagine you want to change one small thing on a page. You know: "If I will change this page, then ten people will get a notification about this change". And what will you do? You won't do this little clean up, since you don't want to annoy people with this small change.

Yes, I know that there are some special buttons like "Don't notify watchers", but lets look at the default.

If someone wants to get notifications if a page changes, then there should be a simple way to subscribe to changes.

But if you don't subscribe to changes, then you should not get notifications.

General rule: Avoid [Information overload](https://en.wikipedia.org/wiki/Information_overload)



# Stop dreaming: It will never be perfect

An intranet wiki will never be perfect. There are two competing goals:

* Crisp overview
* detailed information

You can have a perfect crips overview, but then the detailed information will be missing. Or you provide detailed information, then the crisp overview gets lost.

If you are responsible for the intranet wiki and people complain about this: Listen to their **particular** issues. If it just general and vauge complaining, tell them that you need concrete proposals for improvement.

It is likely that you need to repeat "I need concrete proposals for improvement" again and again.

# Dealing with outdated pages

Create a simple guideline how you want to handle outdated pages. You should keep in mind that the one that notices the outdated page should have nearly no effort. Otherwise this person won't tell you the fact and he will silently leave to something else.

One pragmatic solution would be to ask on the corresponding #contact-channel.


# I need your feedback

Please tell me what is nice and useful or wrong and useless. Please write me an email (info.intranet-wiki-guidelines@thomas-guettler.de) or [create an issue](https://github.com/guettli/intranet-wiki-guidelines/issues).
