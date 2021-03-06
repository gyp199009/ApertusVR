#MIT License
#
#Copyright (c) 2016 MTA SZTAKI
#
#Permission is hereby granted, free of charge, to any person obtaining a copy
#of this software and associated documentation files (the "Software"), to deal
#in the Software without restriction, including without limitation the rights
#to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
#copies of the Software, and to permit persons to whom the Software is
#furnished to do so, subject to the following conditions:
#
#The above copyright notice and this permission notice shall be included in all
#copies or substantial portions of the Software.
#
#THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
#IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
#FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
#AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
#LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
#OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
#SOFTWARE.

option(APE_PLUGIN_OgreRender "Use OgreRenderPlugin?" ON )
option(APE_PLUGIN_OisUserInput "Use OisUserInputPlugin?" ON )
option(APE_PLUGIN_SampleScene "Use SampleScenePlugin?" ON )
option(APE_PLUGIN_EngineeringScene "Use EngineeringScenePlugin?" ON )
option(APE_PLUGIN_PresentationScene "Use PresentationScenePlugin?" ON )
option(APE_PLUGIN_ArtScene "Use ArtScenePlugin?" ON )
option(APE_PLUGIN_FobHeadTracking "Use FobHeadTrackingPlugin?" ON )
option(APE_PLUGIN_Tester "Use TesterPlugin?" ON )
option(APE_PLUGIN_LinkageDesignerVR "Use LinkageDesignerVRPlugin?" ON )
option(APE_PLUGIN_Lego "Use LegoPlugin?" ON )
option(APE_PLUGIN_JsAPI "Use JsAPIPlugin?" ON )
option(APE_PLUGIN_OculusDK2 "Use OculusDK2Plugin?" ON )
option(APE_PLUGIN_RobotMonitoring "Use RobotMonitoringPlugin?" ON )
option(APE_PLUGIN_Industry40 "Use Industry40Plugin?" ON )


if (${APE_PLUGIN_OgreRender})
	add_subdirectory (ogreRender)
endif ()	
if (${APE_PLUGIN_OisUserInput})
	add_subdirectory (oisUserInput)
endif ()
if (${APE_PLUGIN_SampleScene})
	add_subdirectory (sampleScene)
endif ()
if (${APE_PLUGIN_EngineeringScene})
	add_subdirectory (engineeringScene)
endif ()
if (${APE_PLUGIN_PresentationScene})
	add_subdirectory (presentationScene)
endif ()
if (${APE_PLUGIN_ArtScene})
	add_subdirectory (artScene)
endif ()
if (${APE_PLUGIN_FobHeadTracking})
	add_subdirectory (fobHeadTracking)
endif ()
if (${APE_PLUGIN_Tester})
	add_subdirectory (tester)
endif ()
if (${APE_PLUGIN_LinkageDesignerVR})
	add_subdirectory (linkageDesignerVR)
endif ()
if (${APE_PLUGIN_Lego})
	add_subdirectory (lego)
endif ()
if (${APE_PLUGIN_JsAPI})
	add_subdirectory (jsAPI)
endif ()
if (${APE_PLUGIN_OculusDK2})
	add_subdirectory (oculusDK2)
endif ()
if (${APE_PLUGIN_RobotMonitoring})
	add_subdirectory (robotMonitoring)
endif ()
if (${APE_PLUGIN_Industry40})
	add_subdirectory (industry40)
endif ()

