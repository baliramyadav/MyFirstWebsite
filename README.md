# MyFirstWebsite
HTML Page Layout Design 
--------------------------------------------

CSS: 
    <style>
        *{
            box-sizing: border-box;
        }
        div{
            border:2px solid red;
        }
        body{
            margin: 0px;
        }
        .header{
            background-color:aquamarine;
            padding: 20px;
            
            text-align: center;
        }
        .topnav{
            background-color: seagreen;
            overflow: hidden;
        }
        .topnav a{
            display: block;
           color:yellow;
            text-align: center;
            padding: 10px 10px;
            text-decoration: none;
            float: left;
            
        }
        .topnav a:hover
        {
            font-family: cursive;
            font-size: 16px;
            background-color: indigo;
            color: white;            
        }
        .column{
            float: left;
            width:25%;
            padding: 15px;
            
            
        }
        .row:after{
            content: "";
            display: table;
            clear: both;
        }
        .footer{
            
            background-color:skyblue;
            padding: 15px;
            
        }
        
    </style>
    

HTML:

<div class="header">
        <h1>CODER BABA</h1>
            <p> Subscribe my channel</p>
        </div>
        
        <div class="topnav">
            <a href="index.html">Home</a>
            <a href="#">Protfolio</a>
            <a href="#">About</a>
            <a href="#">Blog</a>
        
        </div>
        
        <div class="row"> 
              <div class="column"> 
                <h2>Column1</h2>
                  <p>O level computer course study Materials.</p>
              </div>
            
            <div class="column"> 
                <h2>Column2</h2>
                  <p>O level computer course study Materials.</p>
              </div>
            
            <div class="column"> 
                <h2>Column3</h2>
                  <p>O level computer course study Materials.</p>
              </div>
            
            <div class="column"> 
                <h2>Column4</h2>
                  <p>O level computer course study Materials.</p>
              </div>
        
        </div>
        
        <div class="footer">
        <p style="text-align:center"> Copyright@2021</p>
        </div>
