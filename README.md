<html>
 <head>
 <style>
 body{
 display: flex;
 justify-content: center;
 align-items: center;
 }
 .inner{ 
 background-color:white;
 height:400px;
 width:600px;
 border-radius:5px;
 }
 table{
 margin-left: 30px;
 padding-top: 20px;
 }
 .outer{
 background-color:rgb(68, 68, 255);
 height: 500px;
 width: 800px;
 display: flex;
 justify-content: center;
 align-items: center;
 }
 </style>
 </head>
 <body>
 <form>
 <div class="outer">
<div class="inner">
    <table>
    <tr><td><h1>Registration</h1></td>
    </tr> 
    <tr>
    <td style="color: gray;">Personal Details</td>
    </tr>
    <tr>
    <td><label for="name">Full Name</label></td>
    <td><label for="dob">Date of Birth</label></td> 
    <td><label for="email">Email</label></td> 
    </tr>
    <tr>
    <td>
    name:-<input type="text"id="name"placeholder="Enter your name">
    </td>
    <td>
    <input type="date"id="dob"placeholder="Enter birth date">
    </td>
    <td>
    <input type="email"id="email"placeholder="Enter your email">
    </td>
    </tr>
    <tr>
    <td><label for="no">Mobile number</label></td>
    <td><label for="gender">Gender</label></td>
    <td><lable for="Occupation">Occupation</lable></td>
    </tr>
    <tr>
    <td>
    <input type="number"id="no"placeholder="Enter mobile number">
    </td>
    <td>
    <input type="text"id="gender"placeholder="Enter your gender">
    </td>
    <td>
    <input type="text"id="Occupation"placeholder="Enter occupation">
    </td>
    </tr>
    <tr>
    <td style="color: gray;">Identify Details</td>
    </tr>
    <tr>
    <td><label for="idtype">ID Type</label></td>
    <td><label for="idno">ID Number</label></td>
    <td><label for="ia">Issue Authority</label></td>
    </tr>
    <tr>
    <td><input type="text"id="idtype"placeholder="Enter ID type"/></td>
    <td><input type="number"for="idno"placeholder="Enter ID number"/></td>
    <td><input type="text"for="ia"placeholder="Enter issue department"/></td>
    </tr>
    <tr>
    <td><label for="idate">Issue Date</label></td>
    <td><label for="istate">Issue State</label></td>
    <td><label for="edate">Expiry Date</label></td>
    </tr>
    <tr>
    <td><input type="text"id="idate"placeholder="Enter ID issue date"></td>
    <td><input type="text"id="idate"placeholder="Enter ID issue state"></td>
    <td><input type="text"id="idate"placeholder="Enter ID expiry date"></td>
    </tr>
    <tr>
    <td><input type="button"value="Next" style=" background-color:rgb(68, 68, 255);height: 30px;width:80px;color: white;font-size:15px;margin-top: 15px;"></td>
    </tr>
    </table>
    </div>
    </div>
    </form>
    </body>
   </html>
