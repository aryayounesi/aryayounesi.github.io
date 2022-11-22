# The Demerit and Squalor of Lightweight Markups

So far, I have discussed lightweight markups concepts and attitudes in general, and their importance and role; To this point it has been cleared, I hope, that we do need lightweight markup languages for different reasons. Next reasonable question to ask would be: given the fact that there are a couple of lightweight markups, **why they did not become popular among all people?** In other words, what demerits and squalor deprive lightweight markups from being used by all people? In this article some topics have been discussed which are universality of lightweight markups regarding **all natural languages**, **accessibility for people with special needs**, and **common people needs**. Assessing a few examples, i.e., `markdown`, `textile`, `ReStructuredText`, `Asciidoc`, and to some extent, `djot` (which is reserved for a separate discussion), It has been concluded that `textile` and `djot` are two outstanding lightweight markups. Although, to the moment `textile` are at the top of the list, but as `djot` are in its childhood future development may push it to the top.
Before any discussion, here we need a few clarifications.

## Terms and Premises

Perhaps, a wise selection of terms and samples to continue would be two term: **_lightweight_**, and, **_popularity_**. Previously, I discussed very briefly the meaning and criteria for **Lightweightness** of a markup, which was using the least number of rules and tags and symbols for the language; that makes the markup easy to use and remembrance of rules and tags. However, a concept like _Lightweight_ never could be absolute, objective and concrete; Always, there is a shade of disagreement, but as humans we know how to solve such a vagueness for our practical purposes. While, here we have to clear about one point: **decreasing the number of rules and tags should not remove basic needs**; To be in the same context, let us define **basic needs as any need in writing whose elimination spoils the final formatted text**. Thus, removing an option that is needed for an original need in writings is not acceptable. Now, we have to deal with the term _Popularity_ and a selection of lightweight markups, then the main issue would be discussed.

### Popularity and its Implications

1. by **popular** I mean popular among common people, or being used in different heterogeneous communities. Based on this:

    - a. the raw, pure number of users of a lightweight language does not prove its popularity. because, e.g., ReStructuredText is popular among Python programmers and Pythonists are a big relatively big community now. using ReStructuredText among them is a part of their _cult_ more than indication for usefulness of the language; Not that ReStructuredText is not good, which is good for real, but the point is that why other communities do not use it in their documentations and writings;
    - b. even if, to stick to previous example, a significant number of programmers and IT geeks would have use RST, that number does not justify _popularity_; because still it is a sub-culture, a habit among a big group with common interests (IT). A popular markup will be used by all, even common people with no interest in IT.

2. As far as we are discussing the reason of popularity of a given lightweight markup, that question should be break in two part:

    - a.the first thing that should be met is the possibility of its universality, that is: **Does that markup has all qualifications for being popular?** otherwise, asking why it is not popular is irrational. If it could not serve the needs of all people from different context, why should be popular; actually, if it lacks necessary features and still becomes popular, we should ask why it have been popular;
    - b. the second question, after the previous one, is the subject matter.

### Prototype Lightweight Markups

