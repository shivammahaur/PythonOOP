# PythonOOP

[Advanced python OOP by Ardit Sulce](https://www.udemy.com/course/the-python-pro-course/)

This is a learning repository and will be constantly updated as i complete the course.

---

## App 01: Geometery Game

This app is made in jupyter notebooks using *google colab*.

[Colab](https://colab.research.google.com/drive/12vZFLA2pCE3zWKKs0mtR6ybIsWQDqA30?usp=sharing)

Basically an intro to python classes and class structure.

### Learnings

- Python has 9 things you work with:

    ```python
    a = 4
    b = 5
    c = [6, 7]

    d = "Hi"
    "Hello"

    def area(x):
        return x**2

    area(3)
    ```

    From the above code :-

    | Syntax | Description |
    | ------ | ----------- |
    | Objects | 4, 5, [6, 7], 6, 7, "Hello" |
    | Identifiers | a, b, c, d, area, x |
    | Operators | **, *, -, +, / etc. |
    | Delimiters | =, " ( ) : [ ] |
    | Keywords | def, return |
    | Comments | # Code starting with hash |
    | Blank Lines | As the name suggests |
    | White Spaces | -do- |
    | Indentation | -do- |

- **What is a python object?**
    
    ```python
    inty = 5
    listy = [6, 7]

    stringy = "Hi"

    import folium
    azores = folium.folium.Map(location = (38, -27), zoom_start = 6)
    ```

    We will use above code example to learn that.

    Objects in the above code : 5, [6, 7], 6, 7, "Hi", folium.folium.Map(location = (38, -27), zoom_start = 6), 38, -27, 6

    All objects have a type : 

    | Object | Type |
    | ------ | ---- |
    | 5 | int |
    | [6, 7] | list |
    | "Hi" | string |
    | Map | folium.folium.Map |

    ```python
    int(x = 5)
    #5
    list((6, 7))
    #[6,7]
    ```

    Above all the declarations are the same as just writing the number or the list itself. Same goes for strings and other objects in python.

---