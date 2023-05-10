# nd101

These are encoded powershell commands I use to simulate second-stage malware activity. Useful for demonstrating to your leadership why allowing unrestricted powershell to access the internet from your enterprise is a bad idea. The first two lines will create a phony pdf in your current directory, and write a nonsense string into it. The last line pretends to open a python HTTP listener (it simply writes the command to your screen, doesn't actually execute it).

TmV3LUl0ZW0gLU5hbWUgJzczNzA2MTc3NjE3MjczNzU2MzZiNzMucGRmJw==

U2V0LUNvbnRlbnQgJy8vYWNlZ2l7Z3JhYmFsbHRoZWdvb2RpZXN9JyAtcGF0aCAuXDczNzA2MTc3NjE3MjczNzU2MzZiNzMucGRm

cG93ZXJzaGVsbCB7IFdyaXRlLUhvc3QgJ1NJTVVMQVRJTkcgRVhGSUw6ICBweXRob24zIC1tIGh0dHAuc2VydmVyIDgwMDAnIH0=


There is also a jpg file, "Avatar2", that contains an embedded text file with additional powershell commands that pop a useless notification window. They can be extracted with the steghide utility using the passkey "Avatar2". The plaintext commands were also pasted at the tail-end of the file.
