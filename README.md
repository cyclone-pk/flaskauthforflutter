
# Login Register Form with Flask + SQLAlchemy

I have just created this simple python flask auth system for learning purpose so that you can implement it in flutter as well as in web for learning purpose.

### Requirements

    pip install flask
    pip install SQLAlchemy

### Testing Command 
# For Registering account from terminal
replace username email@provider.com and password with the actual values

    CURL -X POST http://127.0.0.1:5000/register -d "uname=username&mail=email@provider.com&passw=password" 

if Status is equal to 11 it mean successfully created account if 22 it mean username already exist

replace username with email@provider.com and passw with password

    CURL -X POST http://127.0.0.1:5000/login -d "uname=username&passw=password" 

if Status is equal to 11 it mean successfully login if 22 it mean username or password is incorrect
    
