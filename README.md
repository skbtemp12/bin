 NVIDIA Xavier - Maximizing Performance document.documentElement.className = document.documentElement.className.replace( /(^|\\s)client-nojs(\\s|$)/, "$1client-js$2" ); (window.RLQ=window.RLQ||\[\]).push(function(){mw.config.set({"wgCanonicalNamespace":"","wgCanonicalSpecialPageName":false,"wgNamespaceNumber":0,"wgPageName":"Xavier/JetPack\_5.0.2/Performance\_Tuning/Maximizing\_Performance","wgTitle":"Xavier/JetPack 5.0.2/Performance Tuning/Maximizing Performance","wgCurRevisionId":43240,"wgRevisionId":43240,"wgArticleId":2011,"wgIsArticle":true,"wgIsRedirect":false,"wgAction":"view","wgUserName":null,"wgUserGroups":\["\*"\],"wgCategories":\["Pages using sidebar with the child parameter","NVIDIA Xavier","Jetson"\],"wgBreakFrames":false,"wgPageContentLanguage":"en","wgPageContentModel":"wikitext","wgSeparatorTransformTable":\["",""\],"wgDigitTransformTable":\["",""\],"wgDefaultDateFormat":"dmy","wgMonthNames":\["","January","February","March","April","May","June","July","August","September","October","November","December"\],"wgMonthNamesShort":\["","Jan","Feb","Mar","Apr","May","Jun","Jul","Aug","Sep","Oct","Nov","Dec"\],"wgRelevantPageName":"Xavier/JetPack\_5.0.2/Performance\_Tuning/Maximizing\_Performance","wgRelevantArticleId":2011,"wgRequestId":"Y4cz0o\_FlTTaVW16jThZMAAAAPU","wgIsProbablyEditable":false,"wgRelevantPageIsProbablyEditable":false,"wgRestrictionEdit":\[\],"wgRestrictionMove":\[\],"wgWikiEditorEnabledModules":\[\],"wgCategoryTreePageCategoryOptions":"{\\"mode\\":0,\\"hideprefix\\":20,\\"showcount\\":true,\\"namespaces\\":false}","wgSmjUseCdn":true,"wgSmjUseChem":true,"wgSmjDisplayMath":\[\],"wgSmjExtraInlineMath":\[\],"wgSmjScale":1,"wgSmjEnableMenu":true,"wgSmjDisplayAlign":"left"});mw.loader.state({"site.styles":"ready","noscript":"ready","user.styles":"ready","user":"ready","user.options":"ready","user.tokens":"loading","ext.pygments":"ready","ext.CookieWarning.styles":"ready","mediawiki.legacy.shared":"ready","mediawiki.legacy.commonPrint":"ready","mediawiki.sectionAnchor":"ready","mediawiki.skinning.interface":"ready","skins.vector.styles":"ready"});mw.loader.implement("user.tokens@1t09xzz",function($,jQuery,require,module){/\*@nomin\*/mw.user.tokens.set({"editToken":"+\\\\","patrolToken":"+\\\\","watchToken":"+\\\\","csrfToken":"+\\\\"}); });mw.loader.load(\["site","mediawiki.page.startup","mediawiki.user","mediawiki.hidpi","mediawiki.page.ready","mediawiki.toc","mediawiki.searchSuggest","ext.CookieWarning","skins.vector.js"\]);});               {"@context" : "http://schema.org","name":"NVIDIA Xavier - Maximizing Performance","headline":"NVIDIA Xavier - Maximizing Performance","description":"Jetson Xavier is a powerful platform from NVIDIA supported by RidgeRun Engineering",}   

Cookies help us deliver our services. By using our services, you agree to our use of cookies.

NVIDIA Jetson Xavier - Maximizing Performance
=============================================

From RidgeRun Developer Connection

