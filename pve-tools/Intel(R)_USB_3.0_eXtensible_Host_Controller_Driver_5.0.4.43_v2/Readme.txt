********************  WARNING  *****************************
Do not run this driver’s installer (Setup.exe) from a USB
storage device (ie. external USB hard drive or USB thumb 
drive). For proper installation, please copy driver files 
to a local hard drive folder and run from there.
************************************************************
*
*  Production Version Release
* 
*  Microsoft Windows* 7 
*
*  Intel(R) USB 3.0 eXtensible Host Controller:  5.0.4.43
*
*  May 2017
*
*  NOTE:  This document refers to systems containing the 
*         following Intel processors/chipsets: 
*
*	Intel(R) 8 Series/C220 series Chipset Family
*	4th generation Intel(R) Core(TM) Processors
*	Intel(R) C230 series Chipset Family
*	Intel(R) C610 series Chipset Family      
*	Intel(R) 9 Series Chipset Family
*	Intel(R) Pentium(R) Processor or Intel(R)	            
*	Celeron(R) Processor N- & J- Series
*	5th generation Intel(R) Core(TM) Processors
*	Intel(R) Core(TM) M Processor
*	Intel(R) 6th generation Intel(R) Core(TM) processors.
*	Intel(R) 100 Series/C230 series Chipset Family.
*	Intel(R) 200 Series Chipset Family + Skylake CPU Platform
*	Alpine Ridge USB3.1 Host Controller
*	Alpine Ridge LP USB3.1 Host Controller
*	Lewisburg Platform Control Hub
*	
*  Installation Information
*
*  This document makes references to products developed by
*  Intel. There are some restrictions on how these products
*  may be used, and what information may be disclosed to
*  others. Please read the Disclaimer section and contact
*  your Intel field representative if you would like more
*  information.
*
************************************************************
************************************************************
*  DISCLAIMER: Intel is making no claims of usability,
*  efficacy or warranty.  The INTEL SOFTWARE LICENSE
*  AGREEMENT contained herein completely defines the license
*  and use of this software.
*
*  This document contains information on products in the 
*  design phase of development. The information here is 
*  subject to change without notice. Do not finalize a 
*  design with this information.
************************************************************
************************************************************

************************************************************
*  CONTENTS OF THIS DOCUMENT
************************************************************

This document contains the following sections:

1.  System Requirements
2.  Localized Language Abbreviations
3.  Installing the Software
4.  Verifying Installation of the Software
5.  Identifying the Software Version Number
6.  Installation switches available
7.  Uninstalling the software

************************************************************
*  1.  SYSTEM REQUIREMENTS
************************************************************

1. The system must contain one of the following Intel
   Processors/Chipsets:
                    
	Intel(R) 8 Series Chipset Family.
	4th Generation Intel(R) Core(TM) Processors.
	Intel(R) C230 series Chipset Family.
	Intel(R) C610 series Chipset Family.
	Intel(R) 9 Series Chipset Family.
	Intel(R) Pentium(R) Processor or Intel(R)
	Celeron(R) Processor N- & J- Series.
	5th generation Intel(R) Core(TM) Processors
	Intel(R) Core(TM) M Processor.
	Intel(R) 6th generation Intel(R) Core(TM) processors.
	Intel(R) 100 Series/C230 series Chipset Family.
	Intel(R) 200 Series Chipset Family + Skylake CPU Platform.
	Lewisburg Platform Control Hub.

2. The software should be installed on systems with at
   least 1 GB of system memory.

3. There should be sufficient hard disk space in the <TEMP>
   directory on the system in order to install this
   software.

   The drivers included with this distribution package are
   designed to function with all released versions of
   Microsoft Windows* 7 OS available at the time of release 
   of this package.

Please check with your system provider to determine the
operating system and Intel Chipset used in your system.
************************************************************
*  2.  LOCALIZED LANGUAGE ABBREVIATIONS
************************************************************

