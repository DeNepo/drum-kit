# Drum Kit

A static web page for rhythmic expression built with only HTML, CSS & JavaScript.  This project uses .wav audio files and keypress events to turn the user's keyboard into a drum set.

Try the live demo [right here](https://hackyourfuture.be/drum-kit), it looks something like this:

[![drum kit screen shot](./images/screen-shot.png)](https://hackyourfuture.be/drum-kit)

---

## Notes

Studying this project we learned about:

* Dynamically setting classes
* Using the `<audio>` tag and .wav assets
* How the query selector can be used to easily interact with many elements
* How milestones, labels & issues can help organize work ->
  * user stories === milestones
  * tasks === issues
  * labels === what type of task it is

We struggled with:

* How to create the development strategy.  It was tricky to figure out that the `playHandler` can actually work without changing the `.played` class, once that was clear it was easier to create the _Keys Light Up_ user story.
* We kept making mistakes with the `data-key` attributes and linking the wrong keys and sounds.
* Merge Conflicts!  whoever invented these has no soul
* Keeping track of all the branches and forks.  OMG, github is confusing

These resources were very helpful:

* [KeyBoard Event Values](https://css-tricks.com/snippets/javascript/javascript-keycodes/)
* [gmlwjd9405/git-collaboration](https://github.com/gmlwjd9405/git-collaboration)
* [GitHub Project Management](https://github.com/features/project-management)

---

> * Code refactored from [Wes Bos](https://github.com/wesbos/JavaScript30/tree/master/01%20-%20JavaScript%20Drum%20Kit)
