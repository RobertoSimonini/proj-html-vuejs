<script>
export default {
    data() {
        return {
            matches: [
                {
                    homeTeam: 'Istanbul Sports',
                    homePic: '/src/assets/img/league-club-1.png',
                    transferTeam: 'United Fs Club',
                    transferPic: '/src/assets/img/league-club-2.png',
                    id: 1
                },
                {
                    homeTeam: 'Schalke Club',
                    homePic: '/src/assets/img/league-club-3.png',
                    transferTeam: 'Inter Club',
                    transferPic: '/src/assets/img/league-club-4.png',
                    id: 2
                },
                {
                    homeTeam: 'Madrid Club',
                    homePic: '/src/assets/img/league-club-5.png',
                    transferTeam: 'Schalke Club',
                    transferPic: '/src/assets/img/league-club-6.png',
                    id: 3  
                },
                {
                    homeTeam: 'Arsenal Club',
                    homePic: '/src/assets/img/league-club-7.png',
                    transferTeam: 'Bayern Club',
                    transferPic: '/src/assets/img/league-club-8.png',
                    id: 4
                },
                {
                    homeTeam: 'Atletico Club',
                    homePic: '/src/assets/img/league-club-9.png',
                    transferTeam: 'Istanbul Sports',
                    transferPic: '/src/assets/img/league-club-1.png',
                    id: 5
                },
                {
                    homeTeam: 'Unite Fs Club',
                    homePic: '/src/assets/img/league-club-2.png',
                    transferTeam: 'Schalke Club',
                    transferPic: '/src/assets/img/league-club-3.png',
                    id: 5
                },
                {
                    homeTeam: 'Inter Club',
                    homePic: '/src/assets/img/league-club-4.png',
                    transferTeam: 'Madrid Club',
                    transferPic: '/src/assets/img/league-club-5.png',
                    id: 5
                },
                {
                    homeTeam: 'Schalke Club',
                    homePic: '/src/assets/img/league-club-6.png',
                    transferTeam: 'Arsenal Club',
                    transferPic: '/src/assets/img/league-club-7.png',
                    id: 5
                },
                {
                    homeTeam: 'Bayern Club',
                    homePic: '/src/assets/img/league-club-8.png',
                    transferTeam: 'Atletico Club',
                    transferPic: '/src/assets/img/league-club-9.png',
                    id: 5
                },
            ]
        }
    }   
}

</script>

