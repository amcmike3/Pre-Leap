
#### `touch` *create new file* and `mkdir`- *Make Directory (create a new folder)*

* To make a new folder use the `mkdir` command.

  * In your _Documents_, create a folder called `notes`

    ```bash
    cd ~/Documents

    mkdir notes

    ls
    ```

* To navigate to this location I would have to go from my HOME to `Documents` to `notes`.


* If I wanted to go from `Home` to `notes` directly, you can chain the paths into one `cd` command, ```cd ~/Documents/notes```.

<hr />


#### `touch`- *(create a file)*

* Lets navigate to our notes folder and make some new, empty files using the `touch` command.

  ```bash

  cd ~/Documents/notes

  touch blah.txt

  touch blah.java

  touch blah.py

  ls
  ```


<hr>

[Prev](cd-ls.md) | [Up](README.md) | [Next](mv-cp.md)