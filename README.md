<!DOCTYPE html>
<html>
<head>
    <script>
    function grade(){
        var grade = document.getElementById("number") .value;
        if(grade<0 || grade > 100){alert('Number needs to be 1-100')
        }else if(grade >=90){
            alert =letter= ('A');
        }else if(grade >=80){
            alert =letter= ('B');
    }else if(grade >=70){
            alert =letter= ('C');
    }else if(grade >=60){
            alert =letter= ('D');
        } else {alert =letter= ('F')}
        document.getElementById('demo').innerHTML = "your grade:" + alert;
    }
</script>
<meta charset="utf-8"/>
<h1>Javascript Convert Grades</h1>
</head>
<body>
    Please enter the numeric grade (0-100): <input type="text" id="number" onblur="grade()">
    <p id= "demo"> </p>
</body>
</html>
