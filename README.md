## CEMA implemented in OpenFOAM-6

## Installation

- Since the new library is developed based on OpenFOAM 6.0 in Linux operating systems, the complete installation of OpenFOAM 6.0 framework is required.

- Prepare a directory on your system, e.g., `yourDirectory`:

  ```bash
  mkdir ~/yourDirectory/
  cd ~/yourDirectory/
  ```

- Download source files using git:

  ```bash
  git clone https://github.com/jjkimCombustion/CEMA.git
  ```

- Specify the path of your `src` directory to an environment variable, `LIB_REALFLUID_SRC`. For example:

  ```bash
  echo "export LIB_CEMA_SRC=~/yourDirectory/src/" >> ~/.bashrc
  source ~/.bashrc
  ```

- To compile the library and applications, go to `realFluidThermophysicalModels` directory and run the `Allwmake` script:

  ```bash
  cd ~/yourDirectory
  ./Allwmake
  ```
