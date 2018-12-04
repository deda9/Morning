# Morning
In every morning I always need to check slack and work/persoanl emails while having my coffee, so instead each time open it manually, this is a tiny script do that work.


### Setup
1- move the morning.sh into your hope
```Shell 
mv morning.sh $HOME
```

2- Update the `.bash_profile` or `.zshrc` where you add an alias to run the script by appending to the file
```Shell 
echo " 
alias morning="./morning.sh"
alias mor="./morning.sh"
" >> .zshrc
```

3- to run the script, just type in your Terminal `mor`or `morning`

### TODO
- Check if the time is working time or not to open.

