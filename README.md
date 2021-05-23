# 👷‍♂️⚙️ Automating the Boring Stuff with Python

↓ Read to know what each file does. ↓

## addnum.py

<details>
<summary>
Add an auto increment numbers on each lines of a text file.
</summary>

```text
Eg.
    From:
        This is line one
        This a second line
        3. I'm line three
        Yay Fourth
    To:
        1. This is line one
        2. This a second line
        3. I'm line three
        4. Yay Fourth
```

</details>

## autowrtxt.py

<details>
<summary>
Auto write text with `pyautogui`
</summary>

Options `(edit source code to select different option)`

1. Write contents of a text file
2. Write contents of the text provided by you
3. Write contains of this file
4. Write contains of the clipboard! (default)

```text
Requirements:
pyautogui
pyperclip   # for Option 4
```

</details>

## bored.py

Run this if you get bored!

## createfile.py

Instantly create a file of any size (in GB).

## generat2FAcodes.py

Instantly create a text file with 6 digit two factor authentication codes.

## getfiles.py

Returns the list of every file in a directory tree.

## getpath.py

<details>
<summary>
Get either file path or directory path from the user.
</summary>

```python
filepath()
# Ask for a file path to the user then, returns the absolute path of the file if it exist.

dirpath()
# Asks for a directory path to the user then, returns absolute path of the directory if it exists.
```

</details>

## getyesno.py

Returns `True` if input from the user is `yes`, `False` if `no`, that is all.

## refreshWin.py

> Requirement: `pyautogui`

A simple and fun program that refresh windows any numbers of times you want.

## renamefiles.py

<details>
<summary>
Rename all file on a folder to randomly generated 6 digit code.
</summary>

```text
From:
    __fjdsl7439fRHzzt77UUvfTRe7362.png
To:
    544305.png
```

</details>

## sorttxt.py

Sort contents of a text file into ascending or descending order.

## timer.py

A Cli timer that prints like clock ticking.

## removelines.py

<details>
<summary>
Remove certain line from a text file.
</summary>

```python
rmdublicatelines(filepath)
# Remove duplicate lines from a (text) file.

rmlessthan(n, filepath)
# Remove lines with less than n (n = length of a character) numbers of characters from a file.
```

</details>

## sync_files.py

<details>
<summary>
Move all files from a directory tree to single directory.
</summary>

```text
From:
    src
    |---dir1
    |   |---file1
    |   |---file2
    |---dir2
    |   |---dir3
    |   |   |---dir3
    |   |   |   |---file3
    |   |   |   |---file4
    |---dir4
    |   |---file4
    |   |---file5
    |---file3
    |---file5

To:
    dist
    |---file1
    |---file2
    |---file3
    |---file4
    |---file5
```

</details>

---

\# That is all.
