# logs_in_tar
Simple bash script to put logs inside a tar archive

# For better perfomance
After cloning or downloading the bash file, just make the next command:
mv mf_timex /.local/bin/mf_timex
Or create a new directory with and add it to the PATH:
mkdir ~/scripts
Next line goes into ~/.bashrc or ~/.zshrc:
export PATH="$HOME/scripts:$PATH"
Then move mf_timex there:
mv mf_timex ~/scripts

# How to use it
After moving the file to the proper directory, you are ready to use it.
It accepts two parameters, first one is mandatory, where are we going to compress the files from, the other one, where are we going to store it (optional).

Finally, the script is going to make the work and we have our logs in .tar.gz archive.

