## Object & Array iterations

|                           | Object                            | Array                                             |
| -------------             |:-------------                     |:-----                                             |
| Object.keys               | Returns an array of keys          | Returns an array of index                         |
| Object.values             | Returns an array of values        |   Returns an array of values/items                |
| for (var i **in** obj)    | Iteraable by keys                 |    Iterable by index                              |
| for (var i **of** obj)    |  **`Error`**                      |    Iterable by values/items                       |
| { ...varialble }          |  returns similar object           |    Returns object contining index:vale key:pair   |
| [ ...variable ]           |  **`Error`**                      |    Returns similar array                          |