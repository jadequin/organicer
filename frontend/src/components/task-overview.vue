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
      <li class="list-group-item task-item">
        <div class="custom-checkbox d-flex align-items-center">
          <input class="form-check-input me-1 custom-checkbox-input" type="checkbox" value="" id="firstCheckboxStretched">
          <input class="form-control" type="text" placeholder="Bezeichnung der Aufgabe">
        </div>
      </li>
      <li class="list-group-item task-item">
        <div class="custom-checkbox d-flex align-items-center">
          <input class="form-check-input me-1 custom-checkbox-input" type="checkbox" value="" id="secondCheckboxStretched">
          <input class="form-control" type="text" placeholder="Bezeichnung der Aufgabe">
        </div>
      </li>
      <li class="list-group-item task-item">
        <div class="custom-checkbox d-flex align-items-center">
          <input class="form-check-input me-1 custom-checkbox-input" type="checkbox" value="" id="thirdCheckboxStretched">
          <input class="form-control" type="text" placeholder="Bezeichnung der Aufgabe">
        </div>
      </li>
    </ul>
  </div>
</template>

<style scoped>

.custom-checkbox-input {
  width: 30px;
  height: 30px;
  cursor: pointer;
}


.task-item {
  margin: 2px;
  border-radius: 10px;
}
.form-control {
  margin: 5px;
}

</style>