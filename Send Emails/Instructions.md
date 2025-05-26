1. Read Excel file and save it as collection.
2. Loop through element and verify the email as templet using regular expression as : {First Name}.{Last Name}@gmail.com.
3. If the email is match correctly add it to the Match group.
4. If the email is not match , add to no match group and send email as :{"Dear"&{Name}&" your email is not following the best practice " &{Email}}. 