The following list contains the hexadecimal key of all
languages into which the driver has been localized. You may
have to refer to this section while using this document.
    Code #, Language, Language Code
	0401 -> Arabic (International), ARA
	0804 -> Chinese (Simplified), CHS
	0404 -> Chinese (Traditional), CHT, 
	0405 -> Czech, CSY
	0406 -> Danish, DAN
	0407 -> German, DEU
	0408 -> Greek, ELL
	0409 -> English (United States), ENU
	040A -> Spanish, ESP
	040B -> Finnish, FIN
	040C -> French (International), FRA
	040D -> Hebrew, HEB
	040E -> Hungarian, HUN
	0410 -> Italian, ITA
	0411 -> Japanese, JPN
	0412 -> Korean, KOR
	0413 -> Dutch, NLD
	0414 -> Norwegian, NOR
	0415 -> Polish, PLK
	0416 -> Portuguese (Brazil), PTB
	0816 ->Portuguese (Portugal), PTG
	0419 -> Russian, RUS
	041B -> Slovak, SKY
	0424 -> Slovenian, SLV
	041D -> Swedish, SVE
	041E -> Thai, THA
	041F -> Turkish, TRK


************************************************************
*  3.  INSTALLING THE SOFTWARE
************************************************************

General Installation Notes:

1. The operating system must be installed prior to the 
   installation of the driver.

2. This installation procedure is specific only to the 
   version of driver and installation file included in this 
   release.

3. This procedure assumes that all of the software 
   associated with this release is located in the same 
   directory.

INSTALLATION INSTRUCTIONS 
------------------------------------------------------------

To install from a Web download, you will download either a
ZIP file or an EXE file from the Web.

a. If it is an EXE file, double-click the file you 
   downloaded and specify a location into which the  driver
   files will be extracted. Click "Unzip" and the files 
   will extract. Click "OK" on the next window, then click 
   "Close". 

b. If it is a ZIP file, double-click the file you downloaded
   and choose “Extract all files”. Next,  browse to a 
   destination folder in which the files can be placed and 
   choose “Extract”.

************************************************************
*   Operating Systems supported
************************************************************

Intel(R) 8 Series Chipset Family
4th Generation Intel(R) Core(TM) Processors
Intel(R) C610 series Chipset Family
Intel(R) 9 Series Chipset Family
Intel(R) Pentium(R) Processor or Intel(R)
Celeron(R) Processor N- & J- Series
5th generation Intel(R) Core(TM) Processors
Intel(R) Core(TM) M Processor
Intel(R) 6th generation Intel(R) Core(TM) processors
Intel(R) 100 Series Chipset Family
Intel(R) 200 Series Chipset Family + Skylake CPU Platform
Alpine Ridge USB3.1 Host Controller
Alpine Ridge LP USB3.1 Host Controller:

•  Windows* 7 Operating System (both 32-bit and 64-bit 
   versions).

Intel(R) C220 series chipset family
Intel(R) C230 series chipset family
Intel(R) C610 series Chipset Family
Lewisburg PCH:

•  Windows* 7 Operating System (both 32-bit and 64-bit 
   versions).
•  Windows* Server 2008 R2 Operating System.
•  Windows* Small Business Server 2008 Operating System.


************************************************************
*   Microsoft Windows* 7 and Windows* Server 2008 
    "Setup.exe" Installation
************************************************************

1. Locate the hard drive directory where the driver files 
   are stored with the browser or the explore feature of 
   Windows*.

2. Double click the “Setup.exe” from this directory.

3. The Install dialog will appear.
 
4. Click “Next” to continue.

5. Read License Agreement and click “Yes” to proceed.

6. Review Readme File Information and click “Next” to 
   proceed.

7. When the “Setup Progress” is complete click “Next” 
   to proceed.

8. Lastly, the “Setup Complete” screen appears so click
   “Finish” to restart your computer.
   
