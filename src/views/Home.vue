<template>
  <div class="lg:w-2/5 w-full">
    <div class="text-center lg:flex justify-center block lg:space-x-2 ">
      <div
        v-for="card in cards"
        :key="card.index"
        class="border border-white rounded-md lg:p-5 p-3 text-white cursor-pointer"
      >
        <p>{{ card.name }}</p>
        <p>{{ card.school }}</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      cards: [
        {
          name: "Ayo",
          school: "GPS",
        },
        {
          name: "Ayo",
          school: "GPS",
        },
        {
          name: "Ayo",
          school: "GPS",
        },
      ],
    };
  },
};
</script>

<style></style>
