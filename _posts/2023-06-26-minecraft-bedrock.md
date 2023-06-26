---
title:  "How to play Minecraft Bedrock on Mac/Linux"
description: "Minecraft Bedrock is not really a crossplay platform"
author: atius
image: https://github.com/AtiusAmy/atiusamy.github.io/blob/master/images/Unix%20Bedrock2.png
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

As you know, Minecraft Bedrock despite being a crossplay platform is not available on two platforms that Minecraft Java is on, Mac and Linux, or Steam Deck which I will refer to as Linux from now on so I don’t have to keep saying “And Steam Deck”, and in this video, we will try to fix that and here are a couple of ways you can run Minecraft Bedrock on Mac and Linux, and some suggestions for Mojang if they want to fix this.
<figure markdown="1">

![Parrot](https://media.giphy.com/media/l3q2zVr6cu95nF6O4/giphy.gif)

<figcaption>A pretty parrot</figcaption>
</figure>

See, isn't that nice. You can also put them halvsies (`.half`) or… thirdsies (`.third`)?

<figure class="half" markdown="1">

![Parrot](https://media.giphy.com/media/l3q2zVr6cu95nF6O4/giphy.gif)
![Parrot](https://media.giphy.com/media/l3q2zVr6cu95nF6O4/giphy.gif)

<figcaption>A couple of cool parrots</figcaption>
</figure>

I really hope you don't have light- or motion-sensitivity or something, because this page is becoming painful.

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
