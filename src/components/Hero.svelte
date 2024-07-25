<script>
  import SectionWrapper from "./SectionWrapper.svelte";
  import Header from "./Header.svelte";
  import CallToActionBtns from "./CallToActionBtns.svelte";
  import RatingStars from "./RatingStars.svelte";
</script>

<SectionWrapper id="hero">
  <Header />
  <div
    class="flex flex-col gap-10 flex-1 items-center justify-center pb-10 md:pb-14"
  >
    <h2
      class="text-5xl sm:text-6xl md:text-7xl lg:text-8xl max-w-[1200px] mx-auto w-full text-center font-semibold"
    >
    <span class="text-indigo-400">Live</span> Kabaddi Scores Just Got
    <span class="text-indigo-400">Simpler</span>
  
    </h2>

    <p class="text-xl sm:text-2xl md:text-3xl text-center max-w-[1000px] mx-auto w-full">
      Prioritize action over keeping scores in your head   
    </p>
    

    <CallToActionBtns />

    <!-- <RatingStars /> -->
  </div>
</SectionWrapper>
