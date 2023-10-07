<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    #container{
     
      padding: 10px;
      padding-right: 10px;
      margin: 10px;
      display: grid;
      grid-auto-flow: row;
      width: 40%;
      height: 350px;
      grid-gap:1px;
      grid-template-areas:
      "a b c "
      "a d d" 
      "e f g"
      "h h g";
    }
    .no{
      background-color: white;
      color: brown;
    }
    #a{
      grid-area: a;
      background-color: rgb(234, 200, 212);

      
      
    }
    #b{
      grid-area: b; 
      background-color: rgb(164, 220, 234);
      
    }
    #c{
      grid-area: c;
      background-color: rgb(164, 220, 234); 
      
    }
    #d{
      grid-area: d; 
      background-color: rgb(167, 232, 167);
      
      
    }
    #e{
      grid-area: e;
      background-color: rgb(164, 220, 234);
     
    }
    #f{
      grid-area: f;
      background-color: rgb(164, 220, 234);
      
    }
    #g{
      grid-area: g;
      background-color: rgb(234, 200, 212);
      
    }
    #h{
      grid-area: h;
      background-color: rgb(167, 232, 167);
      
    }
    
    .no{
      text-align: center;
      padding-top: 20px;
      font-size: xx-large;
    }
    @media (max-width: 460px) {
    .ban {
        grid-template-columns: 1fr; 
        grid-gap: 5px;
        padding: 10px;
    }
  }
  </style>
  <title>Document</title>
</head>
<body class="ban">
  <div id="container">
  <div class="no" id="a">1</div>
  <div class="no" id="b">2</div>
  <div class="no" id="c">3</div>
  <div class="no" id="d">4</div>
  <div class="no" id="e">5</div>
  <div class="no" id="f">6</div>
  <div class="no" id="g">7</div>
  <div class="no" id="h">8</div>
  
</div>
  
</body>
</html>
