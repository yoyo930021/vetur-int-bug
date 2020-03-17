<template>
  <div class="hello">
    <ul
      v-for="group in groups"
      :key="group.id"
    >
      <li>
        <ul
          v-for="item in group.list"
          :key="item"
        >

        </ul>
      </li>
    </ul>
  </div>
</template>

<script lang="ts">
import { defineComponent, computed } from "@vue/composition-api";

export default defineComponent({
  setup() {
    const groups = computed(() => {
      const result = []
      result.push({
        id: 1,
        text: '',
        list: []
      })

      return result
    });

    return {
      groups
    };
  }
});
</script>
