# LibMatic

## Format

Create a folder with the library name and inside put your readme file, a requirements.txt file and the python file with any submodules.

```
└── Library name/
    ├── library name.py
    ├── requirements.txt
    └── submodule.py
    └── README.md
```

In the requirements.txt file put any required modules divided by lines.

```
numpy
```

Additionaly, you can add a scripts.txt file to your folder to add commands to the package. Inside the scripts.txt file put the name of the command space the file it is in space the function name like so

```
name-of-command file-its-in name-of-function
name-of-command file-its-in name-of-function
```

Remember to put newlines between functions.

## Commands

### How to format your code

run:
```
lib-convert
```

Then, answer the questions.
```
Name of Library:
version:
Full Name:
email:
Homepage:
issues page:
```
Your code will be formated

### How to compile

To compile the formatted code into a wheel, run:
```
wheel-matic
```

A file called dist will appear with the wheel and a targz file inside.