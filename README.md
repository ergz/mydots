tool to manage all my dot files across both windows and linux machines

the goal is that I run this script and it will detect either windows or linux
and just do the right thing. 

There will be three folders:

- linux - where linux specific things will go
- windows - where windows specific things go 
- global - where configs for both are stored

What should happen:

```
python mydots.py sync # this will sync with the remote repo
python mydots.py sync --just nvim # this will sync just the nvim configs
python mydots.py sync 
```
