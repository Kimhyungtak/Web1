<head>
    <style>
        a {
            text-decoration: none;
        }
        
        .js {
            font-weight: bold;
            color: red;
        }
        
        h2 {
            font-size: 40px;
        }
        
        .saw {
            color: gray;
        }
        
        h1 {
            font-size: 50px;
            border-bottom: 3px solid gray;
            text-align: center;
            padding-bottom: 20px;
            margin: 0;
        }
        
        ol {
            font-size: 30px;
            border-right: 3px solid gray;
            text-align: left;
            margin: 0;
            width: 110px;
        }
    </style>
    <meta charset="utf-8">
    <title></title>
</head>

<body>
    <h1><a herf="index.html">WEB
    <input type="button" value="Night" onclick="
      var target = document.querySelector('body') ;
      if(this.value === 'Night'){
        target.style.backgroundColor='black';
        target.style.color='white';
        this.value = 'Day';
      } else{
        target.style.backgroundColor='white';
        target.style.color='black';
        target.dataset.mode ='Day';
        this.value = 'Night';
      }
    ">
    </a></h1>
    <ol><br>
        <li><a href="http:\\google.com" class="saw">Google</a></li>
        <li><a href="http:\\naver.com" class="saw">Naver</a></li>
        <li><a href="http:\\daum.net">Daum</a></li>
    </ol>
    <p>
        <span class="js">JavaScript</span><br> often abbreviated as JS, is a high-level, <br>dynamic, weakly typed, protoype-base, multi-paradigm, and interpreted programing language.
    </p>
</body>

</html>
