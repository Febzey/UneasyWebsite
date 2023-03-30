# ℹ Frequently Asked Questions

{% hint style="warning" %}
Please note that this page is a work in progress and may be incomplete. If you find any missing information or have questions, please contact us on our [Discord](https://discord.uneasyvanilla.com/) and we'll be happy to assist you.
{% endhint %}

## General Questions

#### What the server IP?

* <mark style="color:yellow;">UneasyVanilla.com</mark> - Direct connect to vanilla server.
* <mark style="color:yellow;">Play.UneasyVanilla.com</mark> - Direct connect to vanilla server.
* <mark style="color:yellow;">Queue.UneasyVanilla.com</mark> - Direct connect to queue server.

#### What version does the server support?

* The server is running on version 1.19.3
* We support minecraft version 1.19-1.19.3

{% hint style="info" %}
We recommend that you join the server with Minecraft version 1.19.3
{% endhint %}

#### When was the server created?

* 10th of March 2020

#### Where can I find the server rules?

* Ingame <mark style="color:yellow;">/rules</mark> and <mark style="color:yellow;"></mark> [General Server Rules](general-server-rules/)

#### Is duping allowed?

* <mark style="color:red;">**NO.**</mark> Except for Carpets, Rails and TNT.

#### I'm unable to connect to the server.

* Try to connect to the server using '<mark style="color:yellow;">play.uneasyvanilla.com</mark>' or change your DNS server to <mark style="color:yellow;">1.1.1.1</mark>, <mark style="color:yellow;">1.0.0.1</mark>

#### **Can I use the Nether roof?**

* It has been disabled to avoid lag caused by players loading new chunks, which would significantly increase the size of the world file.

#### **I got false banned, what should I do now?**

* Contact us via a ticket in our [Discord](https://discord.uneasyvanilla.com/)

#### Where do I create a suggestion for the server?

* You can create a new Suggestion, Issue request at [Github Ticket](https://github.com/UneasyVanilla/UneasyNetwork/issues/new/choose).
  * Choose between Bugs or Feature Request.

#### **Who are the staff on the server?**

* MrEDok - Owner
* Iberium - Admin
* Staff will have a <mark style="color:red;">**♢**</mark> suffix ingame.

## Server Environment Information

### Queue

{% hint style="warning" %}
The queue is currently under development, but you can visit <mark style="color:yellow;">Queue.Uneasyvanilla.com</mark> to check it out.
{% endhint %}

### Vanilla

{% hint style="info" %}
This is a list of server configuration options that modify gameplay mechanics in order to accommodate the number of players while maintaining good server performance.
{% endhint %}

#### View/Render distance.

* view-distance: 8
* simulation-distance: 6
* mob-spawn-range: 5

#### MobCaps

* Monster: 25
* Animal: 10

#### Despawn range

* Soft: 30
* Hard: 72

#### Phantoms

* Toggle phantoms on or off with <mark style="color:yellow;">/togglephantoms</mark> You need to complete the <mark style="color:purple;">\[Two Birds, One Arrow]</mark> achievement for this command.

#### Trident

* Using a riptide enchanted trident with elytra will reduce elytra durability.

#### Villager

{% hint style="info" %}
It is necessary for everyone to lobotomize their villager to reduce server loads. Fail to do so will result in the villager being removed. \
Check below on how to lobotomize.
{% endhint %}

* Villager sensors and behaviour ticks is slower compare to vanilla.
  * Affect job changing speed.
  * Pathfinding speed.
* Take the following things into consideration when you're designing your farm(s).
  * Make sure that the villager state switching isn't too fast (Idle <-> Panic) in an ironfarm.

{% hint style="danger" %}
Avoid lobotomize the villagers that are part of a farm, such as an iron farm, because it will remove their AI and cause the farm to not work properly.
{% endhint %}

* Below, you can find a scalable ironfarm design schematic that work the server and available for download.

{% file src="../.gitbook/assets/IronFarmBaseBuild.litematic" %}



