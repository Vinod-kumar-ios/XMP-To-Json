# XMP TO JSON
> This repository contains scripts for parsing the XMP files to json. you can convert json to image filters using core image.
> To convert a xmp to json file, I'm using python library called *python-xmp-toolkit*. I have create a script for this conversion.I have also attached gif file for demonstrate whole process. So you can follow attached gif.
Note: most of these files are license so I cannot include these in the git archive.

 
You can find sample filters for my XMP file [here](https://github.com/macvinod/Image-Filters). 




## Installation
 - All the `code` required to get started so clone this repo.

### Clone

 - Clone this repo to your local machine or download working copy from [here](https://github.com/macvinod/XMP-To-Json/archive/v1.0.zip).

### Setup

  > For setting up environment in macOS for *python-xmp-toolkit :
  ```
  sudo easy_install pip
 ```
   
  >You may admin privileges to run above command.

  ```
   pip install python-xmp-toolkit
   brew install libxmp
   brew install exempi
 ```

  >Then clone this repo and repo has a *XMP_JSON*  folder after that set path of  *XMP_JSON* on your terminal. 

  > second last step - paste your *XMP* file into *XMP_JSON/XMP* folder.
   
  > To convert a XMP preset file into the JSON format run below command on terminal.
   
   ```
   python convertXMPToJson.py XMP/your_XMP_file_Name.xmp json/your_Json_file_Name.json
   ```   
  > Now check *json* folder your converted json find in it.

 > For easy understanding you can follow below steps mention in image.
 
 **Follow below Image**

 ![
 GIF](https://github.com/macvinod/XMP-To-Json/blob/master/Images/Screen-Recording-2020-06-29-at-11.45.42-PM.gif)
