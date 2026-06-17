Cybersec (edit the name later)
Here I am just adding my own thinking and structure for better workflow:
structure:
1st page when visited should consist 3 options: 
    a> register(for new users)
    b> login(for existing users)
    c> exit(to quit using that page)
if choose register:
    a> ask for user details to be used later
    b> store these details in the file named: user_txt
if choose login:
    a> ask for the login credentials
        if credential not matched: print invalid credential, try again
        if credential matched: 
            a> give them options:
                (i)study
                (ii)test/quiz
    b> if choose to study, give options:
        list all the modules available(ex: networking, passwordsec, phishing, etc...)
    c> if choose quiz, give options:
        list all the quizzing options available(ex: networking, passwordsec, phishing, etc...)
Now, keep all the users progress in the file named: Progress
    if completed the module and the quiz, provide a certificate
    store the certificate in the certificate file 
