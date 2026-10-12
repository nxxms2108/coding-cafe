pwd prints the path of your directory, for me it was /Users/nandinikoneti
ls -Force shows a more detailed, timeline based output than just plain ls
The mode cl=olumn tells me what kind of item it is and shows some of its properties.
It works because PowerShell starts from my current folder and follows the folders named in the command. coding-cafe\week02 is a relative path because it does not begin from a drive such as C:\.
The first mv command moved README-backup.md into the week01 folder. The second one renamed it to old-readme.md.
There were 14 folders on my PATH
My Python was located at C:\Users\Nandini\AppData\Local\Programs\Python\Python313\python.exe
No, our paths were different. 
It said, The term 'pyton' is not recognized as the name of a cmdlet, function, script file, or operable program.
The lab expects .venv to be hidden and therefore visible with ls -Force.
(.venv) appeared at the beginning of the prompt. 
It changed to C:\Users\Nandini\coding-cafe\.venv\Scripts\python.exe. 
The second list contained requests. It also contained its required packages.
It points back to C:\Users\Nandini\AppData\Local\Programs\Python\Python313\python.exe.
The -Recurse flag makes the command look inside the selected folder and all of its subfolders. 
Ctrl + C interrupted the current Python action and returned a KeyboardInterrupt, but Python stayed open. Ctrl + Z followed by Enter sent an end-of-input signal and exited Python.