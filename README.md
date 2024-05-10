I was making a short script to upload stuff to pixeldrain and discovered pdup as I was looking at how people use the api. Reused some code from pdup but most of this is written by me. Unlike pdup this script uses the even newer api™, which can upload files to a list with -l

### ----OLD----

Hello, I made a little Bash script that you can use to upload files to https://pixeldrain.com/ from the terminal. This is very useful for showing log files to developers or making quick backups of remote files through SSH.

To install it you can execute this command:

    sudo wget https://raw.githubusercontent.com/Fornax96/pdup/master/pdup -O "/usr/local/bin/pdup"; sudo chmod +x "/usr/local/bin/pdup"

Explanation: The wget command downloads the script from github and saves it to /usr/local/bin/pdup so you can run it from the terminal. Then chmod makes it executable

Then you can upload files from anywhere in the system using

    pdup file.txt

If you want to uninstall pdup you can run

    sudo rm "/usr/local/bin/pdup"

Be careful for typos! You don't want to accidentally remove your [/usr](https://github.com/MrMEEE/bumblebee-Old-and-abbandoned/issues/123) ;)
