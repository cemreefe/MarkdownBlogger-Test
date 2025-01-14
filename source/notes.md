# Notes

Notes I take from blogs I read

Legend:

<ul>
  <li><find-tag>#bookRec</find-tag>: Book recommendations</li>
  <li><find-tag>#shortRead</find-tag>: Related short reads, e.g. blog posts</li>
</ul>

### 2025-01-14 21:57 

<https://openbenches.org/>

### 2025-01-14 19:30 

from <https://shkspr.mobi/blog/2024/12/book-review-the-ministry-of-time-kaliane-bradley/>

<https://www.goodreads.com/book/show/199798179-the-ministry-of-time> <tag>#bookRec</tag>

### 2025-01-13 17:31

> from <https://vale.rocks/posts/the-design-of-this-site.html>

Digital Garden 

<https://maggieappleton.com/garden-history>

> Perhaps the greatest contributor to the philosophy behind my site is taken from the website of notable synth pioneer Wendy Carlos. Her site houses a page describing how her website ‘lives’:
>
> > I’m happy to report that this page (like most housework) will never be finished. It is a living document that grows and matures, just like most of real life. It is not a “work in progress”, for this would imply not much intrinsic value until that magic day it is completed.
> >
> >A novel is a work of art that, once completed may continue to exist forever in that finished state. An encyclopedia must be published at regular intervals to reflect new information gathered since the day it was published. Periodicals are timely only when first printed, then fall behind the times – get the latest issue to keep up. The technology behind web documents allows us to update information as often as is necessary. In this context, publishing dates become an outdated concept.
> >
> >While it is possible to “finish” a web document, the fixed information becomes stagnant, thus abolishing any desire for a return visit. This is something I call a cob-web page.

Github powered comments solution. Better replacement for commentbox! <https://giscus.app/>

<https://gwern.net/> Absolutely beautiful blog. Reads like a newspaper

<https://www.lesswrong.com/> Worth a visit. A bit too overwhelming as a first time visitor tbh.

<https://turntrout.com/> good-looking little blog, ai

<https://www.joshwcomeau.com/> cool design

### 2025-01-11 11:17 

<https://kill-the-newsletter.com/>; newsletter -> RSS.

Ethical? I'm not so sure. Useful? Probably.

### 2025-01-10 21:10 

> [O]rganizations which design systems (in the broad sense used here) are constrained to produce designs which are copies of the communication structures of these organizations.
> 
> — Melvin E. Conway, [How Do Committees Invent?](https://www.melconway.com/Home/pdf/committees.pdf) <tag>#shortRead</tag>

### 2025-01-10 18:53 

[Bookmarklet](https://en.wikipedia.org/wiki/Bookmarklet) is a js script as a bookmark that can be executed on demand in any webpage.

### 2025-01-09 20:13 

[Yggdrasil Network](https://yggdrasil-network.github.io/) <tag>#shortRead</tag>

### 2025-01-08 12:48

Open source & free (!!!) map provider.

<https://openfreemap.org/> & <https://openfreemap.org/quick_start/>

### 2025-01-08 12:01

<https://moxie.org/2024/09/23/a-good-engineer.html> <tag>#shortRead</tag> from @boramalper@mastodon.social

### 2025-01-07 13:48

[Yılkı Atı](https://www.goodreads.com/book/show/10576557-y-lk-at) #<tag>#bookRec</tag>

### 2025-01-07 10:32

From <https://blog.codinghorror.com/the-great-filter-comes-for-us-all/>

[Story of your life](https://en.wikipedia.org/wiki/Story_of_Your_Life) the book the movie "arrival" was based on. #bookRec

<https://en.wikipedia.org/wiki/Great_Filter> <tag>#shortRead</tag>

<https://waitbutwhy.com/2014/05/fermi-paradox.html> <tag>#shortRead</tag>

### 2025-01-06 23:01

From <https://taylor.town/pardon-2024>

[The High Cost of Free Parking](https://en.wikipedia.org/wiki/The_High_Cost_of_Free_Parking) - Donald Shoup <tag>#bookRec</tag> from 

<https://www.efavdb.com/math-of-parking-tickets> <tag>#shortRead</tag>

<script>
// If a specific note is linked, give the next note a 100vw top padding
document.addEventListener("DOMContentLoaded", function() {
    // Get the current h3 element based on the URL fragment
    const currentH3Id = window.location.hash.substring(1); // Get the part after the #
    const currentH3 = document.getElementById(currentH3Id);

    if (currentH3) {
        let nextElement = currentH3.nextElementSibling;

        // Keep looking for the next h3 until one is found
        while (nextElement && nextElement.tagName !== "H3") {
            nextElement = nextElement.nextElementSibling;
        }

        if (nextElement && nextElement.tagName === "H3") {
            // Set the margin-top of the next h3 to 100vh
            nextElement.style.marginTop = "100vh";
        }

        // Scroll back to the original linked h3 instantly
        currentH3.scrollIntoView({ behavior: 'auto', block: 'start' });
    }
});
</script>
