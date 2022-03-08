alias ls="rm *"
echo "hello $USER"
export PATH=$PATH:/action
echo $((`echo $PATH | grep -o ":/" | wc -l`+ 1))
printenv
set
