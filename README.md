# MWICowardSim

## intro
this is a current repo in progress being developed for my goal in mwi to get lvl 69 in all combat stats simultaneously, [which is (still) being recorded in this doc](https://docs.google.com/document/d/1xL80__dmRz18wWRvgZAKR-DEBwU8VB-kGZ1m3IsD1Gc/edit?usp=sharing).

~~the main differing feature that i plan on implementing is running away. with this, i can simulate my goal of hitting enemies and leaving before i can get hit in order to never gain stamina/defense xp.~~

with recent updates, this strategy of running away is no longer possible. i never worked on it much, so it's not too much of a waste, i suppose.

this repo now just serves for me to test various things. most notably, it 

## todo
roughly in order:

### ~~functionality:~~ previous goals, left here as a remnant
* [ ] implement running away
* [ ] sim loading into combat and running away
  * [ ] set trigger for when to run away
    * [ ] time-based
    * [ ] ability/attack-based
  * [ ] add realism
    * [ ] input time it'll take after trigger to run away
    * [ ] add chance of failure
* [ ] implement basic gc targeting system for threat?

### ~~(f)unimportant:~~
* revamp the ui because i can't stand looking at basic bootstrap
* maybe transfer the contents of my doc here? might be a bit of a stretch though, main goal is for this to be a sim of course

## credits

thanks to KuganDev and AmVoidGuy for the *original* original sim, and MWISim for letting me fork this <3

see also: the above doc's credit section!

---

the following is a remnant of the previous repos' readme.

## How to run locally for development purposes

Install dependencies: 

```bash
npm install
```

Build webpack bundle

```bash
npm run build
```

That's it. You can now open index.html in your browser of choice. You may need to enable CORS or host the site locally for it to load properly. 

[Here](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll) is an example to integrate GitHub for local testing purposes.
