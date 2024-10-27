---
title: The Serpent Grail | Free Book
date: 2024-10-24 14:56:34
updated: 2024-10-26 12:13:16
categories:
  - \n                            Body, Mind & Spirit\n                        
thumbnail: https://thmb-001-ebook.techidaily.com/6a368d9d5a05d2c315303406bb99c2c5075a2ba4f3edfc4b9e53ed4ccb9a16cf.jpg
---
<main id="book-container">
  <div class="flex flex-col">
    <div class="book-brief flex-1 py-6 px-4 sm:p-6 md:py-10 md:px-8">
      <!-- brief-->
      <div class="book-brief-main">
        The Truth Behind The Holy Grail, The Philosopher's Stone and The Elixir
        of Life
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
          src="https://img-001-ebook.techidaily.com/6eb323042628ea03e5242be15d015985ea6cfdbfe7efa7ad5f9e34d5a5e58752.jpg"
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
          This is the extraordinary story of the discovery of the ultimate
          secrets of some of the world's most enigmatic mysteries - including
          the Holy Grail, the Elixir of Life and the Philosopher's Stone.
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
        href="https://www.ebooks.com/en-us/book/1985912/the-serpent-grail/philip-gardiner/"
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
