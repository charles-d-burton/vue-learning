<template>
<div class="frontpage">
    <div class="nav">
        <div class="container">
        <ul class="pull-left">
            <li><a href="#">Products</a></li>
            <li><a href="#">Devices</a></li>
        </ul>
        <ul class="pull-right">
            <li><a href="#">Sign Up</a></li>
            <li><a href="#">Log In</a></li>
        </ul>
        </div>
    </div>
    <div class="jumbotron">
      <div class="container">
        <h1>Send to your machines from anywhere.</h1>
        <p>A remote solution for RS232 powered machines.</p>
        <a href="#">Learn More</a>
      </div>
    </div> 
    
    <div class ="hardware">
      <div class="container">
        <h2>Open Source Remote RS232 Interface</h2>
        <p>Built on Open Source ideas and principles.</p>
        <div class="row">
          <div class="col-md-4">
            <div class="thumbnail">
              <img src="../assets/RS232-Board-2.jpg">
            </div>
          </div>
          <div class="col-md-4">
          <div class="thumbnail">
              <img src="../assets/Raspberry-Pi-Zero-FL.jpg">
            </div>
          </div> 
        </div>
      </div>
    </div>

    <div class="learn-more">
	  <div class="container">
		<div class="row">
	      <div class="col-md-4">
			<h3>Build your own.</h3>
			<p>Learn how to build your own interface.</p>
			<p><a href="#">Get started.</a></p>
	      </div>
		  <div class="col-md-4">
			<h3>Contribute</h3>
			<p>Help us make RSMachiner better.</p>
			<p><a href="#">Start Contributing.</a></p>
		  </div>
		  <div class="col-md-4">
			<h3>Use our service.</h3>
			<p>Connect your devices to our service.</p>
			<p><a href="#">Learn how.</a></p>
		  </div>
	    </div>
	  </div>
	</div>
</div>
</template>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.nav a {
  color: #5a5a5a;
  font-size: 11px;
  font-weight: bold;
  padding: 14px 10px;
  text-transform: uppercase;
}

.nav li {
  display: inline;
}

.jumbotron {
  background-image: url("../assets/CNC-Machining.jpg");
  height: 500px;
  background-repeat: no-repeat;
  background-size: cover;
}

.jumbotron .container {
  position: relative;
  top: 100px;
}

.jumbotron h1 {
  color: #fff;
  font-size: 48px;
  font-family: "Shift", sans-serif;
  font-weight: bold;
}

.jumbotron p {
  font-size: 20px;
  color: #fff;
}

.hardware {
  background-color: #efefef;
  border-bottom: 1px solid #dbdbdb;
}

.hardware h2 {
  color: #393c3d;
  font-size: 24px;
}

.hardware p {
  font-size: 15px;
  margin-bottom: 13px;
}

.learn-more {
  background-color: #f7f7f7;
}

.learn-more h3 {
  font-family: "Shift", sans-serif;
  font-size: 18px;
  font-weight: bold;
}

.learn-more a {
  color: #00b0ff;
}
</style>