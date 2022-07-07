<template>
  <div class="flex">
    <Chat/>
  </div>
</template>

<script>
import Chat from "../components/chat.vue";
export default {
    name: "IndexPage",
    data() {
        return { arr: [1, 2, 3, 4, 5, 6, 7, 8, 9, 10] };
    },
    components: { Chat }
};
</script>
