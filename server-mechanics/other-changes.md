---
description: >-
  This Page holds all other changes that were too simple to justify having their
  own page
icon: lightbulb-gear
---

# Other Changes

## Spawning Changes:

In the Jungle you can  now spot a new rare variant of a cow called the Coffee Cow.

<div><figure><img src="../.gitbook/assets/coffee_cow.png" alt=""><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/mugged_cow.png" alt=""><figcaption><p>*When Hit by Lightning, Coffee Cow Will turn into Mugged Cow, seen above*</p></figcaption></figure></div>

Ocean Monuments now also spawn Elder guardians at 0.25% chance.

Bastions now spawn piglins with 0.25% to spawn piglin brutes instead.

Shulkers Respawn at the location of the End Cities with 30% chance to spawn instead of an enderman as long as there is no shulker within 10 blocks.

### Farm Limiter:

Some passive mobs (Pig, Cow, Sheep and Chicken) despawn if there are too many of them near each other to keep the TPS stable for the server.&#x20;

The current settings is 20 mobs in 8 block radious, meaning if there is 21 all within 8 block radius, 1 will despawn. _<mark style="color:$danger;">\*This setting is a potential subject to change and could there for be out of date\*</mark>_

You can bypass this limiter by using nametags on the mobs. Nametagged mobs will not despawn.

## Shulker Redyeing:

When you punch a living shulker with a dye in hand, the dye is consumed and the shulker is dyed the corresponding color.

<figure><img src="../.gitbook/assets/shulkers.png" alt=""><figcaption></figcaption></figure>

## Enchantment Changes:

Impaling enchantment has been adjusted to be more flexible for combat.

* Impaling now works on all mobs, not just aquatic
* Impaling now adds the same damage bonus like Sharpness

## Other Loot Table Changes:

* Jungle Leaves have been adjusted to reflect the same drop rates of saplings as other tree types

## Snowball Changes:

Snowballs have knockback.

## Phantom Toggle:

You can use the command <mark style="color:purple;">**/phantomisolation**</mark> to enable or disable phantom spawns for you.

## View Distance Tweaks:

The server automatically adjusts the server render and simulation distance based on the performance of the server.&#x20;

You can see the current status by using the command <mark style="color:purple;">**/vdt stats**</mark>&#x20;

For example if there are many players online loading different chunks, the server wil lower the view distance to keep the TPS stable. If there player count goes down or the less chunks are loaded, the server will render more.

## Invisible Item Frames:

You can turn item frames invisible & back to visible by Shift Right Clicking them.
