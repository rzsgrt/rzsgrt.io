---
layout: post
title:  On How to Write (good or just ordinary) Documentation
categories: [documentation,writing]
---
As a developer, writing documentation is tedious task because it's easy to get write block. Here's some point that maybe can help to make good documentation.

1. Start with what reader needs.
Start by answering, what readers need to know? What information that readers need in order to help them solve their job?
For example, reader (our new colleague) need to know how to use a internal tools that been used by our team or know how our past project looks like or simply to reproduce on local.

2. Write less.
Write less. We don't need to write a long documentation. This is relevant with point 1. We need to answer, do our user need this context? or do our user need this really detail one command cli? Long documentation also means a lot of part that need to be maintaned. If you write a long documentation, and you can't maintain it some part will outdated. And outdated documentation is either not useful or can lead to wrong action.

3. Write outline first.
Start with answering question that mentioned above. Write all things needed by reader as a header outline. In each outline, write some point to elaborate your question. This will make writing process easier.

4. Use rubber ducking method.
This point not speccific to write documentation. But it'll help writing process. This will help because sometimes it's easy to explain in verbal rather than write and documentation doesn't need to be in formal writing sytle.

5. Write readably.
Since we want to make our reader job easy, we need to write something that also easy to follow. Writing with 5 point bullet will be easier to follow compare to one long paragraph. Write documentation with instruction language compare to general information. For example, one bullet point saying: Execute command A and expect result B compare is better than "you can expect result B if you execute command A". This also apply to header. Instead of saying "Custom code generation", we can say "Writing a code generator". On the second header, user already know what they will found in this section.

6. Don't write documentation to fix problem.
If you write documentation to fix problem, then you shouldn't write documentation. You need to fix that problem.

---
Source:
Writing effective documentation [youtube video link](https://www.youtube.com/watch?v=R6zeikbTgVc)
