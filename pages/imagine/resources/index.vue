<template>
  <div class="page imagine">
    <hero-section
      title="Resources"
      subtitle="The changing social, technological, and economic environment"
      image="https://source.unsplash.com/2JIvboGLeho/1600x900"
      image-alt="Stadsbiblioteket, Stockholm, Sweden"
      color="primary"
      size="is-large"
    />
    <section-intro
      title="Adapting to Changing Technology"
      subtitle="To recognize the opportunities that arise from the adjacent
        possible, we must understand first what tools and technologies are
        available to make the most of the available opportunities, given those
        possibilities."
    >
      <p class="intro-paragraph">
        The tools that we use to communicate have changed over time. Much of our
        work was manual and analog. As graphic designers, we were engaged in a
        creative process that evolved from pencils, pens, rapidographs and
        rubylith to fonts, software and hardware to CMYK printing, foil
        stamping, stochastic screens and paper stocks. The breadth and depth of
        resources required for competence in the practice of design and
        communications grows as technology progresses.
      </p>
      <p>
        Designers now collaborate with teams of business leaders, entrepreneurs,
        marketers, researchers, content strategists, and developers to build web
        applications, and digital products using lean startup principles, agile
        methodology, behaviour-driven development, and usability testing. We
        have experienced revolutions from the web standards movement, to the
        responsive web design movement, to the recognition of design as a
        primary driver in developing trust and brand recognition as user
        experience research drives the direction of product design and
        innovation for businesses. We have come to recognize that, whatever
        business or service is being offered, every individual in the
        organization is part of designing the systems that embody the culture.
        People support the effort to build tools and systems that meet human,
        technical, and business needs with their time, energy, and resources.
      </p>
      <p>
        To recognize the opportunities that arise from the adjacent possible, we
        must understand first what tools and technologies are available to make
        the most of the available opportunities, given those possibilities.
      </p>
    </section-intro>
  </div>
</template>

<script>
import HeroSection from '~/components/HeroSection'
import SectionIntro from '~/components/SectionIntro'

export default {
  name: 'ImaginePage',
  components: {
    HeroSection,
    SectionIntro
  }
}
</script>
