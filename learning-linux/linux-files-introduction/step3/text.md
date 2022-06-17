
Now we're getting serious! We can use the read.py as a python script to read from the file 'my-new-file/random-city.txt' if we so please.

<br>

### Solution
Check if the file is there using

```plain
ls ./random-city.txt
```{{exec}}

Now to create the python script we need to create the file for it to be run.

```plain
touch ./read.py
```{{exec}}

Now that we have a file to act as our script we can write in some simple code to read from the file.

```plain
nano ./read.py  
```{{exec}}

And inside the program we can use our tools to write 'file1 = open("random-city.txt","r+")' which will allow the python program to open the file and more specifically read.

On the following lines down it will read:
print("The random city named is: ")

print(file1.read())

print()

Now that the script itself is finished, we can then call the script using 'python read.py' and the city of your choosing that you wrote should be recalled promptly.
