# travel-form-

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TRAVEL AGENCY FORM </title>
</head>
<body>
 <center><h1>TRAVEL AGENCY FORM</h1> </center> 
<form>
    <center>
    <div>
    <label for="name"> NAME </label>
    <input type="text"name=name required placeholder="e.g. hello123">
    </div>
    <br>
    <div>
    <label for="AGE"> AGE </label>
    <input type="number" required placeholder="e.g. 11">
    </div>
    <br>
    <div>
        <label for="email">E MAIL ID </label>
        <input type="text" name="email" required placeholder="e.g. hello123@gmail.com">
    </div>
    <br><br>
    <div>
        <label for="pass">Password (8 characters minimum):</label>
        <input type="password" id="pass" name="password" minlength="8" required placeholder="e.g. hello"/>
      </div>
      <br>
      <br>    
    <span>
    <label for="sex">GENDER</label>
    <br>
    <label for="male">Male</label>
    <input type="radio" name="GENDER" id="male" value="male">
    <label for="Female">Female</label>  
    <input type="radio" name="GENDER" id="female" value="female">
    <label for="others">others</label>
    <input type="radio" name="GENDER" id="others" value="others">
    </span>
    <br>
    <br>
    <div>
    <label for="start"> DATE OF BIRTH </label>
    <input type="date" id="DATE OF BIRTH" name="trip-start" value="2018-07-22" min="1800-01-01" max="9999-12-31" />
    </div>
    <br>
    <br>
    <div>
        <label for="city">CITY YOU WANT TO VISIT </label>
        <select name="city" id="city">
            <option> SELECT AN OPTION </option>
        <option value="MANALI">MANALI</option>
        <option value="SHIMLA">SHIMLA</option>
        <option value="CHANDIGARH">CHANDIGARH</option>
        <option value="KASHMIR">KASHMIR</option>
        <option value="UTTARAKHAND">UTTARAKHAND</option>
        </select>
    </div>
    <br>
    <div>
        <label for="persons"> How Many Persons Are Coming </label>
        <input type="text" required>
    </div>
    <br>
    <div>
        <label for="number">Phone No.</label>
        <input type="number" required>
    </div>
    <br>
    <div>
        <button>Submit</button>
    </div>

</form>
</body>
</html>
