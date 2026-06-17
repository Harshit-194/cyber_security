Cybersec (edit the name later)<br>
Here I am just adding my own thinking and structure for better workflow:<br>
structure:<br>
1st page when visited should consist 3 options: <br>
    a> register(for new users)<br>
    b> login(for existing users)<br>
    c> exit(to quit using that page)<br>
if choose register:<br>
    a> ask for user details to be used later<br>
    b> store these details in the file named: user_txt<br>
if choose login:<br>
    a> ask for the login credentials<br>
        if credential not matched: print invalid credential, try again<br>
        if credential matched: <br>
            a> give them options:<br>
                (i)study<br>
                (ii)test/quiz<br>
    b> if choose to study, give options:<br>
        list all the modules available(ex: networking, passwordsec, phishing, etc...)<br>
    c> if choose quiz, give options:<br>
        list all the quizzing options available(ex: networking, passwordsec, phishing, etc...)<br>
Now, keep all the users progress in the file named: Progress<br>
    if completed the module and the quiz, provide a certificate<br>
    store the certificate in the certificate file <br>
