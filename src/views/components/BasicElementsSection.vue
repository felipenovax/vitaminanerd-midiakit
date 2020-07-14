<template>
  <div class="wrapper">
    <div id="buttons">
      <div class="title members">
        <section class="container members__body">
          <div
            v-for="member in members"
            :key="member.imgUrl"
            class="members__body--avatar"
          >
            <img :src="member.imgUrl" alt="" class="members__body-img" />
            <p>{{ member.name }}</p>
          </div>
        </section>
        <section>
          textos
        </section>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  components: {
    // Badge
  },
  data() {
    return {
      members: [
        {
          name: "Felipe Erick",
          imgUrl:
            "https://vitaminanerd.com.br/wp-content/uploads/2018/01/20031675_1487525227957897_2100959413562236891_n-1-150x150.jpg"
        },
        {
          name: "Luan Bião",
          imgUrl:
            "https://vitaminanerd.com.br/wp-content/uploads/2019/01/luan-150x150.jpg"
        },
        {
          name: "Danilo Alcantara",
          imgUrl:
            "https://vitaminanerd.com.br/wp-content/uploads/2020/03/Danilo-Alcantara-Araujo-de-Azevedo-e1585785691274-150x150.jpeg"
        },
        {
          name: "Douglas Euclides",
          imgUrl:
            "https://vitaminanerd.com.br/wp-content/uploads/2018/02/P_20180202_124525_1_p-150x150.jpg"
        },
        {
          name: "Douglas MCT",
          imgUrl:
            "https://vitaminanerd.com.br/wp-content/uploads/2018/01/douglasmct-36-150x150.jpg"
        },
        {
          name: "Elis Regina",
          imgUrl:
            "https://vitaminanerd.com.br/wp-content/uploads/2018/01/elisassuncao-26-150x150.jpg"
        },
        {
          name: "Fernanda Cavalcanti",
          imgUrl:
            "https://vitaminanerd.com.br/wp-content/uploads/2018/01/perfil-fernanda-150x150.jpg"
        },
        {
          name: "Marcelo Del Debbio",
          imgUrl:
            "https://vitaminanerd.com.br/wp-content/uploads/2018/01/marcelodeldebbio-30-150x150.jpg"
        },
        {
          name: "Marco Bettoni",
          imgUrl:
            "https://vitaminanerd.com.br/wp-content/uploads/2018/01/marcobettoni-33-150x150.jpg"
        },
        {
          name: "Paulo Martins",
          imgUrl:
            "https://vitaminanerd.com.br/wp-content/uploads/2019/12/paulo-martins-perfil-150x150.png"
        },
        {
          name: "Veri Luna",
          imgUrl:
            "https://vitaminanerd.com.br/wp-content/uploads/2018/03/Perfil01-2-150x150.jpg"
        },
        {
          name: "David Almeida",
          imgUrl:
            "https://vitaminanerd.com.br/wp-content/uploads/2018/03/Perfil01-2-150x150.jpg"
        },
        {
          name: "William Mendes",
          imgUrl:
            "https://vitaminanerd.com.br/wp-content/uploads/2019/12/IMG-20191121-WA0009-150x150.jpg"
        },
        {
          name: "Wislom Almeida",
          imgUrl:
            "https://vitaminanerd.com.br/wp-content/uploads/2019/11/Foto-Wislom-Almeida-150x150.jpg"
        }
      ]
    };
  }
};
</script>

<style lang="sass" scoped>
.members
  background-image: linear-gradient(to top, rgba(0, 0, 0, 0) 2%, rgba(255, 255, 255, 1) 100%), url('~@/assets/img/bg-space.jpg')
  background-size: 100%
  display: grid
  grid-template-columns: 1fr 1fr
  padding: 0px 80px

  &__body
    display: grid
    grid-template-columns: repeat(4, 1fr)
    grid-gap: 8px
    margin-top: 20px
    color: white

    &-img
      width: auto
      border-radius: 12px
      box-shadow: 0px -1px 2px rgba(0, 0, 0, 0.2)

.vertical-center
  display: flex
  align-items: center

.flex-column
  display: flex
  flex-direction: column

.md-checkbox,
.md-radio
  display: flex
  margin: 0
  margin-bottom: 0.5rem
</style>