<template>
    
    <section id="ratings" class="p-5">
        <div class="container d-flex justify-content-between flex-wrap">

            <!-- Qui metto la classifica  -->
            <div id="rating">
                <h1 class="text-center py-2"> League Table </h1>
                <table class="table table-borderless">
                    <thead>
                        <tr>
                            <th scope="col" class="w-75">TEAM</th>
                            <th scope="col">W</th>
                            <th scope="col">D</th>
                            <th scope="col">L</th>
                            <th scope="col">PTS</th>
                        </tr>
                    </thead>
                    <tbody>
        
                        <tr>
                            <th scope="row">
                                <span class="pe-2">1</span>
                                <img src="../assets/img/league-club-1.png" alt="">
                                <span class="ps-2">Istanbul Sports</span> 
                            </th>
                            <td>18</td>
                            <td>2</td>
                            <td>0</td>
                            <td>42</td>
                        </tr>
        
                        <tr>
                            <th scope="row">
                                <span class="pe-2">2</span>
                                <img src="../assets/img/league-club-2.png" alt="">
                                <span class="ps-2">United Fs Club</span> 
                            </th>
                            <td>14</td>
                            <td>2</td>
                            <td>1</td>
                            <td>35</td>
                        </tr>
        
                        <tr>
                            <th scope="row">
                                <span class="pe-2">3</span>
                                <img src="../assets/img/league-club-3.png" alt="">
                                <span class="ps-2">Shalcke Club</span> 
                            </th>
                            <td>14</td>
                            <td>2</td>
                            <td>1</td>
                            <td>35</td>
                        </tr>
        
                        <tr>
                            <th scope="row">
                                <span class="pe-2">4</span>
                                <img src="../assets/img/league-club-4.png" alt="">
                                <span class="ps-2">Inter Club</span> 
                            </th>
                            <td>13</td>
                            <td>2</td>
                            <td>1</td>
                            <td>31</td>
                        </tr>
        
                        <tr>
                            <th scope="row">
                                <span class="pe-2">5</span>
                                <img src="../assets/img/league-club-5.png" alt="">
                                <span class="ps-2">Madrid Club</span> 
                            </th>
                            <td>12</td>
                            <td>1</td>
                            <td>2</td>
                            <td>30</td>
                        </tr>
        
                        <tr>
                            <th scope="row">
                                <span class="pe-2">6</span>
                                <img src="../assets/img/league-club-6.png" alt="">
                                <span class="ps-2">Shalcke Club</span> 
                            </th>
                            <td>11</td>
                            <td>0</td>
                            <td>3</td>
                            <td>28</td>
                        </tr>
        
                        <tr>
                            <th scope="row">
                                <span class="pe-2">7</span>
                                <img src="../assets/img/league-club-7.png" alt="">
                                <span class="ps-2">Arsenal Club</span> 
                            </th>
                            <td>10</td>
                            <td>5</td>
                            <td>0</td>
                            <td>26</td>
                        </tr>
        
                        <tr>
                            <th scope="row">
                                <span class="pe-2">8</span>
                                <img src="../assets/img/league-club-8.png" alt="">
                                <span class="ps-2">Bayern Club</span> 
                            </th>
                            <td>10</td>
                            <td>2</td>
                            <td>2</td>
                            <td>24</td>
                        </tr>
        
                        <tr>
                            <th scope="row">
                                <span class="pe-2">9</span>
                                <img src="../assets/img/league-club-9.png" alt="">
                                <span class="ps-2">Atletico Club</span> 
                            </th>
                            <td>9</td>
                            <td>0</td>
                            <td>4</td>
                            <td>20</td>
                        </tr>
        
                        <tr class="league-table text-center">
                            <td class="fw-bold">
                                View Full League Table
                            </td>
                            <td></td>
                            <td></td>
                            <td></td>
                            <td></td>
        
                        </tr>
                    </tbody>
        
                </table>
    
            </div>

            <!-- Qui metto i risultati e le fixtures  -->
            <div id="results">
                <h1 class="text-center py-2"> Fixtures & Results </h1>
                <table class="table table-striped">
                    <tbody>
                        <tr v-for="match in matches" class="text-center">
                            <td>
                                <img :src="match.homePic" alt="">
                                <span class="fw-normal">{{match.homeTeam}} </span>
                                <span class="px-2">VS</span>
                                <span class="fw-normal">{{match.transferTeam}}</span>
                                <img :src="match.transferPic" alt="">
                            </td>
                           
                        </tr>
                        <tr>
                            <td class="text-center fixtures">
                                View Full Fixtures
                            </td>
                        </tr>
                    </tbody>
                </table>
    
            </div>
            <!-- Qui metto la tabelle dei risultati/partite -->
    
            <!-- Qui metto l'immagino dello sponsor -->
        </div>
    </section>

</template>


<style lang="scss" scoped>


// GENERICS 
#rating, #results {
    width: 48%;
}


//TABELLA

#ratings {
    
        table {
            width: 100%;
            height: 750px;

            th {
                font-weight: normal;

                img {
                    height: 50px;
                }

            }
            
            tr td:last-child{
                font-weight: bold;
            }

            td {
                vertical-align: middle;
            }
        }
}

// Qui gestisco i colori in base alla sezione della tabella 

thead {
    background-color: #212121;
    color: #ffff;

    th {
        font-weight: bold;
        font-size: 20px;
    }

}

tbody {
    background-color: #F5F5F5;
}


// RESULTS 

#results {

    img {
        height: 50px;
    }

    .teams {
        line-height: 75px;
    }

}

// GENERICS

.league-table, .fixtures {
    background-color: rgb(0,0,0);
    color: #ffff;
    height: 75px;
    cursor: pointer;
}

.league-table .fw-bold {
    transform: translateX(60px);
}

</style>