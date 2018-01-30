# Carnet-alexa
Give Alexa the power to control your car from anywhere

## Installing
**Requirements**
* Amazon AWS & developer accounts
* A carnet-enabled Volkswagen

Upload `lambda_function.py` and the  `modules` folder as a .zip file to a new lambda function.<br>
Add your username and password to `lambda_function.py` in the `VWCarnet` constructor.<br>
In the Amazon developer console create a new Alexa Skill and link it to the function.<br>
Copy and paste the contents of `inteactionmodel.json` into the code section of the Skill builder.<br>
Save, build and enjoy.


## Huge Thank you to
@robinostlund: https://github.com/robinostlund/volkswagen-carnet