# README
A place where I experiment.

def login(username: str, password: str) -> str:
    '''
  This "super-secure" function simulates the login process.
  If password is equal to "12345678",
  it is considered that the user has successfully logged in.
''' 
    if password == "12345678":
        return "Successfully logged in!"
    else: 
        return "Login Failed: incorrect password"
