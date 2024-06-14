# Abstract
 This write-up guides you through the step-by-step process on how to set up omnivory for those who are having a difficult time following the documentation, mainly beginners. To compile omniORBpy and generate it's
	python bindings we would also need the omniORB library

# Pre-Requisites
### Visual Studio Code
Any version of Visual Studio will do; this will be needed to compile the omniORB package, alternatively, you can use MinGW to compile omniORB, although it is not that documented.
Including **"Desktop Development for C++"** saves you the hassle of fixing your PATH for C++ development so this is **highly recommended** as shown below:

![Installation Screenshot](https://github.com/VladTemp27/omniORBpy-windows-installation/assets/85033864/486c80cc-489e-454b-995f-7988b05ef8ef)

### Cygwin
This will be used on top of the installed packages from Visual Studio, refer to [Cygwin site](https://x.cygwin.com/docs/ug/setup.html) to install cygwin. Ensure that you include "make" to your install of cygwin
shall you have problems retrieving the list of mirrors for the installer you can add [these](https://www.cygwin.com/mirrors.htm) as your mirror inside the installer using the GUI

After installation you would need to add the bin of cygwin to your PATH, the default path would typically be `C:/cygwin64/bin`. After adding this to your PATH it should look like the image below:

![Path Screenshot](https://github.com/VladTemp27/omniORBpy-windows-installation/assets/85033864/d20a7858-559d-487d-99cd-806775f9b882)


### omniORB & omniORBpy
We would need to download omniORB and omniORBpy this can be obtained [here](https://omniorb.sourceforge.io/)

# Steps
### Step 1. Extract the files
Create a directory under C:/ named `python-modules` and extract omniORB and omniORBpy zip here
![Directory screenshot](https://github.com/VladTemp27/omniORBpy-windows-installation/assets/85033864/7322a679-85ba-42b0-b45b-3d07aa73d6f7)
Moving forward the directory, `C:/python-modules/omniORB-4.3.2/` would now be referenced as $TOP<a href="#reference_1">[1]</a>

### Step 2. Move omniORBpy
Firstly we would need to remove the version number from "omniORBpy-4.3.2" it would be renamed to "omniORBpy". Now once the version number has been stripped from the directory name move this folder into `$TOP/src/lib`

### Step 3. Configure install variables

### Step 4. Compile omniORB

### Step 5. Compile omniORBpy

### Step 6. Use the python bindings

# References
[1] <a id="reference_1" href="https://www.omniorb-support.com/omnipy43/omniORBpy.pdf">omniORB Documentation</a> page 3 #Temporary citation to be revised later


