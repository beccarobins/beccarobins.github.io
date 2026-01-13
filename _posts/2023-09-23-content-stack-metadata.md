---
layout: post
title: The content stack
published: false
subtitle: >
    Part 3: metadata
# cover-img: /assets/img/path.jpg
thumbnail-img: https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExOXJ6b2tvbHcwZ3hoYmRqdW85MTU5NDA3bDd3NHM5OXc4anMxbTVzayZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/4FQMuOKR6zQRO/giphy.gif
share-img: /images/social-share-logo.png
gh-repo: beccarobins/beccarobins.github.io
# gh-badge: [star, fork, follow]
gh-badge: [follow]
tags: [content stack, metadata]
---

You may or may not be familiar with the term metadata, but you've certainly used it before. Metadata is what is, well, _meta_. It's data _about_ data. And you've used it any time you've searched for something, whether it's in Google, on Amazon, or while watching Netflix. Metadata provides the backbone to a library of content by making it searchable, filterable, sortable, et cetera. Without metadata tagged to content, you'd spend A LOT more time looking for what you want (and a lot more time being annoyed).

## Metadata

So, we've defined metadata already as "data about data", but what does that actually mean? Well, it's data that describes attributes of your data, and what your metadata consists of is entirely dependent on what you're working with...(what a helpful definition, I know). Pretty much anything that you can catalog can have metadata (it's definitely not just a content thing) and the metadata you use will certainly always vary by context.

In the context of content, there are likely to be a few constants in your metadata, such as title, author, publish date, etc. For the most part though, the metadata that you capture is situation and context-dependent. If you'd like some more examples, this article from Dataedo, [What is Metadata (with examples)], has a bunch of great examples for different types of content.

<div>
<img src="../images/mick-oscar-meta.png" alt="Becca's cats Mick and Oscar along with their associated metadata including type equals cat, name equals Mick or Oscar, alias equals Wild Man or Smart Boy." width="70%" height="70%" class="center">
</div>

Here's a quick example of some non-content metadata, using my two favorite boys, my cats Mick and Oscar. If I were to catalog them, I could capture things like: name, breed, fur color, weight, age, etc. In a CMS, you'll often see metadata in its own file, or perhaps relegated to its a separate section of the file. It might look something like the code below, where metadata field (e.g., type, name, alias, etc) precedes the metadata value (cat, 'Mick', 'Wild Man'). And while data types are well beyond the scope of this post, metadata isn't limited to just categorical information, (i.e., cat or dog), but can be numerical (ages), date/time information, and even lists of information (such as the traits used in the example below). Basically, if you can use it to describe something, it can be metadata.

```
Becca's cats = 
{
    {
        type: cat
        name: 'Mick'
        alias: 'Wild Man'
        age: 5
        traits: ['Loud', 'Dog-like', 'Silly']
    },
    {
        type: cat
        name: 'Oscar'
        alias: 'Smart Boy'
        age: 5
        traits: ['Curious', 'Affectionate', 'Intelligent']
    }
}
```

## Okay, but why metadata?

 I'd be _shocked_ if your site weren't already using metadata, but are you using it to its fullest potential? Do you know its full potential?
 
 AND if you're using it to it's fullest extent, it will probably changing frequently.

## Summary

Continue learning about the content stack with the next post in the series: [content management systems](../coming-soon).

Need to catch up? Check out [part 2: authoring tools](../content-stack-authoring-tools)

[What is Metadata (with examples)]: https://dataedo.com/kb/data-glossary/what-is-metadata

[Metadata: Definition, Examples, Benefits & Use Cases]: https://atlan.com/what-is-metadata/

[What is metadata? Understanding the type of data that describes data sets and determines much of what you see online]: https://www.businessinsider.com/guides/tech/what-is-metadata

[metadata]: https://www.techtarget.com/whatis/definition/metadata

[What Is Metadata? Metadata is critically important for website and database management]: https://www.thoughtco.com/metadata-definition-and-examples-1019177

[What Is Metadata?]: https://dataedo.com/kb/data-glossary/what-is-metadata

[How the Modern Data Platform Fuels Success]: https://www.cdw.com/content/cdw/en/articles/dataanalytics/how-the-modern-data-platform-fuels-success.html?cm_ven=acquirgy&cm_cat=bing&cm_pla=SLG+Analytics&cm_iteBundle+Modern+Data+Platform+Broad&s_kwcid=AL!4223!10!73392704939126!73392726583179&ef_id=229801ead6521294ae2164e2ecb518c4:G:s&msclkid=229801ead6521294ae2164e2ecb518c4

[]: https://www.schoolofcontent.net/blog/metadata-content-strategy

[]: https://www.informatica.com/resources/articles/what-is-metadata-management.html

[]: https://www.claravine.com/metadata-impact-on-content-management/

[]: https://en.wikipedia.org/wiki/Metadata_management#:~:text=Metadata%20management%20involves%20managing%20metadata%20about%20other%20data%2C,forms%20of%20metadata%20are%20catalogs%2C%20dictionaries%2C%20and%20taxonomies.

[]: https://www.linkedin.com/advice/3/how-do-you-leverage-metadata-improve

[]: http://charlottehwise.com/docs/ia-metadata.pdf

[]: https://www.astera.com/type/blog/introduction-to-metadata-architecture/

[]: https://engineering.linkedin.com/blog/2020/datahub-popular-metadata-architectures-explained

[]: https://www.businessinsider.com/guides/tech/what-is-metadata

[]: https://simplea.com/Articles/What-is-Website-and-Content-Metadata