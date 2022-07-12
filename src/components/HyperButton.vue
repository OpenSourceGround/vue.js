<script setup>
import { ModelCollada, ModelObj } from "vue-3d-model";
</script>

<template >
  <div class="grid flex-wrap grid-cols-1">
    <div class="flex flex-wrap h-screen">
      <div class="w-full">
        <model-obj
          src="/src/static/models/Name.obj"
          mtl="/src/static/models/Name.mtl"
        />
      </div>
    </div>
  </div>
</template>