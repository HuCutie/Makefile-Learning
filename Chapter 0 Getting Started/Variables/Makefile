files = file1 file2
x = dude

all: some_file
	echo $(x)
	echo ${x}

	echo $x
# Bad example, but works

some_file: $(files)
	echo "Look at this variable: " $(files)
	touch some_file

file1:
	touch file1
file2:
	touch file2

clean:
	rm -f file1 file2 some_file