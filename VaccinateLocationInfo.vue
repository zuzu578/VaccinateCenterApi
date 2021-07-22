<template>
  <div>
      <h1> VaccinationCorona </h1>
              <!-- 데이터 동적 binding !-->
       <div class="board_view_area" v-for="(jData, idx) in boardData" :key="idx">
           {{jData}}

        </div>
  </div>
</template>

<script>
import axios from 'axios'
export default {
    data(){
        return{
            boardData:''
        }
    },
    mounted(){
        axios.get('http://localhost:8082/myapp/VaccinationCorona')

    .then((res)=>{
        //get Data List 
        console.log(res.data.data);
        this.boardData = res.data.data;
    })
    },
    created(){

    },
    methods:{

    },

}
</script>

<style>

</style>