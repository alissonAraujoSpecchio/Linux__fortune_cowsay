# Linux__fortune_cowsay
How to use fortune and cowsay in linux
MODT = "Message of the day"

To install them (Ubuntu):

```
sudo apt install cowsay fortune-mod
```

To show the motd, type "fortune" and press enter:

```
$ fortune
An honest tale speeds best being plainly told.
		-- William Shakespeare, "Henry VI"
```

Now to show a cow saying the message, use "fortune | cowsay":

```
$ fortune | cowsay
 _____________________________________
/ Chicken Little only has to be right \
\ once.                               /
 -------------------------------------
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||

```

If you want another animal saying, use the "-f" parameter:

```
$ fortune | cowsay -f dragon
 _________________________________________
/ Well, anyway, I was reading this James  \
| Bond book, and right away I realized    |
| that like most books, it had too many   |
| words. The plot was the same one that   |
| all James Bond books have: An evil      |
| person tries to blow up the world, but  |
| James Bond kills him and his henchmen   |
| and makes love to several attractive    |
| women. There, that's it: 24 words. But  |
| the guy who wrote the book took         |
| *thousands* of words to say it.         |
|                                         |
| Or consider "The Brothers Karamazov",   |
| by the famous Russian alcoholic Fyodor  |
| Dostoyevsky. It's about these two       |
| brothers who kill their father. Or      |
| maybe only one of them kills the        |
| father. It's impossible to tell because |
| what they mostly do is talk for nearly  |
| a thousand pages. If all Russians talk  |
| as much as the Karamazovs did, I don't  |
| see how they found time to become a     |
| major world power.                      |
|                                         |
| I'm told that Dostoyevsky wrote "The    |
| Brothers Karamazov" to raise the        |
| question of whether there is a God. So  |
| why didn't he just come right out and   |
| say: "Is there a God? It sure beats the |
| heck out of me."                        |
|                                         |
| Other famous works could easily have    |
| been summarized in a few words:         |
|                                         |
| * "Moby Dick" -- Don't mess around with |
| large whales because they symbolize     |
|                                         |
| nature and will kill you. * "A Tale of  |
| Two Cities" -- French people are crazy. |
|                                         |
\ -- Dave Barry                           /
 -----------------------------------------
      \                    / \  //\
       \    |\___/|      /   \//  \\
            /0  0  \__  /    //  | \ \    
           /     /  \/_/    //   |  \  \  
           @_^_@'/   \/_   //    |   \   \ 
           //_^_/     \/_ //     |    \    \
        ( //) |        \///      |     \     \
      ( / /) _|_ /   )  //       |      \     _\
    ( // /) '/,_ _ _/  ( ; -.    |    _ _\.-~        .-~~~^-.
  (( / / )) ,-{        _      `-.|.-~-.           .~         `.
 (( // / ))  '/\      /                 ~-. _ .-~      .-~^-.  \
 (( /// ))      `.   {            }                   /      \  \
  (( / ))     .----~-.\        \-'                 .~         \  `. \^-.
             ///.----..>        \             _ -~             `.  ^-`  ^-_
               ///-._ _ _ _ _ _ _}^ - - - - ~                     ~-- ,.-~
                                                                  /.-~
```

List of parameter are in this path, go check it out!

```
ls /usr/share/cowsay/cows -l
total 188
-rw-r--r-- 1 root root  115 out 28  2019 apt.cow
-rw-r--r-- 1 root root  310 ago 14  1999 bud-frogs.cow
-rw-r--r-- 1 root root  123 ago 14  1999 bunny.cow
-rw-r--r-- 1 root root 1127 out 28  2019 calvin.cow
-rw-r--r-- 1 root root  480 ago 14  1999 cheese.cow
-rw-r--r-- 1 root root  181 out 28  2019 cock.cow
-rw-r--r-- 1 root root  230 ago 14  1999 cower.cow
-rw-r--r-- 1 root root  569 ago 14  1999 daemon.cow
-rw-r--r-- 1 root root  175 ago 14  1999 default.cow
-rw-r--r-- 1 root root 1284 nov  3  1999 dragon-and-cow.cow
-rw-r--r-- 1 root root 1000 ago 14  1999 dragon.cow
-rw-r--r-- 1 root root  132 out 28  2019 duck.cow
-rw-r--r-- 1 root root  284 ago 14  1999 elephant.cow
-rw-r--r-- 1 root root  357 out 28  2019 elephant-in-snake.cow
-rw-r--r-- 1 root root  585 ago 14  1999 eyes.cow
-rw-r--r-- 1 root root  490 ago 14  1999 flaming-sheep.cow
-rw-r--r-- 1 root root  540 out 28  2019 fox.cow
-rw-r--r-- 1 root root 1018 ago 14  1999 ghostbusters.cow
-rw-r--r-- 1 root root 1054 out 28  2019 gnu.cow
-rw-r--r-- 1 root root  126 ago 14  1999 hellokitty.cow
-rw-r--r-- 1 root root  687 out 28  2019 kangaroo.cow
-rw-r--r-- 1 root root  637 ago 14  1999 kiss.cow
-rw-r--r-- 1 root root  162 ago 14  1999 koala.cow
-rw-r--r-- 1 root root  406 ago 14  1999 kosh.cow
-rw-r--r-- 1 root root  226 out 28  2019 luke-koala.cow
-rw-r--r-- 1 root root  814 out 28  2019 mech-and-cow.cow
-rw-r--r-- 1 root root  439 ago 14  1999 milk.cow
-rw-r--r-- 1 root root  249 out 28  2019 moofasa.cow
-rw-r--r-- 1 root root  203 ago 14  1999 moose.cow
-rw-r--r-- 1 root root 1623 out 28  2019 pony.cow
-rw-r--r-- 1 root root  305 out 28  2019 pony-smaller.cow
-rw-r--r-- 1 root root  252 ago 14  1999 ren.cow
-rw-r--r-- 1 root root  234 ago 14  1999 sheep.cow
-rw-r--r-- 1 root root  433 ago 14  1999 skeleton.cow
-rw-r--r-- 1 root root  283 out 28  2019 snowman.cow
-rw-r--r-- 1 root root  854 ago 14  1999 stegosaurus.cow
-rw-r--r-- 1 root root  364 ago 14  1999 stimpy.cow
-rw-r--r-- 1 root root  229 out 28  2019 suse.cow
-rw-r--r-- 1 root root  293 ago 14  1999 three-eyes.cow
-rw-r--r-- 1 root root 1302 ago 14  1999 turkey.cow
-rw-r--r-- 1 root root 1105 ago 14  1999 turtle.cow
-rw-r--r-- 1 root root  215 nov 12  1999 tux.cow
-rw-r--r-- 1 root root 1718 out 28  2019 unipony.cow
-rw-r--r-- 1 root root  365 out 28  2019 unipony-smaller.cow
-rw-r--r-- 1 root root  279 ago 14  1999 vader.cow
-rw-r--r-- 1 root root  213 ago 14  1999 vader-koala.cow
-rw-r--r-- 1 root root  248 ago 14  1999 www.cow
```
