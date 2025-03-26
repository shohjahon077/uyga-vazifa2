<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        form {
            border: 2px solid teal;
            width: 250px;
            padding: 30px;
           
           background: linear-gradient(45deg, #91ffd5, #7562e2, #0c7eb3, #003585);

        }
        select {
            border: 1px solid;
            width: 200px;
            padding: 20px;
            
        }
        body {
            
            background: linear-gradient(45deg, #b82020, #a0c51c, #109b1c, #0e32aa);
        }

        input,select,button {
            background-color: rgb(255, 255, 255);
        }

    </style>
</head>
    <body>
        <form > 
           
            <h2>Sign up</h2>
            <br>
            <label >Name:</label>
            <br>
        <input type="text" placeholder="full name">
        <br><br>
        <label >email:</label>
            <br>
            <input type="text" placeholder="gmail id">
            <br><br>
            <label >Password:</label>
            <br>
            <input type="password" placeholder="8 characters">
            <br><br>
            <label >Confirm Password:</label>
            <br>
            <input type="password" placeholder="8 characters">
            <br><br>
            <label >Data Of Birth</label>
            <br>
            <input type="date">
            <br><br>
            <label >Gander:</label>
            <br>
            <input type="checkbox">
            <label>Male</label>
            <input type="checkbox">
            <label >Female</label>
            <input type="checkbox">
            <label >Other</label>
            <br><br>
            <label>Insert your photo:</label>
            <br>
            <input type="file">
            <br><br>
            <label>Insert your resume:</label>
            <br>
            <input type="file">
            <br><br>
            <label>Security Question:</label>
            <br>
            <select name="select"></select>
            <br><br>
            <input type="checkbox">
            <label>I agree terms and conditions </label>
            <button>Register</button>

        
        
        
        
        
        </form>
       



    </body>
</html>