************************************************************
*  4.  VERIFYING INSTALLATION OF THE SOFTWARE
************************************************************
1. Click "Start" then right click on "Computer" button and 
   then click on properties.

2. Click on the "Device Manager" selection on the left.

3. Select "Universal Serial Bus controllers". The Intel(R) 
   USB 3.0 eXtensible Host Controller device and Intel(R) 
   USB 3.0 Root Hub device should be listed and not yellow 
   banged. 
   If not, the driver is not installed correctly. 

************************************************************
*  5. IDENTIFYING THE SOFTWARE VERSION NUMBER
************************************************************

1. Click "Start" then right click on "Computer" button and 
   then click on properties.

2. Click on the "Device Manager" selection on the left.

3. Select "Universal Serial Bus controllers" then double 
   click on the Intel(R) USB 3.0 eXtensible Host Controller 
   device or Intel(R) USB 3.0 Root Hub device.

4. Click on "Driver" tab and note the driver version.

************************************************************
*  6. INSTALLATION SWITCHES AVAILABLE
************************************************************
The switches in the SETUP.EXE file will have the following 
syntax. 
Switches are not case sensitive and may be specified in any 
order (except for the -s switch). Switches must be separated 
by spaces.
SETUP [-?]

-? Displays help dialog.

************************************************************
*  7. UNINSTALLING THE SOFTWARE
************************************************************
NOTE: This procedure assumes the above installation process
was successful. This uninstallation procedure is specific
only to the version of the driver and installation files
included in this package.

1. Click on the "Start" button, then click on the "Control 
   Panel" icon, and then double click on "Programs and 
   Features", right click on "Intel(R) USB 3.0 eXtensible 
   Host Controller Driver" and select "Uninstall" option

2. Click "Next" to uninstall the driver.

3. Click on "Finish" button to restart the computer.


***************************************************************************
* INTEL SOFTWARE LICENSE AGREEMENT 
* (OEM / IHV / ISV Distribution & Single User)
***************************************************************************


IMPORTANT - READ BEFORE COPYING, INSTALLING OR USING.
Do not use or load software (including drivers) from this site or any 
associated materials (collectively, the "Software") until you have 
carefully read the following terms and conditions. By loading or 
using the Software, you agree to the terms of this Agreement, which 
Intel may modify from time to time following reasonable notice to You. 
If you do not wish to so agree, do not install or use the Software.

Please Also Note:
•	If you are an Original Equipment Manufacturer (OEM), Independent 
Hardware Vendor (IHV) or Independent Software Vendor (ISV), this 
complete LICENSE AGREEMENT applies;
•	If you are an End-User, then only Exhibit A, the INTEL SOFTWARE 
LICENSE AGREEMENT, applies.

For OEMs, IHVs and ISVs:

LICENSE. Subject to the terms of this Agreement, Intel grants to You a 
nonexclusive, nontransferable, worldwide, fully paid-up license under 
Intel's copyrights to:
•	Use, modify and copy the Software internally for Your own 
development and maintenance purposes; and
•	Modify, copy and distribute (subject to any restrictions imposed 
by Intel) the Software, including derivative works of the Software, to 
Your end-users, but only under a license agreement with terms at least 
as restrictive as those contained in Intel's Final, Single User 
License Agreement, attached as 

