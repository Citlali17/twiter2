<template>
<body>
    <div class="icons">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/4f/Twitter-logo.svg/2491px-Twitter-logo.svg.png" alt="bird"></img>
        <img src="data:image/jpeg;base64,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">
        <img src="data:image/jpeg;base64,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">
        <i class="fa-regular fa-bell"></i>
        <i class="fa-regular fa-envelope"></i>
        <i class="fa-regular fa-envelope"></i>
        <i class="fa-regular fa-user"></i>
        <i class="fa-sharp fa-solid fa-comment-dots"></i>
        <img id="newTwit" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ5WOIZFGXMM0Lro7ISpeaxjjfv2nMNKu6FP-y79H66DCsKuwGC_NNH_5Ynn-4CRB2PtrE&usqp=CAU">
     
        

    </div>
    <div class="container">
            <div class="search">
                <img class="search-icon" src="data:image/svg+xml;utf8;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iaXNvLTg4NTktMSI/Pgo8IS0tIEdlbmVyYXRvcjogQWRvYmUgSWxsdXN0cmF0b3IgMTkuMC4wLCBTVkcgRXhwb3J0IFBsdWctSW4gLiBTVkcgVmVyc2lvbjogNi4wMCBCdWlsZCAwKSAgLS0+CjxzdmcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB4bWxuczp4bGluaz0iaHR0cDovL3d3dy53My5vcmcvMTk5OS94bGluayIgdmVyc2lvbj0iMS4xIiBpZD0iQ2FwYV8xIiB4PSIwcHgiIHk9IjBweCIgdmlld0JveD0iMCAwIDU2Ljk2NiA1Ni45NjYiIHN0eWxlPSJlbmFibGUtYmFja2dyb3VuZDpuZXcgMCAwIDU2Ljk2NiA1Ni45NjY7IiB4bWw6c3BhY2U9InByZXNlcnZlIiB3aWR0aD0iMTZweCIgaGVpZ2h0PSIxNnB4Ij4KPHBhdGggZD0iTTU1LjE0Niw1MS44ODdMNDEuNTg4LDM3Ljc4NmMzLjQ4Ni00LjE0NCw1LjM5Ni05LjM1OCw1LjM5Ni0xNC43ODZjMC0xMi42ODItMTAuMzE4LTIzLTIzLTIzcy0yMywxMC4zMTgtMjMsMjMgIHMxMC4zMTgsMjMsMjMsMjNjNC43NjEsMCw5LjI5OC0xLjQzNiwxMy4xNzctNC4xNjJsMTMuNjYxLDE0LjIwOGMwLjU3MSwwLjU5MywxLjMzOSwwLjkyLDIuMTYyLDAuOTIgIGMwLjc3OSwwLDEuNTE4LTAuMjk3LDIuMDc5LTAuODM3QzU2LjI1NSw1NC45ODIsNTYuMjkzLDUzLjA4LDU1LjE0Niw1MS44ODd6IE0yMy45ODQsNmM5LjM3NCwwLDE3LDcuNjI2LDE3LDE3cy03LjYyNiwxNy0xNywxNyAgcy0xNy03LjYyNi0xNy0xN1MxNC42MSw2LDIzLjk4NCw2eiIgZmlsbD0iIzAwMDAwMCIvPgo8Zz4KPC9nPgo8Zz4KPC9nPgo8Zz4KPC9nPgo8Zz4KPC9nPgo8Zz4KPC9nPgo8Zz4KPC9nPgo8Zz4KPC9nPgo8Zz4KPC9nPgo8Zz4KPC9nPgo8Zz4KPC9nPgo8Zz4KPC9nPgo8Zz4KPC9nPgo8Zz4KPC9nPgo8Zz4KPC9nPgo8Zz4KPC9nPgo8L3N2Zz4K" />  
                <input class="styleButton" placeholder="        search people" type="text"> 
                <button class="submit" type="submit">Search</button>
            </div>

            <div class="options">
                <p>Top</p>
                <p>Latest</p>
                <p>People</p>
                <p>Photos</p>
                <p>Videos</p>
            </div>

            <div class="post">
                <h4>-------------------------------</h4>
                <img src="https://images.hindustantimes.com/img/2021/06/27/original/Twitter_crush_tweet_1_1624765365241.PNG"/>
                <br> </br>
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQFbud_5ln3DZPO-kfibeTU_o0tkGAmzbk9Yy7ykm1Ak-oIj9vtMBBQuzhOJcSCDR9ZT6s&usqp=CAU"/>

            </div>
    </div>

    <div class="right">
        <div class="Filters">
            <h2>Search filters</h2>
            <h3>People</h3>
            <h4>From anyone</h4>
            <h4>People you follow</h4>
            <br> </br>
            <h3>Location</h3>
            <h4>Anywhere</h4>
            <h4>Near you</h4>
            <br> </br>
            <h3 class="bluetext">Advanced search</h3>
            <br> </br>
            
    
        </div>

        <div class="Happening">
            <h2>What´s happening</h2>
            

        </div>
    </div>
</body>

</template>



<script>
    export default{
        name: 'twitter',
        
    }


</script>


<style scoped>

body{
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: space-around;
}

.styleButton{
    background-color: rgb(240, 238, 238);
    border-radius: 5px;
    border-color: transparent;
    width: 300px;
    height: 20px;
}

.search-icon{
    position: absolute;
    margin-left: 8px;
    margin-top: 1px;
}

.submit{
    background-color: rgb(4, 184, 255);
    border-color: transparent;
    color: white;
    width: 60px;
    height: 20px;
    border-radius: 10px;

} 

.icons{
    display: flex;
    flex-direction: column;
    justify-content: flex-start;  
    padding-left: 30px;
    padding-right: 30px;
    border-right: solid gray ;

}

.icons>img{
    width: 25px;
    height: 25px;
    margin-bottom: 20px;
    
}

.icons>i{
    width: 25px;
    height: 25px;
    margin-bottom: 20px;
    
}

#newTwit{
    width: 80px;
    height: 50px;
    position: absolute;
    margin-top: 360px;
    margin-left: -15px;
}



.container{
    display: flex;
    flex-direction: column;
    justify-content:  flex-start;
    width: 800px;
    border-right: solid;
}


.options{
    margin-top: 50px;
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    
}

.options>p{
    color: rgb(85, 85, 85);
    font-weight: bold;
    width: 60px;
    height: 30px;
}

.options>p:hover{
    color:  rgb(4, 184, 255);
    font-weight: bold;
    border-bottom: solid;
}


.right{
    justify-content: start;
    display: flex;
    flex-direction: column;
    border-right: solid;
}

.Filters{
    justify-content: start;
    display:flex;
    flex-direction: column;
    justify-content: flex-start;
}

.bluetext {
    color:  rgb(4, 184, 255);
}

.happening{
    justify-content: start;
}
</style>