<template>
    <div class="container-fluid pt-5">
         <div class="row h-350 justify-content-center">
            <div class="col-8 text-center d-flex flex-column align-items-center">
                 <h3>Latest News</h3>
                 <hr>
                 <p class="p">Lorem ipsum dolor sit amet consectetur adipisicing elit. Itaque pariatur voluptatibus exercitationem expedita aspernatur corporis, culpa deserunt nobis at unde ea cum quas laudantium illum sit maiores neque quis assumenda.</p>
            </div>
        </div>
        <div class="cont-cards d-flex justify-content-center">
                <CardsNews v-for="(card,index) in cards"
                :key="index"
                :img="card.img"
                :titolo="card.title"
                :date="card.date"
                :descr="card.descr" />
            </div>
            <div class="d-flex justify-content-center mt-5">
                <hr>
                <a href=""><span class="link-project">view all projects</span></a>
                <hr>
         </div>
    </div>
  
</template>

<script>
import CardsNews from "./CardsNews.vue";
export default {
    name: 'MainNews',
    components: {
     CardsNews,
  },
    data(){
        return {
            cards: [
                {"img": 'ruspaaa.jpg',
                "title": 'Redeveloping Florida Remote Southern Coast', 
                "date":'October 6th, 2021',
                "descr": 'Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam eaque ipsa, quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt, explicabo. Nemo enim ipsam voluptatem, quia voluptas sit, aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos, qui ratione voluptatem sequi nesciunt, neque porro quisquam est'},

                {"img": 'bridge.jpg',
                "title": 'How To Manage Large Construction Projects', 
                "date":'January 31th, 2021',
                "descr": 'Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam eaque ipsa, quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt, explicabo. Nemo enim ipsam voluptatem, quia voluptas sit, aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos, qui ratione voluptatem sequi nesciunt, neque porro quisquam est'},

                {"img": 'homemodern.jpg',
                "title": 'Future Proofing A Modern Home', 
                "date":'April 8th, 2022',
                "descr": 'Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam eaque ipsa, quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt, explicabo. Nemo enim ipsam voluptatem, quia voluptas sit, aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos, qui ratione voluptatem sequi nesciunt, neque porro quisquam est'},
                
            ]
        }
    }

    }

</script>

<style lang="scss" scoped>
    .container-fluid {
        background-color:#f0ede6;
        height: 870px;
    }
    .p {
        color: grey;
        font-size: 12px;
        line-height: 2em;
    }
    .link-project {
        margin-right: 2em;
        margin-left: 2em;
        font-size: 10px;
        text-transform: uppercase;
    }
    a, a:hover{
        text-decoration: none;
        color: rgb(177, 177, 177);
    }
    hr {
            color: orange;
        }

</style>