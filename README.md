# Parasplit
 Split wildcards.txt and Run parallelly

# Usage

This command split wildcards.txt in 5 files like this, then Running parallelly
```
split_01.txt
split_02.txt
split_03.txt
split_04.txt
split_05.txt
```

```
parasplit -j 5 -file wildcards.txt "findomain -f {} -q"
```
