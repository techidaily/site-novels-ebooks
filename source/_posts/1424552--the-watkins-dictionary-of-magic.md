---
title: The Watkins Dictionary of Magic | Free Book
date: 2024-10-23 15:44:43
updated: 2024-10-26 11:24:50
categories:
  - \n                            Body, Mind & Spirit\n                        
thumbnail: https://thmb-001-ebook.techidaily.com/f611ed832f6543593101425ff4efcad953eea2fc6dde342c4f14fdea2e3fee0a.jpg
---
<main id="book-container">
  <div class="flex flex-col">
    <div class="book-brief flex-1 py-6 px-4 sm:p-6 md:py-10 md:px-8">
      <!-- brief-->
      <div class="book-brief-main">
        Over 3000 Entries on the World of Magical Formulas, Secret Symbols and
        the Occult
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
          src="https://img-001-ebook.techidaily.com/bc586508cc70c8bde57d790a8bbbf103b96e6a813b81bdbc3e29aca2b5f29738.jpg"
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
          Over 3000 authoritative, cross-referenced entries, covering magical
          traditions from all around the world.
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
        href="https://www.ebooks.com/en-us/book/1424552/the-watkins-dictionary-of-magic/nevill-drury/"
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
