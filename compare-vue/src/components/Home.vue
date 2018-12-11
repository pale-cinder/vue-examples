<template>
  <div class="home">
  
   <section class="hero">
  <div class="hero-body">
    <div class="container">
      <h1 class="title">{{ heading }}</h1>
      <div class="is-two-third column is-paddingless">
        <h2 class="subtitle is-4">{{ subheading }}</h2>
      </div>
      <a class="button is-large is-primary" id="learn">Learn more</a>
    </div>
  </div>
</section>


<section class="section pd">
  <div class="container">
    <div class="columns">
      <div class="column is-1 has-text-centered">
        <i class="fa fa-cog is-primary"></i>
      </div>
      <div class="column is-one-third">
        <p class="title"><strong>The Developer Guide provides practical, real-world examples and instruction on using the framework without the noise and complexity of the complete library reference. </strong></p>
      </div>
      <div class="column">
        <p>The API Reference provides a searchable reference guide of every detail of the framework's interfaces, handlers, and extensions. </p>
      </div>
    </div>

    <div class="columns pd">
        <div class="column">
          <div class="card">
            <div class="card-content">
              <p class="title">Quickstart your introduction with a beginner tutorial on building a command-line based task management application.</p>
              <p class="subtitle">20 minute beginner tutorial </p>
            </div>
          </div>
        </div>
        
        <div class="column">
            <div class="card">
              <div class="card-content">
                <p class="title">Quickstart your introduction with a beginner tutorial on building a command-line based task management application.</p>
                <p class="subtitle">20 minute beginner tutorial </p>
              </div>
            </div>
          </div>

          <div class="column">
              <div class="card">
                <div class="card-content">
                  <p class="title">Quickstart your introduction with a beginner tutorial on building a command-line based task management application.</p>
                  <p class="subtitle">20 minute beginner tutorial </p>
                </div>
              </div>
            </div>
    </div>
  </div>

</section>
  </div>
</template>

<script>
export default {
  name: 'home',
  data () {
    return {
      heading: 'Happiness is the meaning and the purpose of life, the whole aim and end of human existence.”',
      subheading: 'It comes down to this: What are you DOING that’s making a difference?'
    }
  } 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="sass" scoped>

@import '../mq'

</style>
