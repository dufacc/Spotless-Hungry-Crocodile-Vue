<template>
  <div :id="stats3Id" class="thq-section-padding">
    <div class="stats3-max-width thq-section-max-width">
      <div class="stats3-container2">
        <h2 class="thq-heading-2 stats3-title">
          <slot name="heading1">
            <!--Default content for heading1-->
            <div class="stats3-fragment1">
              <span class="stats3-text18">Business value of teleportHQ</span>
            </div>
          </slot>
        </h2>
      </div>
      <div class="stats3-container3">
        <div class="stats3-container4">
          <h2 class="thq-heading-2">
            <slot name="stat1">
              <!--Default content for stat1-->
              <div class="stats3-fragment9">
                <span class="stats3-text26">99%</span>
              </div>
            </slot>
          </h2>
          <span class="thq-body-small stats3-text11">
            <slot name="stat1Description">
              <!--Default content for stat1Description-->
              <div class="stats3-fragment8">
                <span class="stats3-text25">Customer satisfaction</span>
              </div>
            </slot>
          </span>
        </div>
        <div class="stats3-container5">
          <h2 class="thq-heading-2">
            <slot name="stat2">
              <!--Default content for stat2-->
              <div class="stats3-fragment2">
                <span class="stats3-text19">44%</span>
              </div>
            </slot>
          </h2>
          <span class="thq-body-small stats3-text13">
            <slot name="stat2Description">
              <!--Default content for stat2Description-->
              <div class="stats3-fragment3">
                <span class="stats3-text20">Active users</span>
              </div>
            </slot>
          </span>
        </div>
        <div class="stats3-container6">
          <h2 class="thq-heading-2">
            <slot name="stat3">
              <!--Default content for stat3-->
              <div class="stats3-fragment7">
                <span class="stats3-text24">99%</span>
              </div>
            </slot>
          </h2>
          <span class="thq-body-small stats3-text15">
            <slot name="stat3Description">
              <!--Default content for stat3Description-->
              <div class="stats3-fragment4">
                <span class="stats3-text21">Customer satisfaction</span>
              </div>
            </slot>
          </span>
        </div>
        <div class="stats3-container7">
          <h2 class="thq-heading-2">
            <slot name="stat4">
              <!--Default content for stat4-->
              <div class="stats3-fragment5">
                <span class="stats3-text22">44%</span>
              </div>
            </slot>
          </h2>
          <span class="thq-body-small stats3-text17">
            <slot name="stat4Description">
              <!--Default content for stat4Description-->
              <div class="stats3-fragment6">
                <span class="stats3-text23">Active users</span>
              </div>
            </slot>
          </span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Stats3',
  props: {
    stats3Id: String,
  },
}
</script>

<style scoped>
.stats3-max-width {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
}
.stats3-container2 {
  gap: var(--dl-space-space-twounits);
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.stats3-container3 {
  flex: 0 0 auto;
  width: 100%;
  height: auto;
  display: flex;
  flex-wrap: wrap;
  align-items: center;
}
.stats3-container4 {
  flex: 1;
  display: flex;
  padding: var(--dl-space-space-twounits);
  align-items: center;
  flex-direction: column;
}
.stats3-container5 {
  flex: 1;
  display: flex;
  padding: var(--dl-space-space-twounits);
  align-self: flex-start;
  align-items: center;
  flex-direction: column;
}
.stats3-container6 {
  flex: 1;
  display: flex;
  padding: var(--dl-space-space-twounits);
  align-items: center;
  flex-direction: column;
}
.stats3-container7 {
  flex: 1;
  display: flex;
  padding: var(--dl-space-space-twounits);
  align-self: flex-start;
  align-items: center;
  flex-direction: column;
}
.stats3-fragment1 {
  display: contents;
}
.stats3-text18 {
  display: inline-block;
}
.stats3-fragment2 {
  display: contents;
}
.stats3-text19 {
  display: inline-block;
}
.stats3-fragment3 {
  display: contents;
}
.stats3-text20 {
  display: inline-block;
}
.stats3-fragment4 {
  display: contents;
}
.stats3-text21 {
  display: inline-block;
}
.stats3-fragment5 {
  display: contents;
}
.stats3-text22 {
  display: inline-block;
}
.stats3-fragment6 {
  display: contents;
}
.stats3-text23 {
  display: inline-block;
}
.stats3-fragment7 {
  display: contents;
}
.stats3-text24 {
  display: inline-block;
}
.stats3-fragment8 {
  display: contents;
}
.stats3-text25 {
  display: inline-block;
}
.stats3-fragment9 {
  display: contents;
}
.stats3-text26 {
  display: inline-block;
}
@media(max-width: 991px) {
  .stats3-container3 {
    flex-wrap: wrap;
  }
  .stats3-container6 {
    align-self: flex-start;
  }
  .stats3-container7 {
    align-self: flex-start;
  }
}
@media(max-width: 767px) {
  .stats3-title {
    text-align: center;
  }
  .stats3-container3 {
    flex-wrap: wrap;
    align-items: center;
    flex-direction: row;
  }
  .stats3-container4 {
    align-self: flex-start;
  }
  .stats3-text11 {
    text-align: center;
  }
  .stats3-container5 {
    flex: 1;
  }
  .stats3-text13 {
    text-align: center;
  }
  .stats3-text15 {
    text-align: center;
  }
  .stats3-text17 {
    text-align: center;
  }
}
@media(max-width: 479px) {
  .stats3-title {
    align-self: center;
    text-align: center;
  }
  .stats3-container3 {
    flex-wrap: wrap;
  }
  .stats3-container5 {
    align-self: flex-start;
  }
  .stats3-container6 {
    align-self: flex-start;
  }
  .stats3-container7 {
    align-self: flex-start;
  }
}
</style>
