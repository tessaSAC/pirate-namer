<script>
const pirateTitles = [
  'Anchor Watch',
  'Arrrrmourer',
  'Arrrrmourer\'s Mate',
  'Arrrtist',
  'Boatswain',
  'Bosun\'s Mate',
  'Cape-Merchant',
  'Captain',
  'Cap\'n',
  'Carrrrrrrrrrpenter',
  'Carrrrrrrrrrpenter\'s Mate',
  'Chirurgeon',
  'Cooper',
  'Coxswain',
  'First Mate',
  'Gunner',
  'Gunner\'s Mate',
  'Helmsperson',
  'Linguist',
  'Musketeer',
  'Ropemaker',
  'Sea-Arrrrrrrrrrrrrrtist',
  'Skipper',
  'Stand-by Watch',
  'Steersperson',
  'Surgeon',
  'Top Person',
  'Watch',

  // Nicknames
  'Birdeye',
  'Dread Pirate',
  'Old-Tide',
  'Stinkin',
  'Silly',
  'Viewtiful',
]

const pirateNames = [
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
]

const pirateNicknames = [
  'Dark-Skull',
  'One Piece',
  'The Gentle Pirate',
  'The Rhode Island Pirate',
  'The Unicorn',
  'The Vue Fan',
]

export default {
  data: _ => ({
    userName: ''
  }),

  methods: {
    generatePirateName() {
      const characterToGenerateName = this.userName.charCodeAt(Math.round(Math.random() * 10000) % this.userName.length)
      return pirateNames[characterToGenerateName % pirateNames.length]
    }
  },
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
