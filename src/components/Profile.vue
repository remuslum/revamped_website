<template>
    <div class="container">
        <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@500&display=swap" rel="stylesheet">
        <link href="https://fonts.googleapis.com/css2?family=Ubuntu&display=swap" rel="stylesheet">
        <div class="topic">
            <h1 class="topic_name"> Profile </h1>
        </div>
        <div class="summary">
            <p class="text"> Remus is an experienced Data Analyst with a demonstrated history of working in the computer software industry. 
                He is adept at receiving and monitoring data from multiple data streams, including SQL and Excel data sources and uses data visualization tools such as Tableau and Power BI to conduct extensive analysis and present his findings. 
                Remus is also a self-starter with a strong attention to detail, wholly committed to ensuring compliance with company policies and laws and is committed to helping companies advance by helping them to develop strategic plans based on predictive modelling and findings. 
            </p>
        </div>
    </div>
</template>

<style scoped>
    .container {
        display: flex ; 
        justify-content: space-between;
    }
    .topic {
        width : 15% ; 
        text-align: center;
        margin-left: 1.5em ; 
    }
    .topic_name {
        font-family: 'Ubuntu', sans-serif;
        font-size: 2.5rem ; 
    }
    .summary {
        width: 85% ; 
    }
    .text{
        font-family: 'Cormorant Garamond', serif;
        font-size: 1.5rem ; 
        margin-left: 1em ; 
    }

    @media screen and (max-width: 800px) {
        .container {
            flex-direction: column;
        }
        .topic{
            width: 100% ; 
            text-align: center;
        }
        .summary {
            width: 100% ; 
            text-align: center ;
        }
    }
</style>