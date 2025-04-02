## About ExtentionPrintR

ExtPrint3r is an exploit created by [Blobby Boi](https://github.com/Blobby-Boi/) with the goal of being the successor to ExtHang3r, The old ExtentionStoppR was based on ExtHang3r, and now ExtentionPrintR is based off of ExtPrint3r, and is a proper fork! The exploit recreates the behavior of the LTMEAT Print method by flooding iframes and then printing the page. This is exactly what ExtPrint3r exploits, since it also works with extension pages (as long they are under web_accessible_resources). This seems to be much more consistent than the patched ExtentionStoppR ever was, and it also lasts for a longer period of time, Just like normal ExtPrint3r.
> It is heavily recommended that you disable the V8 optimizer (chrome://settings/content/v8) prior to using this exploit! This was found by [ts353](https://github.com/ts353).

makes ChromeOS forget that extentions should run, or think.
Based off of **ExtentionStoppR** and [ExtPrint3r](https://github.com/Blobby-Boi/ExtPrint3r). 

*This project is a tech demo, and is not intended to be misused, and should only be used for security research. I do not promote academic dishonesty, and simply want to highlight issues in Google's awful operating system. Please do not use this to get around restrictions set by companies or school districts.*
####  
----------------------------------------
# Instructions:

## Type 1: "NoJavBoot"

* Step 1: Pin the extention you want to disable

* Step 2: open the exploit like normal, follow along with its instructions and kill the extention

* Step 3: After checking it won't start, go back to the extention's page `chrome://extensions/?id=EXTENTIONID`, and click `Allow access to file URLs` twice.

* Step 4: Click on the extention you just pinned, if it doesn't load, continue to step 5, if it loads, press `Reload + Power Button` and retry the exploit from the start

* Step 4: If step 3 succeeds or the extention is no longer loading, stay on the page for the exploit, click the extention, and quickly press `esc + Reload + Power Button `

* Step 5: Whenever you reach the recovery page, press ` Reload + Power Button ` within 10 seconds.

* Step 6: Once you are signed in, Make sure you have NO TABS OPEN except chrome://newtab.

* Step 7: Click on your extention 1-3 times, see if it says it's disabled, or javascript isn't working. If it does continue to step 8, if it doesn't, retry the exploit.

* Step 8: Ta-da! You just found out how bad ChromeOS is.

#### 

*Type 1 has only been tested with the extention Linewise (CRX), if it doesnt work on another extention, create a pull request or submit an issue :D*
 
-------
# How to Disable (Type 2):
- Simply press `Reload + Power Button` and it'll reboot your chromebook back to normal.
#### 
--------
# Disclaimer:

By using "ExtentionStoppR" in educational environments, you acknowledge that you have read and understood the potential risks involved. Using this exploit may result in:

Suspension or expulsion : Your educational institution may take disciplinary action against you for using software intended to bypass security features.
Consequences from administrators : You may face consequences from school administrators, including but not limited to detention, disciplinary action, or other penalties.
Damage to relationships with peers and teachers. Using this exploit may potentially effect your academic performance and overall educational experience, use "ExtentionStoppR" at your own risk.

By proceeding, you acknowledge that you have read and understood the potential consequences of using this project. You also agree to not hold the creators of this project, dmdtutorials.com, DMD™, and any other parties involved in its development or distribution accountable for damages in any way.
-----------------
# License
BSD 2-Clause License

Copyright (c) 2025, dmdtutorials.com

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this
   list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice,
   this list of conditions and the following disclaimer in the documentation
   and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
