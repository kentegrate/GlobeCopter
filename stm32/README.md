## Build on eclipse

* First, prepare your environment. http://www.carminenoviello.com/2014/12/28/setting-gcceclipse-toolchain-stm32nucleo-part-1/ may be usable.
* Run Eclipse, File > New > Project > Makefile Project with Existing Code
* Fill name, code location
* Select 'Ac6 STM32 MCU GCC' for 'Toolchain for Indexer Settings'
* If you don't have arm-none-eabi-gcc in PATH, open project properties
  * C/C++ Build > Environment > Add
  * Name: BIN_PATH_PREFIX
  * Value: \<your arm-none-eabi-gcc path\> (INCLUDING TRAILING SLASH)
