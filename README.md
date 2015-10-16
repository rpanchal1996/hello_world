<!DOCTYPE html>
<html>
<head>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
<script>
$(document).ready(function(){
    $("button").click(function(){
        $("#p1").css("color", "red")
            .slideUp(2000)
            
    });
});
</script>
</head>
<body>

<p id="p1" color:red>jQuery is fun!!</p>

<button>Hello World to test jquery chaining </button>

</body>
</html>
