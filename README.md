# scan-radar-Lua
scan radar code for stormworks made in Lua (first repository)


This is the beginning of my first github repository

Its main usecases are version control as well as a way to share my knowledge

---

The scan radar project will enable the sorting of unknown contacts, such that an easy to use table of known targets with their respective ID is created.

The (planned) features are:

- creation of new targets - (done)
- updating of known targets - (done)
- deletion of old targets after a set amount of ticks - (done)
- filtering the noise target data induced by the new radar component
- calculation each known target velocity vector
- assigning a threat level to each target based on distance and closing rate or velocity vector
- outputting the highest threat targets as well as their threat level
- outputting an alarm boolean if an attack is detected
- drawing known targets on a map for situational awareness (GUI)
