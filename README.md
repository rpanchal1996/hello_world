<!DOCTYPE html>
<html>
<head>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
<script>
$(document).ready(function(){
    $("button").click(function(){
        $("#a1").css("color", "black")
            .slideDown(2000)
            
    });
});
</script>
</head>
<body>

<p id="a1" color:red>This is my first code on github</p>

<button>Hello World to test jquery chaining </button>

</body>
</html>
