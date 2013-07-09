tracker
=======

An extremely modest script.

I like to store my date as plain text files and I like to sync it with bittorrentSync between my computers. This script is just used to keep a git repository of this data up to date.

# installation

1. put tracker somewhere in your path and `chmod +x` it
2. go to the directory in question and setup the git repo: `git init`
3. in the case of bittorrentSync you might want to do `echo '*.sync' >> .gitignore`
4. add `tracker path/to/directory` as cron job or whatever



