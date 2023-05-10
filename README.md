# Stuff-I-Made
Hi i am Uday and i am in grade 6. Also i like to raed books sometimes.
<!DOCTYPE html>
<html>
    <head>
    </head>
    <body style="background-color:lightskyblue;text-align:;font-size:19px;color:navy">
     <form target="_blank" action="/form.php" method="GET" >
         <fieldset>
             <legend style="font-size:23px;text-align:center;">Subscripton Form</legend>
            
        Name
          <input type="text" name="fname" placeholder="First" required>
          
          <input type="text" name="lname" placeholder="Last" required><br><br>
          Date
          <input type="date" name="date" required>
           Email 
        <input type="email" name="email" placeholder="Email" required><br><br>
        Phone number
        <input required type="number" name="phone" placeholder="Contact Number"><br>
        Address
        <input required type="text" name="Address" placeholder="address"><br>
            Topic Solection<br>
        <input class="in" type="checkbox" name="pick">Sports Weekly Mania<br>
        <input class="in" type="checkbox" name="pick">Men's Health<br>
        <input class="in" type="checkbox" name="pick">Busines Weekly <br>
        <input class="in" type="checkbox" name="pick">Fast Cars Mania<br>
        <input class="in" type="checkbox" name="pick">Holiday Wonders<br>
        <h3> please select billing freqcuncy</h3>
            <select id="pay" name="pay" required> 
            <option value="monthly">Monthly</option>
            <option value="yearly">Yearly</option>
            <option value="qurterly">Qurterly</option>
             </select>
         </fieldset>
         <input style="font-size:15px;" type="submit" value="submit">

     </form>
        
    </body>
</html>      