< [Xavier](/wiki/index.php/Xavier "Xavier")‎ | [JetPack 5.0.2](/wiki/index.php/Xavier/JetPack_5.0.2 "Xavier/JetPack 5.0.2")‎ | [Performance Tuning](/wiki/index.php/Xavier/JetPack_5.0.2/Performance_Tuning "Xavier/JetPack 5.0.2/Performance Tuning")

Jump to: [navigation](#mw-head), [search](#p-search)

  

  
  

[Previous: JetPack 5.0.2‎/Performance Tuning/Tuning Power](/wiki/index.php/Xavier/JetPack_5.0.2/Performance_Tuning/Tuning_Power "Xavier/JetPack 5.0.2/Performance Tuning/Tuning Power")

[Index](/wiki/index.php/Xavier "Xavier")

[Next: Development in the Board](/wiki/index.php/Xavier/Development_in_the_Board "Xavier/Development in the Board")

  

[NVIDIA®Jetson Xavier™](/wiki/index.php/Xavier "Xavier")

![Xavier](/wiki/images/thumb/5/5c/NVLogo_2D.png/150px-NVLogo_2D.png "Xavier")

[Introduction](/wiki/index.php/Xavier/Introduction "Xavier/Introduction")

[SoM Overview](/wiki/index.php/Xavier/Introduction/SoM_Overview "Xavier/Introduction/SoM Overview")

[Carrier Boards](/wiki/index.php/Xavier/Introduction/Carrier_Boards "Xavier/Introduction/Carrier Boards")

*   [NVIDIA Xavier Developer Kit](/wiki/index.php/Xavier/Introduction/Carrier_Boards/Nvidia_developer_kit "Xavier/Introduction/Carrier Boards/Nvidia developer kit")
*   [Connect Tech Rogue](/wiki/index.php/Xavier/Introduction/Carrier_Boards/Connect_Tech_Rogue "Xavier/Introduction/Carrier Boards/Connect Tech Rogue")
*   [Connect Tech Mimic](/wiki/index.php/Xavier/Introduction/Carrier_Boards/Connect_Tech_Mimic "Xavier/Introduction/Carrier Boards/Connect Tech Mimic")

[Software Support](/wiki/index.php/Xavier/Introduction/Software_Support "Xavier/Introduction/Software Support")

*   [NVIDIA JetPack](/wiki/index.php/Xavier/Introduction/Software_Support/NVIDIA_JetPack "Xavier/Introduction/Software Support/NVIDIA JetPack")

[JetPack 5.0.2](/wiki/index.php/Xavier/JetPack_4.1 "Xavier/JetPack 4.1")

[Getting Started](/wiki/index.php/Xavier/JetPack_4.1/Getting_Started "Xavier/JetPack 4.1/Getting Started")

*   [Installing JetPack](/wiki/index.php/Xavier/JetPack_4.1/Getting_Started/Installing_Jetpack "Xavier/JetPack 4.1/Getting Started/Installing Jetpack")
*   [Flashing the board with GUI installer](/wiki/index.php/Xavier/JetPack_4.1/Getting_Started/Wizard_Flashing "Xavier/JetPack 4.1/Getting Started/Wizard Flashing")
*   [JetPack Components](/wiki/index.php/Xavier/JetPack_4.1/Getting_Started/Components "Xavier/JetPack 4.1/Getting Started/Components")

[Compiling Source Code](/wiki/index.php/Xavier/JetPack_4.1/Compiling_Code "Xavier/JetPack 4.1/Compiling Code")

[Flashing the Board from Cmdline](/wiki/index.php/Xavier/JetPack_4.1/Flashing_Board "Xavier/JetPack 4.1/Flashing Board")

[Performance Tuning](/wiki/index.php/Xavier/JetPack_4.1/Performance_Tuning "Xavier/JetPack 4.1/Performance Tuning")

*   [Evaluating Performance](/wiki/index.php/Xavier/JetPack_4.1/Performance_Tuning/Evaluating_Performance "Xavier/JetPack 4.1/Performance Tuning/Evaluating Performance")
*   [Set Values Manually](/wiki/index.php/Xavier/JetPack_4.1/Performance_Tuning/Set_Values_Manually "Xavier/JetPack 4.1/Performance Tuning/Set Values Manually")
*   [Tuning Power](/wiki/index.php/Xavier/JetPack_4.1/Performance_Tuning/Tuning_Power "Xavier/JetPack 4.1/Performance Tuning/Tuning Power")
*   [Maximizing Performance](/wiki/index.php/Xavier/JetPack_4.1/Performance_Tuning/Maximizing_Performance "Xavier/JetPack 4.1/Performance Tuning/Maximizing Performance")

[Development in the Board](/wiki/index.php/Xavier/Development_in_the_Board "Xavier/Development in the Board")

[Getting into the Board](/wiki/index.php/Xavier/In_Board/Getting_into_the_Board "Xavier/In Board/Getting into the Board")

*   [Using Serial Console](/wiki/index.php/Xavier/In_Board/Getting_in_Board/Serial_Console "Xavier/In Board/Getting in Board/Serial Console")
*   [Using SSH](/wiki/index.php/Xavier/In_Board/Getting_in_Board/SSH "Xavier/In Board/Getting in Board/SSH")
*   [Using Ubuntu Login](/wiki/index.php/Xavier/In_Board/Getting_in_Board/Ubuntu "Xavier/In Board/Getting in Board/Ubuntu")

[Installing Packages](/wiki/index.php/Xavier/In_Board/Installing_Packages "Xavier/In Board/Installing Packages")

[Video Capture and Display](/wiki/index.php/Xavier/Video_Capture_and_Display "Xavier/Video Capture and Display")

[Description](/wiki/index.php/Xavier/Video_Capture_and_Display/Description "Xavier/Video Capture and Display/Description")

[Supported Cameras](/wiki/index.php/Xavier/Video_Capture_and_Display/Cameras "Xavier/Video Capture and Display/Cameras")

*   [Imx219 Driver](/wiki/index.php/Xavier/Video_Capture_and_Display/Cameras/IMX219 "Xavier/Video Capture and Display/Cameras/IMX219")

[Software Support](/wiki/index.php/Xavier/Video_Capture_and_Display/Software_Support "Xavier/Video Capture and Display/Software Support")

*   [Using GStreamer](/wiki/index.php/Xavier/Video_Capture_and_Display/Software_Support/GStreamer "Xavier/Video Capture and Display/Software Support/GStreamer")
*   [Using Libargus](/wiki/index.php/Xavier/Video_Capture_and_Display/Software_Support/Libargus "Xavier/Video Capture and Display/Software Support/Libargus")

[Processors](/wiki/index.php/Xavier/Processors "Xavier/Processors")

[HD Audio and Video Subystem](/wiki/index.php/Xavier/Processors/HDAV_Subsystem "Xavier/Processors/HDAV Subsystem")

*   [Video Encoder](/wiki/index.php/Xavier/Processors/HDAV_Subsystem/Video_Encoder "Xavier/Processors/HDAV Subsystem/Video Encoder")
*   [Video Decoder](/wiki/index.php/Xavier/Processors/HDAV_Subsystem/Video_Decoder "Xavier/Processors/HDAV Subsystem/Video Decoder")
*   [JPEG Encoder and Decoder](/wiki/index.php/Xavier/Processors/HDAV_Subsystem/JPEG "Xavier/Processors/HDAV Subsystem/JPEG")
*   [Video Image Compositor](/wiki/index.php/Xavier/Processors/HDAV_Subsystem/Compositor "Xavier/Processors/HDAV Subsystem/Compositor")
*   [Audio Processing Engine](/wiki/index.php/Xavier/Processors/HDAV_Subsystem/Audio_Engine "Xavier/Processors/HDAV Subsystem/Audio Engine")

[Deep Learning Accelerator](/wiki/index.php/Xavier/Processors/Deep_Learning_Accelerator "Xavier/Processors/Deep Learning Accelerator")

[Volta GPU](/wiki/index.php/Xavier/Processors/GPU "Xavier/Processors/GPU")

*   [Description](/wiki/index.php/Xavier/Processors/GPU/Description "Xavier/Processors/GPU/Description")
*   [Using CUDA](/wiki/index.php/Xavier/Processors/GPU/CUDA "Xavier/Processors/GPU/CUDA")
*   [Using OpenGL](/wiki/index.php/Xavier/Processors/GPU/OPENGL "Xavier/Processors/GPU/OPENGL")

[Interfaces](/wiki/index.php/Xavier/Interfaces "Xavier/Interfaces")

*   [I2C](/wiki/index.php/Xavier/Interfaces/I2C "Xavier/Interfaces/I2C")
*   [SD/eMMC Controller](/wiki/index.php/Xavier/Interfaces/SD_eMMC "Xavier/Interfaces/SD eMMC")
*   [USB Controller](/wiki/index.php/Xavier/Interfaces/USB "Xavier/Interfaces/USB")

[GStreamer Pipelines](/wiki/index.php/Xavier/GStreamer_Pipelines "Xavier/GStreamer Pipelines")

*   [Capture and Display](/wiki/index.php/Xavier/GStreamer_Pipelines/Capture_and_Display "Xavier/GStreamer Pipelines/Capture and Display")
*   [H264](/wiki/index.php/Xavier/GStreamer_Pipelines/H264 "Xavier/GStreamer Pipelines/H264")
*   [H265](/wiki/index.php/Xavier/GStreamer_Pipelines/H265 "Xavier/GStreamer Pipelines/H265")
*   [VP9](/wiki/index.php/Xavier/GStreamer_Pipelines/VP9 "Xavier/GStreamer Pipelines/VP9")
*   [MPEG4](/wiki/index.php/Xavier/GStreamer_Pipelines/MPEG4 "Xavier/GStreamer Pipelines/MPEG4")
*   [Simultaneous Streams](/wiki/index.php/Xavier/GStreamer_Pipelines/Maximum_Number_of_Simultaneous_Streams "Xavier/GStreamer Pipelines/Maximum Number of Simultaneous Streams")
*   [Compositor](/wiki/index.php/Xavier/GStreamer_Pipelines/Compositor "Xavier/GStreamer Pipelines/Compositor")

[Deep Learning](/wiki/index.php/Xavier/Deep_Learning "Xavier/Deep Learning")

[TensorRT](/wiki/index.php/Xavier/Deep_Learning/TensorRT "Xavier/Deep Learning/TensorRT")

*   [Using TensorRT integrated with Tensorflow](/wiki/index.php/Xavier/Deep_Learning/TensorRT/Tensorflow "Xavier/Deep Learning/TensorRT/Tensorflow")
*   [Parsing a Tensorflow model for TensorRT](/wiki/index.php/Xavier/Deep_Learning/TensorRT/Parsing_Tensorflow "Xavier/Deep Learning/TensorRT/Parsing Tensorflow")
*   [Parsing Caffe model for TensorRT](/wiki/index.php/Xavier/Deep_Learning/TensorRT/Parsing_Caffe "Xavier/Deep Learning/TensorRT/Parsing Caffe")
*   [Building TensorRT API examples](/wiki/index.php/Xavier/Deep_Learning/TensorRT/Building_Examples "Xavier/Deep Learning/TensorRT/Building Examples")

[Deep Learning Accelerator](/wiki/index.php/Xavier/Deep_Learning/Deep_Learning_Accelerator "Xavier/Deep Learning/Deep Learning Accelerator")

*   [Software Support](/wiki/index.php/Xavier/Deep_Learning/Deep_Learning_Accelerator/Software_Support "Xavier/Deep Learning/Deep Learning Accelerator/Software Support")

[Deep Learning Tutorials](/wiki/index.php/Xavier/Deep_Learning/Deep_Learning_Tutorials "Xavier/Deep Learning/Deep Learning Tutorials")

*   [Jetson Inference](/wiki/index.php/Xavier/Deep_Learning/Deep_Learning_Tutorials/Jetson_Inference "Xavier/Deep Learning/Deep Learning Tutorials/Jetson Inference")
*   [Jetson Reinforcement](/wiki/index.php/Xavier/Deep_Learning/Deep_Learning_Tutorials/Jetson_Reinforcement "Xavier/Deep Learning/Deep Learning Tutorials/Jetson Reinforcement")

[RidgeRun Products](/wiki/index.php/Xavier/RidgeRun_Products "Xavier/RidgeRun Products")

*   [GstPTZR](/wiki/index.php/Xavier/RidgeRun_Products/GstPTZR "Xavier/RidgeRun Products/GstPTZR")
*   [GstCUDA](/wiki/index.php/Xavier/RidgeRun_Products/GstCUDA "Xavier/RidgeRun Products/GstCUDA")
*   [GstColorTransfer](/wiki/index.php/Xavier/RidgeRun_Products/GstColorTransfer "Xavier/RidgeRun Products/GstColorTransfer")
*   [GstWebRTC](/wiki/index.php/Xavier/RidgeRun_Products/GstWebRTC "Xavier/RidgeRun Products/GstWebRTC")
*   [GstRtspSink](/wiki/index.php/Xavier/RidgeRun_Products/GstRtspSink "Xavier/RidgeRun Products/GstRtspSink")
*   [GstInterpipe](/wiki/index.php/Xavier/RidgeRun_Products/GstInterpipe "Xavier/RidgeRun Products/GstInterpipe")
*   [GstInference](/wiki/index.php/Xavier/RidgeRun_Products/GstInference "Xavier/RidgeRun Products/GstInference")
*   [GStreamer Daemon](/wiki/index.php/Xavier/RidgeRun_Products/GStreamer_Daemon "Xavier/RidgeRun Products/GStreamer Daemon")
*   [GstShark](/wiki/index.php/Xavier/RidgeRun_Products/GstShark "Xavier/RidgeRun Products/GstShark")

[Reference Documentation](/wiki/index.php/Xavier/Reference_Documentation "Xavier/Reference Documentation")

[**Contact Us**](/wiki/index.php/Xavier/Contact_Us "Xavier/Contact Us")

  

  

  

  

Contents
--------

*   [1 Activate CPUs](#Activate_CPUs)
*   [2 Activate Fans](#Activate_Fans)
*   [3 VIC clocking](#VIC_clocking)
*   [4 Jetson Clocks](#Jetson_Clocks)

Activate CPUs
-------------

By default 4 out of 8 possible CPU cores are disabled on the Jetson Xavier. You can activate them with the following commands (you need root permissions):

sudo su
echo 1 > /sys/devices/system/cpu/cpu4/online
echo 1 > /sys/devices/system/cpu/cpu5/online
echo 1 > /sys/devices/system/cpu/cpu6/online
echo 1 > /sys/devices/system/cpu/cpu7/online
exit

You can also set the nvvpmodel (power model) to the maximum. To see the options:

nvpmodel -p --verbose | grep POWER\_MODEL

which outputs:

NVPM VERB: POWER\_MODEL: ID=0 NAME=MODE\_15W\_2CORE
NVPM VERB: POWER\_MODEL: ID=1 NAME=MODE\_15W\_4CORE
NVPM VERB: POWER\_MODEL: ID=2 NAME=MODE\_15W\_6CORE
NVPM VERB: POWER\_MODEL: ID=3 NAME=MODE\_10W\_2CORE
NVPM VERB: POWER\_MODEL: ID=4 NAME=MODE\_10W\_4CORE
NVPM VERB: POWER\_MODEL: ID=5 NAME=MODE\_10W\_DESKTOP
NVPM VERB: POWER\_MODEL: ID=6 NAME=MODE\_20W\_2CORE
NVPM VERB: POWER\_MODEL: ID=7 NAME=MODE\_20W\_4CORE
NVPM VERB: POWER\_MODEL: ID=8 NAME=MODE\_20W\_6CORE

To select the maximum, let's choose the ID=8:

nvpmodel -m 8

Activate Fans
-------------

We recommend also turning on the Xavier module fan if you turn on all CPUs:

The method to set the fan speed in JP 4.x is not longer working. You need to, instead, use the nvfancontrol daemon for this purpose: more info [here](https://docs.nvidia.com/jetson/archives/r34.1/DeveloperGuide/text/SD/PlatformPowerAndPerformance/JetsonXavierNxSeriesAndJetsonAgxXavierSeries.html?highlight=nvfancontrol#fan-profile-control).

However, it sets only to "cool", which is still managed by the temperature sensor in an open loop control. To set the fan at full speed, edit the `/etc/nvfancontrol.conf` with:

	FAN\_PROFILE quiet {
...
	}
	FAN\_PROFILE full {
		#TEMP 	HYST	PWM	RPM
		0	8 	255 	6000
		108	0 	255 	6000
	}
	FAN\_PROFILE cool {
...
	FAN\_DEFAULT\_CONTROL open\_loop
	FAN\_DEFAULT\_PROFILE full
	FAN\_DEFAULT\_GOVERNOR pid

then, execute the following commands:

sudo systemctl stop nvfancontrol
sudo rm /var/lib/nvfancontrol/status
sudo systemctl start nvfancontrol

And that's it.

_Another observation:_ the monitor from jetson-stats (a.k.a. jtop) does not work with the fan :(

You must activate all CPUs **before** running jetson\_clocks to overclock these CPUs too.

VIC clocking
------------

By default, Jetson clocks command does not activate the full clock in VIC. To manually set them to the maximum clock (Jetson), first inspect which one is the highest:

cat /sys/devices/platform/13e10000.host1x/15340000.vic/devfreq/15340000.vic/available\_frequencies

In the case of Jetson NX, it is: 601600000 Hz.

Then, set the manual control of the VIC:

\# Set manual control to the max frequency
echo on > /sys/devices/platform/13e10000.host1x/15340000.vic/power/control
echo userspace > /sys/devices/platform/13e10000.host1x/15340000.vic/devfreq/15340000.vic/governor
echo 601600000 > /sys/devices/platform/13e10000.host1x/15340000.vic/devfreq/15340000.vic/max\_freq
echo 601600000 > /sys/devices/platform/13e10000.host1x/15340000.vic/devfreq/15340000.vic/userspace/set\_freq

\# Current freq
cat /sys/devices/platform/13e10000.host1x/15340000.vic/devfreq/15340000.vic/cur\_freq

Note: for JP 4.x, change `/sys/devices/platform/13e10000.host1x` by `/sys/devices/13e10000.host1x`

Jetson Clocks
-------------

Xavier provides the jetson\_clocks script to maximize Jetson Xavier performance by setting static max frequency to CPU, GPU, and EMC clocks. The script can also be used to show current clock settings, store current clock settings into a file, and restore clock settings from a file.

Options

Usage:
jetson\_clocks \[options\]
  options,
  --help, -h         show this help message
  --show             display current settings
  --fan              set PWM fan speed to maximal
  --store \[file\]     store current settings to a file (default: ${HOME}/l4t\_dfs.conf)
  --restore \[file\]   restore saved settings from a file (default: ${HOME}/l4t\_dfs.conf)
  run jetson\_clocks without any option to set static max frequency to CPU, GPU and EMC clocks.

*   To show the current settings:

sudo jetson\_clocks --show

*   To store the current settings:

sudo jetson\_clocks --store

*   To maximize Jetson Xavier performance

sudo jetson\_clocks

*   To restore the previous settings

sudo jetson\_clocks --restore

  
  

[Previous: JetPack 5.0.2‎/Performance Tuning/Tuning Power](/wiki/index.php/Xavier/JetPack_5.0.2/Performance_Tuning/Tuning_Power "Xavier/JetPack 5.0.2/Performance Tuning/Tuning Power")

[Index](/wiki/index.php/Xavier "Xavier")

[Next: Development in the Board](/wiki/index.php/Xavier/Development_in_the_Board "Xavier/Development in the Board")

  

  

Retrieved from "[http://developer.ridgerun.com/wiki/index.php?title=Xavier/JetPack\_5.0.2/Performance\_Tuning/Maximizing\_Performance&oldid=43240](http://developer.ridgerun.com/wiki/index.php?title=Xavier/JetPack_5.0.2/Performance_Tuning/Maximizing_Performance&oldid=43240)"

[Categories](/wiki/index.php/Special:Categories "Special:Categories"):

*   [NVIDIA Xavier](/wiki/index.php/Category:NVIDIA_Xavier "Category:NVIDIA Xavier")
*   [Jetson](/wiki/index.php/Category:Jetson "Category:Jetson")

Hidden category:

*   [Pages using sidebar with the child parameter](/wiki/index.php/Category:Pages_using_sidebar_with_the_child_parameter "Category:Pages using sidebar with the child parameter")

Navigation menu
---------------

### Personal tools

*   [Log in](/wiki/index.php?title=Special:UserLogin&returnto=Xavier%2FJetPack+5.0.2%2FPerformance+Tuning%2FMaximizing+Performance "You are encouraged to log in; however, it is not mandatory [o]")

### Namespaces

*   [Page](/wiki/index.php/Xavier/JetPack_5.0.2/Performance_Tuning/Maximizing_Performance "View the content page [c]")
*   [Discussion](/wiki/index.php?title=Talk:Xavier/JetPack_5.0.2/Performance_Tuning/Maximizing_Performance&action=edit&redlink=1 "Discussion about the content page (page does not exist) [t]")

### Variants

### Views

*   [Read](/wiki/index.php/Xavier/JetPack_5.0.2/Performance_Tuning/Maximizing_Performance)
*   [View source](/wiki/index.php?title=Xavier/JetPack_5.0.2/Performance_Tuning/Maximizing_Performance&action=edit "This page is protected.
    You can view its source [e]")
*   [View history](/wiki/index.php?title=Xavier/JetPack_5.0.2/Performance_Tuning/Maximizing_Performance&action=history "Past revisions of this page [h]")

### More

### Search

[](/wiki/index.php/Main_Page "Visit the main page")

### Navigation

*   [Main Page](/wiki/index.php/Main_Page "Visit the main page [z]")
*   [Recent changes](/wiki/index.php/Special:RecentChanges)

### Useful Links

*   [RidgeRun Blog](https://www.ridgerun.com/blog)
*   [NVIDIA Developer Zone](https://devtalk.nvidia.com/)
*   [Xilinx Forum](https://forums.xilinx.com)
*   [NXP iMX Community](https://community.nxp.com/community/imx)

### Legal

*   [Licensing:](https://www.ridgerun.com/standard-license-agreement)
*   [Privacy Policy](https://www.ridgerun.com/privacy-policy)
*   [Terms of Use](https://www.ridgerun.com/website-terms-of-use)
*   [Disclaimer](https://www.ridgerun.com/disclaimer)

### Services

*   [RidgeRun Engineering Services](https://www.ridgerun.com/engineering-services)
*   [Client Engagement Process](https://www.ridgerun.com/process)
*   [Professional Services and Support Hours](/wiki/index.php/RidgeRun_Professional_Services)
*   [Subscription Model](/wiki/index.php/RidgeRun_Subscription_Model)
*   [List of V4L2 Camera Sensor Drivers for Jetson SOCs](/wiki/index.php/V4L2_drivers_available_for_Jetson_SoCs)
*   [V4L2 Camera Sensor Driver Wiki](/wiki/index.php/V4L2_driver_for_camera_sensor_or_capture_chip)

### Tools

*   [What links here](/wiki/index.php/Special:WhatLinksHere/Xavier/JetPack_5.0.2/Performance_Tuning/Maximizing_Performance "A list of all wiki pages that link here [j]")
*   [Related changes](/wiki/index.php/Special:RecentChangesLinked/Xavier/JetPack_5.0.2/Performance_Tuning/Maximizing_Performance "Recent changes in pages linked from this page [k]")
*   [Special pages](/wiki/index.php/Special:SpecialPages "A list of all special pages [q]")
*   [Printable version](/wiki/index.php?title=Xavier/JetPack_5.0.2/Performance_Tuning/Maximizing_Performance&printable=yes "Printable version of this page [p]")
*   [Permanent link](/wiki/index.php?title=Xavier/JetPack_5.0.2/Performance_Tuning/Maximizing_Performance&oldid=43240 "Permanent link to this revision of the page")
*   [Page information](/wiki/index.php?title=Xavier/JetPack_5.0.2/Performance_Tuning/Maximizing_Performance&action=info "More information about this page")

*   This page was last edited on 7 September 2022, at 10:34.

*   [Privacy policy](/wiki/index.php/RidgeRun_Developer_Connection:Privacy_policy "RidgeRun Developer Connection:Privacy policy")
*   [About RidgeRun Developer Connection](/wiki/index.php/RidgeRun_Developer_Connection:About "RidgeRun Developer Connection:About")
*   [Disclaimers](/wiki/index.php/RidgeRun_Developer_Connection:General_disclaimer "RidgeRun Developer Connection:General disclaimer")
*   [Terms of Use](/wiki/index.php/Termsofuse "Termsofuse")

*   [![Powered by MediaWiki](/wiki/resources/assets/poweredby_mediawiki_88x31.png)](//www.mediawiki.org/)

(window.RLQ=window.RLQ||\[\]).push(function(){mw.config.set({"wgPageParseReport":{"limitreport":{"cputime":"0.136","walltime":"1.725","ppvisitednodes":{"value":443,"limit":1000000},"ppgeneratednodes":{"value":1351,"limit":1000000},"postexpandincludesize":{"value":67250,"limit":2097152},"templateargumentsize":{"value":498,"limit":2097152},"expansiondepth":{"value":6,"limit":40},"expensivefunctioncount":{"value":0,"limit":100},"unstrip-depth":{"value":0,"limit":20},"unstrip-size":{"value":4538,"limit":5000000},"timingprofile":\["100.00% 1682.099 1 -total"," 27.83% 468.134 10 Template:Sidebar"," 18.95% 318.841 1 Template:Xavier/Head"," 17.57% 295.597 1 Template:Xavier/TOC"," 0.23% 3.927 1 Template:Xavier/Foot"\]},"scribunto":{"limitreport-timeusage":{"value":"0.120","limit":"7.000"},"limitreport-virtmemusage":{"value":9416704,"limit":52428800},"limitreport-estmemusage":0},"cachereport":{"timestamp":"20221130091633","ttl":86400,"transientcontent":false}}});}); (function(i,s,o,g,r,a,m){i\['GoogleAnalyticsObject'\]=r;i\[r\]=i\[r\]||function(){ (i\[r\].q=i\[r\].q||\[\]).push(arguments)},i\[r\].l=1\*new Date();a=s.createElement(o), m=s.getElementsByTagName(o)\[0\];a.async=1;a.src=g;m.parentNode.insertBefore(a,m) })(window,document,'script','//www.google-analytics.com/analytics.js','ga'); ga('create', 'UA-2001544-2', 'auto'); ga('send', 'pageview'); (window.RLQ=window.RLQ||\[\]).push(function(){mw.config.set({"wgBackendResponseTime":152});});
