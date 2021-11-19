<script lang="ts">
  let a: Number = null;
</script>

<sl-tab-group>
  <sl-tab slot="nav" panel="Add">Add Measures</sl-tab>
  <sl-tab slot="nav" panel="Women">Women's Measures</sl-tab>
  <sl-tab slot="nav" panel="Medications">Medications</sl-tab>
  <sl-tab slot="nav" panel="Diabetic">Diabetic Care</sl-tab>

  <sl-tab-panel name="Add">
    <div>Add Measures</div>
  </sl-tab-panel>

  <sl-tab-panel name="Women">
    <div>Women's Measures</div>
  </sl-tab-panel>

  <sl-tab-panel name="Medications">
    <div>Medications</div>
  </sl-tab-panel>

  <sl-tab-panel name="Diabetic">
    <div>Diabetic Care</div>
  </sl-tab-panel>
</sl-tab-group>
