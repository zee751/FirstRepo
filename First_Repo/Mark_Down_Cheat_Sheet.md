
# **MARKDOWN CHEATSHEET**

# Table of Content

[1- Headings](#1--headings)\
[2- Block of Words](#2--block-of-words)\
[3- Line Break](#3--line-break)\
[4- Text face](#4--text-face)\
[5- Bullet Points](#5---bullet-points)\
[6- Page Break](#6--page-break)\
[7- Links & Hyperlinks](#7--links--hyperlinks)\
[8- Images With LInks](#8--images-files-folders-with-links)\
[9- Adding Block of Codes](#9--adding-code-or-block-code)\
[10- Adding Tables](#10--adding-table)\
[11- Install Extensions](#11--install-extensions)


# 1- Headings

How to give headings in MarkDown Files

simply by initiating a line with HashTag (#) and a Space after it.
# Heading 1
## Heading 2

Maximum 6 headinds are allowed in Markdown
Single (#) means First Heading and so on.

---
---
# 2- Block of Words

Block of words in Markdown start with Greater-Than (>) sign

> This is Special Block of words in Markdwon

> You need to hit Enter button Twice to start a new Block of Words

> If You want to connect more than one Block of Words You need to give line space between them with Greater-Than sign (>)

**For Example:-**

> This is the first line of Block of Words
>
> This is the second line of Block of Words

---
---
# 3- Line Break

There are 2 Methods for **Line Break** in **MarkDown**

1- Hit Enter Button Twice

Or

2- Use Back-Slash ( \ )

If you write Two Block of words with single Line Space it will consider it as One Line

**For Example:-**

- With Single Line Space:

    >This is the first block of words.
    >This is the second block of words.



- With Double Line Space:

        This is the firt block of words
        
        This is the second block of words

- With Black-Slash:

        This is the Second block of words

---
---
# 4- Text Face

> Text Face can also be changed in MarkDown just like MS Word
>
> - Itallic
> - Bold
> - Bold & Itallic


1- Single Astaric (* *) or Underscore ( _  _ ) is used for Itallic Text Face *Ittalic*,

2- Double Astaric (** **) or Double Underscores ( __ __ ) are used for Blod Text Face **Bold**

3- Triple Astaric (*** ***) or Triple Underscores ( ___  ___ ) are used for Ittalic + Blod Text Face ***Itallic + Bold***


---
---
# 5 - Bullet Points

Simply use Dash,Astaric or Plus sign with Space (-,* or +) for Bullet Points in Markdown

- Day-1
    - Day-1(a)

Numbering

Simply use Numbers with Space

    1- Day-1
        1- Day-1(a)


---
---
# 6- Page Break

There are 3 Methods used for Page in MarkDown.

1- use 3 Astarics ***

2- Use 3 Dashes ---

3- Use 3 Underscores ___

__Example:-__

* This is Page No. 1
___

* This is Page No. 2
***

* This is Page No. 3
---
* 
___
___
___
# 7- Links & Hyperlinks

- **Link**
    - To insert links in MarkDown write or paste the link in **Angle Brackets < Link >**

        **Example:-**

        <https://youtu.be/qJqAXjz-Rh4>


- **Hyperlinks**

    - To insert Hyperlink in MarkDown write the text in **Square Brackets [ Text ]** and write or paste the link in **Paranthesis ( Link )**

        **Example**

        [The Playlist of Python ka Chilla with Baba Ammar is here](https://www.youtube.com/playlist?list=PL9XvIvvVL50HVsu-Ao8NBr0UJSO8O6lBI)


- **Link or Hyperlink as Variable**
    
    - Links or Hyperlink can aslo be used as variable or key if it needed to be used again and again

    **Example**
            
            [Python]:https://www.youtube.com/playlist?list=PL9XvIvvVL50HVsu-Ao8NBr0UJSO8O6lBI

            Here [Codanics] is the key or        variable and link is it's value


[Python]:https://www.youtube.com/playlist?list=PL9XvIvvVL50HVsu-Ao8NBr0UJSO8O6lBI


The Complete playlist of **Python ka Chilla with Baba Ammar** is ([Here][Python])

___
___
___
# 8- Images, Files, Folders with links

- **File in Local Directory** :- Put file, folder, images etc in the same folder where MarkDown file is stored.

        Write any text in Square Brackets [Text] then write the exact name of file, folder or image in Paranthesis (File Name)

        Example:- [QR](qr.png)

        Put Excalamation Mark (!) before Sqaure Bracket [ ] to display the Image or File

Here is the Picture ***[PIC](Arsalan.jpeg)***


- **File with Online Link** :- Copy the Link of Image or File.

        Write any text in Square Brackets [Text] then paste the link of file, folder or image in Paranthesis (File Name)

        Example:- [Image](Link)

        Put Excalamation Mark (!) before Sqaure Bracket [ ] to display the Image or File        

Here is the Image **[IMG](https://www.google.com/search?q=codanic&sxsrf=ALiCzsbySpw5M5j9w5Xp9KLDk0Cca8WboA:1661688295493&source=lnms&tbm=isch&sa=X&ved=2ahUKEwigzNGkv-n5AhXAi_0HHZ4WB1kQ_AUoAnoECAEQBA&biw=1366&bih=635&dpr=1#imgrc=GRjVtCcWAILqOM)**

___
___
___

# 9- Adding Code or Block Code

- Use **Single Backtick (`)** to write code in string in MarkDown

- Color will be assigned to the string written inside the Backticks 

    **Example : -**

    To print a string use `print("Hello")`


- Use **Three Backticks(```)** to write code in block



    **Example : -**

    ```
    x = 2 + 3
    y = 4 + 5
    z = x + y
    ```

- Note :- write name of coding language after opening Three Backtikcs and code color will be changed according to the language

    **Example : -**

    
    ``` Python
    x = 2 + 3
    y = 4 + 5
    z = x + y
    ```
___
___
___

# 10- Adding Table

- To create table in MarkDown type between **Vertical Bars/Pipes (|)**

- On the second line put Dashes between **Vertical Bars/Pipes (|)** and it will create table

    **Example : -**

    | Species | Petal Length | Sepal Length |
    | :-: | :------: | :-------: |
    | Virginica | 18.2 | 19.2 |
    | Setosa | 15.1 | 17.2 |
    | Versicolor | 12.2 | 12.2 |
    | Virginica | 18.2 | 19.2 |
    | Setosa | 15.1 | 17.2 |
    | Versicolor | 12.2 | 12.2 |


- **Text Alignment in Table**

    - **Right : -** put a colon (:) on the right side of dashes (--) on second line of table

    - **Left : -** put a colon (:) on the left side of dashes (--) on second line of table

    - **Center : -** put a colon (:) on the both sides of dashes (--) on second line of table

    ____
    ____
    ____

    # 11- Install Extensions

    - 1- MarkDown All in One
    - 2- MarkDown Shortcuts
    - 3- MarkDown PDF
    - 4- MarkDownlint
