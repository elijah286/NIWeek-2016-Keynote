#Installers and Packages
__Package Manager__

`\\nirvana\perforceExports\AST\PackageManagement\components\nipkgui\export\16.0\{BUILD}\targets\win64U\x64\msvc-14.0\release\Install.exe`
Note the `{BUILD}` must be replaced with an actual build number. Use 16.0 for Tech Preview
Add the following repo

__LabVIEW PDP__ 

`\\us-aus-argo\ni\nipkg\packages\ni-l\ni-labview-pdp\4.7.1\latest`
WebVI projects only work if you have PDP (KitchenSink) installed

__Skyline Tags__

`\\us-aus-argo\ni\nipkg\packages\ni-s\ni-skyline-tag-client\17.0.0\latest`
Install ni-skyline-tag-client, requires showing infrastructure packages

__Tag Suppport__

Copy the following package to your desktop 
`\\hades\ss\group\jprewitt\temp\skyline\packages\ni-skyline-tag-labview-features-techpreview-support_17.0.0.0-0+d0_windows_x64.nipkg`
Then use the nipkg command line to install ni-skyline-tag-labview-features-techpreview-support

Copy `\\hades\ss\group\jprewitt\temp\skyline\niweek2016\MessageBusConfiguration.json` TO `C:\ProgramData\National Instruments\Skyline\`

#Desktop VI
`Desktop\*.lvproject`
`Keynode Dashboard.gvi`

#Web VI on Stage
`Web VI\WebVI and Tag Keynote\WebVI and Tag Keynote.lvproject`

#Hosted Web VI
`http://skyline.southcentralus.cloudapp.azure.com/packages/local/simplelvplugin/index.html`
