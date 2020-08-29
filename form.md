<!DOCTYPE html>
<html>
<head>
<title>HTML Form</title>

</head>
<body>
  <center></center>
    <form action="home.html">
        <label for="fname">First name:</label><input type="text" id="fname" name="fname">
        <br><br>
        <label for="lname">Last name:</label> &nbsp;   <input type="text" id="lname" name="lname">
        <br><br>
        <label>Gender:</label><br>
        &nbsp;  &nbsp;  &nbsp;  &nbsp; <input type="radio" id="male" name="gender" value="male"><label for="male">Male</label><br>
        &nbsp;  &nbsp;  &nbsp;  &nbsp; <input type="radio" id="female" name="gender" value="female"><label for="female">Female</label><br>
        &nbsp;  &nbsp;  &nbsp;  &nbsp; <input type="radio" id="other" name="gender" value="other"><label for="other">Other</label><br>
        <label>Course</label><br>
        <input type="checkbox"> Mathematics<br>
        <input type="checkbox"> English<br>
        <input type="checkbox"> Physics<br>
        <br><br>
        <div>
        <!-- <input type="submit" value="Register" style="margin-left: 400px;"/> -->
        <button>Save</button>
      </div>
      </form>
</body>

</html>