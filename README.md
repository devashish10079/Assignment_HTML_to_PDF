# Assignment_HTML_to_PDF
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
 <body>
<h1>HTML-Only:Mega Application Form</h1>
<h3>Use only valid inputs.All starred feilds are required.Read titles for hints.NO java script</h3>
      <form>
        <!-- ACCOUNT -->
        <fieldset>
          <legend><b>Account</b></legend>
          <label for="Username"><span style="color: red;">*</span>Username </label><br>
          <input type="text" required>
          <br><br>
          <label for="Password"> <span style="color: red;">*</span>Password</label><br>
          <input type="password" name="" id="" required>
          <br><br>
          <label for="Applying as"> <span style="color: red;">*</span>Aplying as</label><br>
          <select name="" id="" required>
          <option value="School Student">Student</option>
          <option value="Graduate">Teacher</option>
          <option value="Working professional">Working professional</option>
          </select>

        </fieldset>

        <!-- PERSONAL INFORMATION -->
         <fieldset>
          <legend><b>Personal information</b></legend>
          <label for="Full Name"><span style="color: red;">*</span>Full Name</label><br>
          <input type="text" required>
          <br><br>
          <label for="DOB"><span style="color: red;">*</span>Date of Birth</label><br>
          <input type="date" required>
          <br><br>
          <label for="Gender"><span style="color: red;">*</span>Gender</label>
          <br>
          <input type="radio" name="Gender">
          <label for="Male">Male</label>
          
          <br>
          <input type="radio" name="Gender">
          <label for="Female">Female</label>
          
          <br>
          <input type="radio" name="Gender">
          <label for="Others">Others</label>
          <br><br>
      
          <label for="GOV ID(PAN Format)">GOV ID(PAN Format)</label>
          <input type="text" id="govIdPan" name="govIdPan" 
       pattern="[A-Z]{5}[0-9]{4}[A-Z]{1}" 
       maxlength="10" required>

       </fieldset>
       <!-- Contact and Address -->
      <fieldset>
        <legend><b>Contact & Address</b></legend><br><br>
        <label for="Email"><span style="color: red;">*</span>Email</label><br>
        <input type="email" required>
        <br><br>
        <label for="Phone(India)"><span style="color: red;">*</span>Phone(India)</label><br>
        <input type="number" placeholder="+91" required>
        <br><br>
        <label for="Portfolio URL">Portfolio URL</label><br>
        <input type="url">
        <br><br>
        <label for="country"><span style="color: red;">*</span>Country</label><br>
        <input type="text" placeholder="Start typing" required>
        <br><br>
        <label for="State/UT">State/UT(India)</label><br>
        <input type="text" name="" id=""><br><br>
        <label for="PIN code"> PIN code</label><br>
        <input type="number">
        <br><br>
        <label for="Address"><span style="color: red;">*</span>Address</label><br>
        <textarea name="" id=""placeholder="Flat/house NO,br
      
Street,Area"  rows="5" cols="40"></textarea>

      </fieldset>

      <!-- EDUCATION & SKILLS -->
       <fieldset>
        <legend><b>Education and skills</b></legend><br>

        <label for="Highest Qualification"><span style="color: red;">*</span>Highest Qualification</label>
        <select name="" id="" required>
          <option value="Intermediate">Intermediate</option>
          <option value="High School">High School</option>
          <option value="Graduate"> High School</option>
          </select><br><br>
          <label for="CGPA">CGPA(0-10)</label>
          <input type="number" min="0" max="10" placeholder="e.g.,8.23">
          <br><br>
          <label for="Primary skills"><span style="color: red;">*</span>Primary skills</label><br>
          <select name="" id="" required>
            <option value="Coding lang">Python</option>
            <option value="Coding lang">JAVA</option>
            <option value="Communication">English</option>
            <option value="Management">Manager</option>
          </select>
          <br><br>
          <label for="Other skills">Other skills</label><br>
          <input type="checkbox">
           <label for="">HTML</label><br>
           <input type="checkbox">
           <label for="">CSS</label><br>
           <input type="checkbox">
           <label for="">JavaScript</label><br>
           <input type="checkbox">
           <label for="">TypeScript</label><br>
           <input type="checkbox">
           <label for="">React</label><br>
           <input type="checkbox">
           <label for="">Node.js</label><br><br>

           <label for="Quick add skills">Quick add via datalist</label><br>
           <textarea name="" id="" rows="3" cols="30"></textarea>

           </fieldset>

           <!-- Availability and preferences -->

           <fieldset>
            <legend><b>Availability and preferences</b></legend><br>
            <label for="Date"><span style="color: red;">*</span>Earliest Start Date</label><br>
            <input type="date" name="" id="" required><br><br>
            <label for="Time">Prefferd Interview Time</label><br>
            <input type="time"><br><br>
            <label for="Time zone">Time zone</label><br>
            <select name="" id="">
              <option value="Asia/Kolkata(IST)">Asia/Kolkata(IST)</option>
              <option value="JST	Japan Standard Time">JST	Japan Standard Time</option>
              <option value="KGT	Kyrgyzstan Time">KGT	Kyrgyzstan Time</option>
            </select><br><br>
            <label for="colour">Brand colour</label>
            <input type="color"><br><br>
            <label for="CTC">Expected CTC(Lakhs/Year)</label><br>
            <input type="range" placeholder="We know you want 40+">

            </fieldset>

            <!-- Document -->
             <fieldset>
              <legend><b>Documents</b></legend>
              <label for="Resume"><span style="color: red;">*</span>Upload Resume</label><br>
              <input type="file" accept=".pdf" required><br><br>
              <label for="Profile Photo(JPG/PNG)">Profile Photo(JPG/PNG)</label><br>
              <input type="file" accept=".png,.jpg,.png" required><br><br>

             </fieldset>

             <!-- Short answers -->
              <fieldset>
                <legend><b>Short answers</b></legend><br>
                <label for="Acceptance"><span style="color: red;">*</span>Why should we consider you?</label><br>
                <textarea name="" id="" rows="3" cols="30" placeholder="Write atleast 30 words" required></textarea><br><br>
                <label for="Refferal">Refferal code (pattern:ABC-1234)</label><br>
                <input type="text" placeholder="ABC-1234">
              </fieldset>

              <!-- optional survey -->

              <fieldset>
                <legend><b>Optionla survey(expand)</b></legend><br>
                <input type="checkbox">
           <label for=""><span style="color: red;">*</span> I Confirm all information is accurate and I accept the terms.</label><br>
           <input type="submit" required>
           <input type="reset">
           </fieldset>
           <h5>Made with using only HTML5 elements and built-in validation.</h5>



           </form>

</body>
</html>

                
              

            
           

            
           
          

               

      

        
        

        
       

          
          
          

          


         
        

  
