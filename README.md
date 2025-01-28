<html>
<head>
<title>TEST</title>

<script type="text/javascript">
flag=1
function f1()
{
    var Name = prompt("Name: ");
    
    if(Name == "" || Name == null) {
    alert("please enter your name.");
    } else {
    alert("Hi " + Name +  ", my honeybunchsugarplum pumpiampiamkin ko<3"); 
    }
}
function f()
{
    if(flag==1)
        {
            Bn.style.top=400
            Bn.style.left=300
            flag=2
        }
    else if(flag==2)
        {
            Bn.style.top=400
            Bn.style.left=50
            flag=3
        }
    else if(flag==3)
        {
            Bn.style.top=370
            Bn.style.left=166
            flag=1
        }
}
</script>

</head>
<body>
<img src="https://media.tenor.com/d5Nc1WdsUX0AAAAM/happy-valentines-day-cat.gif" height="200" />
<h1>Can you be my</h1>
<h1 style="#">my Valentines date?</h1>
<div id="By" style="position:absolute; left:64px; top:370px; width:210px;
height:210px;">
<input type="button" value=" YES " onClick="f1()" />
</div>
<div ID="Bn" style="position:absolute; left:166px; top:370px; width:210px; height:210px;">
<input type="button" value=" NO " onMouseOver="f()" />
</div>

</body>
</html>