Exhibit A; and
•	Modify, copy and distribute the end-user documentation which may 
accompany the Software, but only in association with the Software.
Intel reserves the right to further restrict your distribution of the Software 
to specific Intel-approved platforms, operating systems, segments, and/or 
devices in its sole and absolute discretion upon reasonable notice to You.
If You are not the final manufacturer or vendor of a computer system or 
software program incorporating the Software, then You may transfer a copy 
of the Software, including derivative works of the Software (and related 
end-user documentation) to Your recipient for use in accordance with the 
terms of this Agreement, provided such recipient agrees to be fully bound 
by the terms hereof. You will not otherwise assign, sublicense, lease, or 
in any other way transfer or disclose Software to any third party. You will 
not reverse- compile, disassemble or otherwise reverse-engineer the Software.
You may not subject the Software, in whole or in part, to any license 
obligations of Open Source Software including without limitation combining 
or distributing the Software with Open Source Software in a manner that 
subjects the Software or any portion of the Software provided by Intel 
hereunder to any license obligations of such Open Source Software. 
"Open Source Software" means any software that requires as a condition of 
use, modification and/or distribution of such software that such software 
or other software incorporated into, derived from or distributed with such 
software (a) be disclosed or distributed in source code form; or (b) be 
licensed by the user to third parties for the purpose of making and/or 
distributing derivative works; or (c) be redistributable at no charge. 
Open Source Software includes, without limitation, software licensed or 
distributed under any of the following licenses or distribution models, or 
licenses or distribution models substantially similar to any of the following:
 
(a) GNU’s General Public License (GPL) or Lesser/Library GPL (LGPL), 
(b) the Artistic License (e.g., PERL), 
(c) the Mozilla Public License, 
(d) the Netscape Public License, 
(e) the Sun Community Source License (SCSL), 
(f) the Sun Industry Source License (SISL), 
(g) the Apache Software license and 
(h) the Common Public License (CPL). 

NO OTHER RIGHTS. The Software is protected by the intellectual property laws 
of the United States and other countries, and international treaty provisions. 
Except as otherwise expressly above, Intel grants no express or implied rights 
under Intel patents, copyrights, trademarks, or other intellectual property rights. 
Except as expressly stated in this Agreement, no license or right is granted to 
You directly or by implication, inducement, estoppel or otherwise. Intel will 
have the right to inspect or have an independent auditor inspect Your relevant 
records to verify Your compliance with the terms and conditions of this Agreement.
CONFIDENTIALITY. If You wish to have a third party consultant or subcontractor 
("Contractor") perform work on Your behalf which involves access to or use of 
Software, You will obtain a written confidentiality agreement from the Contractor 
which contains terms and obligations with respect to access to or use of Software 
no less restrictive than those set forth in this Agreement and excluding any 
distribution rights, and use for any other purpose. Otherwise, You will not 
disclose the terms or existence of this Agreement or use Intel's Name in any 
publications, advertisements, or other announcements without Intel's prior 
written consent. You do not have any rights to use any Intel trademarks or logos.
OWNERSHIP OF SOFTWARE AND COPYRIGHTS. Title to all copies of the Software 
remains with Intel or its suppliers. The Software is copyrighted and protected 
by the laws of the United States and other countries, and international treaty 
provisions. You may not remove any copyright notices from the Software. Intel 
may make changes to the Software, or to items referenced therein, at any time 
without notice, but is not obligated to support or update the Software. Except 
as otherwise expressly provided, Intel grants no express or implied right under 
Intel patents, copyrights, trademarks, or other intellectual property rights. 
You may transfer the Software only if the recipient agrees to be fully bound by 
these terms and if you retain no copies of the Software.

SUPPORT. Intel may make changes to the Software, or to items referenced therein, 
at any time without notice, but is not obligated to support, update or provide 
training for the Software. Intel may in its sole discretion offer such services 
under separate terms at Intel’s then-current rates. You may request additional 
information on Intel’s service offerings from an Intel sales representative. 

You agree to be solely responsible to Your End Users for any update or support 
obligation or other liability which may arise from the distribution of the Software.

EXCLUSION OF OTHER WARRANTIES. THE SOFTWARE IS PROVIDED "AS IS" WITHOUT ANY EXPRESS 
OR IMPLIED WARRANTY OF ANY KIND INCLUDING WARRANTIES OF MERCHANTABILITY, 
NONINFRINGEMENT, OR FITNESS FOR A PARTICULAR PURPOSE. Intel does not warrant or 
assume responsibility for the accuracy or completeness of any information, text, 
graphics, links or other items contained within the Software.

