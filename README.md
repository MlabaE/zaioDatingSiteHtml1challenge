# zaioDatingSiteHtml1challenge
<?php

if(isset($_POST["submit"])){
    
    $name =($_POST["name"]);
    
    echo 'welcome '.$name.' your details have been recorded';
}
?>
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <title>Dating Site Registration Form</title>
    </head>
    <body>
        <h1>Tindi</h1>
        <h2>Please enter your information below</h2>
        <form action="index.php" method="post">
            <p>Name</p>
            <input type="text" name="name" placeholder="Enter Name" required><br>
            <p>Surname</p>
            <input type="text" name="surname" placeholder="Enter Surname" required><br>
            <p>Gender</p>
            <input type="radio" name="gender" value="male">Male<br>
            <input type="radio" name="gender" value="female">Female<br>
            <p>Age</p>
            <input type="number" name="age" placeholder="Enter Age" required><br>
            <br>
            <input type="submit" name="submit" value="submit">
        </form>
    </body>
</html>
