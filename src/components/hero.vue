<template>
  <div class="hero-header78">
    <div class="hero-column thq-section-padding thq-section-max-width">
      <div class="hero-content1">
        <h1 class="hero-text1 thq-heading-1">{{ heading1 }}</h1>
        <p class="hero-text2 thq-body-large">{{ content1 }}</p>
      </div>
      <div class="hero-actions">
        <router-link to="/" class="hero-button1 thq-button-filled">
          <span class="thq-body-small">{{ action1 }}</span>
        </router-link>
        <button class="thq-button-outline hero-button2">
          <a
            href="https://app.uniswap.org/explore/tokens/optimism/0x62fc0b85b64959b16d16c69d9075b5acd0ad034f"
            target="_blank"
            rel="noreferrer noopener"
            class="hero-text4 thq-body-small"
          >
            {{ action2 }}
          </a>
        </button>
      </div>
    </div>
    <div class="hero-content2">
      <div
        class="hero-row-container1 thq-mask-image-horizontal thq-animated-group-container-horizontal"
      >
        <div class="thq-animated-group-horizontal">
          <img
            :alt="image1Alt"
            src="https://dc-cdn.s3-ap-southeast-1.amazonaws.com/dc-Cover-t2gm64u3s76difpdus3malfip3-20160217173241.Medi.jpeg"
            class="hero-placeholder-image10 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image3Alt"
            src="https://i.etsystatic.com/19515243/r/il/b2dcef/5079669340/il_1080xN.5079669340_gy9v.jpg"
            class="hero-placeholder-image11 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image2Alt"
            src="https://c.tenor.com/nW9fUL09fqsAAAAd/tenor.gif"
            class="hero-placeholder-image12 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image4Alt"
            src="https://c.tenor.com/Dtapka0DcX4AAAAd/tenor.gif"
            class="hero-placeholder-image13 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image5Alt"
            :src="image5Src"
            class="hero-placeholder-image14 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image6Alt"
            :src="image6Src"
            class="hero-placeholder-image15 thq-img-scale thq-img-ratio-1-1"
          />
        </div>
        <div class="thq-animated-group-horizontal">
          <img
            :alt="image1Alt"
            :src="image1Src"
            class="hero-placeholder-image16 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image2Alt"
            :src="image2Src"
            class="hero-placeholder-image17 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image3Alt"
            :src="image3Src"
            class="hero-placeholder-image18 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image4Alt"
            :src="image4Src"
            class="hero-placeholder-image19 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image5Alt"
            :src="image5Src"
            class="hero-placeholder-image20 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            alt="Hero Image"
            src="https://images.unsplash.com/photo-1534312527009-56c7016453e6?ixid=M3w5MTMyMXwwfDF8c2VhcmNofDIxfHxhYnN0cmFjdHxlbnwwfHx8fDE3MTA4NzA5MzB8MA&amp;ixlib=rb-4.0.3&amp;w=1500"
            class="hero-placeholder-image21 thq-img-scale thq-img-ratio-1-1"
          />
        </div>
      </div>
      <div
        class="hero-row-container2 thq-mask-image-horizontal thq-animated-group-container-horizontal"
      >
        <div class="thq-animated-group-horizontal-reverse">
          <img
            :alt="image7Alt"
            :src="image7Src"
            class="hero-placeholder-image22 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image8Alt"
            :src="image8Src"
            class="hero-placeholder-image23 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image9Alt"
            :src="image9Src"
            class="hero-placeholder-image24 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image10Alt"
            src="https://c.tenor.com/NZJXajcwChgAAAAd/tenor.gif"
            class="hero-placeholder-image25 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image11Alt"
            :src="image11Src"
            class="hero-placeholder-image26 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image12Alt"
            src="https://i.insider.com/58b4a13a54905720098b6f49?width=1300&amp;format=jpeg&amp;auto=webp"
            class="hero-placeholder-image27 thq-img-scale thq-img-ratio-1-1"
          />
        </div>
        <div class="thq-animated-group-horizontal-reverse">
          <img
            :alt="image7Alt"
            :src="image7Src"
            class="hero-placeholder-image28 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image8Alt"
            :src="image8Src"
            class="hero-placeholder-image29 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image9Alt"
            :src="image9Src"
            class="hero-placeholder-image30 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image10Alt"
            src="https://c.tenor.com/LSd7_eiK00UAAAAd/tenor.gif"
            class="hero-placeholder-image31 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image11Alt"
            :src="image11Src"
            class="hero-placeholder-image32 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            alt="Hero Image"
            src="https://images.unsplash.com/photo-1568214379698-8aeb8c6c6ac8?ixid=M3w5MTMyMXwwfDF8c2VhcmNofDEyfHxncmFmaWN8ZW58MHx8fHwxNzE1Nzk0OTk5fDA&amp;ixlib=rb-4.0.3&amp;w=1500"
            class="hero-placeholder-image33 thq-img-scale thq-img-ratio-1-1"
          />
        </div>
      </div>
    </div>
    <div>
      <div class="hero-container2">
        <DangerousHTML
          html="<style>
    @keyframes scroll-x {
      from {
        transform: translateX(0);
      }
      to {
        transform: translateX(calc(-100% - 16px));
      }
    }
  
    @keyframes scroll-y {
      from {
        transform: translateY(0);
      }
      to {
        transform: translateY(calc(-100% - 16px));
      }
    }
  </style>
  "
        ></DangerousHTML>
      </div>
    </div>
  </div>
