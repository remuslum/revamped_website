<template>
    <div class="container">
        <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@500&display=swap" rel="stylesheet">
        <link href="https://fonts.googleapis.com/css2?family=Ubuntu&display=swap" rel="stylesheet">
        <link href="https://fonts.googleapis.com/css2?family=Oswald:wght@500&display=swap" rel="stylesheet">
        <div class="title">
            <h1 class="title_name"> Skills </h1>
        </div>
        <div class="section">
            <div class="subsection">
                <div class="skills">
                    <div class="name">
                        <h1 class="skill"> Python </h1>
                    </div>
                    <div class="level">
                        <p class="proficiency"> Expert </p>
                    </div>
                </div>
                <div class="skills">
                    <div class="name">
                        <h1 class="skill"> R </h1>
                    </div>
                    <div class="level">
                        <p class="proficiency"> Expert </p>
                    </div>
                </div>
            </div>
            <div class="subsection">
                <div class="skills">
                    <div class="name">
                        <h1 class="skill"> Microsoft Excel </h1>
                    </div>
                    <div class="level">
                        <p class="proficiency"> Expert </p>
                    </div>
                </div>
                <div class="skills">
                    <div class="name">
                        <h1 class="skill"> MySQL </h1>
                    </div>
                    <div class="level">
                        <p class="proficiency"> Expert </p>
                    </div>
                </div>
            </div>
            <div class="subsection">
                <div class="skills">
                    <div class="name">
                        <h1 class="skill"> Tableau </h1>
                    </div>
                    <div class="level">
                        <p class="proficiency"> Expert </p>
                    </div>
                </div>
                <div class="skills">
                    <div class="name">
                        <h1 class="skill"> Microsoft Power BI </h1>
                    </div>
                    <div class="level">
                        <p class="proficiency"> Expert </p>
                    </div>
                </div>
            </div>
            <div class="subsection">
                <div class="skills">
                    <div class="name">
                        <h1 class="skill"> JavaScript (Vue.js) </h1>
                    </div>
                    <div class="level">
                        <p class="proficiency"> Expert </p>
                    </div>
                </div>
                <div class="skills">
                    <div class="name">
                        <h1 class="skill"> HTML,CSS </h1>
                    </div>
                    <div class="level">
                        <p class="proficiency"> Expert </p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
    .container {
        display: flex ;
        justify-content: space-between ;
    }
    .title {
        width : 15% ;
        text-align: center;
        margin-left: 1.5em ; 
    }
    .title_name {
        font-family: 'Ubuntu', sans-serif;
        font-size: 2.5rem ; 
    }
    .skills {
        width: 45% ; 
        display: flex;
        justify-content: space-between;
    }
    .section {
        width: 85% ; 
        display: flex ; 
        flex-direction: column;
        justify-content: space-between;
    }
    .subsection {
        display: flex ; 
        justify-content: space-between;
        width: 100% ; 
    }
    .name {
        width: 50% ; 
    }
    .level {
        width: 50% ; 
        text-align: right ; 
    }
    .skill {
        margin-top: .5em ; 
        margin-left : .5em ; 
        font-family: 'Oswald', sans-serif;
        font-size: 1.5rem ; 
    }
    .proficiency {
        margin-top: .5em ; 
        margin-right : .5em ; 
        font-family: 'Cormorant Garamond', serif;
        font-size: 1.5rem ; 
    }

    @media screen and (max-width: 800px) {
        .container {
            flex-direction: column ; 
        }
        .title {
            width: 100% ; 
            text-align: center ; 
        }
        .section {
            width: 100% ;
        }
    }
</style>