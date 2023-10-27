# CMPSC 200: The Moon Rocks

| Date              |          |
|:------------------|:---------|
| 26 October 2023 | Assigned  |
| 3 November 2023| Due, end of lab       |
| Status           | [![GatorGrader](../../actions/workflows/main.yml/badge.svg)](../../actions/workflows/main.yml) |


## Learning objectives

* express familiarity with basic `C` language syntax and language design
* identify and describe the basic data structures of `C` (`array`, `struct`)
* explain the relationship between data structures and system memory (i.e. roles of `stack` and `heap`)

## classifier

Complete this work in [classifier/main.c](classifier/main.c).

Most folks would arrive on the moon and laze around in the lunar ocean a bit. Not us! We've been collecting rocks. Of course, you need to catalog them using a struct. Heck, we'll even send you out to collect _at least 1 more_ to test the system and see if it stands up to future development.

This program should:
- add all samples from arrays containing data to the `struct array`, `samples`
- find the average of any type of rock by first letter of the `type`

For this assignment, once you've completed the basic program, find [one more sample](https://en.wikipedia.org/wiki/Moon_rock) and create an entry in the data structure(s) which matches its `name`, `type`, `ID`, and `weight`. What you pick is up to you!

### Assignment "Hacks"

See the `Suggestion` below to challenge yourself to implement a Hack. As always, you are allowed to develop
your own Hack to satisfy this stretch goal. Place the code for the Hack inline with the code in the corresponding
file.

In order to recieve credit for the Hack, you must fill out the [hack.md](docs/hack.md) file located in the
`docs` folder.

#### Additional statistics

Choose an additional statistic to report on beyond average weight by type. You might:

* average the number of letters in a given title
* display a count of each type
  * here, you might need to add more that `1` additional sample

If you choose to implement an additional statistic, there's an additional question for you to answer in (docs/hack.md)[docs/hack.md].

#### Create a basic management system

For this hack, [look into the `scanf` function](https://diveintosystems.org/book/C2-C_depth/IO.html#_scanf). How could we use it to create a moon rock management system (MRMS)? How can we add or add _and_ delete samples?

> You'll probably need to discuss some of the weirdness of device input with the instructor.
 
### Changes to files in `.vscode`

Based on your system setup (refer to your `hello-blinky` assignment), you will need switch out the `.vscode` folder in each exercise with the _last working copy_.

See our [wiki's entry  on "Configuring Assignments"](https://github.com/allegheny-college-cmpsc-200-fall-2023/course-materials/wiki/03-Configuring-Assignments)
for more inforamtion.
