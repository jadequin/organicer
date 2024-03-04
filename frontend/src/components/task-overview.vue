<script>
import 'bootstrap/dist/css/bootstrap.css';
export default {
  name: 'task-overview'
}
</script>

<template>
  <div>
    <h2>TaskList</h2>
    <ul class="list-group">
      <li class="list-group-item">
        <input class="form-check-input me-1" type="checkbox" value="" id="firstCheckboxStretched">
        <label class="form-check-label stretched-link" for="firstCheckboxStretched">First checkbox</label>
      </li>
      <li class="list-group-item">
        <input class="form-check-input me-1" type="checkbox" value="" id="secondCheckboxStretched">
        <label class="form-check-label stretched-link" for="secondCheckboxStretched">Second checkbox</label>
      </li>
      <li class="list-group-item">
        <input class="form-check-input me-1" type="checkbox" value="" id="thirdCheckboxStretched">
        <label class="form-check-label stretched-link" for="thirdCheckboxStretched">Third checkbox</label>
      </li>
    </ul>
  </div>
</template>

<style scoped>

</style>