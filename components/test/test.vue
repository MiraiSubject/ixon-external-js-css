<!-- https://stackoverflow.com/questions/65547199/using-bootstrap-5-with-vue-3 -->

<template>
  <main>
    <button class="btn btn-primary" data-bs-target="#collapseTarget" data-bs-toggle="collapse">
      Bootstrap collapse
    </button>
    <div class="collapse py-2" id="collapseTarget">
      This is the toggle-able content!
    </div>
  </main>
</template>

<script>
import "../../node_modules/bootstrap/dist/css/bootstrap.min.css"
import "../../node_modules/bootstrap/dist/js/bootstrap.bundle"
export default {
  name: 'test',
  props: ['context'],
};
</script>