</template>

<script>
import DangerousHTML from 'dangerous-html/vue'

export default {
  name: 'Hero',
  props: {
    image11Alt: {
      type: String,
      default: 'GatesCoin future plans',
    },
    action1: {
      type: String,
      default: 'Learn More',
    },
    image9Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1641370417425-951641190fff?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczMjIwODkxOXw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    image10Alt: {
      type: String,
      default: 'GatesCoin community',
    },
    image3Alt: {
      type: String,
      default: 'Bill Gates funny gif',
    },
    image8Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1642388538891-38b2d14e750e?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczMjIwODkxOXw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    image11Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1604029969271-2d61f0182334?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczMjIwODkxOHw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    image5Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1644924735973-0ba06d83268e?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczMjIwODkxOXw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    image1Alt: {
      type: String,
      default: 'Bill Gates dancing at the Windows 95 launch event',
    },
    image2Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1541726260-e6b6a6a08b27?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczMjIwODkxN3w&ixlib=rb-4.0.3&q=80&w=1080',
    },
    image7Alt: {
      type: String,
      default: 'Bill Gates crypto tribute',
    },
    image12Alt: {
      type: String,
      default: 'GatesCoin team',
    },
    image6Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1641180210732-9f94818ae5fc?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczMjIwODkxOXw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    heading1: {
      type: String,
      default: 'Welcome to GatesCoin - The Meme Coin Tribute to Bill Gates',
    },
    image5Alt: {
      type: String,
      default: 'Bill Gates Windows 95 launch',
    },
    image3Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1641180210732-9f94818ae5fc?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczMjIwODkxN3w&ixlib=rb-4.0.3&q=80&w=1080',
    },
    image1Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1550533105-d412cbf5bfcc?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczMjIwODkyMHw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    image7Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1641803166724-5f32ad7a11d0?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczMjIwODkxOHw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    content1: {
      type: String,
      default:
        "Join us in celebrating the legacy of Bill Gates and the launch of Windows 95 with GatesCoin. We pay homage to the tech pioneer by creating a fun and innovative meme coin that will make you dance like it's 1995!",
    },
    image4Alt: {
      type: String,
      default: 'Bill Gates meme dancing',
    },
    image2Alt: {
      type: String,
      default: 'Bill Gates meme image',
    },
    image6Alt: {
      type: String,
      default: 'Bill Gates meme coin',
    },
    action2: {
      type: String,
      default: 'Get Started',
    },
    image8Alt: {
      type: String,
      default: 'Bill Gates dance moves',
    },
    image4Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1597702693388-c985cfd3eaea?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczMjIwODkxOXw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    image9Alt: {
      type: String,
      default: 'GatesCoin logo',
    },
  },
  components: {
    DangerousHTML,
  },
}
</script>

<style scoped>
.hero-header78 {
  gap: var(--dl-space-space-threeunits);
  width: 100%;
  height: auto;
  display: flex;
  overflow: hidden;
  position: relative;
  align-items: center;
  flex-shrink: 0;
  flex-direction: column;
}
.hero-column {
  gap: var(--dl-space-space-oneandhalfunits);
  width: auto;
  display: flex;
  align-items: center;
  flex-direction: column;
  padding-bottom: var(--dl-space-space-unit);
}
.hero-content1 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
.hero-text1 {
  text-align: center;
}
.hero-text2 {
  text-align: center;
}
.hero-actions {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-space-space-unit);
}
.hero-button1 {
  text-decoration: none;
}
.hero-text4 {
  text-decoration: none;
}
.hero-content2 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  position: relative;
  align-items: flex-start;
  flex-direction: column;
}
.hero-row-container1 {
  width: 100%;
}
.hero-placeholder-image10 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image11 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image12 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image13 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image14 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image15 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image16 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image17 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image18 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image19 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image20 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image21 {
  width: 400px;
  height: 400px;
}
.hero-row-container2 {
  width: 100%;
}
.hero-placeholder-image22 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image23 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image24 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image25 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image26 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image27 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image28 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image29 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image30 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image31 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image32 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image33 {
  width: 400px;
  height: 400px;
}
.hero-container2 {
  display: contents;
}
@media(max-width: 767px) {
  .hero-content2 {
    width: 100%;
  }
}
@media(max-width: 479px) {
  .hero-actions {
    width: 100%;
    flex-direction: column;
  }
  .hero-button1 {
    width: 100%;
  }
  .hero-button2 {
    width: 100%;
  }
}
</style>
