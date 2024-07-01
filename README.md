<!DOCTYPE>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <title> <h1 id="title">Survey Form</h1></title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
<h1 id="title">
  Servey form</h1>    
    <h4>freeCodeCamp Survey Form</h4>
    <p id="description">Thank you for taking the time to help us improve the platform</p>
    
    <form method="post" action="https://register-demo.freecodecamp.org" id="survey-form">

 <fieldset>     <label id="name-label" for="name">Name<br><input id="name" name="name" type="text" required placeholder="Enter your name"/></label><br>
      <label id="email-label" for="Email">Email<br><input id="email" name="email" type="email" required placeholder="Enter your Email"/></label><br/>
      <label id="number-label" for="Age">Age(optional)<br><input id="number" name="Age" type="number" required min="18" 
max="60"      placeholder="Enter your Age"/></label><br/>
      </fieldset>
<label for="referrer">Which option best describes your current role?<br/>
          <select id="dropdown" name="dropdown">
            <option value="">select current role</option>
            <option value="1">student</option>
            <option value="2">full time job</option>
            <option value="3">Full time learner</option>
            <option value="4">Prefer not to say</option>
            <option value="5">Other</option>
          </select>
        </label>
   <fieldset>     <legend>Would you recommend freeCodeCamp to a friend?</legend>
        <label for="personal-account"><input id="personal-account" type="radio" name="account-type" class="inline" checked  value="personal-account"/> Definitely</br></label>
        <label for="business-account"><input id="business-account" type="radio" name="account-type" class="inline" value="business-account" /> Maybe<br/></label>
        <label for="account"><input id="account" type="radio" name="account-type" class="inline" value="account" /> Not sure<br/></label></fieldset>
<label for="referrer">What is your favorite feature of freeCodeCamp?<br/>
          <select id="referrer" name="referrer">
            <option value="">select an option</option>
            <option value="1">Challenges</option>
            <option value="2">Projects</option>
            <option value="3">Community</option>
            <option value="4">Open Source</option>
            <option value="5">Other</option>
          </select><br/>
        </label>
        <label for="terms-and-conditions">What would you like to see improved? (Check all that apply)<br/>
        <input id="terms-and-conditions" type="checkbox" required name="terms-and-conditions" value="terms-and-conditions" /> Front-end Projects</br>
        <input id="terms-and-conditions" type="checkbox" required name="terms-and-conditions" value="terms-and-conditions"  /> Back-end Projects<br/>
        <input id="terms-and-conditions" type="checkbox" required name="terms-and-conditions" value="terms-and-conditions" /> Data Visualization<br/>
<input id="terms-and-conditions" type="checkbox" required name="terms-and-conditions" value="terms-and-conditions" /> Challenges<br/>
<input id="terms-and-conditions" type="checkbox" required name="terms-and-conditions" value="terms-and-conditions"  /> Open Source Community<br/>
<input id="terms-and-conditions" type="checkbox" required name="terms-and-conditions" value="terms-and-conditions" />Gitter help rooms<br/>
<input id="terms-and-conditions" type="checkbox" required name="terms-and-conditions" value="terms-and-conditions"  />Videos<br/>
<input id="terms-and-conditions" type="checkbox" required name="terms-and-conditions" value="terms-and-conditions"  />City Meetups<br/>
<input id="terms-and-conditions" type="checkbox" required name="terms-and-conditions" value="terms-and-conditions"  />Wiki<br/>
<input id="terms-and-conditions" type="checkbox" required name="terms-and-conditions"  value="terms-and-conditions"  />Forum<br/>
<input id="terms-and-conditions" type="checkbox" required name="terms-and-conditions" value="terms-and-conditions"  />Additional Courses<br/>
</label>
<label for="bio">Any comments or suggestions?<br/>


          <textarea id="bio" name="bio" rows="3" cols="30" placeholder="Enter your comment here..."></textarea><br/>
        </label>
        <input type="submit" value="Submit" id="submit" />
    </form>
  </body>
</html>
body {
  width: 180%;
  height: 150vh;
  margin: 0;
  background-color: #1b1b32;
  color: #f5f6f7;
  font-family: Tahoma;
  font-size: 16px;
}
h4, p {
  margin: 1em auto;
  text-align: center;
}
form {
  width: 150vw;
  max-width: 500px;
  min-width: 300px;
  margin: 0 auto;
  padding-bottom: 2em;
}
fieldset {
  border: none;
  /*padding: 2rem 0;*/
  
}
input,
textarea,
select {
  margin: 10px 0 0 0;
  }
