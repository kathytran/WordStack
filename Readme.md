# Word Stack

This is a single-user word game called WordStack. The idea of the game is to try to separate out two words of the same length whose letters have been scrambled (but the order of the letters has been preserved). For example, 'cat' and 'dog' might get scrambled in many ways but 'c' will always come before 'a' and 'a' will always come before 't'. Similarly, 'd' will always come before 'o' and 'o' will always come before 'g'. So we get permutations like:

* cdaotg
* cadogt
* catdog
* dogcat
* dcoagt
* ...

But never 'actdog' ('a' is out of order) or 'coatdg' ('o' out of order).
