# Exercism - Daily Problem 001: Hello, World!
- PowerShell is a scripting and automation language that was created by Microsoft.

## Solution Overview:
- Inside the function `Get-HelloWorld`, we simply write a return statement that returns the string "Hello, World!".

## Solution Code:
```powershell
Function Get-HelloWorld {
    <#
    .SYNOPSIS
    Outputs "Hello, World!"
    
    .DESCRIPTION
    Output "Hello, World!".
    
    .EXAMPLE
    Get-HelloWorld
    #>	
    
    Return "Hello, World!"
}
```
## Output:
```
Hello, World!
```

## Synopsis, Description and Example:
- After some research, I learned that a multi-line comment in Powershell starts with `<#` and ends with `#>`.
    - But here it's formatted specifically so that it's treated as helping metadata for the function `Get-HelloWorld`.
    - `.SYNOPSIS`, `.DESCRIPTION` and `.EXAMPLE` are tags.
        - `.SYNOPSIS`: It provides a one-line explanation about what the function does.
        - `.DESCRIPTION`: Gives a more detailed explanation about what the function does.
        - `.EXAMPLE`: Shows an example of how to run thee function and sometimes a sample output too.
    - There exists a `Get-Help` function that will fetch show this metadata info when it's used as follows in the terminal:
    ```powershell
    Get-Help Get-HelloWorld
    ```

## Note:
- Generally, I would use the `ni` command to create a new `HelloWorld.ps1` file, in which I write the following:
```powershell
echo "Hello, World!"
```
- After which I run the `HelloWorld.ps1` file using the terminal command:
```powershell
./HelloWorld.ps1
```
- Which will give the same output:
```
Hello, World!
```
- But, in Exercism's evaluator only wants me to return the string "Hello, World!" for a function `Get-HelloWorld` they already defined, similar to the [Exercise 001 in Java](https://github.com/praharshidha-anandan/learning-log/blob/main/daily-problems/java/exercism-java-001.md).

