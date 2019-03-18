<template>
  <div class="container is-fullhd">
    <div class="tile is-ancestor">
      <div class="tile is-vertical is-8">
        <div class="tile">
          <div class="tile is-parent is-vertical">
            <article class="tile is-child box">
              <b-field label="Select a date">
                <b-datepicker
                    placeholder="Click to select..."
                    icon="calendar-today">
                </b-datepicker>
              </b-field>
            </article>
            <article class="tile is-child box">
              <!-- Put any content you want -->
            </article>
          </div>
          <div class="tile is-parent">
            <article class="tile is-child box">
              <!-- Put any content you want -->
            </article>
          </div>
        </div>
        <div class="tile is-parent">
          <article class="tile is-child box">
            <!-- Put any content you want -->
          </article>
        </div>
      </div>
      <div class="tile is-parent">
        <article class="tile is-child box">
          <!-- Put any content you want -->
        </article>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    HelloWorld
  }
};
</script>
