# <!DOCTYPE html>
<html>

<head>
    <style>
        .js {
            font-weight: bold;
            color: red;
        }
    </style>
    <meta charset="utf-8">
    <title></title>
</head>

<body>
    <h1><a herf="index.html">WEB</a></h1>
    <h2 style="background-color:rgb(193, 243, 247);color:rgb(252, 194, 141)">JavaScript</h2>
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
    <o1><br>
        <li><a href="http:\\google.com" target="_blank">Google</a></li>
        <li><a href="http:\\naver.com" target="_blank">Naver</a></li>
        <li><a href="http:\\daum.net" target="_blank">Daum</a></li>
    </o1>
    <p>
        <span class="js">JavaScript</span><br> often abbreviated as JS, is a high-level, <br>dynamic, weakly typed, protoype-base, multi-paradigm, and interpreted programing language.
    </p>
</body>

</html>
