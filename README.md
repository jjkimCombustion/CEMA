## CEMA implemented in OpenFOAM-6

## Installation

- Prepare a directory on your system, e.g., `yourDirectory`:

  ```bash
  mkdir ~/yourDirectory/
  cd ~/yourDirectory/
  ```

- Download source files using git:

  ```bash
  git clone https://github.com/jjkimCombustion/CEMA.git
  ```

- Specify the path of your directory to an environment variable

  ```bash
  echo "export LIB_CEMA_SRC=~/yourDirectory/src/" >> ~/.bashrc
  source ~/.bashrc
  ```

- To compile the library and applications, run the `Allwmake` script:

  ```bash
  cd ~/yourDirectory
  ./Allwmake
  ```
