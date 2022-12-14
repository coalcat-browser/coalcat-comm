Please note that on Windows, the Outlook 2010 MAPI Header files are required.
If you do not get these, you will get a build error about header files with names
starting with MAPI.

Microsoft have pulled it from their site for no reason, but it is available
on the Internet Archive.

https://web.archive.org/web/20171206083840/http://www.microsoft.com/en-us/download/details.aspx?id=12905

The Windows Prerequisites page may mention about Visual Studio Express 2013 and
Windows SDK 8.1. Please note that has been confirmed to build on Visual Studio
2017 and the Windows 10 1809 SDK (17763). However, this has not been tested to 
build on Visual Studio 2019/2022 with newer SDKs, but it *might* work.

Build instructions are available here for the time being:

Mail: https://web.archive.org/web/20160616153952/https://developer.mozilla.org/en-US/docs/Mozilla/Developer_guide/Build_Instructions/Simple_Thunderbird_build
Suite: https://web.archive.org/web/20160805025336/https://developer.mozilla.org/en-US/docs/Mozilla/Developer_guide/Build_Instructions/Simple_SeaMonkey_build