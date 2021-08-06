<script>
const pirateTitles = {

}

const pirateNames = {
      'Aegea',
      'Anamaria',
      'Angelica',
      'Anne',
      'Arcelia',
      'Bonny',
      'Calypso',
      'Charlotte',
      'Ching',
      'Christina',
      'Destiny',
      'Elise',
      'Elizabeth',
      'Flora',
      'Grace',
      'Jacquotte',
      'Jade',
      'Jeanne',
      'Johanna',
      'Lindsey',
      'Maire',
      'Margaret',
      'Maria',
      'Marina',
      'Mary',
      'Nerina',
      'Rachel',
      'Ruth',
      'Sadie',
      'Sayyida',
      'Sirene',
      'Teuta',
      'Tia',
      'Ula',
      'Amaro',
      'Archer',
      'Barbossa',
      'Bartholomew',
      'Calico',
      'Caspian',
      'Charles',
      'Cornelius',
      'Davy',
      'Drake',
      'Edmund',
      'Edward',
      'Francis',
      'Frederick',
      'Hawkins',
      'Henry',
      'Hudd',
      'Jack',
      'JohnIsland',
      'Kiddduring',
      'Marquis',
      'Nathaniel',
      'Nicholas',
      'Phineas',
      'Pierre',
      'Raleigh',
      'Richard',
      'Roger',
      'Ronan',
      'Stede',
      'Thomas',
      'William',
      'Zheng',
      'Bellamy',
      'James',
      'Jordan',
      'Journey',
      'Morgan',
      'Phoenix',
      'Scout',
      'Sailor',
}

export default {
  data: _ => ({
    userName: ''
  }),


}
</script>

<template>
<label>
  What be yer name?
  <input v-model="userName" />
</label>
</template>


<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
