# C/C++ Snippets Plus (OutSide Code Supported)

This extension for Visual Studio Code adds snippets for C/C++ base On [kkonghao/snippet-dog](https://github.com/kkonghao/snippet-dog), Now add supportting Outside code like `Visual Studio`.

>这个扩展为Visual Studio Code 添加 C/C++ 代码段，现在添加支持外侧代码，就像 Visual Studio 2019，当你选择了文本之后，可以插入外侧包围。

for more information：[heartacker/snippet-plus](https://github.com/heartacker/snippet-dog.git)

## Usage

C/C++ Snippets use Tab to change one position to another.

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
-    system("pause");

+    for (int lop = 0; lop < 10; lop++)
+    {
+       system("pause");
+    }

    return 0;
}

```

There is the demo:
![demo](images/demo.gif)

## Keyboard Shortcuts

Also, add `ctrl+alt+i` (`cmd+alt+i` on mac) to trigger `insert snippet` for better experience. this keybinding is for all languages, not only for this extension. 

after that, you can select those code or not, then press `ctrl+alt+i` to insert snippet.

## Snippets

### C Snippets

| Snippet      | Description                      | Outside Support |
| ------------ | -------------------------------- | --------------- |
| `#def`       | snippet for #define              |                 |
| `#ifdef`     | snippet for #if                  | Y               |
| `#ifndef`    | snippet for #ifndef              | Y               |
| `#inc`       | snippet for #include             |                 |
| `case`       | snippet for case (...)           |                 |
| `do`         | snippet for a do...while loop    | Y               |
| `else`       | snippet for else                 | Y               |
| `else if`    | snippet for else-if              | Y               |
| `enum`       | snippet for an enum declaration  |                 |
| `fileheader` | snippet for a file header        |                 |
| `for`        | snippet for a for loop           | Y               |
| `if`         | snippet for an if statement      | Y               |
| `main`       | snippet for a main function      |                 |
| `struct`     | snippet for a struct declaration |                 |
| `switch`     | snippet for a switch statement   |                 |
| `union`      | snippet for a union declaration  |                 |
| `while`      | snippet for a while loop         | Y               |

### C++ Snippets

| Snippet         | Description                             | Outside Support |
| --------------- | --------------------------------------- | --------------- |
| `#def`          | snippet for #def                        |                 |
| `#ifdef`        | snippet for #if                         | Y               |
| `#ifndef`       | snippet for #ifndef                     | Y               |
| `#inc`          | snippet for #include                    |                 |
| `case`          | snippet for case (...)                  |                 |
| `class`         | snippet for a class declaration         |                 |
| `class inherit` | snippet for a class-inherit declaration |                 |
| `do`            | snippet for a do...while loop           | Y               |
| `else`          | snippet for else                        | Y               |
| `else if`       | snippet for else-if                     | Y               |
| `enum`          | snippet for an enum declaration         |                 |
| `fileheader`    | snippet for a file header               |                 |
| `for`           | snippet for a for loop                  | Y               |
| `foreach`       | snippet for a for-auto loop             | Y               |
| `if`            | snippet for an if statement             | Y               |
| `main`          | snippet for a main function declaration |                 |
| `namespace`     | undefined                               |                 |
| `struct`        | snippet for a struct declaration        |                 |
| `switch`        | snippet for a switch statement          |                 |
| `template`      | snippet for a template                  |                 |
| `try`           | snippet for a try-catch block           | Y               |
| `union`         | snippet for a union declaration         |                 |
| `using`         | snippet for using namespace             |                 |
| `while`         | snippet for a while loop                | Y               |

## Recommendations

In order to give you a perfect plugin experience and avoid conflict with C/C++ Microsoft edition's snippet,
I recommend you turn off C/C++ Microsoft edition's snippet. Details can be find in the below.
```
Settings/Extensions/ C or C++/ C_CPP:Suggest Snippets
```

## Suggestions for improvement are welcome
