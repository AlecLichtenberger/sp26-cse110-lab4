## 1
The bug is that the num variables are being read as strings and thus are concatenating instead of adding in the result

## 2
I would fix by finding some way to convert it to int or extract the int out of the string with likte a stoi command of some kind
