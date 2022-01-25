<template>
    <div class="container-fluid mt-5">
         <div class="row h-350 justify-content-center">
            <div class="col-8 text-center d-flex flex-column align-items-center">
                 <h3>Latest News</h3>
                 <hr>
                 <p class="p">Lorem ipsum dolor sit amet consectetur adipisicing elit. Itaque pariatur voluptatibus exercitationem expedita aspernatur corporis, culpa deserunt nobis at unde ea cum quas laudantium illum sit maiores neque quis assumenda.</p>
            </div>
        </div>
        <div class="cont-cards">
                <CardsNews v-for="(card,index) in cards"
                :key="index"
                :titolo="card.title"
                :date="card.date"
                :descr="card.descr" />
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
                {"img": '',
                "title": 'Redeveloping Florida Remote Southern Coast', 
                "date":'October 6th, 2021',
                "descr": 'Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam eaque ipsa, quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt, explicabo. Nemo enim ipsam voluptatem, quia voluptas sit, aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos, qui ratione voluptatem sequi nesciunt, neque porro quisquam est'},

                {"img": '',
                "title": 'How To Manage Large Construction Projects', 
                "date":'January 31th, 2021',
                "descr": 'Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam eaque ipsa, quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt, explicabo. Nemo enim ipsam voluptatem, quia voluptas sit, aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos, qui ratione voluptatem sequi nesciunt, neque porro quisquam est'},

                {"img": '',
                "title": 'Future Proofing A Modern Home', 
                "date":'April 8th, 2022',
                "descr": 'Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam eaque ipsa, quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt, explicabo. Nemo enim ipsam voluptatem, quia voluptas sit, aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos, qui ratione voluptatem sequi nesciunt, neque porro quisquam est'},
                
            ]
        }
    }

    }

</script>

<style lang="scss" scoped>
    .p {
        color: grey;
        font-size: 12px;
        line-height: 2em;
    }

</style>