# bpmcalc
A bash script to calculate musical fractions of a bpm
Add this to your $path and type `bpm` into a terminal. You will be asked for a bpm and it will output the fractions useful for manually entering delay, reverb, and compression settings. 

Look at `echo $PATH` for places to save this to, or google how to add a directory to your $PATH if you want it somewhere else. You may need to make the script executable so you can do `cd /path/to/script/` and then `chmod +x bpm`. 


Example usage:

```
./bpm 
Enter bpm: 120
EVEN
1/1: 500 ms
1/2 250 ms
1/4 125 ms
1/6 83 ms
1/8 62 ms
1/10 50 ms
1/12 41 ms
1/14 35 ms
1/16 31 ms
ODD
1/3 166 ms
1/5 100 ms
1/7 71 ms
1/9 55 ms
1/11 45 ms
1/13 38 ms
1/15 33 ms
```
