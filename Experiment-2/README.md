Aim: To install a C compiler in a virtual machine created using VirtualBox and execute a simple C program.


Procedure

1. Open VirtualBox and import the provided Ubuntu .ova file using File → Import Appliance.

2. Browse and select the ubuntu_gt6.ova file and complete the import process.

3. Open Settings → USB and select USB 1.1, then start the Ubuntu virtual machine.

4. Open the Terminal in Ubuntu and navigate to the required directory.

5. Create a C program using:
gedit hello.c

6. Write the simple C program and save the file.

6. Compile the program using:
gcc hello.c

7. Execute the compiled program using:
./a.out

8. Verify the displayed output.