<template>
  <div class="pagination-container">
    <page-location current="1" total="2" />
    <sort-order sortby="Sort Order" />
    <limit-drop-down limit="10" />
  </div>
</template>

<script>
import LimitDropDown from "./LimitDropDown.vue";
import PageLocation from "./PageLocation.vue";
import SortOrder from "./SortOrder.vue";

export default { components: { LimitDropDown, PageLocation, SortOrder } };
</script>
<style scoped>
.pagination-container {
  max-width: 450px;
  min-width: 300px;
  display: flex;
  justify-content: space-around;
  align-items: center;
}
</style>

