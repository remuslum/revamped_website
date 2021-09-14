<template>
    <div class="container">
        <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@500&display=swap" rel="stylesheet">
        <link href="https://fonts.googleapis.com/css2?family=Ubuntu&display=swap" rel="stylesheet">
        <link href="https://fonts.googleapis.com/css2?family=Bree+Serif&display=swap" rel="stylesheet">
        <div class="topic">
            <h1> Education </h1>
        </div>
        <div class="summary">
            <div class="institute">
                National University of Singapore
            </div>
            <div class="degree">
                Bachelor of Science in Business Analytics Specialising in Financial Analytics
            </div>
            <div class="time">
                August 2019 - Present
            </div>
            <div class="list">
                <ul>
                    <li> Vice Chairman of NUS Computing Club FLAG Fundraising Committee </li>
                    <li> Currently enrolled in the NUS Overseas College New York Programme </li>
                </ul>
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
        margin-left: .5em ;
        margin-top: .5em ; 
        font-family: 'Ubuntu', sans-serif;
        font-size: 1.5rem ; 
    }
    .summary {
        font-family: 'Cormorant Garamond', serif;
        width: 75% ; 
        margin-top: .5em ; 
        font-size: 1.5rem ; 
    }
    .institute {
        font-family: 'Bree Serif', serif;
    }

    @media screen and (max-width: 800px) {
        .container {
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

