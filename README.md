<html>
<h1 style="background: skyblue"><center> HERE</center></h1>
</html>
<html>
<h1 style="background: skyblue"><center> Welcome. Were glad to see you.</center></h1>
</html>
<html>
<h1 style="background: skyblue"><center>Please fill in Everything</center></h1>
</html>
<body bgcolor="skyblue">
<table cellpadding="5" width="30%" bgcolor="skyblue" align="center"
cellspacing="5">
<tr>
	<td colspan="2">
		<center><font size="4"><b></b></font></center>
	</td>
</tr>
<tr>
	<center>
	 <form id="registrationForm">
    <label for="firstname">First Name:</label>
    <input type="text" id="firstname" name="firstname" required>
    <div id="firstnameError" class="error"></div>
    <label for="lastname">Last Name:</label>
    <input type="text" id="lastname" name="lastname" required>
    <div id="lastnameError" class="error"></div>
    <label for="email">Email:</label>
    <input type="text" id="email" name="email" required>
    <div id="emailError" class="error"></div>
   <label for="password">Password:</label>
    <input type="password" id="password" name="password" required>
    <div id="passwordError" class="error"></div>
    <div id="passwordError" class="error"></div>

</tr>
<tr>
</center>
<center>
<div>
		Country/Region:
	</div>
<div><select> name="Date of Birth"> placeholder="select"
<option>Country</option>
					<option>Philippoines</option>
					<option>Usa</option>
					<option>China</option>
					<option>Japan</option>
				</select>
			</div>
			<center>
						<label for="phoneno">PhoneNo:</label>
    <input type="text" id="p" name=phoneno"phoneno" required>
    <div id="phonenoError" class="error"></div>


    <label for="gender">Gender:</label>
	<div><input type="radio" name="gender">Male
		<input type="radio" name="gender">Female
	</div>

		<div>
		Date of Birth:
	</div>
<div><select> name="Date of Birth"> placeholder="select"
<option>Month</option>
					<option>January</option>
					<option>February</option>
					<option>March</option>
					<option>April</option>
				</select>
			</div>
<div class="select">
          <select name="format" id="format">
            <option selected disabled>DAY</option>
            <option value="1">1</option>
            <option value="2">2</option>
            <option value="3">3</option>
            <option value="4">4</option>
        </select>
    </div>
  
<div><select> name="Date of Birth"> placeholder="select"
<option>Year</option>
					<option>2000</option>
					<option>2001</option>
					<option>2002</option>
					<option>2003</option>
				</select>
			</div>
	</center>

	<div>Security Check</div>
	<div><input type="Security Check" name="Security Check" placeholder="" size="30"></div></tr>
	</tr>
	<center>
			<div>
				<input type="Reset"></td>
				<div colspan="2"><input type="Submit" value="NEXT"/></div>
			</div>
			</center>
			<script>
				<script>
    // Get form and form elements
    const registrationForm = document.getElementById('registrationForm');
    const username = document.getElementById('username');
    const email = document.getElementById('email');
    const password = document.getElementById('password');
    const confirmPassword = document.getElementById('confirmPassword');
    const usernameError = document.getElementById('usernameError');
    const emailError = document.getElementById('emailError');
    const passwordError = document.getElementById('passwordError');
    const confirmPasswordError = document.getElementById('confirmPasswordError');

    // Validate username
    username.addEventListener('input', () => {
      if (username.validity.valid) {
        usernameError.textContent = '';
      } else {
        usernameError.textContent = 'Username must be at least 4 characters long.';
      }
    });

    // Validate email
    email.addEventListener('input', () => {
      if (email.validity.valid) {
        emailError.textContent = '';
      } else {
        emailError.textContent = 'Please enter a valid email address.';
      }
    });

    // Validate password
    password.addEventListener('input', () => {
      if (password.validity.valid) {
        passwordError.textContent = '';
      } else {
        passwordError.textContent = 'Password must be at least 8 characters long.';
      }
    });

    // Validate confirm password
    confirmPassword.addEventListener('input', () => {
      if (confirmPassword.validity.valid && confirmPassword.value === password.value) {
        confirmPasswordError.textContent = '';
      } else {
        confirmPasswordError.textContent = 'Passwords must match.';
      }
    });

    // Submit form
    registrationForm.addEventListener('submit', (event) => {
      if (!username.validity.valid) {
        usernameError.textContent = 'Username must be at least 4 characters long.';
        event.preventDefault();
      }
      if (!email.validity.valid) {
        emailError.textContent = 'Please enter a valid email address.';
        event.preventDefault();
      }
      if (!password.validity.valid) {
        passwordError.textContent = 'Password must be at least 8 characters long.';
        event.preventDefault();
      }
      if (!confirmPassword.validity.valid || confirmPassword.value !== password.value) {
        confirmPasswordError
      </center>
      </script>
			</script>
		</table>
	</form>
	</body>
	</html>
