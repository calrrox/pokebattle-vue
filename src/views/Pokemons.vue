<template>
  <div class="pokemons">
    <h1>Pokemons index</h1>
    <PokeCard />
  </div>
</template>

<script>
import PokeCard from "@/components/PokeCard.vue";

export default {
  name: "Pokemons",
  components: {
    PokeCard
  }
};
</script>
