# Documentation in Intranets: My point of view

> "Without clarity of speech man is only a garden gnome" (German pop music band "Element of Crime" in the song "Alle vier minuten")

I maintain documentation in intranets for fun and provit. I like:

* [Single Source of Truth](https://en.wikipedia.org/wiki/Single_source_of_truth)
* [Canonicalization](https://en.wikipedia.org/wiki/Canonicalization)
* [Hyperlinks](https://en.wikipedia.org/wiki/Hyperlink)

With the following text I would like to share my findings with you.

Keep in mind, that this is my personal opinionated point of view. Read them and create your own point of view.

Unfortunately there is no clear term for the topic I write about. Here are some examples:

* Documentation in intranets
* Internal knowledge-base
* Wiki
* Some call it like the tool: Sharepoint, Confluence, Zendesk, Jive, ...
* Or just "Intranet"

I know that an intranet is more than the collaboratively edited content, but for this article I would just use the term "Intranet Wiki".

Raising obviousness is my passion. Our modern infrastructure is based on roads, water/gas/electricity supply. 
Clean, simple docs are like good roads in a knowledge-worker environment. 

Raising obviousness helps to increase the efficiency.

If something is unclear to me, then it is very likely that several other collegues have the same issue (but just don't talk about this).

If something is unclear, I seek the answer (like everybody) and then I update the central docs (only few people do this).

So it helps twice: I learn, and the learning process for other employees get improved. 
But you need to be careful: Too detailed information won't help (and gets outdated too soon). 
My goal is to provide a clear terminology and an overview. 

# What is a Intranet Wiki ?

* An Intranet Wiki is a tool on which users collaboratively edit content.
* This content is available for all employees in a company and it is not visible on the world wide web.
* One term is explained on one page. This page is accessible via [a canonical URL](https://en.wikipedia.org/wiki/Canonicalization#URL).

Every company has its terminology. For new employees, it is very helpful to have a definition of the terms which
are custom.

But a central Wiki is useful to improve the communication between departments, too, because the terminology between departments differs.

# Difference between an Intranet Wiki and Wikipedia

Wikipedia pages are often very detailed. Usually, it makes no sense to explain every detail in an Intranet Wiki.

An Intranet Wiki should provide an overview. Historical details should be removed or put onto an second page to focus on the current state.

# "Fancy Blob Posts" vs "Boring Docs"

You could call this "docs vs news", too.

During the COVID-19 lock-down it got very apparent. There are two ways to deal with information.

You can create news or blog posts: emotional text about the current state. It will get outdated soon. Three days later the situation is
different and you can create a new blog post.

Or you can go the less emotional, more boring solution: You have one static page per topic, and this page gets updated. Most modern tools even allow you
to greate a "diff". For interested readers, the diff shows the changes which happened during the last days.

Be aware of those two completely different ways to handle information.

I prefer the boring solution: docs instead of news. Have a look at the blog post way: Who cares for them, if things change? Who will update hyperlinks which lead to nowhere? I most cases nobody has time for this.

But you can have the best of both worlds: A fancy news channel full of emotions, which sometimes announces changes in the central and boring documentation.


# Which Wiki Software?

There are several open source wikis: [DokuWiki](https://www.dokuwiki.org/dokuwiki), [MediaWiki](https://www.mediawiki.org/wiki/MediaWiki), [XWiki](https://www.xwiki.org/xwiki/bin/view/Main/WebHome), ... See [Comparison of wiki software](https://en.wikipedia.org/wiki/Comparison_of_wiki_software)

I worked with DokuWiki, MediaWiki, Trac, Github and Confluence. Today I would choose DokuWiki, but before I would have a look at modern alternatives, since I am not 100% happy with it.

This text is about how to use a system for an intranet knowledge base. Choosing the right system is a different topic.

# Drafts needed?

Simple wiki systems don't have drafts. Drafts are not realy needed. If someone wants to change a page he/she should go ahead and change it.

If you want to discuss your changes before actually changeing the page, then you have a lot of alternatives to drafts: You can create copy of the page and work on this copy. Or you use a  [Collaborative real-time editor](https://en.wikipedia.org/wiki/Collaborative_real-time_editor) like GSuite, office365 or Nextcloud.

If the wiki system provides drafts, then one feature is important: Sharing the draft should be easy. The draft has no value, if you try to share the draft and the people you want check your text get a "Permission denied".

# Default permissions

The default should be: Everybody can create/update/delete pages. Only a few pages should be restricted.

# Delete/Undelete

If you delete a page, you should be able to undelete it again.

This is no possible in Confluence. Deleting a page is not allowed for most users. And undelete is not possible, too. You need to be space-admin to undelete the page you deleted.


# #contact-channel

It is feasible to publish a #contact-channel on every wiki page. If a reader of the page has a question that is not answered on this page, he should know where he can ask his questions.

This could be a chat-channel, an email address or a role. It is feasible to avoid particular people, since they can be on holiday, busy or [hit by bus](https://en.wikipedia.org/wiki/Bus_factor).

More about contact-channels here: [IUA (if unsure ask ...)](https://github.com/guettli/IUA-Channel)


# Avoid contact persons, use contact channels.

> If you want to use a volunteer day, write an e-mail to "emma.sunshine@our-company.com"

What happens if Emma is on vacation?


# Avoid Spaces

Most Wiki systems allow you to create several spaces. This sounds feasible in the beginning. 
This way department D1 can create
pages in space-D1 and department D2 can create pages in space-D2 and there will be peace since these spaces don't overlap.

No, please avoid spaces. Sooner or later term "X" will get explained twice. Once in space-D1 and once in space-D2. Now an employee of department D3 wants to learn about "X". What should he do?

This "peace" you get with spaces, will lead to [information silos](https://en.wikipedia.org/wiki/Information_silo).


Next argument against spaces: Imagine you are new at the company and you realize that there is no page up to now for "foo".

You want to add value to the wiki and you want to create a page about "foo". Now you are faced with the question "Which space should I use?". Likely, the new and motivated employee can't get an answer to this question soon. Then it is Friday evening, then comes the weekend, and on Monday there are so many different things, that he will forget to create a page for "foo".

Without spaces, it is easier to create new pages.

The big benefit of a central intranet wiki is that you have **one** place for the single source of truth. If you use spaces, then this gets lost, because you don't have one source anymore, you have several sources. Each space has its own "world".

Getting to a single source of truth is hard, but worth the effort.

Example: If people are unsure which space to choose, then they soon find an easy way: Let's create a personal space. I call it like my name "Emma Sunshine" and then I am free. Can you feel this great feeling of freedom and relaxed lack of concerns?
Yes, great feeling, but useless in the long run. Will you improve a page which is the space of "Emma Sunshine"? I guess you won't. And if no one improves these pages, they will get outdated soon. Personal spaces are the opposite of collaboration.


Example 2: Team B wants to work on a new topic and discover that a different team 
A started to work on this topic some month ago, but it seems that the process is stuck. 
Team B sees no progress of team B. The pages of team A are outdated.
Team A has its own space, and team B has its own space. What will happen? Team B will take the easy road: 
They will start with new pages in Space B. What will happen to the old pages in Space A? Nothing. 
Team B is motivated to do it better. It is likely that noone of team B will talk to team B.
That's the easy road. That's why I think
working without spaces is better in the long run. If there is only **one** space, then it would be more likely 
that team B would get in contact with team A and
update the old pages, instead of just starting from scratch in their own space.

Starting from scratch feels great. No constraints, no legacy stuff ....

What would be better? Team B should talk to team A and work on **one** joint solution.

# An optional context is better than spaces

How does Wikipedia solve this?

They append the context in parentheses. For example the "Python (programming language)" and "Python (genus)"

# Only send email notifications if requested.

Some Wiki engines love sending mails. As soon as you edited a page one time, you always get an email notification if someone else updates the pages. 

This slows down the process.

Imagine you want to change one small thing on a page. You know: "If I will change this page, then twenty people will get a notification about this change". And what will you do? You won't do this little clean up, since you don't want to annoy people with this small change.

Yes, I know that there are some special buttons like "Don't notify watchers". You know this button, I know this button but the average non-intranet-fanatic does not know it.

If someone wants to get notifications if a page changes, then there should be a simple way to subscribe to changes.

But if you don't subscribe to changes, then you should not get notifications.

General rule: Avoid [Information overload](https://en.wikipedia.org/wiki/Information_overload)

# What to add, and what not

The acronyms JS, CI, HTML, CSS, AFAIK have all one thing in common: If you search for it with your favorite search engine, then you will find an explanation. 

This means there is no need to create a wiki page for it.

Example: CI means [Continuous integration](https://en.wikipedia.org/wiki/Continuous_integration).

But it makes sense to explain the particular way your company does the CI. If you create a page about CI, then start with the introduction. 
Even if you think "everybody knows this". Maybe everybody in the engineering department knows it. But a person without software development knowledge should understand what it is about. It is ok to just copy+paste this from the Wikipedia and create a link from your page to the source.

After the introduction explain your particular set-up. Add the URL where you can access the system (or systems) and add [#contact-channel](#contact-channel) where new users can ask questions.


# Stop dreaming: It will never be perfect

An intranet wiki will never be perfect. There are two competing goals:

* Crisp overview
* detailed information

You can have a perfect crips overview, but then the detailed information will be missing. Or you provide detailed information, then the crisp overview gets lost.

If you are responsible for the intranet wiki and people complain about this: Listen to their **particular** issues. If it just general and vauge complaining, tell them that you need concrete proposals for improvement.

It is likely that you need to repeat "I need concrete proposals for improvement" again and again.

# Fast Feedback

Provide a simple way for every reader to submit his feedback:

* I like this page
* I think this pages looks outdated
* I think this page is not needed any more
* This page is related to URL/other-page
* I am missing "....."

# Page ownership

The feedback which gets sent to a page needs owners. This needs to be explicit. Who will respond to the feedback?

In most cases it is 100% ok, if one person responses to the feedback once a week. That's better then ten people responding to
the feedback from time to time.

# Lists

It helps to get to clear and easy to understand processes if lists are visible and not stored in the brain.

For example: List of departments, list of teams, list of customers, list of roles, list of employees, list of products, 
list of contracts, ...

There is no need to store them in the wiki. If this list is already stored in a different system,
then create a hyperlink to this system.

Hardworking people can cause harm, if they think they can create valuable content by doing copy and paste.

There should be one, canonical, authoritive list. There should not be a second (redundant) list.

# Discussion per page: Great, but ....

Some Wiki Software provides you a way to comment on the page. Sounds feasible at first sight, but .....

The page is common ground. If there was a mistake, it gets updated. 

But you can't update the comment of someone else.

I like the Wikipedia way: There is an extra page for discussions and feedback, but the average user just sees the page and he sees no comments. Only if you are curious and switch to the extra page you see the discussions.

In Confluence you see the discussion immediately. One thing makes it more wired: The first comment is the oldest. It is very likely that the user sees a comment which does not apply any more since the concern in the first comment was already solved several months ago.

# Avoid duplications

If the term "Review" gets used for source code review and for the sprint review, it is likely that misunderstandings will happen. Try to have unique terms. For example use "Sprint-Demo".

# Dealing with outdated pages

Create a simple guideline how you want to handle outdated pages. You should keep in mind that the one that notices the outdated page should have nearly no effort. Otherwise this person won't tell you the fact and he will silently leave to something else.

One pragmatic solution would be to ask on the corresponding #contact-channel.

# "One big glossary page" vs "many small pages"

I recommend "many small pages". Create a page for every term. I know a lot of people don't like this idea, but I don't see an better alternative.

This gives every term a unique and canonical URL. This helps a lot.

Creating hyperlinks which link to a part inside the page (like "#my-term" in https://..../glossary#my-term) are
difficult to handle.

# Free yourself from hierarchies

People like hierarchies. Some examples.

* Org-Charts: On top is the CEO, below him/her the C-level, then managers, then at the bottom the normal workers.

* In the past encyclopedias got sold in collections of book: The first book contained all terms starting with "A"....

* Books have several chapters, and each chapter has several sections.

* The world consists of several countries. Most countries have sub-divisions like "states".

* Local files in your hard-disk get stored in folders, which can contain folders ... Like "C:\Users\YourUsername"

These hierarchical view works for some terms, but not for all.

Imagine you want to buy a new smartphone. If you go to a price comparison website, the website won't show you huge big tree.

It will show you several aspects for filtering and finding the product which matches your needs.

There are inputs for a price range, for the vendor, the size of the internal storage, size of the display, ....

This is not a single big hierarchy. There are several **aspects**.

Back to our topic "Intranets". What does this mean for the structure of intranets?

I say "free yourself from hierarchies": One term, one page. This is like a very long glossary. 

Unfortunately this perspective is new and up to now not wide spread. But slowly this insight grows and 
people avoid hierarchies for intranet pages.

# Approval Process

An approval process will slow everything down. See [Disadvantages of article validation (Wikipedia)](https://meta.wikimedia.org/wiki/Article_validation#Disadvantages)

In the past several projects started with the big goal to be better than Wikipedia. They advertised with
a review and approval process which will result in better results.

AFAIK there is no real alternative Wikipedia. This concept has won. And if you disagree with a particular
part, then go ahead and improve it. No complicated process is between your idea and the world wide visible change.


# If you use the Intranet Wiki for Brainstorming and Dreaming: State this

Most new projects start with enthusiasm. This will result in text like 

> We meet once a week to present the results of the working group.

I would start slow here: Just write down the current facts. Just because you did
this in the last month, does not mean you do this six months later. It is likely
that the working group won't do this regular presentations in the future.

My hint: For brainstorming, dreaming and New Year Resulutions it is better to use GSuite/M365/Nextcloud.

If you use it for brainstorming, then state this at the top of the page.

# I need your feedback

Please tell me what is nice and useful or wrong and useless. Please write me an email (info.intranets@thomas-guettler.de) or [create an issue](https://github.com/guettli/intranets/issues).
