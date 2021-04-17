# WebApp_C

### start a git repo
mkdir web-app && cd "$_" && git init

### add AISL as a submodule
git submodule add https://github.com/lowenware/aisl.git

### initialize and start your application
make -f aisl/Makefile quickstart

### delete Makefile
rm Makefile

### restart your application
make -f aisl/Makefile quickstart


