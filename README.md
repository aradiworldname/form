<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>form</title>
</head>

<body>
    <h2>Enquiry form</h2>
    <form>
        <fieldset> 
            <legend>Enquiry</legend>
        Name: <input type="text" name="name"  placeholder="enter your name here">

        <br><br>
        Adress:<textarea name="adresss" ></textarea><br><br>
Gender:
<input type="radio" value="m" name="gender"\>Male
<input type="radio" value="f" name="gender"\>female
<input type="radio" value="o" name="gender"\>other  
<br><br>
<br><br>
Country:
<select>
<option value="India">India</option>
<option value="USA">USA</option>
<option value="UK">UK</option>
<option value="Germany">Germany</option>
<option value="France">France</option>
<option value="Australia">Australia</option>
<option value="China">China</option>
</select>
<br><br>
Hobbies:
<input type="Checkbox" name="Hobbies[]"> Dancing
<input type="Checkbox" name="Hobbies[]"> Singing
<input type="Checkbox" name="Hobbies[]"> Playing
<Br><br>
Image:
<input type="file" name="image"\>
<Br><br>

<input type="submit"\>
<input type="reset"\>

</fieldset>



</form>


</body>

</html>