LIMITATION OF LIABILITY. IN NO EVENT WILL INTEL OR ITS SUPPLIERS BE LIABLE FOR ANY 
DAMAGES WHATSOEVER (INCLUDING, WITHOUT LIMITATION, LOST PROFITS, BUSINESS 
INTERRUPTION, OR LOST INFORMATION) ARISING OUT OF THE USE OF OR INABILITY TO USE 
THE SOFTWARE, EVEN IF INTEL HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGES. 
SOME JURISDICTIONS PROHIBIT EXCLUSION OR LIMITATION OF LIABILITY FOR IMPLIED 
WARRANTIES OR CONSEQUENTIAL OR INCIDENTAL DAMAGES, SO THE ABOVE LIMITATION MAY NOT 
APPLY TO YOU. YOU MAY ALSO HAVE OTHER LEGAL RIGHTS THAT VARY FROM JURISDICTION TO 
JURISDICTION. THE SOFTWARE LICENSED HEREUNDER IS NOT DESIGNED OR INTENDED FOR USE 
IN ANY MEDICAL, LIFE SAVING OR LIFE SUSTAINING SYSTEMS, TRANSPORTATION SYSTEMS, 
NUCLEAR SYSTEMS, OR FOR ANY OTHER MISSION CRITICAL APPLICATION IN WHICH THE FAILURE 
OF THE SOFTWARE COULD LEAD TO PERSONAL INJURY OR DEATH. YOU WILL INDEMNIFY AND HOLD 
INTEL AND THE INTEL PARTIES HARMLESS AGAINST ALL CLAIMS, COSTS, DAMAGES, AND 
EXPENSES, AND REASONABLE ATTORNEY FEES ARISING OUT OF, DIRECTLY OR INDIRECTLY, 
THE DISTRIBUTION OF THE SOFTWARE AND ANY CLAIM OF PRODUCT LIABILITY, PERSONAL INJURY 
OR DEATH ASSOCIATED WITH ANY UNINTENDED USE, EVEN IF SUCH CLAIM ALLEGES THAT AN 
INTEL PARTY WAS NEGLIGENT REGARDING THE DESIGN OR MANUFACTURE OF THE SOFTWARE. THE 
LIMITED REMEDIES, WARRANTY DISCLAIMER AND LIMITED LIABILITY ARE FUNDAMENTAL ELEMENTS 
OF THE BASIS OF THE BARGAIN BETWEEN INTEL AND YOU. INTEL WOULD NOT BE ABLE TO PROVIDE 
THE SOFTWARE WITHOUT SUCH LIMITATIONS. 

TERMINATION OF THIS AGREEMENT. Intel may terminate this Agreement immediately, upon 
notice from Intel, if You violate its terms. Upon termination, You will immediately 
destroy the Software (including providing certification of such destruction back to 
Intel) or return all copies of the Software to Intel. In the event of termination of 
this Agreement, all licenses granted to You hereunder will immediately terminate, 
except for licenses that you have previously distributed to Your end-users pursuant 
to the license grant above.

APPLICABLE LAWS. Any claims arising under or relating to this Agreement will be 
governed by the internal substantive laws of the State of Delaware or federal courts 
located in Delaware, without regard to principles of conflict of laws. Each Party 
hereby agrees to jurisdiction and venue in the courts of the State of Delaware for 
all disputes and litigation arising under or relating to this Agreement. The Parties 
agree that the United Nations Convention on Contracts for the International Sale of 
Goods is specifically excluded from application to this Agreement. The Parties consent 
to the personal jurisdiction of the above courts. 
Export Regulations / Export Control. You will not export, either directly or 
indirectly, any product, service or technical data or system incorporating such items 
without first obtaining any required license or other approval from the U. S. 
Department of Commerce or any other agency or department of the United States 
Government. In the event any product is exported from the United States or re-exported 
from a foreign destination by You, You will ensure that the distribution and 
export/re-export or import of the product is in compliance with all laws, regulations, 
orders, or other restrictions of the U.S. Export Administration Regulations and the 
appropriate foreign government. You agree that neither you nor any of your subsidiaries 
will export/re-export any technical data, process, product, or service, directly or 
indirectly, to any country for which the United States government or any agency thereof 
or the foreign government from where it is shipping requires an export license, or 
other governmental approval, without first obtaining such license or approval. 

