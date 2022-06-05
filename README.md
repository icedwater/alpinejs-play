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

[site]: https://alpinejs.dev
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
