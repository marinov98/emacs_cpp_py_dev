# Emacs guide MY WAY

# I was inspired to write this after I finished configuring my emacs file to write C++, Python, and JavaScript code as well as take notes in Org mode and write LaTex

## please note: 
I have used emacs ONLY on MacOS and Ubuntu so my knowledge is limited
NOTE: in order to for brew install {package name} make sure your mac has brew installed

## Contains my .emacs file 

## Usages:
  C++,
  Python,
  Javascript,
  HTML/CSS,
  GIT
  
## Necesities before using all Packages in my .emacs file (I put sections so that you can pick only the ones you need) :

  ### C++
  
  ####  gcc
  - Windows (MinGw)
  - Ubuntu (sudo apt-get install gcc)
  - MacOS (brew install gcc)
  #### clang
  - Ubuntu (sudo apt-get install clang)
  - MacOS (brew install clang)
  #### libclang
  - Ubuntu (sudo apt-get install libclang-dev)
  - MacOS should already have it
  #### CMake
  - Ubuntu (sudo apt-get install cmake)
  - MacOS (brew install cmake)
  
  ### Python
  
  #### virtualenv
  - Ubuntu (sudo apt-get install virtualenv)
  - MacOS (brew install virtualenv)
  
  #### Pip (allows you to use pip install in your terminal)
  - Ubuntu (sudo apt-get install python-pip)
  - MacOS (brew install pip)
  ##### Packages to install with Pip
  - Rope: pip install rope (refactoring library)
  - Jedi: pip install jedi (intellisense)
  - flake: pip install flake8 (code checks)
  - autopep: pip install autopep8 (Pep8 formatting) 
  - yapf: pip install yapf (Formatting)
  
  ### JavaScript 
  
  #### Before going to Nodejs
  
  ##### install curl (Necessary for Ubuntu only!)
  -sudo apt-get install curl
  
  ##### install npm
  - Ubuntu: sudo apt-get install npm
  - MacOS: brew install npm
  
  #### Nodejs
  - look up how to install nodejs
  - After installing node,  install eslint (npm install eslint)
  
  #### GIT
  ### search up how to set up git on your Operating System AFTER installing it
  - Ubuntu (sudo apt-get install git)
   
  #### Bonus
  ##### Auctex (creating latex files) 
  - Ubuntu: sudo apt-get install auctex
  - MacOS: brew install auctex
  ##### Cask (for using the dashboard package)
  - MacOS: brew install cask
  - Ubuntu: curl -fsSL https://raw.githubusercontent.com/cask/cask/master/go | python
   
