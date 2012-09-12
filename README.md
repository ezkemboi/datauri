datauri
=======

A simple Data URI scheme generator built on top of [Node.js][nodejs]. To install datauri, just run:

`npm install -g datauri` (maybe it would require Root privileges)

HOW TO USE
----------

### Print datauri scheme
To print a datauri scheme from a file
```CLI
$ datauri brand.png
```

### CSS Background
You can generate or update an output css file with datauri background:
```CLI
$ datauri brand.png asset/background.css
```
If you want to define a Class Name, just type:
```CLI
$ datauri brand.png asset/background.css MyNewClass
```

[nodejs]: http://nodejs.org/download