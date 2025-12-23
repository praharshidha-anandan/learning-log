# Exercism - Daily Problem 001: Hello, World!

## Solution Overview:
- Batch commands can technically be considered a scripting language.
- A Batch file is a simple list of commands that will be interpreted by `cmd.exe` and then executed.
- Its sort of a legacy Windows equivalent to `script.sh` type files in UNIX based systems.
- Here we simple write a command in Batch scripting syntax to echo "Hello, World!" into the terminal when executed like so:
```
C:Users\Username\Exercism\batch\hello-world> HelloWorld
```

## Solution Code:
```batch
@Echo Hello, World!
:: The filename is HelloWorld.bat
```
## Output:
```
Hello, World!
```