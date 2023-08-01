<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Our Menu</title>
<style>

/********** Base styles **********/
* {
  box-sizing: border-box;
}
h1 {
  margin-bottom: 50px;
  text-align: center;
  font-family: montserrat;
  font-weight: 800px;
}
h2 {
  padding-top: none;
  padding-bottom: none;
  padding-right: 20px;
  padding-left: 20px;
  border: 1px solid black;
  padding-block: 0px;
  display: inline-block;
  font-size: 1.5em;
  margin-block-start: 0px;
  margin-block-end: 0px;
  margin-inline-start: 0px;
  margin-inline-end: 0px;
  font-weight: bold;
  float: right;
}

p {
  border: 1px solid black;
  background-color: #928F8FFF;
  width: 100%;
  height: 200px;
  padding-top: 30px;
  padding bottom: 20px;
  padding-right: 20px;
  padding-left:20px;
  margin top: 20px;
  font-family: montserrat;
  font-size: 20px;
  color: black;
}

/* Simple Responsive Framework. */
.row {
  width: 100%;
}

/********** Large devices only **********/
@media (min-width: 1200px) and (max-width: 1600px) {
  .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
    float: left;
    border: 1px solid black;
  }
  .col-lg-1 {
    width: 8.33%;
  }
  .col-lg-2 {
    width: 16.66%;
  }
  .col-lg-3 {
    width: 25%;
  }
  .col-lg-4 {
    width: 33.33%;
  }
  .col-lg-5 {
    width: 41.66%;
  }
  .col-lg-6 {
    width: 50%;
  }
  .col-lg-7 {
    width: 58.33%;
  }
  .col-lg-8 {
    width: 66.66%;
  }
  .col-lg-9 {
    width: 74.99%;
  }
  .col-lg-10 {
    width: 83.33%;
  }
  .col-lg-11 {
    width: 91.66%;
  }
  .col-lg-12 {
    width: 100%;
  }
}

/********** Medium devices only **********/
@media (min-width: 992px) and (max-width: 1199px) {
  .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
    float: left;
    border: 1px solid black;
  }
  .col-md-1 {
    width: 8.33%;
  }
  .col-md-2 {
    width: 16.66%;
  }
  .col-md-3 {
    width: 25%;
  }
  .col-md-4 {
    width: 33.33%;
  }
  .col-md-5 {
    width: 41.66%;
  }
  .col-md-6 {
    width: 50%;
  }
  .col-md-7 {
    width: 58.33%;
  }
  .col-md-8 {
    width: 66.66%;
  }
  .col-md-9 {
    width: 74.99%;
  }
  .col-md-10 {
    width: 83.33%;
  }
  .col-md-11 {
    width: 91.66%;
  }
  .col-md-12 {
    width: 100%;
  }
}

/********** Small devices only **********/
@media max-width: 991px) {
  .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
    float: left;
    border: 1px solid black;
  }
  .col-md-1 {
    width: 8.33%;
  }
  .col-md-2 {
    width: 16.66%;
  }
  .col-md-3 {
    width: 25%;
  }
  .col-md-4 {
    width: 33.33%;
  }
  .col-md-5 {
    width: 41.66%;
  }
  .col-md-6 {
    width: 50%;
  }
  .col-md-7 {
    width: 58.33%;
  }
  .col-md-8 {
    width: 66.66%;
  }
  .col-md-9 {
    width: 74.99%;
  }
  .col-md-10 {
    width: 83.33%;
  }
  .col-md-11 {
    width: 91.66%;
  }
  .col-md-12 {
    width: 100%;
  }
}
</style>
</head>
<body>
<h1>Our Menu</h1>

<div class="row">
  <div class="col-lg-3 col-md-6"><h2>Chicken</h2><p>Lorem ipsum dolor sit amet, consectetuer odipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim adminim veniam, quisnostrud exercitation ulllam colaboris nisiut aliquip exea commodo consequat.</p></div>
  <div class="col-lg-3 col-md-6"><h2>Beef</h2><p>Lorem ipsum dolor sit amet, consectetuer odipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim adminim veniam, quisnostrud exercitation ulllam colaboris nisiut aliquip exea commodo consequat.</p></div>
  <div class="col-lg-3 col-md-6"><h2>Sushi</h2><p>Lorem ipsum dolor sit amet, consectetuer odipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim adminim veniam, quisnostrud exercitation ulllam colaboris nisiut aliquip exea commodo consequat.</p></div>
</div>

</body>
</html>
