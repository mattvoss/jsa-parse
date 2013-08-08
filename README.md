Installation
============

After cloning the repo run

```
npm install -d
````

Usage
=====

```
node app.js -l {letter of authenticity number goes here E.g. U}
```

Options
=======
-l {A}, --letter {A} = letter of authenticity number

-s {0}, --start {0} = number to begin download of data from website

Output
======
It writes data to a csv file in the directory of the app using the naming format of {letter}00000.csv

The CSV has this format:

```
'Field:Baseball','Signer:Luke Easter','A10517'
'Field:Baseball','Signer:Harry Simpson','A10518'
'Field:Baseball','Signer:Minnesota Twins','A10519'
'Field:Baseball','Signer:Max Patkin','A10520'
'Field:Football','Signer:Darryl Stingley','A10521'
'Field:Baseball','Signer:Don Mattingly','A10522'
'Field:Baseball','Signer:Hank Greenberg','A10523'
'Field:Baseball','Signer:George Sisler','A10524'
'Field:Baseball','Signer:Joe Medwick','A10525'
'Field:Baseball','Signer:Don Mattingly','A10526'
'Field:Baseball','Signer:Don Mattingly','A10527'
'Field:Baseball','Signer:Don Mattingly','A10528'
```
