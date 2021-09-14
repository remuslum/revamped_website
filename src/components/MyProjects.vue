<template>
    <div class="container">
        <link href="https://fonts.googleapis.com/css2?family=Ubuntu&display=swap" rel="stylesheet">
        <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@500&display=swap" rel="stylesheet">
        <link href="https://fonts.googleapis.com/css2?family=Bree+Serif&display=swap" rel="stylesheet">
        <div class="topic">
            <h1> Projects </h1>
        </div>
        <div class="text">
            <div class="summary">
                <div class="project">
                    <a href="https://drive.google.com/file/d/1VOg81VkbROXAaQYP_npVOwOWYrdcZp-u/view?usp=sharing"> Analysis of City Developments Limited 2019 Financial Statement </a>
                </div>
                <div class="time">
                    Jan 2021 - May 2021
                </div>
                <div class="details">
                    <ul>
                        <li> Analysed the net current receivables of the company and how effective is the company in collecting their receivables and also computed their current ratio. </li>
                        <li> Conducted a 5 year trend analysis of the company’s revenue, gross profit and net profit and used the solvency and market prospect ration in evaluating the company’s value. </li>
                        <li> Compared the company with its direct competitor, CapitaLand and determined the reasons on why the company is lagging behind its competitors. </li>
                    </ul>
                </div>
            </div>
            <div class="summary">
                <div class="project">
                    <a href="https://bt3103-feed-me-now.web.app/"> Feed Me Now </a>
                </div>
                <div class="time">
                    Jan 2021 - May 2021
                </div>
                <div class="details">
                    <ul>
                        <li> Developed a complex and custom web application called Feed-Me-Now that allows animal lovers to make remote donations to their local zoo by paying for the animals’ meals using Vue.js and Firebase. </li>
                        <li> Stored the animals’ information given from the zoo into a Firestore database with NoSQL and provided a page that allows the users to view the animals that they can feed. There is also a contributions page to see their past contributions and a leaderboard.  </li>
                        <li> SCRUM master and ensured that the development understood the requirements of the projects and that all members were working well together. </li>
                    </ul>
                </div>
            </div>
            <div class="summary">
                <div class="project">
                    <a href="https://docs.google.com/document/d/13XYNIUBgho2dfupskgVRsedBXfDBzCbPkbMz2FdL8mM/edit?usp=sharing"> Classification and prediction models on Credit Card Holders </a>
                </div>
                <div class="time">
                    Aug 2020 - Dec 2020
                </div>
                <div class="details">
                    <ul>
                        <li> Worked in a team of 5 and build 4 different machine learning models (Logistic Regression, Naïve Bayes, Neural Networks, Decision Trees) to predict whether a customer will default their credit card payment in the next month based on their past payment history.  </li>
                        <li> Analyzed the effectiveness of each model in predicting the outcome and the areas of improvement by calculating the true positive/negative rate, precision, F1 measure, average class accuracy and harmonic mean. </li>
                    </ul>
                </div>
            </div>
            <div class="summary">
                <div class="project">
                    <a href="https://drive.google.com/file/d/1Fe8w4rLmGdE88XWX-qv4p4ym_zcsuSfX/view?usp=sharing"> Data Management for Car Rental Company and Data Visualization for Alpha Airlines </a>
                </div>
                <div class="time">
                    Jan 2021 - May 2021
                </div>
                <div class="details">
                    <ul>
                        <li> Used the entity-relationship modelling approach and build a conceptual data model by identifying entities, their associated attributes, and primary key attributes and produced an Entity-Relationship Diagram. Implemented the schema using a MySQL database.  </li>
                        <li> Analyzed the data and key business metrics of Alpha Airlines and its competitor, Beta Airlines and presented our findings using Tableau Public </li>
                        <li> Worked in a team of 5 and created a report on the data of the 2 companies and devised ways for Alpha Airlines to stand out from its competitor and highlighted the areas that Alpha Airlines need to work on to increase their revenue. </li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
    .container {
        display: flex ;
        justify-content: space-between;
    }
    .topic {
        width: 20% ; 
        text-align: center;
        font-family: 'Ubuntu', sans-serif;
        font-size: 1.5rem ;
    }
    .text {
        width: 75% ; 
    }
    .summary {
        font-family: 'Cormorant Garamond', serif;
        font-size: 1.5rem ;
        margin-top: .5em ; 
    }
    .project {
        font-family:'Bree Serif', serif;;
    }
    a {
        text-decoration: none ; 
        color: #000;
    }
    a:hover {
        color: #FF0000;
    }

    @media screen and (max-width: 800px){
        .container{
            flex-direction: column;
        } 
        .topic {
            width: 100% ; 
        }
        .text {
            width: 100% ; 
        }
    }
</style>