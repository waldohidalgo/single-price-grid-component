<script>
import Footer from "./components/Footer.vue";

export default {
  components: {
    Footer,
  },
};
</script>

<template>
  <main class="py-[72px] bg-lightGray md:py-[163px]">
    <div class="mx-auto w-[83%] overflow-hidden rounded-[7px] max-w-[635px]">
      <section class="bg-white section">
        <div class="pb-[3px]">
          <h2
            class="text-cyan text-[20px] font-bold [word-spacing:-1px] md:text-[23.5px]"
          >
            Join our community
          </h2>
          <h3
            class="text-brightYellow font-bold text-[15px] mt-[19px] [word-spacing:-2px] leading-[21px] md:text-[18px]"
          >
            30-day, hassle-free money back guarantee
          </h3>
          <p
            class="text-grayishBlue mt-[17px] text-[14px] leading-[26px] tracking-[-0.15px] md:text-[16px] md:mt-[12px]"
          >
            Gain access to our full library of tutorials along with expert code
            reviews. Perfect for any developers who are serious about honing
            their skills.
          </p>
        </div>
      </section>
      <div class="grid grid-cols-1 md:grid-cols-2">
        <section class="bg-cyan section">
          <div>
            <h2
              class="text-white mt-[-2px] text-[18px] font-semibold md:mt-[1px]"
            >
              Monthly Subscription
            </h2>
            <div class="flex mt-[7px] items-center gap-[11px]">
              <span class="text-white text-[32px] font-bold">&dollar;29</span>
              <span class="text-lightGray">per month</span>
            </div>
            <p class="mt-[1px] text-white text-[15.5px]">
              Full access for less than &dollar;1 a day
            </p>
            <button
              class="bg-brightYellow text-white w-full rounded-[4px] mt-[27px] text-[16px] font-bold py-[12px] hover:bg-brightYellow/70"
              title="Sign Up"
            >
              Sign Up
            </button>
          </div>
        </section>
        <section class="bg-cyan/80 section">
          <div>
            <h2 class="text-white mt-[-5px] font-bold text-[17px] md:mt-[1px]">
              Why Us
            </h2>
            <ul class="text-lightGray mt-[15px] text-[13.5px]">
              <li>Tutorials by industry experts</li>
              <li>Peer &amp; expert code review</li>
              <li>Coding exercises</li>
              <li>Access to our GitHub repos</li>
              <li>Community forum</li>
              <li>Flashcard decks</li>
              <li>New videos every week</li>
            </ul>
          </div>
        </section>
      </div>
    </div>
  </main>
  <Footer />
</template>
