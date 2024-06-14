<h1>Abstract</h1>
<p>
 This write-up guides you through the step-by-step process on how to set up omnivory for those who are having a difficult time following the documentation, mainly beginners. To compile omniORBpy and generate it's
	python bindings we would also need the omniORB library
</p>

<h1>Pre-Requisites</h1>
<h3>Visual Studio Code</h3>
<p>Any version of Visual Studio will do; this will be needed to compile the omniORB package, alternatively, you can use MinGW to compile omniORB, although it is not that documented.
Including <b>"Desktop Development for C++"</b> saves you the hassle of fixing your PATH for C++ development so this is <b>highly recommended</b> as shown below:</p>
<img src="https://github.com/VladTemp27/omniORBpy-windows-installation/assets/85033864/486c80cc-489e-454b-995f-7988b05ef8ef"></img>

<h3>Cygwin</h3>
<p>This will be used on top of the installed packages from Visual Studio, refer to <a href="https://x.cygwin.com/docs/ug/setup.html">Cygwin site</a> to install cygwin. Ensure that you include "make" to your install of cygwin
shall you have problems retrieving the list of mirrors for the installer you can add <a href="https://www.cygwin.com/mirrors.html">these</a> as your mirror inside the installer using the GUI </p>
<p>After installation you would need to add the bin of cygwin to your PATH, the default path would typically be C:/cygwin64/bin. After adding this to your PATH it should look like the image below: </p>

<img src="https://github.com/VladTemp27/omniORBpy-windows-installation/assets/85033864/d20a7858-559d-487d-99cd-806775f9b882"></img>


<h3>omniORB & omniORBpy</h3>
<p>We would need to download omniORB and omniORBpy this can be obtained <a href="https://omniorb.sourceforge.io/">here</a></p>

<h1>Steps</h1>
<h3>Step 1. Extract the files</h3>
<p>Create a directory under C:/ named "python-modules" and extract omniORB and omniORBpy zip here</p>
<img src="https://github.com/VladTemp27/omniORBpy-windows-installation/assets/85033864/7322a679-85ba-42b0-b45b-3d07aa73d6f7"></img>


