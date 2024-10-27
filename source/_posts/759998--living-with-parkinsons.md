---
title: Living with Parkinson's | Free Book
date: 2024-10-23 14:54:51
updated: 2024-10-26 11:52:56
categories:
  - Body, Mind & Spirit
thumbnail: https://thmb-001-ebook.techidaily.com/c576ad6e24fc24ee33a2163cd09f15c217a351f4523e005bc0373a392a7ec02e.jpg
---
<main id="book-container">
  <div class="flex flex-col">
    <div class="book-brief flex-1 py-6 px-4 sm:p-6 md:py-10 md:px-8">
      <!-- brief-->
      <div class="book-brief-main">Diagnosis, Treatment and Management</div>
    </div>
    <div
      class="book-meta-info flex-1 grid gap-4 col-start-1 col-end-3 row-start-1 sm:mb-6 sm:grid-cols-4 lg:gap-6 lg:col-start-2 lg:row-end-6 lg:row-span-6 lg:mb-0"
    >
      <div
        class="book-meta-info-left place-content-center mt-4 p-4 text-sm leading-6 col-start-2 col-span-2 dark:text-slate-400"
      >
        <img
          class="w-full h-500 object-cover rounded-lg sm:h-255 sm:col-span-2 lg:col-span-full"
          src="https://img-001-ebook.techidaily.com/b475cfbaae2e2acc1de4e5cd799b0d2b632b301e61dc98a9c6331ebda17e137f.jpg"
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
            <strong>Publisher</strong>:<span class="px-2"
              >New Holland Publishers (Australia)</span
            >
          </div>
          <div class="flex-1">
            <strong>Published</strong>:<span class="px-2"
              >February 2011; Copyright</span
            >
          </div>
          <div class="flex-1">
            <strong>ISBN</strong>:<span class="px-2"></span>
          </div>
          <div class="flex-1">
            <strong>Title</strong>:<span class="px-2"
              >Living with Parkinson&#39;s</span
            >
          </div>
          <div class="flex-1">
            <strong>Author</strong>:<span class="px-2">Gabriella Rogers</span>
          </div>
          <div class="flex-1">
            <strong>Imprint</strong>:<span class="px-2"
              >New Holland Publishers</span
            >
          </div>
          <div class="flex-1">
            <strong>Language</strong>:<span class="px-2">English</span>
          </div>
          <div class="flex-1">
            <strong>Number of Pages</strong>:<span class="px-2">224</span>
          </div>
        </div>
      </div>
    </div>
    <div class="book-description flex-1 py-6 px-4 sm:p-6 md:py-10 md:px-8">
      <div class="book-description-main">
        <div accordion-content="" id="description">
          This book will address this with an easy to read, positive text
          covering the medical aspects of Parkinson's as well as incorporating
          the stories of sufferers, their families and carers
        </div>
      </div>
    </div>
    <div class="book-excerpts flex-1 py-6 px-4 sm:p-6 md:py-10 md:px-8"></div>
    <div
      class="book-about-author flex-1 py-6 px-4 sm:p-6 md:py-10 md:px-8"
    ></div>
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
        href="https://www.ebooks.com/en-us/book/759998/living-with-parkinson-s/gabriella-rogers/"
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
