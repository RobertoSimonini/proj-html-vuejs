<script>
import MatchCard from './MatchCard.vue';
export default {
    data (){
        return {
            matches: [
                {
                    homeTeam: 'Schalke Club',
                    homePic: '/src/assets/img/league-club-3.png',
                    transferTeam: 'Inter Club',
                    transferPic: '/src/assets/img/league-club-4.png',
                    date: 'October 20, 2022 17:00 pm',
                    stadium: 'Expert Stadium',
                    id: 1
                },
                {
                    homeTeam: 'Atletico Club',
                    homePic: '/src/assets/img/league-club-9.png',
                    transferTeam: 'Schalke Club',
                    transferPic: '/src/assets/img/league-club-6.png',
                    date: 'September 18, 2022 21:00 pm',
                    stadium: 'Expert Stadium',
                    id: 2
                },
                {
                    homeTeam: 'United Fs Club',
                    homePic: '/src/assets/img/league-club-2.png',
                    transferTeam: 'Bayern Club',
                    transferPic: '/src/assets/img/league-club-8.png',
                    date: 'August 3, 2022 19:00 pm',
                    stadium: 'Expert Stadium',
                    id: 3  
                },
                {
                    homeTeam: 'Arsenal Club',
                    homePic: '/src/assets/img/league-club-7.png',
                    transferTeam: 'Atletico Club',
                    transferPic: '/src/assets/img/league-club-9.png',
                    date: 'July 8, 2022 12:00 pm',
                    stadium: 'Expert Stadium',
                    id: 4
                },
                {
                    homeTeam: 'Istanbul Club',
                    homePic: '/src/assets/img/league-club-1.png',
                    transferTeam: 'United Fs Club',
                    transferPic: '/src/assets/img/league-club-2.png',
                    date: 'June 12, 2022 09:00 am',
                    stadium: 'Expert Stadium',
                    id: 5
                },
            ]
        }
    },
    components: {MatchCard}
}

</script>

<template>

<section id="upcoming-matches" class="text-center py-5 px-4">
    <div class="container">
        <h2 class="text-white">
            Upcoming Matches
        </h2>
        <match-card v-for="match in matches" :match="match" :key="match.id"></match-card>    
    </div>

</section>

</template>


<style lang="scss" scoped>
    #upcoming-matches {
        height: 935px;
        background-image: url(../assets/img/saha.jpg);
        background-position: center;
        background-size: cover;
        background-repeat: no-repeat;

        .match-container {
            background-color: rgb(16 29 47 / 50%);

        }
    }
    


</style>