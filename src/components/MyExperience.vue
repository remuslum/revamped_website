<template>
    <div class="container">
        <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@500&display=swap" rel="stylesheet">
        <link href="https://fonts.googleapis.com/css2?family=Ubuntu&display=swap" rel="stylesheet">
        <link href="https://fonts.googleapis.com/css2?family=Bree+Serif&display=swap" rel="stylesheet">
        <div class="topic">
            <h1> Experience </h1>
        </div>
        <div class="summary">
            <div class="experience">
                <div class="title">
                    Lomotif
                </div>
                <div class="role">
                    Data Analyst Intern
                </div>
                <div class="time">
                    July 2021 - Present
                </div>
                <div class="description">
                    <ul> 
                        <li> Identified, analyzed, and interpreted trends or patterns in complex data sets by finding correlations and visualizing with charts. </li>
                        <li> Utilized various professional statistical techniques and maintained large databases to collect and analyze data from partners and customers. </li>
                        <li> Developed essential metrics derived from raw company data such as retention rate, churn rate and Monthly Average Users to track improvements in organizational efficiency. </li>
                    </ul>
                </div>
            </div>
            <div class="experience">
                <div class="title">
                    Prudential Assurance Company Singapore (Pte) Limited 
                </div>
                <div class="role">
                    Financial Advisor Trainee 
                </div>
                <div class="time">
                    May 2021 - July 2021
                </div>
                <div class="description">
                    <ul> 
                        <li> Helped individuals and families build and execute wealth management strategies based on unique goals and objectives. </li>
                        <li> Educated clients on various financial matters and provided professional recommendations on investment opportunities, products and services based on each client’s individual needs. </li>
                        <li> Assisted clients in making beneficial and strategic decisions regarding investments, low-cash financing, and sourcing overseas partners.  </li>
                    </ul>
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
    .topic {
        width: 20% ; 
        margin-left: .5em ; 
        text-align: center;
        font-family: 'Ubuntu', sans-serif;
        font-size: 1.5rem ; 
    }
    .summary {
        width: 75% ; 
        font-family: 'Cormorant Garamond', serif;
        font-size: 1.5rem ; 
    }
    .experience {
        margin-top: .5em ;
    }
    .title {
        font-family: 'Bree Serif', serif;
    }

    @media screen and (max-width: 800px){
        .container{
            flex-direction: column;
        } 
        .topic {
            width: 100% ; 
        }
        .summary {
            width: 100% ; 
        }
    }
</style>