# Report #
# LINGI2401 - Open Source strategy for software development #

## Table of contents ##

<!-- [Introduction](#introduction) -->

[2018-09-25](#2018-09-25)

[2018-10-09](#2018-10-09)

[2018-10-25](#2018-10-25)

[2018-10-30](#2018-10-30)

[2018-11-06](#2018-10-06)

[2018-11-13](#2018-10-13)

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

<!-- # Links -->

[2401]: https://github.com/ploum/lingi2401 "Open Source strategy for software development"
[anki-desktop]: https://github.com/dae/anki "Anki for desktop computers"
[ankidroid]: https://github.com/ankidroid/Anki-Android "AnkiDroid: Anki on Android"
[anki-desktop-license]: https://github.com/dae/anki/blob/master/LICENSE "Anki desktop license"
[ankidroid-license]: https://github.com/ankidroid/Anki-Android/blob/master/COPYING "AnkiDroid license"
[exercism]: https://github.com/exercism/exercism "Exercism"
[ff]: https://github.com/mozilla-mobile/focus-android/ "Firefox Focus for Android"
[rust]: https://github.com/rust-lang/rust "The Rust Programming Language"

## References

<!-- TODO: find a nicer way to use the refs, which type of refs and cites? -->

[1] “Anki - powerful, intelligent flashcards.” [Online]. Available: https://apps.ankiweb.net/. [Accessed: 25-Sep-2018].

[2] D. Elmes, Anki for desktop computers. Contribute to dae/anki development by creating an account on GitHub. 2018.

[3] AnkiDroid: Anki on Android. Contribute to ankidroid/Anki-Android development by creating an account on GitHub. AnkiDroid, 2018.

[4] L. Dricot, Lingi2401: Open Source strategy for software development - ploum/lingi2401. 2018.
