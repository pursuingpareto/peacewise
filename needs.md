# Needs
## Software
So many big decisions to make! Simplicity is key.

The overarching questions as I see them:

> **What's the minimum viable product, and who is going to help build it, and how are we going to work together**?

### Process

> **Who is going to work on this?** And how do we get them excited?

> **How do we work together?** I like the idea of using some [version of Agile](https://en.wikipedia.org/wiki/Agile_software_development), but I have to admit that I haven't thought about this kind of thing a ton.

### Architecture

> **What is the basic server architecture?** Our answer should:

1. have a viable path to scale to 10 billion simultaneous users (probably not all in the exact same place though).

2. work well with whatever decisions we make regarding our representation of space, time, and synchronicity (see [Physics](#physics)).

3. be as environmentally friendly as is feasible.

> **How do we design our architecture for security?**

> **How do we protect user data?**

> **How do we maintain a welcoming and easy-to-get-up-to-speed developer community**?

### Languages

> **What language(s) should we use?** I'm inclined to go with Python for the majority of backend code due to it's user-friendly syntax, incredible developer community, and because it's interpreted which allows for novel game experiences through the dynamic injection of code developed at runtime.

## Physics

> **What is the dimensionality of the space?** 

Is this a 2D universe? 3D? Or is it an even higher dimensionality?

Some tradeoffs I see:

* 2D games are lightweight and fun. They are easy to learn. Grandma can play them! This will lead our focus to the core social dynamics and not the flash stuff. I think 2D games may be less "immersive" than 3D games as well, which is kinda an upside. We don't want to build a world where people spend all their time playing video games. 

* 3D games are more realistic to the real world. If we're viewing this game as a training ground for how to be in the real world, that could be a huge upside. They're also more immersive, which has upsides and downsides.

* games in 4+ dimensions are... well I don't know of any. But I bet they could be a TON OF FUN. 

> **What physics do we want to include in that space?** 

Sure we could model gravity as $G\frac{M m}{r^2}$, but what if we did [something else](https://en.wikipedia.org/wiki/Introduction_to_general_relativity)?

> **How do we think about time? How does that thinking work when we consider servers across the planet interacting with each other?** 

I feel like time is probably more of an emergent property rather than something we explicitly need to manage / synchronize across servers. Plus, if we have some rule that says "servers operate at 100% compute wherever possible", that might make *underloaded* servers more desirable places for players to be, since the game would advance "faster" there. This would have the effect of naturally equilibrating load across servers.

## Gameplay
I'm imagining a sandbox world with lots of reasons to collaborate. I think dedicated players need to be able to create new in-game games / mechanics. 

### Metaphor
> **What sort of world / universe do players inhabit** Is it a solar system? A planet? A farm?

### Visual Style
> **What does our universe look like? Does it look like only ONE thing, or is it "reskinnable"?**

## Story

> **Is there *A* story?** Seems a little prescriptive to me. Plus that would be a LOT of work. I don't know.