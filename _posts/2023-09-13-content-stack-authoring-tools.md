---
layout: post
title: >
    The content stack - part 2: authoring tools
published: true
# subtitle: Excerpt from Soulshaping by Jeff Brown
# cover-img: /assets/img/path.jpg
# thumbnail-img: /assets/img/thumb.png
share-img: /images/social-share-logo.png
gh-repo: beccarobins/beccarobins.github.io
# gh-badge: [star, fork, follow]
gh-badge: [follow]
tags: [content stack, authoring tools, editorial tools]
---

In the first post of the this series, I wrote about markup languages. To show how those markup languages shape your text, you need an _authoring tool_, otherwise your text will \_just\_ look \*\*crazy\*\* and you won't know what you've actually done to it. Here we'll dive into some of the different types of authoring tools (also known as editors) and look at some widely used tools.

## Built-in authoring tools

If you use a proprietary [content management system](../coming-soon) like WordPress, you're using their built-in authoring tool. In this case, chances are you're _not_ dealing with markup languages, but rather a toolbar with formatting options, much like those found in Word or Google Docs. The main advantage of these tools is their ease of use; most people have used similar tools, so adoption is a piece of cake. A disadvantage, however, is that these tools might have limited functionality, and the flexibility you can achieve with markup languages, such as customizing images, may not be available. Let's take a look at one exception, WordPress' block editor, which gives non-technical users the power of a frontend engineer.

### WordPress block editor

WordPress' authoring tool, the block editor, can do **a lot**. It's vast feature array and flexibility is a large reason it's the market leader in the content management space, constituting a whopping 43% of **all** websites on the internet ([WordPress Statistics: How Many Websites Use WordPress in 2023?][WordPress Statistics: How Many Websites Use WordPress in 2023?]). Content creators love the block editor because it's an all-in-one tool as you can also use it to add and update [metadata][Coming soon], visit your URL, customize a post's landing page appearance, and even tag for SEO.

![The block editor][Welcome to the Gutenberg Editor]

Also known as the Gutenberg editor (named after the inventor of the printing press inventor, Johannes Gutenberg), the editor features your standard formatting options: bold, italics, underlining, etc. But what really makes it pack a punch is the wealth of "blocks" available.


<div>
<img src="https://wordpress.org/documentation/files/2022/10/Screen-Shot-2022-10-24-at-4.24.56-PM.png" alt="Block editor options dialog box." width="50%" height="50%" class="center">
<br>
</div>

If you want to learn how to use the block editor, but don't want to go through the hassle of setting up a WordPress website, you can [use this handy WordPress sandbox][How to start using WordPress Playground], which runs an entire WordPress instance in an iframe. If you've never used WordPress before, follow these steps to get to the block editor:
1. Select **My WordPress Website**.
1. Scroll down to **Posts**.
1. Click the **Add New** button to create a new post.
1. Follow the "Welcome to the block editor" prompt.

## Internal authoring tools

You might be using an _internal_ authoring tool, meaning one built just for your company. 

## elearning authoring tools

Learning & development professionals have slightly different needs than other content creators. In addition to educating their audience, they usually have to _test_ them as well. This means going beyond static webpages (like this one) and adding dynamic features that receive input from your learners, assess them, and return the results.

I won't dive in here too deep because it's an entire field in itself

- Articulate
- Adobe Captivate

## Other authoring tools

Believe or not, we've only touched the surface of authoring tool technology. There are many more tools out there that can be used to create content, including those appropriated from software development (IDEs) and WYSIWYGs (pronounced "wizzy wig") that _only_ support formatting content.

### Integrated Development Environments

For this blog, I've been using Visual Studio Code as an authoring tool. Partly because I've gotten comfortable with it (I use it at work too) and partly because it's free. But another advantage of using an integrated development environment (IDE) is taking advantage of the terminal, or the area where you can use commands to run different programs and utilities to support your work.

My blog is hosted on **Git**Hub, so every time I work on it, I use **git** commands, the version control system on which GitHub is based. Using version control system like git means that if I mess something up and need to back track, I can easily do that. While it takes a bit of knowledge to use git, it's a lot easier to learn a few bits of code than to recreate an entire post from memory.

<div>
<img src="../images/mick-vs-code.jpg" alt="Becca's cat Mick supervising her authoring work in Visual Studio Code]" width="70%" height="70%" class="center">
</div>

In addition to git, IDEs let you use pretty much any coding language you can think of. Something I've more recently begun using (just for this blog) is Ruby, which GitHub Pages are based on. Using some very simple Ruby "gems", I can launch this website on a local server to test out how things are looking before pushing it live, essentially playing the part of a [staging environment][Coming soon].

### WYSIWYGs

If you're thinking, isn't this just a text editor? Well yea, _sometimes_ it is. But really, the distinguishing feature between a text editor (like Notepad) and an authoring tool

<iframe src="https://stackedit.io/app#" title="StackEdit editor" height="500" width="800"></iframe>

## Summary



Next up in the content stack series is [metadata](../coming-soon)&mdash;data about data.

Need to catch up? Check out [part 1: markup languages](../content-stack-markup)

[How to start using WordPress Playground]: https://developer.wordpress.org/playground/
[WordPress Statistics: How Many Websites Use WordPress in 2023?]: https://colorlib.com/wp/wordpress-statistics/
[Block editor options]: https://wordpress.org/documentation/files/2022/10/Screen-Shot-2022-10-24-at-4.24.56-PM.png
[Welcome to the Gutenberg Editor]: https://wordpress.org/documentation/files/2022/10/Screen-Shot-2022-10-24-at-4.20.49-PM-1-1024x666.png
[Coming soon]: ../coming-soon
[Block list]: https://wordpress.org/documentation/article/blocks-list/#:~:text=Below%20is%20a%20list%20of%20the%20blocks%20that,types%3A%20Text%2C%20Media%2C%20Design%2C%20Widgets%2C%20Theme%20and%20Embeds.
[StackEdit]: https://stackedit.io/
