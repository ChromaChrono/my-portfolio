<template>
  <div class="intro" id="intro">
    <div class="intro__welcome">
      <div class="intro__introduction">
        <h3 class="global__section-title">Intro</h3>
        <h1 class="global__title intro__title">
          Are you looking for a custom website that doesn't look like the rest? Look no futher!
        </h1>
        <p class="global__paragraph intro__paragraph">
          I offer you my web tech skills so together we can build your dream website. Perhaps you have got a design you want to see come to life? Or perhaps you
          have an idea or theme you want actualized and made to be? If this is true then I'm the guy for you.
        </p>
        <p class="global__paragraph intro__paragraph">
          I take website building seriously. I say no to popular site builders like Wix and instead focus on a purer approach. I like optimization and creative
          freedom and I can't realize those two things with a website builder. If you like the same thing for your site then let's talk business
        </p>
      </div>
      <div class="intro__img">
        <img src="https://cdn.pixabay.com/photo/2018/06/09/17/25/avenue-3464777_960_720.jpg" alt="Path through twisted trees" />
      </div>
    </div>

    <div class="intro__production-stories">
      <div class="intro__production-story">
        <div class="intro__production-story__icon intro__production-story__icon--1"></div>
        <h2 class="global__title--sub intro__production-story__title">Plan</h2>
        <p class="intro__production-story__paragraph">
          Share with me your design or idea and we'll have a friendly chat about it. We'll establish what you would like for me to do for you and I'll ask a
          bunch of questions to make sure we are on the same page.
        </p>
      </div>
      <div class="intro__production-story">
        <div class="intro__production-story__icon intro__production-story__icon--2"></div>
        <h2 class="global__title--sub intro__production-story__title">Build</h2>
        <p class="intro__production-story__paragraph">
          Without further to do I'll get building! I know what I'm doing and I'll be meticulously making sure everything is how you want it to be.
        </p>
      </div>
      <div class="intro__production-story">
        <div class="intro__production-story__icon intro__production-story__icon--3"></div>
        <h2 class="global__title--sub intro__production-story__title">Revise</h2>
        <p class="intro__production-story__paragraph">
          We'll establish how often you want me to check in with you. It can be as little or often as you like. I'll show you the work so far and you can click
          around and see if everything is how you imagined. If there are any small tweaks or changes let me know.
        </p>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.intro {
  position: relative;
  width: 100%;

  &__welcome {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: space-between;
    margin: 13rem 0;
  }

  &__introduction {
    flex: 1 0 500px;
    // padding: 4rem 6rem 0 0;
    margin: 5rem;
    // max-width: 50%;
  }

  &__title {
    font-size: $font-size-title;
    font-weight: bold;
  }

  &__paragraph {
    font-size: $font-size-text;
  }

  &__img {
    flex: 0 1 600px;
    height: auto;
    margin: 0 auto;

    & > img {
      width: 100%;
      height: auto;
      border-radius: 0.5rem;
    }
  }

  &__production-stories {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    padding: 0 2rem;
  }

  &__production-story {
    flex: 0 0 360px;

    &:nth-child(2) {
      margin: 0 6rem;
    }

    &__icon {
      position: relative;
      left: -2rem;
      width: 12rem;
      height: 12rem;
      clip-path: polygon(50% 0%, 90% 20%, 100% 60%, 75% 100%, 25% 100%, 0% 60%, 10% 20%);
      margin-bottom: 1rem;

      &--1 {
        background: no-repeat center / 60% content-box url("https://cdn.pixabay.com/photo/2016/10/02/19/50/brain-1710293_960_720.png");
      }
      &--2 {
        background: no-repeat center / 60% content-box url("https://cdn.pixabay.com/photo/2014/04/02/16/26/compass-307291_960_720.png");
      }
      &--3 {
        background: no-repeat center / 60% content-box url("https://cdn.pixabay.com/photo/2013/03/30/00/10/comments-97860_960_720.png");
      }
    }

    &__title {
      font-size: $font-size-title--sub;
    }

    &__paragraph {
      font-size: $font-size-text;
    }
  }
}
</style>
