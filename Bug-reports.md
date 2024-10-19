**Link to the project Demo Form**	http://itcareer.pythonanywhere.com/  
**Tester:**	Natallia Zhukava  
**Environment:**	Google Chrome Version 129.0.6668.101 (Official Build) (64-bit)  
**Date:**	19.10.2024

ID | Title |	Severity |	Priority |	Preconditions |	Steps to Reproduce |	Expected Result |	Actual Result |	Attachment
-- | ----- | --------- | --------- | -------------- | ------------------ | ---------------- | ------------- | ----------
1 |	The field "Surname" is named "Surame" |	Trivial |	Medium |	[Demo Form](http://itcareer.pythonanywhere.com//) is opened |	Visually inspect the name of the field "Surname" |	The field is named "Surname" |	The field is named "Surame" | [Link](https://drive.google.com/file/d/1mAv-Gn6s00urozjIXzyjyaRECJMffyE_/view?usp=drive_link)
2 |	The style of placeholder display differs across the fields |	Trivial |	Low |	[Demo Form](http://itcareer.pythonanywhere.com//) is opened |	Visually inspect the placeholders | The placeholders are displayed as:<br>Enter your name<br>Enter your surname<br>Enter your email<br>Enter your password | The placeholders are displayed as:<br>Name?<br>Surname?<br>Your email  address.<br>Enter a password. | [Link](https://drive.google.com/file/d/16-mifT0_eVd41yyYn4Ha_-j0tVAcR-oR/view?usp=drive_link)
3 |	The name of the button [Submit] is not centred |	Trivial |	Medium |	[Demo Form](http://itcareer.pythonanywhere.com//) is opened |	Visually inspect the button [Submit] |	The writing "Submit" is centered |	The position of the writing "Submit" is padding-left:30px |	[Link](https://drive.google.com/file/d/17lY5rEKEvuk_NiB00mAxEzsBZEkt5PWo/view?usp=drive_link)
4 |	The field "Password" is not duplicated for confirmation |	Major |	High |	[Demo Form](http://itcareer.pythonanywhere.com//) is opened |	Visually inspect the field "Password" |	The field "Password" is  duplicated as "Password" and "Confirm password" |	The field "Password" is not duplicated |	[Link](https://drive.google.com/file/d/16wNqV_8YFK1s2WcZC2vMR0k04G6gYpzf/view?usp=drive_link)
5 |	The required fields ("Name", "Email", "Password") are not marked with asterisks |	Minor |	Medium |	[Demo Form](http://itcareer.pythonanywhere.com//) is opened |	Visually inspect the names of the fields |	The required fields are marked with asterisks |	The required fields are not marked with asterisks |	[Link](https://drive.google.com/file/d/1OStpnbXVGgwU2beH7Nf0E8TAcsQnJnyV/view?usp=drive_link)
6 |	The message "Error: Error: All Fields are Required" is displayed after clicking on the [Submit] button when only the fields "Name" and/or "Surname" are left empty |	Major |	High |	[Demo Form](http://itcareer.pythonanywhere.com//) is opened | 1. Enter valid values into the fields "Email" and "Password"<br>2. Leave the fields "Name" and "Surname" empty or enter valid values into one of them<br>3. Click on the [Submit] button" |	**If the field "Name"" is empty:** the field "Name" has a red frame; the message “This field is required” is displayed.<br>**If only the field "Surname" is empty:** the message "Success! Hello: Name" is displayed |	The message "Error: Error: All Fields are Required" is displayed |	[Link](https://drive.google.com/file/d/1jPK8jgvR3M6MHsR65INAboWpBdRJQKVV/view?usp=drive_link)




