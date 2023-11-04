<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div id="containerFull">
        <div id="container">
          <div class="row line-1">
            <div id="1"></div>
            <div id="2"></div>
            <div id="3"></div>
            <div id="4"></div>
          </div>
          <div class="row line-2">
            <div id="5"></div>
            <div id="6"></div>
            <div id="7"></div>
            <div id="8"></div>
          </div>
          <div class="row line-1">
            <div id="9"></div>
            <div id="10"></div>
            <div id="11"></div>
            <div id="12"></div>
          </div>
          <div class="row line-2">
            <div id="13"></div>
            <div id="14"></div>
            <div id="15"></div>
            <div id="16"></div>
          </div>
        </div>
       
      
</body>
</html>

css  
#containerFull {
  width: 280px;
  margin: 0 auto;
}

#container {
  border: 3px solid #000;
  width: 250px;
  height: 250px;
  border-radius: 5px;
  display: flex;
  flex-wrap: wrap;
}

.row {
  display: flex;
}

.row div {
  
  width: 60px;
  height: 60px;
  border-left: 1.5px solid #000;
  border-bottom: 1.5px solid #000;
  text-align: center;
  display: flex;
  justify-content: center;
  align-items: center;
}

.line-1 div:nth-child(2n+1) {
  background: #000;
  color: #FFF;
}

.line-2 div:nth-child(2n) {
  background: #000;
  color: #FFF;
}


