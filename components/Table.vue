<template>
<div>
    <div class="table table-responsive">
        <table class="table table-bordered">
        <thead>
        <tr>
        <th scope="col">Ranking</th>
        <th scope="col">Nama</th>
        <th scope="col">Negara</th>
        <th scope="col">Points</th>
        </tr>
        </thead>
        <tbody>
        <tr v-for="badminton of badmintons" v-bind:key="badminton">
            <td>{{badminton.rank}}</td>
            <td>{{badminton.player}}</td>
            <td>{{badminton.country}}</td>
            <td>{{badminton.points}}</td>
        </tr>
        </tbody>
        </table>
    </div>
</div>
</template>

<script>
export default {
    data(){
        return{
            name:'table',
            badmintons : []
        }
    },
    async fetch(){
        this.badmintons = await fetch(
            'https://www.bwfshuttleapi.com/rankings/api/MS/5'
        ).then(res => res.json())
    }
}
</script>