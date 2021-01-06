<html>
<head>
<style>
    .rootDiv{
width:100%;
height:100%;
display:flex;
justify-content:center;
align-items:center;
color:#30475e;
font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    }
    .rootText{
        text-align:center;
    }
    #textbox{
        width:25rem;
        height:2rem
    }
    </style> 
    </head>
    <div class="rootDiv">
        <div class='rootText'>
    <h1 style="margin-right:20px" >
        GOOGLE IT: 
    </h1>
</div>
    <div class='rootText'>
        <input id="textbox" type="text" placeholder="Type what you would like to know and press enter..." onkeydown="if (event.keyCode == 13 || event.which == 13) { location='http://www.google.com/search?q=' + encodeURIComponent(document.getElementById('textbox').value);}" />
    </div>
    
</div>

</html>
