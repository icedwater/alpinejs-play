# Exploring alpine.js

What is this alpine.js? [15 attributes, 6 properties, 2 methods][site]?
Seems too good to be true. But let's see what it can do first, maybe...

Written by [Caleb][twtC], it seeks to be "jQuery for the modern web" in
that one just needs to put in a script tag.

Here's a minimal example that's on the top of the [site][site]:

    <script src="//unpkg.com/alpinejs" defer></script>

    <div x-data="{ open: false }">
        <button @click="open = true">Expand</button>

        <span x-show="open">
            Stuff goes here...
        </span>
    </div>

## Starting out

I'll be looking at the [start-here][ajsh] page for starters, making one
page for each example so that we can see really how simple the alpinejs
library is.

However, I guess once I'm familiar with how things work, the real bonus
of using alpinejs would be in creating reusable components as one might
do in React, Vue, or Angular... just in a more lightweight way.

I would be reinventing the wheel, though, and if you want to have quick
access to quality I highly recommend [buying components][ajcp] instead.
The Alpine team has already put in their hard work to make things which
look good, so please support them.

## Setting up

As promised, no install is needed, just load the pages into a webserver
of your choice, e.g. Python simpleserver, then click around.

    git clone git@github.com:icedwater/alpinejs
    cd alpinejs
    python -m http.server 8000

The basic stuff should now be available on `http://localhost:8000`.

[site]: https://alpinejs.dev
[ajsh]: https://alpinejs.dev/start-here
[ajcp]: https://alpinejs.dev/components
[twtC]: https://twitter.com/calebporzio

## Attributes

 - x-data
 - x-bind
 - x-on
 - x-text
 - x-model
 - x-show
 - x-transition
 - x-for
 - x-if
 - x-init
 - x-effect
 - x-ref
 - x-cloak
 - x-ignore

## Properties

 - $store
 - $el
 - $dispatch
 - $watch
 - $refs
 - $nextTick

## Methods

 - Alpine.data
 - Alpine.store
