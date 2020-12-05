# PC Remote Connection Through Python:

## Installing Python
I asume you already have python installed, but just incase what you can do is go to https://www.python.org/ and download the latest the version.

## Setting it up
You will install the files.

The main `main.py` file will contain something saying, `host = "192.168.1.2"` There is a high chance that is your default host but if it doesn't work you can get your host by typing
`ipconfig` in command prompt and looking at your ipv4. Set the `"192.168.1.2"` to whatever the ipv4 is.

The `client.py` file is what your client runs. (Client must have python installed.)

## Connecting

First run your `launcher.bat` and that will start the host. Then your client must run the `client.py` file to connect

Type `list` in the host to view all active connections. It will list the connected persons ip and index next to it.
If the index is 0 you can type `link 0` and it will connect to their computer. You will be able to run shell commands
and sudo commands. When you want exit their computer type `quit`.

Let's say that there is another computer connected and their index is 1, type `link 1` and you are connected to their computer.
