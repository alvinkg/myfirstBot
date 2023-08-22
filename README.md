I struggled to install telegram-bot in CLI, as @7.0 return errors. 
Changing to @6.0 did not help until I used the command brew alvinlim@coolhandsg-iMac ~ % brew tap mongodb/brew
alvinlim@coolhandsg-iMac ~ % brew install mongodb-community@6.0
alvinlim@coolhandsg-iMac ~ % brew services start mongodb-community@6.0
Next I found that I had to install the python-telegram-bot again but not under the virtual env for this program to work.
TODO: to test out if everything still works in a virenv.  No reason to doubt.
Need to know why it does not work before.

## Security
dotenv
.env file needed

## Node JS method

https://www.youtube.com/watch?v=bFFMX1L8TKI
require('dotenv').config()
const TOKEN = process.env.TOKEN;

## How to launch webapps

https://www.youtube.com/watch?v=p6jxxd4BU_E

