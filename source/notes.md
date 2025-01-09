# Notes

Notes I take from blogs I read

Legend:

<ul>
  <li><find-tag>#bookRec</find-tag>: Book recommendations</li>
  <li><find-tag>#shortRead</find-tag>: Related short reads, e.g. blog posts</li>
</ul>

### 2025-01-09 17:41

Moshidon vs Mastodon android app

When i go to someone's profile, I expect to see their pinned posts first. 
Thats what pinned means. Mastodon app shows pinned, you need to navigate to posts. 
Moshidon shows posts first, you need to navigate to posts. Neither is ideal. It should
be pinned first, then posts.. I guess. If you're not frequently checking on someone.


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