GOVERNMENT RESTRICTED RIGHTS. The Software is a "commercial item" as that term is 
defined in 48 C.F.R. 2.101, consisting of "commercial computer software" and "commercial 
computer software documentation" as such terms are used in 48 C.F.R. 12.212. Consistent 
with 48 C.F.R. 12.212 and 48 C.F.R 227.7202-1 through 227.7202-4, You will provide the 
Software to the U.S. Government as an End User only pursuant to the terms and conditions 
therein. Contractor or Manufacturer is Intel Corporation, 2200 Mission College Blvd., 
Santa Clara, CA 95052. 

Assignment. You may not delegate, assign or transfer this Agreement, the license(s) 
granted or any of Your rights or duties hereunder, expressly, by implication, by operation 
of law, by way of merger (regardless of whether You are the surviving entity) or acquisition, 
or otherwise and any attempt to do so, without Intel’s express prior written consent, will 
be null and void. Intel may assign this Agreement, and its rights and obligations hereunder, 
in its sole discretion. 

Entire Agreement. The terms and conditions of this Agreement constitutes the entire 
agreement between the parties with respect to the subject matter hereof, and merges 
and supersedes all prior, contemporaneous agreements, understandings, negotiations and 
discussions. Neither of the parties hereto will be bound by any conditions, definitions, 
warranties, understandings or representations with respect to the subject matter hereof 
other than as expressly provided for herein. Intel is not obligated under any other 
agreements unless they are in writing and signed by an authorized representative of Intel. 
Without limiting the foregoing, terms and conditions on any purchase orders or similar 
materials submitted by You to Intel, and any terms contained in Intel’s standard 
acknowledgment form that are in conflict with these terms, will be of no force or effect. 
Attorneys’ Fees. In the event any proceeding or lawsuit is brought by Intel or You in 
connection with this Agreement, the prevailing party in such proceeding will be entitled 
to receive its costs, expert witness fees and reasonable attorneys’ fees, including costs 
and fees on appeal. 
No Agency. Nothing contained herein will be construed as creating any agency, employment 
relationship, partnership, principal-agent or other form of joint enterprise between the 
parties. 
Severability. In the event that any provision of this Agreement will be unenforceable or 
invalid under any applicable law or be so held by applicable court decision, such 
unenforceability or invalidity will not render this Agreement unenforceable or invalid as 
a whole, and, in such event, such provision will be changed and interpreted so as to best 
accomplish the objectives of such unenforceable or invalid provision within the limits of 
applicable law or applicable court decisions. 
Waiver. The failure of either party to require performance by the other party of any 
provision hereof will not affect the full right to require such performance at any time 
thereafter; nor will the waiver by either party of a breach of any provision hereof be 
taken or held to be a waiver of the provision itself. 
Language. This Agreement is in the English language only, which language will be controlling 
in all respects, and all versions of this Agreement in any other language will be for 
accommodation only and will not be binding on you or Intel. All communications and notices 
made or given pursuant to this Agreement, and all documentation and support to be provided, 
unless otherwise noted, will be in the English language.


SLAOEMISV1/RBK/11-02-17
 
EXHIBIT “A”
INTEL SOFTWARE LICENSE AGREEMENT 
(Final, Single User)

IMPORTANT - READ BEFORE COPYING, INSTALLING OR USING.

