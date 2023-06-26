---
title:  "How to play Minecraft Bedrock on Mac/Linux"
description: "Minecraft Bedrock is not really a crossplay platform"
author: atius
image: /images/UnixBedrock2.png
tags:
  - minecraft
  - bedrock
  - mcpe
  - linux
  - mac
---

You can now both get two Minecraft version for free! Now you don’t have to choose!(Only for Windows :P)

### Video form

<p align="center"><iframe style="width:75%;height:300px;" src="https://www.youtube.com/embed/jeFiSXEC1Ps" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></p>

As you know, Minecraft Bedrock despite being a crossplay platform is not available on two platforms that Minecraft Java is on, Mac and Linux, or Steam Deck which I will refer to as Linux from now on so I don’t have to keep typing “And Steam Deck”, and in this article, we will try to fix that and here are a couple of ways you can run Minecraft Bedrock on Mac and Linux, and some suggestions for Mojang if they want to fix this.
<figure markdown="1">

### Minecraft Bedrock Launcher

![Download it on Flathub](/images/BEDROCKLAUNCHER.png)

<figcaption>A pretty nice application</figcaption>
</figure>

The first and easiest option is the Minecraft Bedrock Launcher. On Linux, you just download it from your store, but if you’re on Ubuntu or any distro that doesn’t ship Flathub by default just search for a tutorial online, It’s a few command lines. As for Mac, All you have to do is just download it from their Git Hub. Just click the DMG and install it, press open anyway on your security and privacy settings and you could just play. One thing to note you have to own it on the Google Play store. You could also download the AppImage on Linux here, which will work with a touch screen, but if you want that on Linux I recommend the next solution right after this. Now for the pros and cons of this. The mouse and Keyboard work properly, the controller works on Linux (Didn’t work on Mac for me but it might be a driver issue), and the skin now works (It didn’t before) for the cons: It might not be up to date all the time, but you could always press show incompatible versions. It might be buggy with that.

<figure class="half" markdown="1">

![Running Android](/images/Waydroid.png)

<figcaption>Waydroid is the best tool on Linux</figcaption>
</figure>

Running Android, you could either use Emulators, Virtual Machine, and Containers. On Mac, my preferred choice would be bluestacks and on Linux would be Waydroid. It’s no secret that I am a big fan of Waydroid, here are some pros and cons. The first pro for all of them is that you are running Android. You get the latest update, you get marketplace, basically full functionality…. Well, that’s not entirely true. For the cons, The controls are one. If you’re using Waydroid everything should work. As for Bluestacks, the control for me are just bad. The Bluestacks version on MacOS is on version 4, which you have to manually map the control which is annoying. So yeah, Those are options

<figure class="third" markdown="1">

![Parrot](https://media.giphy.com/media/l3q2zVr6cu95nF6O4/giphy.gif)
![Parrot](https://media.giphy.com/media/l3q2zVr6cu95nF6O4/giphy.gif)
![Parrot](https://media.giphy.com/media/l3q2zVr6cu95nF6O4/giphy.gif)

<figcaption>A trio of trippy parrots</figcaption>
</figure>

Ooh, circle crops could come in handy, especially if we're featuring a developer's mug or something. Let's give that a go down below with a `.circle` class:

<figure class="circle" markdown="1">

![Random](https://source.unsplash.com/random/500x500)

<figcaption>It’s a beautiful circle of… something</figcaption>
</figure>

And we can make sure wider images are constrained to the width of the content (not the wider page width) with a simple `.constrained` class:

<figure class="constrained" markdown="1">

![Random](https://source.unsplash.com/random/2000x1000)

<figcaption>It’s big, but like, smaller</figcaption>
</figure>

And lastly, we can go full bleed if we want with the appropriately-named `.full-bleed` class:

<figure class="full-bleed" markdown="1">

![Random](https://source.unsplash.com/random/2560x720)

<figcaption>My god, it's full of stars!</figcaption>
</figure>

### Other stuff

Okay, that's enough of that. What else can we do? How about a table, using the familiar GitHub syntax:

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

Neat! I'm sure we can spruce those up a bit more later. Now, let's try to embed a post. This will be interesting…

<aside>
{% assign post = site.posts | where:"slug", "test" | first %}
{% include featured.html post=post %}
</aside>

Okay so that was a little more complicated than I'd like, but it actually works. Neato 🌯️.

And of course, pressing <kbd>⌘</kbd> + <kbd>Shift</kbd> will do absolutely nothing. Thought you'd like to know.

And we need to test code blocks like this one:

```vala
public class MyApp : Gtk.Application {

    public MyApp () {
        Object (application_id: "com.github.myteam.myapp",
        flags: ApplicationFlags.FLAGS_NONE);
    }

    protected override void activate () {
        var window = new Gtk.ApplicationWindow (this);
        window.title = "MyApp";
        window.set_default_size (1024, 768);
        window.show_all ();
    }

    public static int main (string[] args) {
        var app = new MyApp ();
        return app.run (args);
    }
}
```

## But wait, there's more!

To help contribute, visit [github.com/elementary/blog-template](https://github.com/elementary/blog-template)
