# STM32_BluePIill_StepperMotor_Proteus
STM32CubeIDE 1.10.1, Proteus 8.13

Stepper Motor with using driver ULN2003A
Not use Arduino Lib

Library Installation :
Download or clone stm32 bluepill for proteus repository.
Open downloaded folder and copy BLUEPILL.IDX and BLUEPILL.LIB file from this folder.
Now open Proteus LIBRARY folder (check your proteus installation folder)
C:\Program Files (x86)\Labcenter Electronics\Proteus 8 Professional\DATA\LIBRARY

Now run proteus and open component Library.
Search for "STM32" or "BLUEPILL" and you can see your installed bluepill library.
Source code (Hex) :
Note: Select board as : STM32F103C6 in STM32CUBEMX or in STM32CUBEIDE. Only code compiled for STM32F103C6 is supported with this library.
Command to create hex file in CubeIDE:
arm-none-eabi-objcopy -O ihex ${ProjName}.elf ${ProjName}.hex

Програма для керування кроковим двигуном з використанням драйверу ULN2003A
Перед початком роботи потрібно встановити необхідні бібліотеки BLUEPILL.IDX та BLUEPILL.LIB для Proteus за шляхом
C:\Program Files (x86)\Labcenter Electronics\Proteus 8 Professional\DATA\LIBRARY
При створенні проекту у CubeIDE необхідно обрати МК STM32F103C6
Для генерування hex файлу потрібно в налаштуваннях IDE додати команду
arm-none-eabi-objcopy -O ihex ${ProjName}.elf ${ProjName}.hex
![StepperProt](https://user-images.githubusercontent.com/98404943/188277396-127f56c2-7864-47a0-8906-980f6c1ff159.png)
![StepperCubeMX](https://user-images.githubusercontent.com/98404943/188277400-b139e615-d594-4a3b-93b7-dd6aa69750ef.png)
