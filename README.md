# LibreOffice Conference 2021

This repository contains the files used in the talk "Python scripts in LibreOffice Calc using the ScriptForge library" given by Rafael Lima during the LibreOffice Conference 2021.

To run the examples in the Python file you need to use LibreOffice >= 7.2.

## Running macros from LibOCon_2021.py

The macros were created as user scripts. To be able to run them, the file LibOCon_2021.py needs to be placed into the LibreOffice user scripts folder in your machine.

On **Linux** machines, the folder is:

`/home/user/.config/4/user/Scripts/python/` (if it does not exist, create it)

On **Windows** machines, the folder is:

`%APPDATA%\LibreOffice\4\user\Scripts\python`

Read [this help page](https://help.libreoffice.org/latest/en-US/text/sbasic/python/python_locations.html) to learn more about where Python scripts are located.

## Data files used by LibOCon_2021.py

Some of the macros use the following data files:
- DataSource.ods
- JobData_v1.csv
- JobData_v2.csv

Download these files and take note of the folders into which they were saved. Before running the macros in LibOCon_2021.py, be sure to update the paths to these files in the scripts.

## Watch the Video from LibOCon 2021

The video presentation is available on my YouTube channel and can be watched through this [link](https://youtu.be/3xnO1prvgmk "YouTube link").

Soon the video will be made available on [TDF's YouTube channel](https://www.youtube.com/channel/UCQAClQkZEm2rkWvU5bvCAXQ).

## Download the Presentation File

The presentation file ([download ODP here](./Presentation.odp)) was created using LibreOffice Impress 7.2. Since it uses multiple columns in shapes, it will only open correctly if you use LibreOffice 7.2 or greater.

I also made the [PDF](./Presentation.pdf) available for those who are not using LibreOffice 7.2.
