---
title: Item Distribution
draft: false
tags:
  - items
---
The items you get dropped from neutrals are more or less random, but do follow a set of rules to prevent extreme edge-cases. Theoretically, under pure randomness, a player could technically receive only a single component from neutrals the entire game. The rules that prevent these cases are known as "Item Distribution."

It's important to note that item distribution pertains only to the components received *from neutral rounds*. Any items chosen off of carousel or received from augments are not factored into the distribution rules. Knowledge of these rules gives you insight on what components are more likely to drop, and when paired with [[Item Economy]], you'll see that you have much higher consistency in having desirable completed items.

## Component Pools
At the start of the game, your component pool starts with 2 copies of each component in the pool. Receiving a component will subtract 1 copy from your pool. In stage 1, there is also a restriction that you may not receive more than one copy of any given component. Stage 1 will drop anywhere from 1 to 5 components depending on the game and you will be compensated for low items with gold, although, every player will receive the same number of items. Games where you receive fewer than 3 components in stage 1 are considered "gold openers" due to the limited options for craftable items (0 or 1 options) and the ability to make 10 gold before stage 2. Most games, however, you'll receive 3 components.

At the start of a new stage, every component will receive +2 to it's pool. If you received a sword in stage 1 as your only item, the pool for swords will now be at 3, whereas the other components that did not drop will be set to 4. This means swords are slightly less likely to drop compared to other components on the stage 2 neutral round. This repeats for each stage, so on stage 3, if you still haven't received a specific component yet, the pool size for that component will be at 6. If you happened to receive 2 more copies of a sword on stage 2 neutrals, the sword pool will be at 3 once again, meaning you are twice as likely to receive a copy of that component than you are to receive a sword.

The game also does not allow you to receive more than 4 copies of a component from neutral drops. If you were to once again receive a sword on stage 3 neutrals, that would be your 4th copy of a sword from neutrals and you would be locked out from being dropped a sword directly on stage 4 (this does not apply to the component anvil options; you could technically be offered a 5th sword).

### You can skip this section if you don't care about math
So why don't they just set the maximum pool size to 4 and don't increase it? You get locked out after 4 copies anyways so why bother? This has to do with how the probability of each component appearing scales with the game. Using the same example of the sword drop, our pool on stage 2 neutrals would have 7 components with a pool of 4 and swords with a pool of 3. That means the probability of an item drop being a sword is 3/31 or roughly 9.6%. This wouldn't change in a world where the pool is set to 4 initially and never increases. However, on stage 3, the pool for unobtained components would not increase to 6, and components that only appeared once so far would also not increase to 5—their pool would still be set to 3 copies. Let's say stage 2 drops gave us 5 components: 2 swords, a bow, a cloak, and a chain. The pool now looks like this (and associated probabilities for a given item drop to be that component):
### 4 pool rule:
- Sword: 1 (~3.8%)
- Bow: 3 (~11.5%)
- Rod: 4 (~15.4%)
- Tear: 4 (~15.4%)
- Chain: 3 (~11.5%)
- Cloak: 3 (~11.5%)
- Belt: 4 (~15.4%)
- Glove: 4 (~15.4%)

Let's compare this to the rules the game actually uses.
### Standard pool rules:
- Sword: 3 (~7.1%)
- Bow: 5 (~11.9%)
- Rod: 6 (~14.3%)
- Tear: 6 (~14.3%)
- Chain: 5 (~11.9%)
- Cloak: 5 (~11.9%)
- Belt: 6 (~14.3%)
- Glove: 6 (~14.3%)

We see that the probability to receive components that we have not yet received are slightly lower, but the probability to receive a 4th sword are much higher. If we expand this to stage 4, you'll find that using the "4 pool rule" has a tendency to homogenize item drops. Since the distribution would begin to heavily skew away from items that have already been received, your overall components available by the end of the game will generally be more similar compared to the standard rules that are used, even if the order of acquisition is different.

Now, you might be thinking, "isn't it bad that my chances for receiving a 4th sword are so much higher?" Which is fair enough, but my opinion is that:
1) It's worth the tradeoff of having more variability in the item drops.
	- Half the fun of the game is playing around/planning for RNG anyways. TFT is not the game for you if you want the same thing every time lmao.
2) 4 copies of a component isn't even that bad most of the time. Some comps would gladly take like 6 copies of a component if they could do so consistently.

It's up to you if you agree but this is simply the world we live in.
## Miscellaneous
These rules don't really pertain directly to the item pool system, but are relevant to how you play around the distribution system regardless.
1) If you receive more than 1 copy of a component on a single stage, you are guaranteed to also receive a Reforger
	- You don't get a second Reforger if you receive 3 copies
	- I don't remember if you get a second Reforger if you get 2 of 2 different components LOL
2) You are guaranteed a component anvil on stage 4 neutrals

Remember, the distribution rules only apply to **item drops**, so any items obtained from augments, carousel rounds, or anvils *do not* affect the pool system, nor are they affected by it, **even if an anvil was dropped by a neutral monster**.
## Applications
The most obvious application is that you don't have to plan around being dropped a 5th copy of any component, but there's more than that. By combining our understanding of [[Item Economy]] with Item Distribution, we can make better decisions on what to slam and what to pick off of carousel. For example, if an AP comp requires a sword for Shojin but has no other uses for the component, it can be risky to take swords from carousels since we will have to find ways to resolve extra swords, and the distribution rules make it likely for us to receive them later on. Furthermore, if we refer to [[Item Economy#Using Item Economy to Inform Slams|the Volibear Example]] , if I had previously received 2 belts and slammed a Warmog's, I may feel inclined to hold onto the belt so I can save it for Striker's Flail instead of making the Evenshroud that I would have otherwise preferred. 