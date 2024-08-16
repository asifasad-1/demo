<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="hello there to practice seo">
    <title> free for all cources of computer science languages </title>
</head>
<body>
    <fieldset>
    <legend><u> fill the form of your instruction </u></legend>   
     <form>
        <label>gender</label><br>
        <input type="radio" required value="male"name="gender">male
        <input type="radio" required value="female"name="gender">female
         <br>
        <label><b><strong>Name</strong></b></label><br>
        <input type="Name" required ="[a-zA-Z ]{3,25}" placeholder="enter your name">
        <br/>
       <label><b> Course </b></label><br>
       <input type="text" required list="Course">
           <datalist id="Course"><br>
            <option value="php"></option>
            <option value="java"></option>
            <option value="Css"></option>
            <option value="C"></option>
           </datalist><br>
        <label><b><strong>Email</strong></b></label><br>
        <input type="Email" required placeholder="enter your email">
        <br/>
        <label><b><strong>Age</strong></b></label><br>
        <input type="Age" required placeholder="enter your Age">
        <br/>
        <label><b><strong>Phone</strong></b></label><br>
        <input type="tel" required pattern="[0-9]{11}"title="enter your phone number whit 11 digits" placeholder="enter your phone number" name="upone">
         
        <br/>
        <label >Message</label><br>
        <textarea></textarea><br>
        <label for="photo"></label><br>
        <input type="file" required><br>
        <label>Password</label><br>
        <input type="password" required><br>
        <label>country</label><br>
        <select> <br>
            <option>------slect country-------</option>
            <option value="Pakistan">Pakistan</option>
            <option value="India">India</option>
            <option value="sirlanka">sirlanka</option>
            <option value="bangladesh">bangladesh</option>
        </select><br>
        <label >Course</label>
        <select>
        <optgroup label="frontend">
        <option>html</option>
        <option>Css</option>
        <option>Js</option>
    </optgroup>
    <optgroup label="backend">
        <option>Php</option>
        <option>Node</option>
        <option>Mysql</option>

    </optgroup>
    </select><br>
    <form> 
       <input type="date">
        <button type="submit">save</button><br>
        <button type="Next">Go</button> <br>
        <button type="reset">reset</button><br>
    </form>
</body>
</html>
