<template>
	<div class="grapharea">
        <p><img src="../assets/analytics.png"/><span class="fees">GENERAL STATISTICS</span></p>
        <div class="threegraphs">
            <h1 class="text">STUDENTS</h1>
            <h2 class="figure">50,000</h2>
            <h3 class="report">VIEW REPORTS</h3>
        </div>
        <div class="threegraphs">
            <h1 class="text">PARENTS</h1>
            <h2 class="figure">15,000</h2>
            <h3 class="report">VIEW LIST</h3>
        </div>
        <div class="threegraphs">
            <h1 class="text">TEACHERS</h1>
            <h2 class="figure">5000</h2>
            <h3 class="report">VIEW LIST</h3>
        </div>
    </div>
</template>

<style scoped>
.fees {
   margin-left: 10px;
   color: #3B3B3B;
   font-size: 10px;
   }
.grapharea {
   float: right;
   margin-top: -350px;
   }
 .threegraphs {
   width: 350px;
   height: 80px;
   background: #FFFFFF;
   border: 1px solid rgba(189, 189, 189, 0.25);
   box-sizing: border-box;
   box-shadow: 0px 4.71062px 23.5531px rgba(0, 0, 0, 0.07);
   border-radius: 4.71062px;
   margin-bottom: 10px;
   margin-right: 10px;
   overflow: none;
   }
 .text {
    font-size: 10px;
    color: #BDBDBD;
    margin-top: -60px;
   }
.figure {
    font-weight: 600;
    font-size: 24px;
    color: #3B3B3B;
    }
.report {
    font-weight: bold;
    font-size: 10px;
    color: #1B75BB;
    }
</style>