Existing dozens of lightweight markups, makes it necessary to select a bunch of them based on a few loose criteria, like their relative popularity, qualifications and perhaps safety. My selection would be these: `markdown` flavor group in general which consists of `commonmark`, `extra markdown`, `R markdown`, etc. `ReStructuredText`, `asciidoc`, and `textile`. these markups are well-known, relatively well-receipted and have many implementations and tools. I have [djot](https://github.com/jgm/djot) in my mind which is the newest one designed by **John MacFarlane** very recently, but as I want to write about it in another article, it has been ignored here but I will point out to some of its features.
One may find it strange that `textile` counted, that has a reason: among listed markups `textile` provides many necessary features that others lack. Note it worthy that, among mentioned markups, `ReStructuredText` define its goal mainly for professional documentation with no strive for becoming multi-purpose markups; as it has been stated in its official [documentations](https://docutils.sourceforge.io/docs/ref/rst/introduction.html#goals):

> The primary goal of reStructuredText is to define a markup syntax for use in Python docstrings and other documentation domains, that is readable and simple, yet powerful enough for non-trivial use.

Others claimed such a goal. However, single-purpose mission would not cancel any critical aspect we are going to discuss; Because, the IT community should let individuals with special needs to be involved. Therefore, all aspects should be considered, even documentations for projects.
These list is not inclusive, but it is exclusive for sure; However, no matter if it is not inclusive, we could build the foundation and add any markup to the process.
Here we should go to discuss the core problem.

## Universality of Lightweight Markup Languages

Having in mind these bases, we should take a simple road to reach a reasonable position to answer the question; In the point (2.a), it has been stated that a requirement for the next question is the assessment of universality of a given lightweight markups; Dealing with this issue might seems a simple question, but it is not. Universality or the possibility of its globality, require take all possible cases into account: all natural languages (including lives and dead ones), cultures, nations, groups (either minorities or majorities), different communities and different groups of people in all societies. Therefore, a lightweight markup needs to meet basic features to be used by all.
Here I would jump to the core of the problem to make my point; among above mentioned groups at least three major division is more important:

1. first is **natural languages with different system of writings** to languages that mostly use Latin scripts and style or Latin-like scripts and style. To name a few, **Arabic, Persian and Hebrew** language use very different style and letters and direction, since they are **Right-To-Left** (_ RTL _) languages, unlike most other languages whose direction is **Left-To-Right** (_ LTR _);
2. second important group is **_people with special needs_**, individuals that their physical or mental conditions imply specific features;
3. third group would be **common people**, who are not IT geeks and use markups for daily use or common writings.

These three have their own weight in the situation: the first group makes globalization possible, the third one cover the big number in any given local society, and the second one fulfills human right requirements, which we will discuss it. I am not going to keep you waiting for the conclusion: all existed lightweight markups fail in fulfilling the basic needs of at least of these three; however, one are better, meaning `textile`.
In the following we are going to look at these issues, and accessibility would be at the first place, since it is related to humanity.

### Accessibility in Lightweight Markups

Regarding accessibility and people with special needs, none of lightweight markups have been cared about; as if their designers and developers think there is no individual with special needs, at best, or they just simply do not care about the issue. Therefore, as far as we are looking for deliberate, on purpose accessibility inclusion, no clue would be found, which solely tells a lot. Why developers do not care about their fellow humans that have special needs, particularly when we all may end up in some physical or cognitive disabilities in our lives.
The issue, however, could be see from a different point of view, which is exploring those markup if any of them accidentally has more compatibility with accessibility. It is possible that a few of them, if any, would be more appropriate regarding people with special needs. In such a way, `ReStructuredText` could not seen as appropriate; for, its syntax is complicated and needs good vision and focus. This goes to `Asciidoc`, as well, since its complicated syntax would not let any accessibility. As to `markdown`, especially I am referring to `commonmark` whose syntax is enhanced, it is better than `ReStructuredText`, although not such better that we could say it is good. To be clear, I am not with special needs, so I could not have a good understanding of the situation except for a basic knowledge on tools and software for accessibility. Based on this common knowledge it could be said that writing down **back-ticks**, for example, is not an easy task for _ talkback _ software and voice-oriented applications; Also, the backtick key is not among well-known keyboard keys and locates in different places in different keyboards. That is a major problem for people with blindness or impaired vision. Furthermore, suppose a person with impaired vision trying to write, or read, a `RST` or `MD`, such small character would not be easy to see. The backtick problem applies to `asciidoc`, as well. Additionally, the obligatory indentation in lists and blocks in RST and markdown cause another problem which is not easy to solve: without counting by seeing it, how it could be possible to know whether it is in correct syntax or not? The _Backtick_ problem could be dealt with by plugins/extensions or adding some tests to tools.
Finally, the most problematic one is `alt` tag in images and visual objects; `Commonmark`, `Markdown`, `textile`,  and `ReStructuredText` provide a plain way for `alt`, while `asciidoc` relies on attributes with no direct indication in its [documentation](https://docs.asciidoctor.org/asciidoc/latest/macros/images/) (the caption is different matter even if it could provide textual description when `alt` is absent). However, If it is possible that add direct `html` codes for that, which could not be added in the right place, it is not that markup, but it is by virtue of `HTML` that those markups cover their defects.
pertaining one remaining lightweight markup, i.e. `textile`, one could say that this excellent and underscored markup is the most suitable one in case of accessibility; Backticks are not important symbol in it, more importantly it has an standard option for including `alt` tags. For [textile](https://textile-lang.com/doc/images) the `alt` text would be put between parentheses, as:

```!/photo.png(the image is ...)!```

this syntax provides `html` codes as:

``<img alt="the carver" src="/image[dot]png" title="the carver" />``
such a possibility in `textile` increase its value by far; Unfortunately, while it provide many basic option that others do not, it has been ignored so far. In the following lines we see that `textile` has many merits and features to meet needs of all people. To be fair, `djot` provide `alt` tags in similar way (but still it has backticks in its syntax). Other than accessibility of writing for people with special needs, there is another problem which is the readability of documents for **screen readers** (voice-oriented user interactive software comes under what has been discussed), and related issues (like screen readers combined with translators). Pertaining readability by screen readers, that has been told that one fundamental aspect of readability of a document produced by a lightweight markup is its language specification; This particular issue will be discussed below. 

### Localization and Different Systems of Writings

Another realm in which many lightweight markups fail is their consistency with different systems of writing, by which I mean mostly writing systems in **right to left** direction, that is the case for **Arabic, Persian and Hebrew, Kurdish, Pashto, Urdu, Kashmiri**, _Turkish and Azari _ (traditional letters are Arabic-derived that are in use still in parts), etc. In addition, traditional **mandarin, Japanese and Korean** are from **top to button**, but in recent decades they quit it, using different direction; As far as, the writer of those languages are satisfied it is not our business(1). The **directionality** in writing is essentially a convention that any direction has its cons and pros; Contemplation about it basically is a kind of guessing game rather than scientific theories(2). There are, just with a raw data for Arabic, Persian, Kurdish, Urdu, and Hebrew (3), approximately more than **740 million** people all over the world with **RTL** (_right-to-left_) directionality. Such a figure should makes us aware of its significance. Now, how do these lightweight markup languages support them? the answer would be: poorly and unsatisfying in general, but once again `textile` are outstanding in this matter.
`asciidoc`, with a exhausting number of syntactic rules, along with `ReStructuredText`, do not bother themselves with the plurality of languages and different directionality, no single one indication for users with RTL; Although, there are ways to inject codes to get correct output but it is either by accident or a kind of forcing the renderer to do it. All `markdown` family apparently are not aware of RTL systems of writing, but in any case, inline style feature able users with `html` knowledge to manage the output; However, it is for inline specification and does not apply to the whole document. Thus, even if it is an option to specify the directionality and also the language, in blocks and lines level, the final document would be a chaos of inline `CSS`; The problem is in any case parsed document would be either in English or without a language specification. When we are writing an English piece of words that has a few sentence in a different language, e.g. Persian, it is fine to pass the language and direction to the document; therefore, in a big paper we have a few inline style, but how about a document whose language and directionality is different? that produce a mess.
Suppose we want to write an Arabic document in markdown or textile; for any paragraph or block we have to pass the `lang` and `dir` attributes to the document; hence, for any paragraph, list, table, etc. we have `html` codes like:
`<p style="dir=rtl; lang=ar">`
`<h1 style="dir=rtl; lang=ar">`
`<li style="dir=rtl; lang=ar">`
`<div style="dir=rtl; lang=ar">`
while, all we need is just language declaration and direction in the `head` section after document type declaration, as:
`<!DOCTYPE HTML>`
`<html lang="ar" dir="rtl">`
this way those codes are not needed. Besides, why a lightweight markup would be valuable when such a big number of codes should be included? this is not lightweight anymore. Additionally, make common people who may not known `html` to do so is not practical. `textile`, `djot`, and in a inappropriate way`markdown`, provide a way to specify language and direction for parts of documents but no way for global specification. This could not be accepted in anyway. If an open source lightweight markup is not open-language and open-culture could not be of any valuable.
I am a polyglot speaking Kurdish (mother tongue), Persian (native), English, Arabic, and a little Latin and Greek; There is no way for any of them to push away others. But whenever I want to write in Persian, Arabic or Kurdish I have to use HTML, ODT, or plain text (format it later). It is not understandable that lightweight markup languages are all Latin-script-centric. **Building a language and a culture takes at least a couple of centuries, while designing a lightweight markup takes a few months; abandoning a markup and preserving a language for a culture is the reasonable decision in this situation.**

### Languages Specification and Accessibility

It has been stated above that this issue leads to more problem other than complexity; when the language, particularly, unspecified screen readers and translation systems could not behave in a desirable way. Even if screen readers and translators could detect the language, for most of languages there are more than one accent, so how the software should deal with them? it is unknown. Although, it is not the end of story: **lightweight markups produce HTML documents that are not accessible, while the HTML itself does not have accessibility problem**; that is, HTML has all needed features including accessibility options, but when a lightweight markup document parsed and converted to HTML it has no language specification. Therefore, the problem with languages is more fundamental.
Giving optional rules for declaring language and direction would not be such impossible.

---

#### notes

1. note it I do not know those languages and have no familiarity with related cultures, so simply this statement is subject to further discussion by others with better knowledge; you can open discussion in [github](https://github.com/aryayounesi/aryayounesi.github.io/discussions).
2. for an introduction see this [link](https://www.babbel.com/en/magazine/right-to-left-languages); apparently the title of it, i.e. _"Why Is Most Language Read From Left To Right?"_ represent Occidental mindset that might ask the question, but the text suggesting the true position.
3. data are from [ethnologue](https://www.ethnologue.com/language/) that its methods need calculation since mother tongue (L1) differentiated from natives (L2).






