<template>
  <div class="steps-container1 thq-section-padding">
    <div class="steps-max-width thq-section-max-width">
      <div class="steps-container2 thq-grid-2">
        <div class="steps-section-header">
          <h2 class="thq-heading-2">Why GATES95?</h2>
          <p class="thq-body-large">
            Coin created to honor a great moment in Bill Gates&apos; life, so
            enjoy the brief history on the side
          </p>
          <div class="steps-actions"></div>
        </div>
        <div class="steps-container3">
          <div class="steps-container4 thq-card">
            <h2 class="thq-heading-2">{{ step1Title }}</h2>
            <span class="steps-text13 thq-body-small">
              {{ step1Description }}
            </span>
            <label class="steps-text14 thq-heading-3">01</label>
          </div>
          <div class="steps-container5 thq-card">
            <h2 class="thq-heading-2">{{ step2Title }}</h2>
            <span class="steps-text16 thq-body-small">
              {{ step2Description }}
            </span>
            <label class="steps-text17 thq-heading-3">02</label>
          </div>
          <div class="steps-container6 thq-card">
            <h2 class="thq-heading-2">{{ step3Title }}</h2>
            <span class="steps-text19 thq-body-small">
              {{ step3Description }}
            </span>
            <label class="steps-text20 thq-heading-3">03</label>
          </div>
          <div class="steps-container7 thq-card">
            <h2 class="thq-heading-2">{{ step4Title }}</h2>
            <span class="steps-text22 thq-body-small">
              {{ step4Description }}
            </span>
            <label class="steps-text23 thq-heading-3">04</label>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Steps',
  props: {
    step1Title: {
      type: String,
      default: 'The Birth of Microsoft',
    },
    step3Description: {
      type: String,
      default:
        'Our meme coin pays homage to Bill Gates and the legacy of Microsoft. We celebrate the entrepreneurial spirit and innovation that Gates brought to the tech industry.',
    },
    step1Description: {
      type: String,
      default:
        "Microsoft was founded by Bill Gates and Paul Allen on April 4, 1975, to develop and sell BASIC interpreters for the Altair 8800. The company's big break came in 1980 when they signed a contract with IBM to provide an operating system (OS) for their first personal computer.",
    },
    step2Description: {
      type: String,
      default:
        'On August 24, 1995, Bill Gates famously launched Windows 95, which revolutionized the world of personal computing with its user-friendly interface and built-in internet support. The iconic image of Gates dancing at the launch became a meme sensation.',
    },
    step4Description: {
      type: String,
      default:
        'When our currency becomes a reality, we will dance like Bill Gates did in 1995 at the Windows 95 launch. Join us in celebrating the spirit of innovation and fun!',
    },
    step2Title: {
      type: String,
      default: 'Windows 95 Launch',
    },
    step3Title: {
      type: String,
      default: 'Homage to Bill Gates',
    },
    step4Title: {
      type: String,
      default: 'Dance Like Bill Gates',
    },
  },
}
</script>

<style scoped>
.steps-container1 {
  width: 100%;
  display: flex;
  position: relative;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.steps-max-width {
  gap: var(--dl-space-space-fourunits);
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: row;
}
.steps-container2 {
  align-items: start;
}
.steps-section-header {
  gap: var(--dl-space-space-oneandhalfunits);
  top: 10%;
  display: flex;
  position: sticky;
  align-items: flex-start;
  flex-direction: column;
}
.steps-actions {
  gap: var(--dl-space-space-unit);
  border: 2px dashed rgba(120, 120, 120, 0.4);
  display: flex;
  align-items: flex-start;
}
.steps-container3 {
  grid-area: span 1/span 1/span 1/span 1;
}
.steps-container4 {
  top: 10%;
  position: sticky;
  transform: rotate(-2deg);
  margin-bottom: var(--dl-space-space-twounits);
  background-color: var(--dl-color-theme-accent1);
}
.steps-text13 {
  text-align: center;
}
.steps-text14 {
  top: var(--dl-space-space-unit);
  right: var(--dl-space-space-unit);
  position: absolute;
  font-size: 40px;
  font-style: normal;
  font-weight: 700;
}
.steps-container5 {
  top: 10%;
  position: sticky;
  transform: rotate(2deg);
  margin-bottom: var(--dl-space-space-twounits);
  background-color: var(--dl-color-theme-accent2);
}
.steps-text16 {
  text-align: center;
}
.steps-text17 {
  top: var(--dl-space-space-unit);
  right: var(--dl-space-space-unit);
  position: absolute;
  font-size: 40px;
  font-style: normal;
  font-weight: 700;
}
.steps-container6 {
  top: 10%;
  position: sticky;
  transform: rotate(-2deg);
  margin-bottom: var(--dl-space-space-twounits);
  background-color: var(--dl-color-theme-accent1);
}
.steps-text19 {
  text-align: center;
}
.steps-text20 {
  top: var(--dl-space-space-unit);
  right: var(--dl-space-space-unit);
  position: absolute;
  font-size: 40px;
  font-style: normal;
  font-weight: 700;
}
.steps-container7 {
  top: 10%;
  position: sticky;
  transform: rotate(2deg);
  background-color: var(--dl-color-theme-accent2);
}
.steps-text22 {
  text-align: center;
}
.steps-text23 {
  top: var(--dl-space-space-unit);
  right: var(--dl-space-space-unit);
  position: absolute;
  font-size: 40px;
  font-style: normal;
  font-weight: 700;
}
@media(max-width: 991px) {
  .steps-max-width {
    flex-direction: column;
  }
}
@media(max-width: 767px) {
  .steps-section-header {
    position: static;
    margin-bottom: var(--dl-space-space-twounits);
  }
  .steps-actions {
    width: 100%;
    align-self: flex-start;
  }
  .steps-container4 {
    width: 100%;
  }
  .steps-container5 {
    width: 100%;
  }
  .steps-container6 {
    width: 100%;
  }
  .steps-container7 {
    width: 100%;
  }
}
</style>
