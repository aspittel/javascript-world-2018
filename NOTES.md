# Navigating the Spooky world of JavaScrypt in 2018

JavaScript (and front-end development in general) can feel intimidating because so many cool things are happening so fast. The language itself is evolving, and so is the ecosystem surrounding it. From frameworks like React, Vue, Angular, and even Hyperapp and their rapidly changing APIs to the bundling systems around them to the language itself, JavaScript is evolving rapidly and it can be tough to keep up. Very few of these tools even existed five years ago. Blog posts like [this one](https://hackernoon.com/how-it-feels-to-learn-javascript-in-2016-d3a717dd577f) outline how hard it is to learn modern JavaScript and stay up to date with everything that's happening. 

I started working with JavaScript during perhaps the peak of the chaos in 2015 after working solely on data analysis scripts and computer science course work previously, and since then, I've had the privilege of teaching hundreds of people the language. So I'm going to be telling a bunch of stories about my JavaScript journey -- and how I decide what to teach -- in hopes that you will make less mistakes than I did and that we can make the world of JavaScript a little less scary 😈!

## How can we face our JavaScript Fears?

### Focus on the fundamentals

The fundamentals of the language are never going to change that dramatically, so being super knowledgeable about the ins and the outs of it can only help you. 

In JavaScript, especially, knowing intermediate concepts like the call stack, context, scope, the prototype chain, higher order functions, asynchronous programming, and the event loop is invaluable and will help you with anything you do further with the language.

I also really appreciate this comment:

{% comment https://dev.to/maxwell_dev/comment/6enk %}

Knowing the fundamentals really well makes frameworks much more helpful and so much easier to learn! Underneath the hood, these frameworks and libraries are just JavaScript anyways -- they aren't magic!

In fact, your project may never need to use a framework -- GitHub runs on vanilla JavaScript and Hacker News runs on [150 lines](https://news.ycombinator.com/hn.js) of unminified JS total. Plus your site will be lighter weight!

I really appreciate Dan Abramov's [You May Not Need Redux](https://medium.com/@dan_abramov/you-might-not-need-redux-be46360cf367) -- I think more libraries and frameworks should have their co-founder be explicit that their tool isn't always the right tool for the job! It's the truth.

### Shiny Object Syndrome

Shiny object syndrome is when you see a new thing and immediately want to drop everything and focus on that shiny object. In tech, that may mean that you re-write your applications every time a new library is on the horizon.

![](https://media.giphy.com/media/CK0gcoAFZZ3G/giphy.gif)

I am super guilty of this -- I used to write my blog posts themed around writing an app with a new library or framework each week. I've also worked with JQuery, Angular.js, Angular, Vue, Elm, and React at some level for work. But, that shouldn't be normal or encouraged.

I think my best shiny object syndrome story was when I worked on a team that was using a Chinese library whose documentation hadn't been fully translated to English yet. I remember running Google Translate to try and figure it out. It wasn't productive and Google Translate isn't great with technical docs in case anyone was wondering. Though the library looked cool, using one that was available in the language we spoke would have been a lot better.

So let's talk about how to overcome "shiny object syndrome."

![](https://pbs.twimg.com/media/Ce5nYp0W4AAxp5Z.jpg)

#### You don't need to know everything

In large part due to imposter's syndrome, a lot of developers feel the need to know everything about everything -- but that's not even possible! There's way too much to know, and nobody knows everything! Keep reminding yourself about that, and don't feel the need to know everything -- even though it's hard.

To quote Dan Abramov about the new React Hooks API:

> Hooks are an experimental proposal to React. You don’t need to learn about them right now. 

[(src)](https://medium.com/@dan_abramov/making-sense-of-react-hooks-fdbde8803889)

The same is true about everything -- even though it might not feel like it.

#### Focus on depth over breadth

Once you know one framework or library, it is so much easier to move to the next one. If you understand the component architecture you are already quarter way through learning React, Angular, and Vue! You don't need to know all of them. Sure, they're all cool and have different features, but chances are you only need one.

#### Don't migrate to the newest thing immediately

Also, when you're picking a stack for your project, don't be the first adopter. Sure it may be cool, you may get a blog post out of it, and maybe it will make some pieces of your code easier. But -- then you get stuck on some bug in the library and you can't progress until it's fixed. Or documentation for what you're trying to do doesn't exist and it isn't realistic to bring anyone but expert level developers onto your team.

Let somebody else find the bugs first, then you can start using that cool new tool! 

Also, its important to keep progressing and creating modern interfaces for your apps, but if your stack is still working for you there isn't a need to change or rewrite it from scratch. React *just* surpassed JQuery in Google searches [(src)](https://www.youtube.com/watch?v=kz3nVya45uQ) even though JQuery may feel like ancient history in the JavaScript world! 

## Choose Wisely

Since you can't learn or use every new framework or library that comes out, you have to also figure out how to choose your tech wisely. A couple key questions when you are choosing what tool to use for a project or to learn:

* Is it well used? If it has a community behind it then it's more likely to have contributors and frequent iteration on features and bug solving. Also, it's more likely to have staying power.
* Who is the community behind the project? Is it a large company? Do they have a code of conduct? How do they treat new users?
* Is it frequently updated? You don't want to be stuck with bugs that aren't being fixed.
* Are there frequent breaking changes? You don't want to have to make major code updates in order to keep the tool up to date. Also, it may make researching the tool difficult. Looking at you Elm and Angular. 
* What features make this tool better than the alternatives? Does it do something extra? Or solve some problem other tools don't? 
* Does it fit your team? If your team is mostly junior developers, for example, does the framework have good learning resources and documentation? If you have mostly functional programmers does the tool fit that paradigm?
* Is the documentation good? This is so important for being able to use the technology easily.
* How does the code look? Does the codebase look well written and maintainable?
* Is the library performant?

There's no singular right answer here -- if the technology works well for your team, it’s the right solution no matter what some thought leader says on Twitter.

## How to stay up to date in the JavaScript world

Okay -- so now that we've discussed shiny object syndrome -- how can you stay up to date on the latest updates in a reasonable way?

* Follow JavaScript people on Twitter -- like [@dan_abramov](https://twitter.com/dan_abramov), [@addyosmani](https://twitter.com/addyosmani), [@getify](https://twitter.com/getify), [@wesbos](https://twitter.com/wesbos), and [@sarah_edo](https://twitter.com/sarah_edo) -- this is normally the quickest way to learn about new tech.
* News Sources -- I follow [dev.to](https://dev.to), [CSS Tricks](https://css-tricks.com/), [Smashing Mag](https://www.smashingmagazine.com/), and [JavaScript Weekly](https://javascriptweekly.com/) as my main resources!

## It's not actually not that spooky!

A quick reality check before finishing up this post, JavaScript isn't actually moving at the speed of light. React, Vue, and Angular have all been around for over four years, and so has ES6 which will probably be the largest change at once to JavaScript ever. There isn't actually a new popular framework every week. And even if there was, you don't have to learn that framework. The awesome parts of technologies are usually integrated into their competitors eventually anyways -- just look at how React inherited from Angular.js and then Angular inherited from React.

Also, I think great that JavaScript and frontend development in general is evolving -- it needs to in order to make development easier and user experience better. 

Hopefully this post made the world of JavaScript a little less spooky and a little more accessible!

## Bonus: JavaScript stuff I'm really excited about right now

* [Webcomponents](https://dev.to/aspittel/building-web-components-with-vanilla-javascript--jho)
* [Hyperapp](https://dev.to/aspittel/functional-programming-in-javascript-done-right-with-hyperapp-570f)
* [Progressive Web Apps](https://dev.to/ben/what-the-heck-is-a-progressive-web-app-seriously-923)
* [CSS Houdini](https://css-tricks.com/interactive-introduction-to-css-houdini/)

## Keep in Touch

* [Twitter](https://twitter.com/aspittel)
* [Newsletter](https://mailchi.mp/b4216331e284/zen-of-programming)
* [GitHub](https://github.com/aspittel)
