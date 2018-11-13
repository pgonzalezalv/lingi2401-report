# Report #
# LINGI2401 - Open Source strategy for software development #

## Table of contents ##

<!-- [Introduction](#introduction) -->

[2018-09-25](#2018-09-25)

[2018-10-09](#2018-10-09)

[2018-10-30](#2018-10-30)

[2018-11-06](#2018-11-06)

[2018-11-13](#2018-11-13)

<!-- [Conclusion](#conclusion) -->

[References](#References)

<!-- ## Introduction ## -->

<!-- TODO: introduction -->

## 2018-09-25 ##

Today I went to the [Open Source strategy for software development][2401] class.

We have to choose an open source project we which to contribute to. The teacher, Lionel Dricot, told us to work preferably on something we like and use. I was thinking of working on the [Anki project](https://apps.ankiweb.net/), which I use a lot for my studies. They have two repos on GitHub:

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

* Mozilla uses a bug tracking system called Bugzilla, aka b.m.o (for [bugzilla.mozilla.org](https://bugzilla.mozilla.org/));
* There is a [student-project tag](https://bugzil.la/kw:student-project) in [b.m.o][bmo]:
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

<!-- ## Conclusion ## -->

<!-- TODO: conclusion -->

<!-- ## Links ## -->

[2401]: https://github.com/ploum/lingi2401 "Open Source strategy for software development"
[2402]: https://uclouvain.be/en-cours-2018-lingi2402 "Open Source Project"
[anki-desktop]: https://github.com/dae/anki "Anki for desktop computers"
[ankidroid]: https://github.com/ankidroid/Anki-Android "AnkiDroid: Anki on Android"
[anki-desktop-license]: https://github.com/dae/anki/blob/master/LICENSE "Anki desktop license"
[ankidroid-license]: https://github.com/ankidroid/Anki-Android/blob/master/COPYING "AnkiDroid license"
[bmo]: https://bugzilla.mozilla.org/ "Bugzilla"
[bugzilla-docs]: https://developer.mozilla.org/en-US/docs/Mozilla/Bugzilla "Documentation about B.m.o."
[codetribute]: https://codetribute.mozilla.org/ "Find your first code contribution with Mozilla"
[exercism]: https://github.com/exercism/exercism "Exercism"
[ff]: https://github.com/mozilla-mobile/focus-android/ "Firefox Focus for Android"
[ff-irc]: irc://irc.mozilla.org/focus "Firefox Focus IRC"
[ff-license]: https://github.com/mozilla-mobile/focus-android/blob/master/LICENSE "Firefox Focus License"
[ff-mailing-list]: https://mail.mozilla.org/listinfo/firefox-focus-public "Firefox-focus-public"
[mdn-web-docs]: https://developer.mozilla.org/en-US/docs/Mozilla/Developer_guide/Introduction "Contributing to the Mozilla code base"
[mibbit]: https://mibbit.com/ "Mibbit IRC WebChat"
[mozilla-guidelines]: https://www.mozilla.org/en-US/about/governance/policies/participation/ "Mozilla Community Participation Guidelines"
[mozilla-mobile-wiki]: https://wiki.mozilla.org/Mobile/Get_Involved "Mobile/Get Involved"
[rust]: https://github.com/rust-lang/rust "The Rust Programming Language"


## References ##

<!-- TODO: find a nicer way to use the refs, which type of refs and cites? -->

[1] “Anki - powerful, intelligent flashcards.” [Online]. Available: https://apps.ankiweb.net/. [Accessed: 25-Sep-2018].

[2] D. Elmes, Anki for desktop computers. Contribute to dae/anki development by creating an account on GitHub. 2018.

[3] AnkiDroid: Anki on Android. Contribute to ankidroid/Anki-Android development by creating an account on GitHub. AnkiDroid, 2018.

[4] L. Dricot, Lingi2401: Open Source strategy for software development - ploum/lingi2401. 2018.


<!-- Final -->

<!-- TODO: read the report's content and correct-->
<!-- TODO: check for typos -->
