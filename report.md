# Report #
# LINGI2401 - Open Source strategy for software development #

*Date: 2018-12-11*

*Author: Pablo Gonzalez Alvarez*

## Table of contents ##

[Introduction](#introduction)

[2018-09-25](#2018-09-25)

[2018-10-09](#2018-10-09)

[2018-10-30](#2018-10-30)

[2018-11-06](#2018-11-06)

[2018-11-13](#2018-11-13)

[2018-11-27](#2018-11-27)

[2018-12-04](#2018-12-04)

[2018-12-06](#2018-12-06)

[2018-12-10](#2018-12-10)

[Conclusion](#conclusion)

[References](#References)

## Introduction ##

This report was made as a journal as advised by the professor at the beginning of the semester. It contains my evolution through the last few months. The references are available at the end of this report.

The project I tried to contribute to is : [Firefox Focus, aka Firefox Klar][ff].
It is a quite recent mobile browser which is privacy-oriented. I choose that project because I believe it is important to have control over our data. Firefox Focus is a step towards that as it tries to block trackers in whatever form they may appear. Firefox Focus uses the [Kotling language][kotling-lang] for the Android version of the app.


## 2018-09-25 ##

Today I went to the [Open Source strategy for software development][2401] class.

We have to choose an open source project we which to contribute to. The teacher, Lionel Dricot, told us to work preferably on something we like and use. I was thinking of working on the [Anki project][anki-web], which I use a lot for my studies. They have two repos on GitHub:

* for [desktop computers][anki-desktop];
* for [Android devices][ankidroid].

The first one is under [AGPLv3][anki-desktop-license]. The second one is under [GNU GPLv3][ankidroid-license]. Hence both are open source.

I will check both to see on which one I will prefer working on, or if I prefer contributing to another project altogether.

Since this is a course about using open source, I am writing this report in a git repo using a MIT license. The report will be organized as a log. References will be available at the end of this report.

## 2018-10-09 ##

I haven't really taken the time to think about which project to contribute to. Other projects that I find interesting:

* [Exercism][exercism]
* [Firefox Focus, aka Firefox Klar][ff]
* [Rust][rust]

From the [course repo][2401], here are a few questions to ask myself:

> How to explore a project?
* Who are the people taking the decisions? (usually, the core commiters)
* What are the main communication channels? (are the deciders available on it?)
* What's the vision for the near future?
* What are the current challenges?

> How to contribute to a project?
* Start with the bug tracker: what are the "easy issues"
* Present yourself on the communication channel, ask for suggestions to "start to play with the code"
* Build the code and use your own build!
* Have a motivation: "In the end, I want to bring to this project this and that!"
* Identify controversial issues and widely discussed issues in the bug trackers

> Bug triaging
* Find bugs that have been unanswered by developers
* Try to reproduce them. Put yourself in the shoes of the developer.
* Add any information that could help the developer.
* If you can't reproduce, ask the initial reporter for more information (usually, there's a template)
* Use tags and/or ping appropriately. Mark duplicates.

> Documentation
* Look at the current documentation. If there's none, ask the preferred way to start one.
* Put yourself in the shoes of a new user. Write down what is not clear in the documentation.
* Take screenshots using the development version if the interface is frozen.

> Take part in the life of the project
* Maintain the website
* Organise/participate in AFK events
* Help with merchandising
* Write blog posts, share on social medias
* Give conferences, make presentations in local events
* Become a local point of contact

## 2018-10-30 ##

I decided to work on [Firefox Focus/Klar for Android][ff] and just forked and cloned the repository. Not sure what I will work on exactly but by playing with the code and since I use the android app daily, I'll eventually find something I think needs improvement or propose a new feature. By the way, [Firefox Focus/Klar][ff] is running on a [Mozilla Public License 2.0][ff-license].

## 2018-11-06 ##

I just had an idea for a possible feature. There is no way to show the caption of an image. Not sure how to proceed right now. Try to do it immediately? Or first propose the feature, see the reactions on the repo, and then code it?

## 2018-11-13 ##

I found an interesting resource today from Mozilla. It is a guide on [Contributing to the Mozilla code base][mdn-web-docs]. There is a lot of information to read. Here are a few things I learned that caught my attention:

* Mozilla uses a bug tracking system called Bugzilla, aka b.m.o (for [bugzilla.mozilla.org][bmo]);
* There is a [student-project tag][mo-student-projet-kw] in [b.m.o][bmo]:
    - this might be a good place to find a project for the [LINGI2402 course][2402];
* Mozilla has a very well made website to find a first contribution called [Codetribute][codetribute];
* Basically how to contribute on a Mozilla project:
    - I will come back to this documentation if I have doubts for a particular step;
* A wiki on how to get involved with [Mozilla mobile projects][mozilla-mobile-wiki];
* There are [Mozilla Community Participation Guidelines][mozilla-guidelines];
    - these gives a good idea on the community's views, which I believe are very respectful one's;
* [Firefox Focus][ff] has a [mailing list][ff-mailing-list] which I subscribed to:
    - we'll see if it has interesting stuff, if not I'll opt out quite rapidly;
* [Firefox Focus][ff] has also an [IRC channel][ff-irc]:
    - I tried to connect to it with my default IRC client (Empathy), but it doesn't work. I get an "Network Error" message, but it doesn't tell me more... I tried looking on the web for a solution. Still no success. By the way, I think it is the first time I will connect to an IRC channel.
    - I used another IRC client, a web-based one called [mibbit][mibbit]. I found a reason why it isn't working: _"You need to be identified to a registered account to join this channel"_. I'll try some other time, I don't know how to register for an account for the moment.

## 2018-11-27 ##

I had a very frustrating phase while playing with the [Firefox Focus][ff] repo. I wasn't able after some hours to just run the app. I didn't think it could be so daunting, or maybe I just forgot how it could be. Trying to find some new hope. Note to my future self: "Audendum est; Venus ipsa audaces adiuvat". Which could be translated as "Be bold; Venus herself favors the bold". I am not at all religious but that will help me find some courage later on to try again. By the way, this is an ancient proverbial maxim a very good friend told me once. I remind myself of that when I'm struggling with something.

## 2018-12-04 ##

I just filed my first issue on the [Firefox Focus repo][ff]. It is a feature request. The issue is available  [here][ff-issue].

This is actually the first issue I file on an open source project where I don't know the people behind it. I am quite excited, let's see how the community will react!

While writing the new issue, there was an interesting helpful [resource][ff-contribute]. I checked it out, and for new features I followed the given [guidelines][mozilla-android-project-contribute]:

> **If you want to work on a new feature**, *always file an issue first* and wait
for our team to discuss it. We want to ensure all teams (product, ux, engineering)
have an opportunity to provide feedback. **Pull requests for unsolicited features
are unlikely to get merged.**

By the way, I noticed a bug on the xkcd.com website when it runs on Firefox Focus. Basically, it doesn't show the whole page (it is concatenated on the left side) and you cannot zoom out to show it (on both phone and tablet). I do think it is related to Firefox Focus "mobile" view, since when I switched to the desktop version of the site there is no problem (in the 3-dots menu, tick the "Request desktop site" box).

## 2018-12-06 ##

No reactions on the issue and I haven't found a way to contact anyone from the repository directly for the moment. About the IRC channel, I have found a [clue][superuser] on how to register for an account. I have the impression I am on a quest right now, with many obstacles on the way. Basically I did the following steps:

* connect to the Mozilla IRC server;
* asked for help to NickServ, a robot, with `\msg NickServ help` and with `msg NickServ Help REGISTER`. It told me to use the command `\msg NickServ REGISTER password email` to register for an account;
* confirm my email address;
* and it works, finally!

I have found the problem I had the other day with the repo. I thought I had Android SDK installed on my system, but it wasn't...! Now it is working... Let's finally test the app a bit.

## 2018-12-10 ##

I tried to get help on the IRC channel without any success the last few days and still no reaction on the issue. I guess people are quite busy at this period of the year. I have tried to run again the app, without success although I know which file needs to be changed (`WebContextMenu.kt`) but I am not sure where to start, since I can't run it to test it.

## Conclusion ##

My journey through this project was quite an [adventure][youtube]. Next follows what I learned from it.

First finding a project is easy, there are a lot of them out there. This is quite incredible since, in theory, it makes it possible for every single person in the world to contribute to projects without necessarily having programming skills.

Further on, trying to contribute is quite another story, at least for this project. In deed, the most difficult part is to make contact with a person behind Firefox Focus to get some help. Both the mailing list and the irc channel seemed to be dead. I believe this is due that it is still a small community.

Moreover, the documentation given on the project repository is well made but not sufficient for a beginner like me. I spent more time trying to solve problems than being able to contribute on the project. Some of these problems  are still unsolved, and finding solution takes a lot of time. Not being able to get a first contact didn't help either.

To put it in a nutshell, although I didn't make a pull request, I however discovered a few things on the way: how to fill a detailed issue on GitHub; how important it is to have feedback for a project to both do something useful and keep the motivation; learned a lot about how Mozilla organizes it's open source community; the basics of the Kotlin language used for Android development; working on an open source project is more difficult than it seems.

As Confucius once said: "The gem cannot be polished without friction, nor man perfected without trials."

<!-- ## Links ## -->

[2401]: https://github.com/ploum/lingi2401 "Open Source strategy for software development"
[2402]: https://uclouvain.be/en-cours-2018-lingi2402 "Open Source Project"
[anki-desktop]: https://github.com/dae/anki "Anki for desktop computers"
[ankidroid]: https://github.com/ankidroid/Anki-Android "AnkiDroid: Anki on Android"
[anki-desktop-license]: https://github.com/dae/anki/blob/master/LICENSE "Anki desktop license"
[ankidroid-license]: https://github.com/ankidroid/Anki-Android/blob/master/COPYING "AnkiDroid license"
[anki-web]: https://apps.ankiweb.net/ "Anki - powerful, intelligent flashcards"
[bmo]: https://bugzilla.mozilla.org/ "Bugzilla"
[bmo-student-projet-kw]: https://bugzil.la/kw:student-project "Keywords: student-project"
[bugzilla-docs]: https://developer.mozilla.org/en-US/docs/Mozilla/Bugzilla "Documentation about B.m.o."
[codetribute]: https://codetribute.mozilla.org/ "Find your first code contribution with Mozilla"
[exercism]: https://github.com/exercism/exercism "Exercism"
[ff]: https://github.com/mozilla-mobile/focus-android/ "Firefox Focus for Android"
[ff-contribute]: https://github.com/mozilla-mobile/focus-android/blob/master/CONTRIBUTING.md "Contributing to Focus for Android"
[ff-issue]: https://github.com/mozilla-mobile/focus-android/issues/3997 " Add title attribute in image context menu #3997"
[ff-irc]: irc://irc.mozilla.org/focus "Firefox Focus IRC"
[ff-license]: https://github.com/mozilla-mobile/focus-android/blob/master/LICENSE "Firefox Focus License"
[ff-mailing-list]: https://mail.mozilla.org/listinfo/firefox-focus-public "Firefox-focus-public"
[kotling-lang]: https://kotlinlang.org/ "Kotling Programming Language"
[mdn-web-docs]: https://developer.mozilla.org/en-US/docs/Mozilla/Developer_guide/Introduction "Contributing to the Mozilla code base"
[mibbit]: https://mibbit.com/ "Mibbit IRC WebChat"
[mozilla-android-project-contribute]: https://github.com/mozilla-mobile/shared-docs/blob/master/android/CONTRIBUTING_code.md "Contributing code to Mozilla's Android projects"
[mozilla-guidelines]: https://www.mozilla.org/en-US/about/governance/policies/participation/ "Mozilla Community Participation Guidelines"
[mozilla-mobile-wiki]: https://wiki.mozilla.org/Mobile/Get_Involved "Mobile/Get Involved"
[rust]: https://github.com/rust-lang/rust "The Rust Programming Language"
[superuser]: https://superuser.com/questions/106965/how-do-i-identify-with-services-on-irc "How do I identify with services on irc"
[youtube]: https://youtu.be/dDKVKG3ESsk?t=2m12s "I'm going on an adventure!"

## References ##

<!-- TODO: find a nicer way to use the refs, which type of refs and cites? -->

* 2401: https://github.com/ploum/lingi2401 "Open Source strategy for software development"
* 2402: https://uclouvain.be/en-cours-2018-lingi2402 "Open Source Project"
* anki-desktop: https://github.com/dae/anki "Anki for desktop computers"
* ankidroid: https://github.com/ankidroid/Anki-Android "AnkiDroid: Anki on Android"
* anki-desktop-license: https://github.com/dae/anki/blob/master/LICENSE "Anki desktop license"
* ankidroid-license: https://github.com/ankidroid/Anki-Android/blob/master/COPYING "AnkiDroid license"
* anki-web: https://apps.ankiweb.net/ "Anki - powerful, intelligent flashcards"
* bmo: https://bugzilla.mozilla.org/ "Bugzilla"
* bmo-student-projet-kw : https://bugzil.la/kw:student-project "Keywords: student-project"
* bugzilla-docs https://developer.mozilla.org/en-US/docs/Mozilla/Bugzilla "Documentation about B.m.o."
* codetribute: https://codetribute.mozilla.org/ "Find your first code contribution with Mozilla"
* exercism: https://github.com/exercism/exercism "Exercism"
* ff: https://github.com/mozilla-mobile/focus-android/ "Firefox Focus for Android"
* ff-contribute: https://github.com/mozilla-mobile/focus-android/blob/master/CONTRIBUTING.md "Contributing to Focus for Android"
* ff-issue: https://github.com/mozilla-mobile/focus-android/issues/3997 "Add title attribute in image context menu #3997"
* ff-irc: irc://irc.mozilla.org/focus "Firefox Focus IRC"
* ff-license: https://github.com/mozilla-mobile/focus-android/blob/master/LICENSE "Firefox Focus License"
* ff-mailing-list: https://mail.mozilla.org/listinfo/firefox-focus-public "Firefox-focus-public"
* kotling-lang: https://kotlinlang.org/ "Kotling Programming Language"
* mdn-web-docs: https://developer.mozilla.org/en-US/docs/Mozilla/Developer_guide/Introduction "Contributing to the Mozilla code base"
* mibbit: https://mibbit.com/ "Mibbit IRC WebChat"
* mozilla-android-project-contribute: https://github.com/mozilla-mobile/shared-docs/blob/master/android/CONTRIBUTING_code.md "Contributing code to Mozilla's Android projects"
* mozilla-guidelines: https://www.mozilla.org/en-US/about/governance/policies/participation/ "Mozilla Community Participation Guidelines"
* mozilla-mobile-wiki: https://wiki.mozilla.org/Mobile/Get_Involved "Mobile/Get Involved"
* rust: https://github.com/rust-lang/rust "The Rust Programming Language"
* superuser: https://superuser.com/questions/106965/how-do-i-identify-with-services-on-irc "How do I identify with services on irc"
* youtube: https://youtu.be/dDKVKG3ESsk?t=2m12s "I'm going on an adventure!"


<!-- Final -->

<!-- TODO: read the report's content and correct-->
<!-- TODO: check for typos -->
