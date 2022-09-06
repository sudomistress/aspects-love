---
title: Understanding Markdown
linkTitle: Markdown # The title of left navigation, optional.
linkTitleIcon: <i class="fas fa-info-circle"></i> # The icon of the link title, optional.
navWeight: 9990 # Upper weight gets higher precedence, optional.
date: 2022-08-30
---

This site makes use of Markdown for changing how content is displayed on a page. This page breaks down different types to help you figure out how to do it.

<!--more-->

{{< alert warning >}}
This page is under construction.
{{< /alert >}}

## General Markdown

### Headers

Every page can be broken down into headers. We highly recommend breaking guides and news into bite-size consumable chunks. You can do this with headers.

Each header starts with #, a space, and then the word you want to use for the header. For our guides, you want to start with 2 # and for each sub section just add another #.

```md
## This is a Section start

### this is a Subsection of sections start

#### There are more things to break down for this section

#### So I am using more and more hashs!

### Hey yo! Another Subsection!
```

### This is a Section start

#### this is a Subsection of sections start

##### There are more things to break down for this section

##### So I am using more and more hashs!

#### Hey yo! Another Subsection!

### Text

Simply typing into a file will result in the words showing up like regular text on the screen. If you want a new paragraph just make sure there is an empty line between the two paragraphs

```md
How will this show up?
```

How will this show up?

```md
Human is in bath tub, emergency! drowning! meooowww!. Swat at dog naughty running cat for steal raw zucchini off kitchen counter spill litter box, scratch at owner, destroy all furniture, especially couch, or touch water with paw then recoil in horror, fall asleep on the washing machine.

I can haz ptracy, but hit you unexpectedly. Wake up wander around the house making large amounts of noise jump on top of your human's bed and fall asleep again crusty butthole but let me in let me out let me in let me out let me in let me out who broke this door anyway stare at ceiling light.
```

Human is in bath tub, emergency! drowning! meooowww!. Swat at dog naughty running cat for steal raw zucchini off kitchen counter spill litter box, scratch at owner, destroy all furniture, especially couch, or touch water with paw then recoil in horror, fall asleep on the washing machine.

I can haz ptracy, but hit you unexpectedly. Wake up wander around the house making large amounts of noise jump on top of your human's bed and fall asleep again crusty butthole but let me in let me out let me in let me out let me in let me out who broke this door anyway stare at ceiling light.

### Bold, Italic, Strikethrough

```md
Make **this word** bold.
```

Make **this word** bold.

```md
Make the _cat_ italics.
```

Make the _cat_ italics.

```md
Strikethrough this ~~thing~~.
```

Strikethrough this ~~thing~~.

### Ordered and Unorder Lists

```md
- Do a dance
- Make a little love
  - Or don't, the choice is yours
  - Cause we're cool like that
- Get down tonight
```

- Do a dance
- Make a little love
  - Or don't, the choice is yours
  - Cause we're cool like that
- Get down tonight

```md
1. Ninja
1. Tanks
   1. Gunborker
   2. Rage Axe User
   3. Emo Boyo
   4. Shiny Shield Suckers
1. Sage
1. Bob
```

{{< alert info >}}
You can use any number you want, it will always put it in numerical order
{{< /alert >}}

1. Ninja
1. Tanks
   1. Gunborker
   2. Rage Axe User
   3. Emo Boyo
   4. Shiny Shield Suckers
1. Sage
1. Bob

## Special Unique MD Shortcodes

The Matriarch has added some special shortcodes to allow for you include Twitch channels and clips to your guides. Our site also comes with some other ones as well!

### Embed YouTube Videos

Sytax is the string of characters found in the URL. As an example:
https://www.youtube.com/watch?v=erWzH5kdiCk can be embeded using this code:

```md
{{</* youtube erWzH5kdiCk */>}}
```

{{< youtube erWzH5kdiCk >}}

### Embed Twitch

When wanting to include Twitch streams or clips/hightlights, please use the following format in your Markdown file.

#### Channel Embeds

```md
{{</* twitch channel channelName */>}}
```

#### Clips/Highlight Embeds

As with YouTube you can ebed highlights and clips by looking at the URL. As an example, https://www.twitch.tv/videos/1543544450

```md
{{</* twitch video 1543544450 */>}}
```

{{< twitch video 1543544450 >}}
