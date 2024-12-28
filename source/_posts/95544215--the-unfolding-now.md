---
title: The Unfolding Now | Free Book
date: 2024-12-27T02:03:14.253Z
updated: 2024-12-27T17:22:32.827Z
categories:
  - \n                            Body, Mind & Spirit\n                        
thumbnail: https://thmb-001-ebook.techidaily.com/6510c87fecc476a2212678dd7d285ee31510280a85f427ae9c88e850f4b5af21.jpg
---
<main id="book-container">
  <div class="flex flex-col">
    <div class="book-brief flex-1 py-6 px-4 sm:p-6 md:py-10 md:px-8">
      <!-- brief-->
      <div class="book-brief-main">
        Realizing Your True Nature through the Practice of Presence
      </div>
    </div>
    <div
      class="book-meta-info flex-1 grid gap-4 col-start-1 col-end-3 row-start-1 sm:mb-6 sm:grid-cols-4 lg:gap-6 lg:col-start-2 lg:row-end-6 lg:row-span-6 lg:mb-0"
    >
      <div
        class="book-meta-info-left place-content-center mt-4 p-4 text-sm leading-6 col-start-2 col-span-2 dark:text-slate-400"
      >
        <img
          class="w-full h-500 object-cover rounded-lg sm:h-255 sm:col-span-2 lg:col-span-full"
          src="https://img-001-ebook.techidaily.com/588db1b1010390e1125a3f9ff2441f4fe9f24022bd7240a335a9a1d482653427.jpg"
          alt=""
          width="312"
          height="500"
        />
      </div>
      <div
        class="book-meta-info-right mt-2 col-start-1 row-start-2 col-span-3 self-center"
      >
        <!-- meta data  -->
        <div class="flex flex-col px-4 md:px-8">
          <div class="flex-1">
            <strong>Publisher</strong>:<span class="px-2"></span>
          </div>
          <div class="flex-1">
            <strong>Published</strong>:<span class="px-2">; Copyright</span>
          </div>
          <div class="flex-1">
            <strong>ISBN</strong>:<span class="px-2"></span>
          </div>
          <div class="flex-1">
            <strong>Title</strong>:<span class="px-2"></span>
          </div>
          <div class="flex-1">
            <strong>Author</strong>:<span class="px-2"></span>
          </div>
          <div class="flex-1">
            <strong>Imprint</strong>:<span class="px-2"></span>
          </div>
          <div class="flex-1">
            <strong>Language</strong>:<span class="px-2"></span>
          </div>
          <div class="flex-1">
            <strong>Number of Pages</strong>:<span class="px-2"></span>
          </div>
        </div>
      </div>
    </div>
    <div class="book-description flex-1 py-6 px-4 sm:p-6 md:py-10 md:px-8">
      <div class="book-description-main">
        <div accordion-content="" id="description">
          <b
            >The keys to self-knowledge and deep contentment are right here
            before us, in this very moment—if we can simply learn to live with
            presence and open awareness</b
          ><br />
          &nbsp;<br />
          In <i>The Unfolding Now</i>, A. H. Almaas presents a marvelously
          effective practice for developing the transformative quality of
          presence. Through a particular method of self-observation and
          contemplative exploration that he calls inquiry, we learn to live in
          the relaxed condition of simply “being ourselves,” without
          interference from feelings of inadequacy, drivenness toward goals,
          struggling to figure things out, and rejecting experiences we don't
          want. Almaas explores the many obstacles that keep us from being
          present—including defensiveness, ignorance, desire, aggression, and
          self-hatred—and shows us how to welcome with curiosity and compassion
          whatever we are experiencing.
        </div>
      </div>
    </div>
    <div class="book-excerpts flex-1 py-6 px-4 sm:p-6 md:py-10 md:px-8">
      <!-- excerpts-->
      <div class="book-excerpts-main">
        <hr />
        <h4 class="placeholder placeholder-heading">
          <span v-cloak="">In The Press</span>
        </h4>
        <p v-html="information.review_quote"></p>
        <!-- <q> -->
        <span class="placeholder placeholder-block"></span>
        <span class="placeholder placeholder-block"></span>
        <span class="placeholder placeholder-sm"></span>
        <!-- </q> -->
      </div>
    </div>
    <div class="book-about-author flex-1 py-6 px-4 sm:p-6 md:py-10 md:px-8">
      <!-- about author-->
      <div class="book-main-author-main">
        <hr />
        <h4 class="placeholder placeholder-heading">
          <span v-cloak="">About the Author</span>
        </h4>
        <p v-html="information.author_bio"></p>
        <!-- <q> -->
        <span class="placeholder placeholder-block"></span>
        <span class="placeholder placeholder-block"></span>
        <span class="placeholder placeholder-lg"></span>
        <!-- </q> -->
      </div>
    </div>
    <div class="book-free-get flex-1 py-6 px-4 sm:p-6 md:py-10 md:px-8">
      <button
        id="btn-free-get"
        class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded"
      >
        Free Get EBook (.PDF/.epub)
      </button>
      <div id="countdown-display" class="px-2 text-lg mt-2"></div>
      <a
        id="free-link"
        class="hidden bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded"
        href="https://www.ebooks.com/en-us/book/95544215/the-unfolding-now/a-h-almaas/"
        target="_blank"
        >Click here to get a free link</a
      >
    </div>
    <script>
      let countdownTime = 0;
      let countdownInterval = null;
      document
        .getElementById('btn-free-get')
        .addEventListener('click', startCountdown);
      function startCountdown() {
        countdownTime = new Date().getTime() + 60000 * 3;
        countdownInterval = setInterval(updateCountdown, 1000);
        document.getElementById('btn-free-get').disabled = true;
        document
          .getElementById('btn-free-get')
          .classList.add('bg-gray-500', 'cursor-not-allowed');
      }
      function updateCountdown() {
        let currentTime = new Date().getTime();
        let timeLeft = countdownTime - currentTime;
        let secondsLeft = Math.floor(timeLeft / 1000);
        document.getElementById('countdown-display').innerHTML =
          `Remaining time: ${secondsLeft} seconds.`;
        if (secondsLeft <= 0) {
          clearInterval(countdownInterval);
          document.getElementById('btn-free-get').classList.add('hidden');
          document.getElementById('free-link').classList.remove('hidden');
          document.getElementById('countdown-display').innerHTML = '';
        }
      }
    </script>
  </div>
</main>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://novels-ebooks.techidaily.com/670799-9781846947278-2013/"><u>2013 | Free Book</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/670512-9780307795434-angel-energy/"><u>Angel Energy | Free Book</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/670800-9781846947285-dreamer/"><u>Dreamer | Free Book</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/670801-9781846947292-generational-patterns-using-astrology/"><u>Generational Patterns Using Astrology | Free Book</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/670802-9781846947308-healing-this-wounded-earth/"><u>Healing This Wounded Earth | Free Book</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/670803-9781846947315-how-to-bond-with-an-aquarius/"><u>How to Bond with An Aquarius | Free Book</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/670806-9781846947346-poppies-from-heaven/"><u>Poppies From Heaven | Free Book</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/670788-9781446447895-the-wheel-of-the-wiccan-year/"><u>The Wheel Of The Wiccan Year | Free Book</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YpnYKIrpgZQ?si=94zicAHp1CH-0oso" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

