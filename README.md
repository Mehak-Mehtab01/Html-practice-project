
 <!DOCTYPE html>
<html>
<head>
   <meta charset="utf-8">
   <meta name="viewport" content="width=device-width, initial-scale=1">
   <title>Survey Form</title>
</head>
<body>   <h2  >   
              <center> freeCodeCamp Survey Form 
         <p> 
          Thankyou for taking the time to help us improve us the platform <center/>
          
        </h2>
      <form> 
            <fieldset> 
             
            Name 
            <br/> 
            <input type="text" name="name" placeholder="Enter your name" />  
             <br/>  
             <br/> 
            Email 
            <br/> 
            <input type="email" name="email" placeholder="Enter your email">  
             <br/>  
             <br/> 
            Age(Optional) 
            <br/>  
            <input type="number" name="age" min="10" max="99"/>  
            <br/>  
             <br/>  
             Which option best describe your current role?
             <br/>  
             <select> 
              <option> Select current role </option> 
              <option>Student</option> 
              <option>Full Time Job</option> 
               <option> Full Time Learner</option> 
                 <option>Prefer not to say</option> 
                  <option>other</option>  
                  </select>  
                  <br/>  
             <br/>  
             Would you recommend freeCodeCamp to a friend? 
             <br/>  
             <input type="radio"  value="definitely" name="Would you recommend freeCodeCamp to a friend?" checked=""/>Definitely 
             <br/>  
             <input type="radio" value="maybe" name="Would you recommend freeCodeCamp to a friend?"/> Maybe 
             <br/>  
             <input type="radio" value="notsure " name="Would you recommend freeCodeCamp to a friend?"/>Not sure   
              <br/>  
             <br/>   
             What is your favorite feature of freeCodeCamp?  
             <br/>  
             <select> 
             <option>Select an option</option>   
               <option>Challenges</option> 
               <option>Project</option> 
               <option>Community</option>  
               <option>Open Source</option>   
             </select> 
             <br/> 
             <br/> 
             What would you like to see improved? (Check all that apply) 
             <br/> 
            <input type="checkbox" name="What would you like to see improved? (Check all that apply) "/>Front-end Projects  
            <br/>    
            <input type="checkbox" name="What would you like to see improved? (Check all that apply) "/> Back-end Projects
            <br/>  
            <input type="checkbox" name="What would you like to see improved? (Check all that apply) "/> Data Visualization 
            <br/>  
            <input type="checkbox" name="What would you like to see improved? (Check all that apply) "/>  Challenges
            <br/>  
            <input type="checkbox" name="What would you like to see improved? (Check all that apply) "/>Open Source Community 
            <br/>          
            <input type="checkbox" name="What would you like to see improved? (Check all that apply) "/> Gitter help rooms 
            <br/>  
            <input type="checkbox" name="What would you like to see improved? (Check all that apply) "/>Videos  
            <br/>   
            <input type="checkbox" name="What would you like to see improved? (Check all that apply) "/> City Meetups 
            <br/>  
            <input type="checkbox" name="What would you like to see improved? (Check all that apply) "/> Wiki 
            <br/>  
            <input type="checkbox" name="What would you like to see improved? (Check all that apply) "/>  Forum
            <br/>  
            <input type="checkbox" name="What would you like to see improved? (Check all that apply) "/> Additional Courses
            <br/>   
            <br/> 
            Any comments or suggestions? 
            <br/> 
            <textarea placeholder="Enter your comment here"></textarea>
             <br/>   
            <br/>   
            <input type="submit" name="submit"/>           
            </fieldset>
      </form>
</body>
</html>
