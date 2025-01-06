---
date: 2025-01-06
emoji: 🧑‍🧑‍🧒‍🧒
---

# Who I am following and what for

This is my notes about people I follow on the web. This is an alternate index for people I follow 
so that I won't have to rely on Twitter to remember they exist, nor have to give them a prerequisite 
of having an rss feed to stay in my reading rotation.

Legend:
I'm tagging links in this article with pound/number sign tips. Click on these tags to highlight all tagged links.
<ul>
<li> <find-href>#rss</find-href>: self-explanatory, really. </li>
<li> <find-href>#blog</find-href>: a person's blog </li>
<li> <find-href>#blogs</find-href>: a person's index of blogs they read/follow </li>
<li> <find-href>#newsletter</find-href>: a newsletter they may be curating </li>
</ul>

## Taylor Troesh

Writes about software and life. Likes to experiment with interesting new concepts. Passionate about their projects. Writes a lot.

Some example projects/posts to give an idea of what they do

- Directory of small blogs [blogs.hn](https://blogs.hn/#blogs)
- Scrapscript [scrapscript.org](https://scrapscript.org/) (I still don't understand it but I will, hopefully)
- Better spreadsheets [taylor.town/better-spreadsheets](https://taylor.town/better-spreadsheets)
- Your next two zeroes [taylor.town/next-two-zeroes](taylor.town/next-two-zeroes)
- [taylor.town/harpsichord](https://taylor.town/harpsichord)

Github: [github.com/surprisetalk](https://github.com/surprisetalk)

RSS: [taylor.town/feed.xml](https://taylor.town/feed.xml#rss)

## Manuel Maruale

<https://manuelmoreale.com/#blog>

What they do:
- People and blogs series <https://peopleandblogs.com/#newsletter>

Their index of blogs <https://manuelmoreale.com/blogroll#blogs>

RSS: <https://manuelmoreale.com/feed/rss#rss>

## Nolen Royalty

<https://eieio.games/#blog>

Creates games in unorthodox places & other fun projects.

Notable:
- <https://stranger.video> (no-blink game)
- Flappy Dird, flappy bird on macos finder <https://eieio.games/blog/flappy-bird-in-macos-finder/>
- Google sheets adventure <https://eieio.games/blog/realtime-google-sheet/>

## Diamond Geezer

Extreme-blogger. London enthusiast. His blog is a holy encyplopedia of everything London. Old chap, legend. Blog 
is 22 yrs old and counting. 

<https://diamondgeezer.blogspot.com/#blog>

<https://feeds.feedburner.com/blogspot/HcFb#rss>

<!-- Testing something -->
<style>
  a.highlighted {
    background-color: darkorchid;
  }
  find-href { 
    text-decoration: underline;
  }
</style>
<script>
  document.querySelectorAll('find-href').forEach(tag => {
    tag.addEventListener('click', () => {
      const searchString = tag.textContent.trim();
      document.querySelectorAll('a').forEach(link => {
        if (link.href.includes(searchString)) {
          link.classList.add('highlighted');
        } else {
          link.classList.remove('highlighted');
        }
      });
    });
  });
</script>
