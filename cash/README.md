# Cash

##The purpose is to convert currencies

#Installation  :

1) Fork the project to your github account

2) Open your CMD and clone your forked project to your workspace:

```sh
❯ cd /path/to/workspace
❯ git clone git@github.com:YOUR_USERNAME/3-musketeers.git
```


Program steps :

1) The program is looking to the API adress in the constants.js file.

2) It's going to check the actual currencies rate on internet in real time.

3) It's also setting currency goal default in an array.

4) The program is using the convert method in node libraries to convert the currency.

5) If you havn't specified any currency goal or/and origin, it will convert you 1 USD in Euro, Britsh Pound, and Japanese Yen.
