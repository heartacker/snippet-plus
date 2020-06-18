# C/C++/C# Snippets (OutSide Code Supported)

This extension for Visual Studio Code adds snippets for C/C++/C# base On [kkonghao/snippet-dog](https://github.com/kkonghao/snippet-dog), Now Adding support Outside code like `Visual Studio`.

[heartacker/snippets-C_C++_C#](https://github.com/kkonghao/snippet-dog)

## Installation

1. Install Visual Studio Code
2. Launch VS Code
3. From the command palette `Ctrl`+`Shift`+`P` (Windows, Linux) or `Cmd`+`Shift`+`P` (OSX)
4. Type `ext install` or just simply select `Install Extension`
5. Choose the extension - C/C++/C# Snippets

## Usage

C/C++/C# Snippets use Tab to change one position to another.

And Some Snippet is **OutSide Code Supported**, which is useful for **refactoring**, just like `Visual Studio`:

```c

int	main(int argc, char **argv)
{
    system("pause");
    return 0;
}

```

select  `system("pause");` and insert snippet like  `for`, 

then that will embedd `system("pause");` by for loop;
```c

int	main(int argc, char **argv)
{
    for (int lop = 0; lop < 10; lop++)
    {
        system("pause");        
    }
    
    return 0;
}

```

## Snippets

### C Snippets

| Snippet      | Description                                                |
| ------------ | ---------------------------------------------------------- |
| `#def`       | snippet for #define                                        |
| `#ifdef`     | snippet for #if (**Outside Code Supported**)               |
| `#ifndef`    | snippet for #ifndef (**Outside Code Supported**)           |
| `#inc`       | snippet for #include                                       |
| `case`       | snippet for case (...)                                     |
| `do`         | snippet for a do...while loop (**Outside Code Supported**) |
| `else`       | snippet for else (**Outside Code Supported**)              |
| `else if`    | snippet for else-if (**Outside Code Supported**)           |
| `enum`       | snippet for an enum declaration                            |
| `fileheader` | snippet for a file header                                  |
| `for`        | snippet for a for loop (**Outside Code Supported**)        |
| `if`         | snippet for an if statement (**Outside Code Supported**)   |
| `main`       | snippet for a main function                                |
| `struct`     | snippet for a struct declaration                           |
| `switch`     | snippet for a switch statement                             |
| `union`      | snippet for a union declaration                            |
| `while`      | snippet for a while loop (**Outside Code Supported**)      |

### C++ Snippets

| Snippet         | Description                                                |
| --------------- | ---------------------------------------------------------- |
| `#def`          | snippet for #def                                           |
| `#ifdef`        | snippet for #if (**Outside Code Supported**)               |
| `#ifndef`       | snippet for #ifndef (**Outside Code Supported**)           |
| `#inc`          | snippet for #include                                       |
| `case`          | snippet for case (...)                                     |
| `class`         | snippet for a class declaration                            |
| `class inherit` | snippet for a class-inherit declaration                    |
| `do`            | snippet for a do...while loop (**Outside Code Supported**) |
| `else`          | snippet for else (**Outside Code Supported**)              |
| `else if`       | snippet for else-if (**Outside Code Supported**)           |
| `enum`          | snippet for an enum declaration                            |
| `fileheader`    | snippet for a file header                                  |
| `for`           | snippet for a for loop (**Outside Code Supported**)        |
| `foreach`       | snippet for a for-auto loop (**Outside Code Supported**)   |
| `if`            | snippet for an if statement (**Outside Code Supported**)   |
| `main`          | snippet for a main function declaration                    |
| `namespace`     | undefined                                                  |
| `struct`        | snippet for a struct declaration                           |
| `switch`        | snippet for a switch statement                             |
| `template`      | snippet for a template                                     |
| `try`           | snippet for a try-catch block (**Outside Code Supported**) |
| `union`         | snippet for a union declaration                            |
| `using`         | snippet for using namespace                                |
| `while`         | snippet for a while loop (**Outside Code Supported**)      |

## Recommendations

In order to give you a perfect plugin experience and avoid conflict with C/C++ Microsoft edition's snippet,
I recommend you turn off C/C++ Microsoft edition's snippet. Details can be find in the below.

Settings/Extensions/ C or C++/ C_CPP:Suggest Snippets

## Suggestions for improvement are welcome
