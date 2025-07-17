Challenge Name: Obedient Cat
Platform: picoCTF
Category: General Skills
Difficulty: Easy

Description:
This file has a flag in plain sight (aka "in the clear"). Download the file and find it.

Steps to solve:

Download the file provided in the challenge. It is named cat.

Open a terminal and check what kind of file it is. Use this command:

file cat

It should return something like: "ASCII text".

Now display the contents of the file. You can use:

cat cat

or

less cat

The flag is visible directly inside the file. No need for decoding or advanced techniques.

Flag:
picoCTF{s4n1ty_v3r1f13d_2aa22101}

Conclusion:
This is a very basic challenge meant to warm up. It teaches us to always check the obvious first before overthinking a problem.
