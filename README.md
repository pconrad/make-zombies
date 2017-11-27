# make-zombies

Sample code to work with fork/exec and zombies 

# Zombies

The zombie.c file is directly from the [Wikipedia page for Zombie
processes](https://en.wikipedia.org/wiki/Zombie_process) as retrieved
on 11/27/2017.

To see the zombie processes:

(1) In one window, use:

```
while true; do clear; ps -al; sleep 1; done
```

Or, if you have it on your system:

```
watch ps -al
```

This keeps an eye on the list of processes

(2) In the other window, run `./zombie`

You should see the Zombie processes appear and then go away.


