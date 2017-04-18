# So you want to help build Xethya?

That's awesome! We're glad you're joining us :smile: The idea of this meta-repo is to keep an eye on the project's agenda, as well as help newcomers in their quest for pull-requesting. Happy coding!

### Technical aspects

#### :package: Flexible and composable

One of the main goals of Xethya is to be as flexible and composable as possible. Therefore, every component is a stand-alone Node package.

#### :stars: Universal

Xethya should run anywhere where JavaScript can run. So, that means both server-side and client-side. Unless the feature's scope is specifically the browser (i.e. audio management), we should attempt to write as universal as possible JavaScript code.

#### :file_folder: Scaffolding

We use the `javascript` generator from `yeoman`, so we have Babel + Rollup already baked in. If a better alternative is out there and you know about it, feel free to suggest it.

### Specifications

The full specification of the framework is being written in the [xethya/.specs](https://github.com/xethya/.specs) repo. If you come from the RPG world, consider this repo the Dungeon Master's Gamebook.

This repo is your starting point if you're becoming a _Feature Champion_. Let's go with an example:

> Meet Vilma 🙋. Vilma is a JavaScript developer that wants to join Xethya. She's an expert in [PRNGs](https://en.wikipedia.org/wiki/Pseudorandom_number_generator) and wants to implement new randomization algorithms in the [Dice](https://github.com/xethya/xethya-dice) module. She wants more _aggresive_ rolls, so she starts writing down how the dice should behave in [xethya/.specs](https://github.com/xethya/.specs). For that, she opens an issue to submit a proposal. The proposal spec is discussed and once that the _Guild_ approves the feature and resolves where should it live, coding may begin. 
> Once the feature is developed, reviewed and merged, a _freezed spec_ entry is created in `.specs`, in order to preserve how the feature works.
> A feature can also be rejected or put on hold until another developer/champion can lead the way with it.
> A `core feature` doesn't require approval, since it's defined by the Guild and has already an internal approval.

Keep in mind that we're working for other developers, so the framework must be clearly documented.

**Also:** The framework is currently in a very early stage, so we'll all be learning together how to make this work. This means that these guidelines at first won't be strongly enforced, but the idea is to be well organised from scratch.

[_The Guild_](https://github.com/orgs/xethya/teams/guild) is the team of core contributors of Xethya.

### Roadmap

We'll keep track of the framework's global status with GitHub issues and [projects](https://github.com/xethya/.roadmap/projects) contained in this repo. 

### Questions?

Leave an issue here with the tag `question`!
