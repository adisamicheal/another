<template>
<div class="wrapper">
    <nav id="sidebar" class="sidebar">
  <div class="sidebar-header">
            <p><img src="../assets/schoolLogo.png"/>Handmaid's International<i class="fa fa-caret-down" style="color:  #1B75BB; margin-left:5px;"></i></p>
  </div>
    <div class="blue-area">
        <ul>
            <li><img src="../assets/dashboardlogo.png"/>Dashboard</li>
            <li><img src="../assets/students.png"/>Students<i class="fa fa-caret-down"></i></li>
            <li><img src="../assets/employees.png"/>Employees<i class="fa fa-caret-down"></i></li>
            <li><img src="../assets/parentsguardians.png"/>Guardians</li>
            <li><img src="../assets/attendance.png"/>Attendance<i class="fa fa-caret-down"></i></li>
            <li><img src="../assets/finance.png"/>Finance<i class="fa fa-caret-down"></i></li>
            <li><img src="../assets/subjects.png"/>Subjects</li>
            <li><img src="../assets/batches.png"/>Batches</li>
            <li><img src="../assets/reportcards.png"/>Report Cards</li>
            <li><img src="../assets/sms.png"/>SMS</li>
            <li><img src="../assets/events.png"/>Events<i class="fa fa-caret-down"></i></li>
            <hr>
            <li>Settings</li>
        </ul>

        <div class="foot">
            <button class="btn"><img src="../assets/question.png">Help</button>
            <span class="terms">Terms. Privacy</span>
        </div>
    </div>    
  </nav>
</div>

</template>

<style>
.wrapper {
  display: flex;
  align-items: stretch;
  perspective: 1500px;
}
.sidebar {
  min-width: 250px;
  max-width: 250px;
  background: #ffffff;
  color: #2C2C2C;
  font-size: 14px;
  font-weight: bold;
  line-height: 22px;
  box-shadow: 0px 2px 10px rgba(0, 0, 0, 0.170509);
  position: fixed; /* Fixed Sidebar (stay in place on scroll) */
  z-index: 1; /* Stay on top */
  top: 0; /* Stay at the top */
  left: 0;
}
.sidebar-header {
  margin-top: 20px;
  margin-left: 20px;
}
.blue-area {
  background: linear-gradient(136.25deg, #1B75BB 0%, #00ADEE 100%);
}
li img {
  margin-right: 10px;
}
ul{
  list-style: none;
  line-height: 4;
  color:#ffffff;
}
li .fa {
  float: right;
  margin-right: 50px;
  line-height: 4;   
}
li:hover {
  color: #1B75BB;
}
hr{
  margin-left: -39px;
  width: 250px;
  background: #ffffff;
} 
.foot {
  margin-top: 40px;
  display: flex;
  margin-left: 30px;
  color: #ffffff;
}
.btn {
  width: 100px;
  height: 38px;
  border-radius: 20px;
  background: #ffffff;
  color: #1B75BB;
  margin-bottom: 10px;
}
button img {
  margin-right: 5px;
}
.terms {
  color: #ffffff;
  margin-left: 15px;
  margin-top: 6px;
  font-size: 14px;
}
</style>
