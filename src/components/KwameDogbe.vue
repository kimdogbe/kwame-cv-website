<template>
  <v-container>
    <v-col cols="8">
      <v-row>
        <v-col cols="8">
          <h1>Hi there.</h1>
          <h2>My name is Kwame Dogbe</h2>
        </v-col>
        <v-col cols="4">
          <v-avatar size="200">
            <v-img :src="require('@/assets/kwame.jpg')"/>
          </v-avatar>
        </v-col>
      </v-row>
      

      <p>I am a recent Computer Science (MEng) graduate from the 
        <a href="https://www.bristol.ac.uk" target="_blank">University of Bristol</a>. 
        Check out my <a href="https://github.com/kimdogbe" target="_blank">Github</a>
        page for projects I have worked on.</p>
      
      <p>My main interests include development of web applications using frameworks
        such as Vuejs and various cloud services from AWS. I have developed using 
        several languages including: Python, JavaScript, Golang, C, C# and Java.
      </p>

      <p>My hobbys include sport in general, primarily basketball and football, but 
        I'm always keen for a game of badminton or table tennis, or for long walks
        and cycles to glorious destinations. I also enjoy photography and have a dedicated
        Instagram account for my shots.
      </p>

      <p>I have had a deverse range of jobs that include the following:</p>
      <ul>
        <li>Farm Assistant role at a <a href="http://graysfarm.co.uk" target="_blank">
        Pick Your Own farm.</a> This involved several odd jobs around a farm</li>
        <li>Bar Staff at the local Wetherspoons working evening shifts on Friday & Saturday Nights</li>
        <li>Team Leader role for <a href="https://wearencs.com" target="_blank">NCS</a>
        that invovled organising and encouraging a team of young adults</li>
        <li>Software Developer role at <a href="https://www.bt.com">BT</a> 
        creating tools to support workflows</li>
      </ul>

      <p></p>
    </v-col>
  </v-container>
</template>

<script>
export default {
  name: 'KwameDogbe',

}
</script>

<style scoped>
h1 {
  font-size: 4em;
}
h2 {
  font-size: 2.5em;
}
p, li {
  font-size: 1.3em;
  color: #808080;
}
v-img {
  border-radius: 50%;
}
</style>