<template>
	<div class="d-flex">
      <form>
          <input class="form-control search-box" type="search">
      </form>
      <div class="right d-flex">
            <img src="../assets/not.png" class="notification"/>
            <div class="c">
              <span class="n">Ukauwa David</span><br />
              <span class="g">ukauwa@gmail.com</span>
            </div>
            <div>
              <img src="../assets/Ellipse.png"/>
            </div>
       </div>
    </div>
</template>

<style>
.form-control {
  background: #FFFFFF;
  border: 1px solid rgba(189, 189, 189, 0.25);
  box-sizing: border-box;
  box-shadow: 0px 2px 9px rgba(196, 196, 196, 0.11);
  border-radius: 3px;
  width: 796px;
  height: 38px;
  margin-left: 300px;
  margin-top: 28px;
}
.right {
  margin-left: 96px;
  margin-top: 8px;
}
.right .notification {
  width: 23px;
  height: 24px;
  margin-right: 25px;
}
.right .n {
  font-family: Khula;
  font-style: normal;
  font-weight: normal;
  font-size: 12px;
  color: #31393C;
}
.right .g {
  font-family: Avenir Next;
  font-size: 9px;
  font-style: italic;
  color: #90A4AE;
}
.right .c {
  text-align: right;
  margin-right: 17px;
}
</style>