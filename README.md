# GitBash Config

When you install GitBash it can sometimes pollute the terminal with random system denotations such as MINGW64 and reveal system names etc, if you take the shell file in this repo and replace it with the one at this location:

> C:\Program Files\Git\etc\profile.d

This removes any and all of the system information from the terminal, changes the username reference to green and any directions to purple (I think this looks nicer, but feel to change the colors (lines 14&16, change the value of 32m to any other valid number for a different color choice).

Also note line 15 specifically:

> 	PS1="$PS1"' atlas '             # user@host<space>
  
  Feel free to replace atlas with your chosen name, this overwrites any C: username within GitBash
