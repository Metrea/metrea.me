<template>
  <div>
    <!-- About me counter -->
    <div>
      <!-- Years of experience counter -->
      <div>
        <counter
          ref="counter"
          :startAmount="0"
          :endAmount="7"
          :duration="1"
          autoinit="true"
          @finished="alert(`Counting finished!`)"
        />
        <span>Years of experience</span>
      </div>

      <!-- Github star counter -->
      <div>
        <counter
          ref="counter"
          :startAmount="0"
          :endAmount="20"
          :duration="1"
          suffix="k+"
          autoinit="true"
          @finished="alert(`Counting finished!`)"
        />
        <span>Stars on Github</span>
      </div>

      <!-- Positive feedback counter -->
      <div>
        <counter
          ref="counter"
          :startAmount="0"
          :endAmount="95"
          :duration="1"
          suffix="%"
          autoinit="true"
          @finished="alert(`Counting finished!`)"
        />
        <span>Positive feedback</span>
      </div>

      <!-- Projects completed counter -->
      <div>
        <counter
          ref="counter"
          :startAmount="0"
          :endAmount="77"
          :duration="1"
          autoinit="true"
          @finished="alert(`Counting finished!`)"
        />
        <span>Projects completed</span>
      </div>
    </div>
  </div>
</template>

<script>
import counter from "vue3-autocounter";

export default {
  components: {
    counter,
  },
};
</script>

<style></style>