Do not use or load software from this site or any associated materials (collectively, the 
"Software") until you have carefully read the following terms and conditions. By loading or 
using the Software, you agree to the terms of this Agreement, which Intel may modify from 
time to time. If you do not wish to so agree, do not install or use the Software.

LICENSE. You may copy the Software onto a single computer for your personal, or internal 
business purpose use, and you may make one back-up copy of the Software, subject to these 
conditions:
•	You may not copy, modify, rent, sell, distribute or transfer any part of the Software 
except as provided in this Agreement, and you agree to prevent unauthorized copying of the 
Software. 
•	You may not reverse engineer, decompile, or disassemble the Software. 
•	You may not sublicense or permit simultaneous use of the Software by more than one 
user. 
•	The Software may contain the software or other property of third party suppliers, 
some of which may be identified in, and licensed in accordance with, any enclosed 
“license.txt” file or other text or file. 

OWNERSHIP OF SOFTWARE AND COPYRIGHTS. Title to all copies of the Software remains with Intel 
or its suppliers. The Software is copyrighted and protected by the laws of the United States 
and other countries, and international treaty provisions. You may not remove any copyright 
notices from the Software. Intel may make changes to the Software, or to items referenced 
therein, at any time without notice, but is not obligated to support or update the Software. 
Except as otherwise expressly provided, Intel grants no express or implied right under Intel 
patents, copyrights, trademarks, or other intellectual property rights. You may transfer the 
Software only if the recipient agrees to be fully bound by these terms and if you retain no 
copies of the Software.

EXCLUSION OF OTHER WARRANTIES. THE SOFTWARE IS PROVIDED "AS IS" WITHOUT ANY EXPRESS OR 
IMPLIED WARRANTY OF ANY KIND INCLUDING WARRANTIES OF MERCHANTABILITY, NONINFRINGEMENT, 
OR FITNESS FOR A PARTICULAR PURPOSE. Intel does not warrant or assume responsibility for 
the accuracy or completeness of any information, text, graphics, links or other items 
contained within the Software.

LIMITATION OF LIABILITY. IN NO EVENT WILL INTEL OR ITS SUPPLIERS BE LIABLE FOR ANY DAMAGES 
WHATSOEVER (INCLUDING, WITHOUT LIMITATION, LOST PROFITS, BUSINESS INTERRUPTION, OR LOST 
INFORMATION) ARISING OUT OF THE USE OF OR INABILITY TO USE THE SOFTWARE, EVEN IF INTEL HAS 
BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGES. SOME JURISDICTIONS PROHIBIT EXCLUSION OR 
LIMITATION OF LIABILITY FOR IMPLIED WARRANTIES OR CONSEQUENTIAL OR INCIDENTAL DAMAGES, SO 
THE ABOVE LIMITATION MAY NOT APPLY TO YOU. YOU MAY ALSO HAVE OTHER LEGAL RIGHTS THAT VARY 
FROM JURISDICTION TO JURISDICTION.
TERMINATION OF THIS AGREEMENT. Intel may terminate this Agreement at any time if you violate 
its terms. Upon termination, you will immediately destroy the Software or return all copies 
of the Software to Intel.
APPLICABLE LAWS. Claims arising under this Agreement will be governed by the laws of Delaware, 
excluding its principles of conflict of laws and the United Nations Convention on Contracts 
for the Sale of Goods. You may not export the Software in violation of applicable export laws 
and regulations. Intel is not obligated under any other agreements unless they are in writing 
and signed by an authorized representative of Intel.
GOVERNMENT RESTRICTED RIGHTS. The Software is provided with "RESTRICTED RIGHTS." Use, 
duplication, or disclosure by the Government is subject to restrictions as set forth in 
FAR52.227-14 and DFAR252.227-7013 et seq. or its successor. Use of the Software by the 
Government constitutes acknowledgment of Intel's proprietary rights therein. Contractor or 
Manufacturer is Intel Corporation, 2200 Mission College Blvd., Santa Clara, CA 95052. 

