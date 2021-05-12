Python code for import csv file data and then save into CPE KMUTT Knowledge Management.\
There are some example of initial file in this PR and you can change csv file to another.

When you started, you should set url and login to get token before save data to km.\
Then if you want to use save command, set `query=True` to execute that code.\
This method I (TK) used to prevent wrong execute cell. And don't forget to set `query=False` back.\

In addition, you set use `query=False` and debug data inside.