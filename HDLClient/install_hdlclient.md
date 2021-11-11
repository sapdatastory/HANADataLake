# HANA Data Lake(IQ) Client 설치

HANA DATALAKE Client 바이너리 파일을 다운로드하고 압축을 해제합니다.

hdl@blizzard2:~/prod/ebf30098> tar xvzf HANADLCLIENT10004_0-80006193.TGZ 

hdl@blizzard2:~/prod/ebf30098> ./setup.bin -i console
Preparing to install
Extracting the JRE from the installer archive...
Unpacking the JRE...
Extracting the installation resources from the installer archive...
Configuring the installer for this system's environment...

Launching installer...

===============================================================================
SAP HANA Cloud, Data Lake IQ Client              (created with InstallAnywhere)
-------------------------------------------------------------------------------

Preparing CONSOLE Mode Installation...




===============================================================================
Introduction
------------

InstallAnywhere will guide you through the installation of SAP HANA Cloud, 
Data Lake IQ Client 1.0 (Build 17.1.04.00.2319) .

It is strongly recommended that you quit all programs before continuing with 
this installation.

Respond to each prompt to proceed to the next step in the installation.  If 
you want to change something on a previous step, type 'back'.

You may cancel this installation at any time by typing 'quit'.

PRESS <ENTER> TO CONTINUE: 



===============================================================================
Choose Install Folder
---------------------

Where would you like to install?

  Default Install Folder: 

ENTER AN ABSOLUTE PATH, OR PRESS <ENTER> TO ACCEPT THE DEFAULT
      : /home/hdl/hdl04    

INSTALL FOLDER IS: /home/hdl/hdl04
   IS THIS CORRECT? (Y/N): y
The directory /home/hdl/hdl04 does not exist. Do you want to create it?
    (Y/N): y



===============================================================================
Choose Install Set
------------------

Please choose the Install Set to be installed by this installer.

  ->1- Typical

    2- Customize...

ENTER THE NUMBER FOR THE INSTALL SET, OR PRESS <ENTER> TO ACCEPT THE DEFAULT
   : 



===============================================================================
End-user License Agreement
--------------------------

 1)  Americas and Asia Pacific                    2)  Argentina               

 3)  Asia Pacific Region - General                4)  Australia               

 5)  Belgium(English)                             6)  Brazil                  

 7)  Canada                                       8)  Denmark                 

 9)  Europe,Middle East, and Africa - General     10) France(English)         

 11) France(French)                               12) Germany(English)        

 13) Hong Kong                                    14) India                   

 15) Italy(English)                               16) Italy(Italian)          

 17) Japan                                        18) Korea                   

 19) Latin America Countries - Other than Argent  20) Malaysia                

 21) Mexico                                       22) Netherlands             

 23) New Zealand                                  24) Norway                  

 25) People's Republic of China(PRC)              26) Singapore               

 27) South Africa                                 28) Spain(English)          

 29) Spain(Spanish)                               30) Sweden                  

 31) Switzerland(English)                         32) Taiwan                  

 33) United Kingdom                               34) United States of America

 35) Any Other Locations                                                      


Please enter the number of the location you are installing. (1-35) (Default:
   1): 18

LICENSE AGREEMENT

General (applies to all countries,
except those for which a specific
country/language version is posted)

IMPORTANT NOTICE: READ THIS LICENSE AGREEMENT CAREFULLY 
BEFORE USING THE ENCLOSED PROGRAM.  YOU MAY USE THE PROGRAM 
ACQUIRED ONLY IN THE COUNTRY IN WHICH THIS LICENSE WAS 
ACCEPTED, AND ONLY IN ACCORDANCE WITH THE FOLLOWING TERMS 
AND CONDITIONS.  IF YOU DO NOT AGREE TO BE BOUND BY THESE 
TERMS, YOU MAY NOT USE THE PROGRAM. BY DOWNLOADING, 
INSTALLING, OR USING THE PROGRAM IN ANY WAY, YOU ACKNOWLEDGE
THAT YOU HAVE READ, UNDERSTAND AND AGREE TO THE TERMS OF 
THIS AGREEMENT.  IF YOU DO NOT AGREE WITH THESE TERMS, 
PRESENT YOUR RECEIPT OR OTHER PROOF OF PURCHASE, TOGETHER 
WITH THE PROGRAM MEDIA, DOCUMENTATION AND PACKAGING (IF ANY)
TO THE ENTITY FROM WHICH YOU OBTAINED THIS PRODUCT WITHIN 30
DAYS TO REQUEST A REFUND.  THIS IS A LICENSE AND NOT A SALE.


Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

If You, Your company or your public agency have signed a 
written software license agreement with Sybase, Inc., SAP 
AG, or one of their subsidiaries or affiliated group 
companies, such signed license agreement shall supersede and
replace this agreement and any other license agreement with 
Sybase, Inc., SAP AG or one of their subsidiaries or 
affiliated group companies that is embedded in or 
accompanying this program.

AS USED HEREIN, �SAP� IS THE COMPANY WITH WHOM YOU ARE 
PURCHASING THE SOFTWARE LICENSES OR RELATED SERVICES, EITHER
DIRECTLY OR INDIRECTLY THROUGH AN AUTHORIZED SAP PARTNER.  
FOR THE PURPOSE OF CLARIFICATION, IN CASE OF OEM, THE 
RELEVANT SAP COMPANY IS THE ONE FROM WHOM YOU ARE PURCHASING
THE SOFTWARE INDIRECTLY THROUGH AN AUTHORIZED SAP PARTNER.

Installation by Agent or other Third Party.  If you are 
downloading or installing the Program on behalf of another 
person or entity, you hereby represent and warrant that you 
have the authority to bind the party or entity for which you

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

are performing the download or installation to the terms and
conditions of this Agreement.  If you do not have such 
authority, you may not download or install the Program.


1.       ABBREVIATIONS AND DEFINITIONS. Abbreviations and 
definitions appear at the end of this Agreement.

2.      LICENSE.
        2.1 Subject to the terms and conditions set forth in this
Software License Agreement, SAP grants to You a 
non-exclusive, non-transferable license to Use the Primary 
Copy of each licensed Program (and make and Use each 
licensed Secondary Copy) at the location(s) specified on the
Order or reseller order.  Each Program shall be subject to 
the usage limitations based on quantity and type of license 
purchased, as indicated on the Order or reseller order. If 
any technology used by You reduces the number of devices 
that directly Use the Program, the number of Seats shall 
include all inputs to the front-end technology.  You may Use

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

the Program (and accompanying Documentation) solely for Your
internal business purposes by Your employees, agents and 
contractors and on the Operating System Software specified 
in the Order or reseller order, unless otherwise permitted 
by the type of license purchased.  If the type of license is
not indicated in the Order or reseller order, each copy 
shall be licensed for a single Seat on a single Machine.  
The Program, license, media and Documentation may not be 
transferred, sold, assigned, sublicensed or otherwise 
conveyed (whether by operation of law or otherwise) to 
another party without SAP's prior written consent and 
payment of any applicable fees in accordance with SAP's then
current policies.  The Program may be transferred to another
Machine, site or Operating System Software only upon prior 
written notice and subject to SAP's transfer policies and 
fees then in effect
        2.2 You understand and agree that some SAP Programs and 
license types are subject to additional or supplemental 
terms and conditions ("Product Specific License Terms") that
are posted on www.sybase.com/pslt as of the date of the 

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

Order or reseller order for such Programs.  Product Specific
License Terms are written and shall be enforceable in the 
English language.  You acknowledge that You have had the 
opportunity to review the Product Specific License Terms 
applicable to each licensed Program prior to Using the 
Program in any way.  By ordering, installing or Using the 
Program in any way, You acknowledge and agree that You have 
read, understood and agreed to the applicable Product 
Specific License Terms.
        2.3 You may not copy the Program except (a) to make a 
reasonable number of copies of each Program solely for 
inactive backup or archival purposes, and (b) to make the 
number of Secondary Copies indicated in the Order or 
reseller order for the Program.  You may not modify, reverse
engineer, decompile or disassemble the Program (except as 
specifically permitted by law without the possibility of 
contractual waiver, or as expressly permitted in the 
Documentation). Transfer of the Program outside the country 
in which it was originally delivered to You is not permitted
without SAP's prior written consent and is subject to 

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

compliance with all applicable export regulations and 
restrictions.  If the Program includes more than one 
component product, Use of all components of the Program is 
restricted to the same Machine and the Program may not be 
unbundled for Use on different or additional Machines. You 
may not Use the Program for timesharing, hosting, rental or 
service bureau purposes, or otherwise allow direct or 
indirect (including over the Internet) access or Use of the 
Program by any third party (except consultants and 
contractors performing services for Your benefit as 
expressly permitted in Sections 2.1 and 5), without SAP's 
prior written consent and subject to any applicable fees.  
You may contract with a third party ("Outsourcer") to 
operate the Program on Your behalf and solely for Your 
benefit; however, You shall remain subject to all of the 
provisions of this Agreement and shall be liable for 
Outsourcer's compliance with the provisions of this 
Agreement.   You shall not remove any copyright notices or 
other proprietary notices from the Program, and shall 
reproduce such notices on all copies of the Program.  

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

Results of benchmark or other performance tests run on the 
Program may not be disclosed to any third party without 
SAP's prior written consent.
        2.4 SAP shall provide an access code permitting You to 
download each Primary Copy, or, if specified on the Order or
reseller order, ship such Primary Copy to You or your 
authorized reseller.  You, at Your own expense, shall be 
responsible for installing the Program and all Updates.
        2.5 Third party products ordered by You and delivered by 
SAP that are accompanied by a license agreement from the 
third party supplier are provided subject to such supplier 
license agreement. The terms of this Agreement shall not 
apply to such third party products, except that, as between 
You and SAP, the provisions of this Section 2.5, Section 3, 
Section 7.4 and Section 9.8 shall apply.  WITHOUT LIMITING 
THE FOREGOING, SAP PROVIDES SUCH THIRD PARTY PRODUCTS "AS 
IS" WITHOUT ANY INDEMNITIES OR WARRANTIES OF ANY KIND, 
WHETHER EXPRESS, IMPLIED OR STATUTORY, INCLUDING, WITHOUT 
LIMITATION, ANY WARRANTIES OF MERCHANTABILITY, SATISFACTORY 
QUALITY, NONINFRINGEMENT, ACCURACY OF INFORMATIONAL CONTENT,

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

CONDITIONS OF MERCHANTABLE QUALITY, OR FITNESS FOR A 
PARTICULAR PURPOSE.  SAP shall not be obligated to provide 
any Support or error correction services for such third 
party products, but such services may be available from the 
third party supplier.  Third party products not accompanied 
by a license agreement from the supplier shall be subject to
the terms of this Agreement.
        2.6 Within 30 calendar days following a written request 
from SAP, which shall be made no more often than once in any
12-month period, You shall provide an accurate written 
report of Programs then currently in Use by You.
        2.7 No more often than once in any 12-month period, SAP 
may, at its expense, upon written notice and during business
hours, audit the number of copies of the Program in Use and 
Your compliance with the applicable usage limitations set 
forth by this Agreement. The auditors shall protect the 
confidentiality of Your information.  If the Use of the 
Program is found to be greater than that for which You are 
licensed, You shall pay any additional amounts due based 
upon the list prices set forth in the Price List in effect 

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

upon the date of notice of the audit.  Your refusal to 
permit an audit within a period of 30 calendar days 
following receipt of notice shall be a material breach of 
this Agreement.

3.      PAYMENT.
  Payment is due to SAP or its assigns within 30 calendar 
days of the invoice date.  You will pay all applicable 
shipping and handling charges and sales, use, personal 
property or similar taxes, tariffs or governmental charges, 
exclusive of those based upon SAP's income and corporate 
franchise taxes.  You will reimburse SAP for all reasonable 
costs incurred (including reasonable attorneys' fees) in 
collecting past due amounts.

4.      SUPPORT AND TECHNICAL SERVICES.
  4.1 The payment of license fees does not entitle You to 
Support services or software Updates, however, Support and 
Updates are available from SAP under this Agreement upon the
payment of additional fees. Except with respect to specific 

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

Programs designated by SAP, You agree to purchase a 
technical support plan ("Support") for the first year for 
each Program licensed.  Support commences on the date the 
Primary Copy is shipped to You (or an access code is 
provided to permit You to download a Primary Copy), or on 
the date You are invoiced for Secondary Copies ("the Support
Date").  Fees for Support ("Support Fees") shall be paid 
annually in advance. Support may be extended for one-year 
periods on the anniversary of each Support Date at the 
Support Fees set forth in the Price List for as long as SAP 
offers Support for the applicable Program.   If You do not 
provide a valid Purchase Order or written acknowledgement 
for the renewal of Support prior to expiration, Support will
be suspended on the expiration date.  Once Support has been 
suspended, You may reinstate Support only by paying SAP's 
then current reinstatement fee.
  4.2 Subject to the terms and conditions of this Agreement,
including, without limitation, Your payment of applicable 
Support Fees, SAP will provide You the level of Support 
corresponding to the Support Plan specified on the Order or 

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

reseller order. Support will be provided in accordance with 
SAP's then current plan description for such Support Plan 
solely to Your authorized support contacts for the 
"Supported Program" listed on such Order or reseller order. 
"Supported Program" shall mean the then current Major 
Version of a listed Program running on the specified 
Operating System Software and, for a period of 12 months 
after introduction of a new Major Version of such Program, 
the immediately preceding Major Version of the Program.  If 
You purchase Support for any Program in Use on a Machine, 
You must purchase the same level of Support for all copies 
of such Program on said Machine.  If You purchase Support 
for any Program in Use on a network, You must purchase the 
same level of Support for all copies of such Program on said
network.  SAP will use commercially reasonable efforts to 
correct or circumvent reported errors in the Supported 
Program that can be reproduced at a SAP support facility. 
SAP shall have no obligation to provide Support with respect
to: (a) Use of any Program on any computer system other than
the specified Machine and Operating System Software; (b) Use

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

of any version of the Program modified by You in breach of 
this Agreement; or (c) Use of versions of different 
Supported Programs together on a Machine or in a network 
that are not specified in the applicable Documentation as 
certified to be compatible.  SAP has no obligation to modify
any version of the Program to run with new versions of the 
Operating System Software.  SAP reserves the right to make 
corrections only to the most current generally available 
Major Version of the Program.
        4.3 Except as otherwise mutually agreed in writing, SAP 
will provide consulting or educational services described in
the Order or reseller order under the terms of this 
Agreement.  All consulting services provided under this 
Agreement will be on a time and materials basis.

5.      CONFIDENTIALITY.
  "Confidential Information" shall include the Program 
(including methods or concepts utilized therein) and all 
information identified by SAP as proprietary or 
confidential.  Confidential Information shall remain the 

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

sole property of SAP and shall not be disclosed to any third
party without the express written consent of SAP; except 
that You may disclose Confidential Information to 
consultants performing services for Your benefit, provided 
that such consultants are bound by a written non-disclosure 
agreement with You that protects such Confidential 
Information in a manner consistent with this Agreement.  
Except with respect to the Program, items will not be deemed
Confidential Information if (a) available to the public 
other than by a breach of an agreement with SAP; (b) 
rightfully received from a third party not in breach of any 
obligation of confidentiality; (c) independently developed 
by You without access to the Confidential Information; or 
(d) proven to have been known to You at the time of 
disclosure.  You shall immediately inform SAP if You are 
required to produce Confidential Information by operation of
law, and if so requested by SAP, shall provide reasonable 
assistance to SAP in seeking to limit such production.  A 
copyright notice on a Program does not, by itself, 
constitute evidence of publication or public disclosure.

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 


  6.    OWNERSHIP AND PROPRIETARY RIGHTS.  Each Program is 
licensed, not sold.  All copyright and other intellectual 
property rights in the Program, Documentation, and media, 
and all copies thereof, are owned by SAP or its 
subsidiaries, or their respective licensors and are 
protected by copyright and/or trade secret laws and 
international treaty provisions.  SAP reserves and retains 
ownership in and to (i) all rights, title and interest to 
the Program, media, Documentation, and all copies thereof, 
(ii) all rights, title and interest to all copyright and 
other intellectual property rights in each Program and each 
copy of the Program, and (iii) all other rights not 
expressly granted herein.  You acquire only the 
non-exclusive non-transferable right to Use the Program 
subject to the conditions set forth in this Agreement, and 
do not acquire any ownership or distribution rights 
whatsoever in the Program.  When You have ceased Using the 
Program, You shall return or destroy the Program, media, 
Documentation, and all copies thereof.  A license to Use a 

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

Program does not include any right, implied or otherwise, to
implement patents or other intellectual property of SAP and 
its licensors.

7.      LIMITED WARRANTY AND LIMITATIONS ON LIABILITY.
        7.1 Unless otherwise specified in the Documentation, for 
a period of ninety (90) days from the date of shipment (or 
date on which an electronic download access code is made 
available) to You, SAP warrants that the Program, when Used 
in accordance with the Documentation, will operate in 
material conformity with such Documentation and the Program 
media shall be free of defects.  In the event of a 
non-conforming Program or defective media, Your sole remedy 
shall be, at SAP's option, replacement of the defective 
Program or a refund of the license fees received by SAP for 
the affected Program.  This limited warranty gives You 
specific legal rights. You may have other rights that vary 
from jurisdiction to jurisdiction.  SAP warranties extend 
solely to You, the original licensee.
        7.2 SAP DISCLAIMS ALL OTHER WARRANTIES AND CONDITIONS, 

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

EXPRESS OR IMPLIED, INCLUDING, WITHOUT LIMITATION, THE 
IMPLIED WARRANTIES OF MERCHANTABILITY, SATISFACTORY QUALITY,
NONINFRINGEMENT, ACCURACY OF INFORMATIONAL CONTENT, FITNESS 
FOR A PARTICULAR PURPOSE, AND CONDITIONS OF MERCHANTABLE 
QUALITY, WHETHER ARISING BY STATUTE OR IN LAW OR AS A RESULT
OF A COURSE OF DEALING OR USAGE OF TRADE, WITH RESPECT TO 
THE PROGRAM, DOCUMENTATION, SUPPORT OR OTHER SERVICES 
RELATED TO THE PROGRAM.  Some jurisdictions do not allow 
limitations on implied warranties so the above limitations 
may not apply to You.  NO WARRANTY IS MADE REGARDING THE 
RESULTS TO BE OBTAINED FROM ANY PROGRAM OR SERVICES, THAT 
THE PROGRAM WILL BE ERROR FREE, THAT ALL ERRORS IN THE 
PROGRAM WILL BE CORRECTED, OR THAT THE PROGRAM'S 
FUNCTIONALITY WILL MEET YOUR REQUIREMENTS.  YOU ACKNOWLEDGE 
YOUR RESPONSIBILITY TO (a) REGULARLY BACK UP DATA, AND (b) 
ADEQUATELY TEST PROGRAM PRIOR TO DEPLOYMENT.
        7.3 The Program and third party products are not 
fault-tolerant and are not designed, manufactured or 
intended for use in applications in which the failure of the
Program could lead directly or indirectly to death, personal

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

injury, or severe physical or environmental damage, 
including, without limitation, the on-line control of 
nuclear facilities, aircraft navigation or communication 
systems, air traffic control, direct life support machines, 
or weapons systems.  SAP AND ITS SUPPLIERS SPECIFICALLY 
DISCLAIM ANY EXPRESS OR IMPLIED WARRANTY OF FITNESS FOR SUCH
PURPOSES.
                        7.4 LIMITATIONS ON LIABILITY.  NEITHER SAP, NOR ITS 
SUBSIDIARIES, NOR ANY OF ITS LICENSORS SHALL BE LIABLE FOR 
ANY LOSS OR INACCURACY OF DATA, LOSS OF PROFITS OR INDIRECT,
SPECIAL, INCIDENTAL OR CONSEQUENTIAL DAMAGES, WHETHER BASED 
ON CONTRACT, TORT OR OTHER LEGAL THEORY, EVEN IF SUCH PARTY 
HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGES.  THE 
TOTAL LIABILITY OF SAP AND ITS SUBSIDIARIES, AND OTHER 
MEMBERS OF THE SAP GROUP, IF ANY, ARISING OUT OF THIS 
AGREEMENT OR YOUR USE OF THE PROGRAM OR RELATED SERVICES 
SHALL NOT EXCEED AN AMOUNT EQUAL TO THE LICENSE OR SERVICE 
FEES PAID FOR THE PROGRAM OR SERVICES GIVING RISE TO THE 
CLAIM.  LICENSORS OF SOFTWARE COMPONENTS INCLUDED IN SAP 
PRODUCTS SHALL NOT BE LIABLE FOR DIRECT DAMAGES.  Some 

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

jurisdictions do not allow the exclusion or limitation of 
certain damages, so the above limitations and exclusions may
not apply to You.

  8.    TERMINATION. SAP may terminate a license if You have 
not paid the fees due within 15 calendar days after written 
notice that payment is past due.  The license and all rights
to Use a Program shall terminate automatically and 
immediately without notice upon any transfer or attempted 
transfer of the Program without SAP's express written 
consent.  Either party may terminate this Agreement upon any
other material breach of this Agreement by the other party 
which has not been corrected within 45 calendar days after 
written notice.  Upon termination of this Agreement, all 
licenses granted hereunder shall terminate, You shall cease 
Using the Program and Documentation (whether or not modified
or merged into other materials) and You shall certify in 
writing to SAP that all copies (in any form or media) have 
been destroyed or returned to SAP.  Termination shall not 
relieve You from paying all fees accruing prior to 

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

termination and shall not limit either party from pursuing 
any other available remedies.  Sections 1, 3, 5, 6, 7, 8, 9,
10, and 11, shall survive termination of this Agreement.

9.      GENERAL.
        9.1     Neither this Agreement, nor any rights or obligations
arising hereunder, nor any license granted herein may be 
assigned by You (whether by operation of law or otherwise) 
without SAP's prior written consent.  Any such purported 
assignment shall be void.  The terms and conditions of the 
licenses granted hereunder shall be binding upon any 
permitted assignees or transferees, if any.
        9.2      This Agreement is the entire agreement of the 
parties and supersedes all previous and contemporaneous 
communications, representations, or agreements regarding the
subject matter hereof. This Agreement may be modified only 
in writing signed by both parties. Purchase Orders shall be 
binding as to the products and services ordered, the fees 
due and the site for installation or performance of 
services. Other terms and preprinted terms on or attached to

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

any Purchase Order shall be void even if SAP has 
acknowledged such Purchase Order. In the event of any 
conflict between the terms of an Exhibit A or reseller order
and a Purchase Order, the terms of the Exhibit A or reseller
order shall prevail over the Purchase Order.
        9.3     You shall not�transfer, directly or indirectly, any 
restricted Program or technical data received from SAP or 
its subsidiaries, or the direct product of such data, to any
destination or entity subject to export restrictions under 
U.S. law, unless prior written authorization is obtained 
from the appropriate U.S. agency.
        9.4     SAP shall not be liable by reason of any failure or 
delay in the performance of its obligations hereunder on 
account of:  acts by You, acts of God or the public enemy, 
war, terrorism, riots, strike, embargo, acts of civil or 
military authority, unavailability of communications 
facilities or energy sources, or any other cause that is 
beyond the reasonable control of SAP.
        9.5 The Program is restricted commercial computer 
software. If this license is acquired under a U.S. 

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

Government contract, Use, duplication or disclosure by the 
U.S. Government is subject to restrictions set forth in this
Agreement or in a written license agreement that 
incorporates applicable FAR provisions, for example FAR 
52.22719. SAP reserves all unpublished rights under the 
United States copyright laws.
        9.6     All notices relating to this Agreement shall be in 
writing and delivered by overnight delivery service or first
class prepaid mail with return receipt requested (in the 
case of SAP to the attention of its local Legal Department
        9.7 If any provision of this Agreement is held to be 
unenforceable, the parties shall substitute an enforceable 
provision for the affected provision that approximates the 
intent and economic effect of the affected provision.  The 
failure or delay by either party to enforce any term of this
Agreement shall not be deemed a waiver of such term.
        9.8. This Agreement and any claims arising out of or 
relating to this Agreement, regardless of the nature of such
claims, and its subject matter shall be governed by and 
construed under the laws of the state, territory and/or 

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

country in which SAP, as defined herein, is located, without
reference to its conflicts of law principles.  In the event 
of any conflicts between foreign law, rules, and 
regulations, and the law, rules, and regulations of the 
state, territory and/or country in which SAP, is located, 
the law, rules, and regulations of the state, territory 
and/or country in which SAP is located  shall prevail and 
govern.  The United Nations Convention on Contracts for the 
International Sale of Goods shall not apply to this 
Agreement.  The Uniform Computer Information Transactions 
Act as enacted shall not apply.  Licensee must initiate a 
cause of action for any claim(s) arising out of or relating 
to this Agreement and its subject matter within one (1) year
from the date when Licensee knew, or should have known after
reasonable investigation, of the facts giving rise to the 
claim(s).
        9.9 If you have any questions about this Agreement, write 
to your local SAP office, Attn: Legal Dept.

  10. COUNTRY UNIQUE TERMS.  If you purchased the Software 

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

in any territory specified below (the �Local Territory�), 
this section sets forth specific provisions as well as 
exceptions to the above terms and condition. To the extent 
any provision applicable to the Local Territory (the �Local 
Provision�) set forth below is in conflict with any other 
term or condition in this agreement, the Local Provision 
will supersede such other term or condition with respect to 
any licenses purchased in the Local Territory.

Australia

a) Limited Warranty and Limitations on Liability (Section 
7.2): The following replaces the terms of Section 7.2 in its
entirety:

7.2 Subject to Sections 7.5 and 7.6 below, SAP DISCLAIMS ALL
OTHER WARRANTIES AND CONDITIONS, EXPRESS OR IMPLIED, 
INCLUDING, WITHOUT LIMITATION, THE IMPLIED WARRANTIES OF 
MERCHANTABILITY, NONINFRINGEMENT, ACCURACY OF INFORMATIONAL 
CONTENT, FITNESS FOR A PARTICULAR PURPOSE, AND CONDITIONS OF

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

MERCHANTABLE QUALITY, WHETHER ARISING BY STATUTE OR IN LAW 
OR AS A RESULT OF A COURSE OF DEALING OR USAGE OF TRADE, 
WITH RESPECT TO THE PROGRAM, DOCUMENTATION, SUPPORT OR OTHER
SERVICES RELATED TO THE PROGRAM. Some jurisdictions do not 
allow limitations on implied warranties so the above 
limitations may not apply to You. NO WARRANTY IS MADE 
REGARDING THE RESULTS TO BE OBTAINED FROM ANY PROGRAM OR 
SERVICES, THAT THE PROGRAM WILL BE ERROR FREE, THAT ALL 
ERRORS IN THE PROGRAM WILL BE CORRECTED, OR THAT THE 
PROGRAM�S FUNCTIONALITY WILL MEET YOUR REQUIREMENTS. YOU 
ACKNOWLEDGE YOUR RESPONSIBILITY TO (a) REGULARLY BACK UP 
DATA, AND (b) ADEQUATELY TEST PROGRAM PRIOR TO DEPLOYMENT.

b) Limitations on Liability (Section 7.4): The following 
replaces the terms of Section 7.4 in its entirety and adds 
Sections 7.5 and 7.6:

7.4 To the full extent permitted by law, NEITHER SAP, ITS 
PARENT CORPORATION AND PARENT CORPORATION�S SUBSIDIARIES, 
NOR ANY OF ITS LICENSORS SHALL BE LIABLE FOR ANY INDIRECT, 

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

SPECIAL, INCIDENTAL OR CONSEQUENTIAL DAMAGES, INCLUDING, BUT
NOT LIMITED TO, LOSS OR INACCURACY OF DATA, LOSS OF PROFITS 
OR EXPECTED SAVINGS, LOSS OF OR DAMAGE TO GOODWILL OR ANY 
OTHER FORM OF EXPECTATION BENEFIT, OR LOSS OR DAMAGE ARISING
FROM ANY LIABILITY TO ANY THIRD PARTY, WHETHER BASED ON 
CONTRACT, TORT OR OTHER LEGAL THEORY, EVEN IF SUCH PARTY HAS
BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGES. THE TOTAL 
LIABILITY OF SAP AND ITS PARENT CORPORATION AND PARENT 
CORPORATION�S SUBSIDIARIES, IF ANY, ARISING OUT OF THIS 
AGREEMENT OR YOUR USE OF THE PROGRAM OR RELATED SERVICES 
SHALL NOT EXCEED AN AMOUNT EQUAL TO THE LICENSE OR SERVICE 
FEES PAID FOR THE PROGRAM OR SERVICES GIVING RISE TO THE 
CLAIM. LICENSORS OF SOFTWARE COMPONENTS INCLUDED IN SAP 
PRODUCTS SHALL NOT BE LIABLE FOR DIRECT DAMAGES.

7.5 In the event that any Program license or services 
supplied under this Agreement is deemed to constitute a 
supply of goods or services to a consumer as defined in the 
Trade Practices Act 1974 (C�th) as amended or other 
legislation (�the Acts�) nothing contained in this Agreement

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

excludes, restricts or modifies any condition, warranty or 
other obligation herein, where to do so is unlawful. To the 
full extent permitted by law, where the benefit of any such 
condition, warranty or other obligation is conferred upon 
You pursuant to any of the Acts, SAP�s sole liability for 
breach of any such condition, warranty or other obligation 
shall be limited to: (a) in relation to goods: (i) 
replacement or repair, or (ii) refund of the fees paid for 
such goods; and (b) in relation to services: (i) the 
supplying of the services again, or (ii) refund of the fees 
paid for such services; as in each case SAP may elect.

7.6 SAP�s goods come with guarantees that cannot be excluded
under the Australian Consumer Law. You are entitled to a 
replacement or refund for a major failure and for 
compensation for any other reasonably foreseeable loss or 
damage. You are also entitled to have the goods repaired or 
replaced if the goods fail to be of acceptable quality and 
the failure does not amount to a major failure. These rights
may be lawfully limited in respect of goods or services not 

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

ordinarily acquired for personal, domestic or household use 
or consumption.  To request a replacement or a refund, 
please send your written request to SAP Australia Pty Ltd. 
Level 7, Northside Gardens 168 Walker Street North Sydney, 
NSW, 2060, Australia or an email to info.australia@sap.com. 
For further details regarding these guarantees and any 
limitation applied to them, please contact SAP.

Belgium and Denmark

a) Limitations on Liability (Section 7.4): The following 
replaces the terms of Section 7.4 in its entirety:

7.4 NEITHER SAP, NOR ITS SUBSIDIARIES, NOR ANY OF ITS 
LICENSORS SHALL BE LIABLE FOR ANY LOSS OR INACCURACY OF 
DATA, LOSS OF PROFITS OR INDIRECT, SPECIAL, INCIDENTAL OR 
CONSEQUENTIAL DAMAGES, WHETHER BASED ON CONTRACT, TORT OR 
OTHER LEGAL THEORY, EVEN IF SUCH PARTY HAS BEEN ADVISED OF 
THE POSSIBILITY OF SUCH DAMAGES. EXCEPT IN CASES OF FRAUD, 
WILFUL MISCONDUCT OR BREACH OF A MATERIAL OBLIGATION (WHERE 

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

THE ABSENCE OF COMPLIANCE WITH THAT OBLIGATION WOULD VOID 
THE CONTRACT FROM ITS SUBSTANCE), THE TOTAL LIABILITY OF SAP
AND ITS SUBSIDIARIES, IF ANY, ARISING OUT OF THIS AGREEMENT 
OR YOUR USE OF THE PROGRAM OR RELATED SERVICES SHALL NOT 
EXCEED AN AMOUNT EQUAL TO THE LICENSE OR SERVICE FEES PAID 
FOR THE PROGRAM OR SERVICES GIVING RISE TO THE CLAIM.  
LICENSORS OF SOFTWARE COMPONENTS INCLUDED IN SAP PRODUCTS 
SHALL NOT BE LIABLE FOR DIRECT DAMAGES.

Germany

a) Limitations on Liability (Section 7.4): the following 
replaces the terms of Section 7.4 in its entirety:

7.4.1 Except in cases of willful misconduct or gross 
negligence neither SAP, any SAP Group Company, nor any of 
its licensors shall be liable for:
        a) any loss or inaccuracy of data, loss of profits, loss 
resulting from business disruption, loss of contracts, loss 
of revenue, loss of anticipated savings, loss of goodwill, 

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

lost or wasted management time or time of other employees or
contractors, and/or
        b) any indirect, special, incidental or consequential 
damages, whether based on contract, tort or other legal 
theory, even if such party has been advised of the 
possibility of such damages.

7.4.2 Except in cases of willful misconduct or gross 
negligence and in cases under the product liability act, the
total liability of SAP and of any SAP Group Company, if any,
arising out of this Agreement whether based on contract, 
tort or other legal theory, or Customer's use of the Program
or related services shall not exceed an amount equal to the 
license or service fees paid for the Program or service 
giving rise to the claim.

7.4.3 Licensors of software components included in the SAP 
products shall not be liable for direct damages.

7.4.4 Neither SAP, any SAP Group Company, nor any of its 

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

licensors shall be liable for damages caused by a negligent 
breach of a non-material contractual obligation or for 
damages considered atypical or unforeseeable in the scope of
this Agreement.

New Zealand

a) Limitations on Liability (Section 7.4): the following 
replaces the terms of Section 7.4 in its entirety and adds 
section 7.5:

7.4 NEITHER SAP, NOR ITS SUBSIDIARIES, NOR ANY OF ITS 
LICENSORS SHALL BE LIABLE FOR ANY INDIRECT, SPECIAL, 
INCIDENTAL OR CONSEQUENTIAL DAMAGES, INCLUDING, BUT NOT 
LIMITED TO, LOSS OR INACCURACY OF DATA, LOSS OF PROFITS OR 
EXPECTED SAVINGS, LOSS OF OR DAMAGE TO GOODWILL OR ANY OTHER
FORM OF EXPECTATION BENEFIT, OR LOSS OR DAMAGE ARISING FROM 
ANY LIABILITY TO ANY THIRD PARTY, WHETHER BASED ON CONTRACT,
TORT OR OTHER LEGAL THEORY, EVEN IF SUCH PARTY HAS BEEN 
ADVISED OF THE POSSIBILITY OF SUCH DAMAGES.  THE TOTAL 

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

LIABILITY OF SAP AND ITS SUBSIDIARIES, IF ANY, ARISING OUT 
OF THIS AGREEMENT OR YOUR USE OF THE PROGRAM OR RELATED 
SERVICES SHALL NOT EXCEED AN AMOUNT EQUAL TO THE LICENSE OR 
SERVICE FEES PAID FOR THE PROGRAM OR SERVICES GIVING RISE TO
THE CLAIM.  LICENSORS OF SOFTWARE COMPONENTS INCLUDED IN SAP
PRODUCTS SHALL NOT BE LIABLE FOR DIRECT DAMAGES.

7.5 In the event that any Program license or services 
supplied under this Agreement is deemed to constitute a 
supply of goods or services to a consumer as defined in the 
Consumer Guarantees Act 1993 as amended or other legislation
("the Acts") nothing contained in this Agreement excludes, 
restricts or modifies any condition, warranty or other 
obligation herein, where to do so is unlawful.  To the full 
extent permitted by law, where the benefit of any such 
condition, warranty or other obligation is conferred upon 
You pursuant to any of the Acts, SAP's sole liability for 
breach of any such condition, warranty or other obligation 
shall be limited to:  (a) in relation to goods: (i) 
replacement or repair, or (ii) refund of the fees paid for 

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

such goods; and (b) in relation to services: (i) the 
supplying of the services again, or (ii) refund of the fees 
paid for such services; as in each case SAP may elect.

South Africa

a) Limitations on Liability (Section 7.4): The following 
replaces the terms of Section 7.4 in its entirety:

7.4 UNDER NO CIRCUMSTANCES SHALL SAP, ANY SAP GROUP COMPANY,
NOR ANY OF SAP'S OR ANY SAP GROUP COMPANY'S LICENSORS BE 
LIABLE TO THE CUSTOMER FOR ANY OF THE FOLLOWING TYPES OF 
LOSS OR DAMAGE ARISING UNDER OR IN RELATION TO THIS 
AGREEMENT (WHETHER ARISING OUT OF ANY INDEMNITY IN THIS 
AGREEMENT, BREACH OF CONTRACT, DELICT (INCLUDING, BUT NOT 
LIMITED TO NEGLIGENCE AND GROSS NEGLIGENCE), 
MISREPRESENTATION (WHETHER UNDER THE LAW OF DELICT OR 
STATUTORY), BREACH OF STATUTORY DUTY, BREACH OF WARRANTY, 
CLAIMS BY THIRD PARTIES FROM ANY REPUDIATORY, MATERIAL OR 
OTHER BREACH (HOWEVER MINOR) OF THIS AGREEMENT (WHETHER OR 

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

NOT INTENTIONAL), FROM WILFUL MISCONDUCT OR OTHERWISE): (a) 
(i) ANY LOSS OR INACCURACY OF DATA, (ii) LOSS OF PROFITS, 
(iii) LOSS OF BUSINESS, (iv) LOSS RESULTING FROM BUSINESS 
DISRUPTION, (v) LOSS OF CONTRACTS, (vi) LOSS OF REVENUE, 
(vii) LOSS OF ANTICIPATED SAVINGS, (viii) LOSS OF GOODWILL, 
(ix) LOSS OF REPUTATION, (x) PAYMENTS MADE TO A THIRD PARTY,
(xi) LOST OR WASTED MANAGEMENT TIME OR TIME OF OTHER 
EMPLOYEES OR CONTRACTORS, (xii) CHARGES LEVIED BY ANY THIRD 
PARTY, (xiii) ANY ADDITIONAL BANK BORROWINGS OR CHARGES 
RELATING TO BANK BORROWINGS, (xiv) COSTS OF RECOVERING DEBT 
(REGARDLESS OF WHETHER DUE) OR (xv) ANY ADMINISTRATIVE COSTS
(REGARDLESS OF WHETHER THESE TYPES OF LOSS OR DAMAGE LISTED 
IN THIS SUB-PARAGRAPH (a) ARE DIRECT, INDIRECT, SPECIAL OR 
CONSEQUENTIAL); OR (b) ANY INDIRECT, SPECIAL, INCIDENTAL OR 
CONSEQUENTIAL LOSSES OR DAMAGES WHATSOEVER, EVEN IF SUCH 
PARTY HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH LOSSES OR 
DAMAGES.  UNDER NO CIRCUMSTANCES SHALL THE TOTAL AGGREGATE 
LIABILITY OF SAP (OR SAP GROUP COMPANIES) TO THE CUSTOMER 
(HOWEVER ARISING) UNDER OR IN CONNECTION WITH THIS 
AGREEMENT, INCLUDING (BUT NOT LIMITED TO) LIABILITY UNDER 

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

ANY INDEMNITY IN THIS AGREEMENT, FOR BREACH OF CONTRACT, 
DELICT (INCLUDING, BUT NOT LIMITED TO NEGLIGENCE AND GROSS 
NEGLIGENCE), MISREPRESENTATION (WHETHER UNDER THE LAW OF 
DELICT OR STATUTORY), BREACH OF STATUTORY DUTY, BREACH OF 
WARRANTY, CLAIMS BY ANY THIRD PARTIES FROM ANY REPUDIATORY, 
MATERIAL OR OTHER BREACH (HOWEVER MINOR) OF THIS AGREEMENT 
(WHETHER OR NOT INTENTIONAL), FROM WILFUL MISCONDUCT OR 
OTHERWISE, EXCEED AN AMOUNT EQUAL TO THE LICENSE OR SUPPORT 
FEES PAID FOR THE PROGRAM OR SERVICES GIVING RISE TO THE 
CLAIM. LICENSORS OF SOFTWARE COMPONENTS INCLUDED IN SAP 
PRODUCTS SHALL NOT BE LIABLE FOR DIRECT DAMAGES.  
NOTWITHSTANDING ANY OTHER CLAUSE IN THIS AGREEMENT, SAP DOES
NOT EXCLUDE OR LIMIT ITS LIABILITY FOR DEATH OR PERSONAL 
INJURY CAUSED BY ITS NEGLIGENCE OR FOR ANY LIABILITY WHICH 
CAN NOT BE EXCLUDED BY LAW.

b) General (section 9.2): the following replaces the terms 
of Section 9.2 in its entirety:

9.2 This Agreement is the entire agreement between the 

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

parties and supersedes and extinguishes all previous and 
contemporaneous communications, representations, 
arrangements, understandings, collateral contracts, 
agreements or draft  agreements (both oral and written) 
regarding the subject matter hereof (including without 
limitation additional terms of any purchase orders, order 
acknowledgments or invoices) and no representation, 
condition, understanding or agreement of any kind, oral or 
written, shall be binding upon the parties unless 
incorporated herein. Each party acknowledges and agrees that
it does not enter into this Agreement on the basis of and 
does not rely and has not relied upon and shall have no 
remedy in respect of any oral or written statement, 
collateral or other warranties, assurances, undertakings or 
representations which were made, by or on behalf of the 
other party in relation to the subject matter of  this 
Agreement at any time before its signature  (whether 
negligently or innocently made) (together "Statements") 
except those expressly referred to in this Agreement.  
Nothing in this paragraph 9.2 shall operate to limit or 

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

exclude the liability of either party arising out of its 
fraud, fraudulent concealment or fraudulent 
misrepresentation.  This Agreement may be modified only in 
writing signed by both parties.  Purchase Orders shall be 
binding as to the products and services ordered, the fees 
due and the site for installation or performance of 
services.  Other terms and preprinted terms on or attached 
to any Purchase Order shall be void even if SAP has 
acknowledged such Purchase Order.  In the event of any 
conflict between the terms of an Exhibit A or reseller order
and a Purchase Order, the terms of the Exhibit A or reseller
order shall prevail over the Purchase Order.

United Kingdom and Europe, Middle East, and Africa (except 
Belgium, Denmark, Germany, Netherlands, Norway, South 
Africa, Sweden, and Switzerland)

a) Limitations on Liability (Section 7.4): The following 
replaces the terms of Section 7.4 in its entirety:


Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

7.4.1 UNDER NO CIRCUMSTANCES SHALL SAP, ANY SAP GROUP 
COMPANY, NOR ANY OF SAP'S OR ANY SAP GROUP COMPANY'S 
LICENSORS BE LIABLE TO THE CUSTOMER FOR ANY OF THE FOLLOWING
TYPES OF LOSS OR DAMAGE ARISING UNDER OR IN RELATION TO THIS
AGREEMENT  (WHETHER ARISING OUT OF LIABILITY UNDER BREACH OF
CONTRACT, TORT (INCLUDING BUT NOT LIMITED TO NEGLIGENCE), 
ANY INDEMNITY IN THIS AGREEMENT, MISREPRESENTATION (WHETHER 
TORTIOUS OR STATUTORY), BREACH OF STAUTORY DUTY, BREACH OF 
WARRANTY, CLAIMS BY THIRD PARTIES FROM ANY REPUDIATORY, 
MATERIAL OR OTHER BREACH (HOWEVER MINOR) OF THIS AGREEMENT 
(WHETHER OR NOT INTENTIONAL), FROM WILFUL MISCONDUCT OR 
OTHERWISE):
(a) (i) ANY LOSS OR INACCURACY OF DATA, (ii) LOSS OF 
PROFITS, (iii) LOSS OF BUSINESS (iv) LOSS RESULTING FROM 
BUSINESS DISRUPTION, (v) LOSS OF CONTRACTS, (vi) LOSS OF 
REVENUE, (vii) LOSS OF ANTICIPATED SAVINGS, (viii) LOSS OF 
GOODWILL, (ix)LOSS OF REPUTATION (x) PAYMENTS MADE TO A 
THIRD PARTY (xi) LOST OR WASTED MANAGEMENT TIME OR TIME OF 
OTHER EMPLOYEES OR CONTRACTORS, (xii) CHARGES LEVIED BY ANY 
THIRD PARTY, (xiii) ANY ADDITIONAL BANK BORROWINGS OR 

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

CHARGES RELATING TO BANK BORROWINGS, COSTS OF RECOVERING 
DEBT (REGARDLESS OF WHETHER DUE) OR (xiv) ANY ADMINISTRATIVE
COSTS, (REGARDLESS OF WHETHER THESE TYPES OF LOSS OR DAMAGE 
LISTED IN THIS SUB-PARAGRAPH (a) ARE DIRECT, INDIRECT, 
SPECIAL OR CONSEQUENTIAL); or
 (b) ANY INDIRECT, SPECIAL, INCIDENTAL OR CONSEQUENTIAL 
LOSSES OR DAMAGES WHATSOEVER,
EVEN IF SUCH PARTY HAS BEEN ADVISED OF THE POSSIBILITY OF 
SUCH LOSSES OR DAMAGES.

7.4.2 SUBJECT TO SECTION 7.4.4, UNDER NO CIRCUMSTANCES SHALL
THE TOTAL AGGREGATE LIABILITY OF SAP (OR SAP GROUP 
COMPANIES) TO YOU (HOWEVER ARISING) UNDER OR IN RELATION TO 
THIS AGREEMENT OR IN CONNECTION WITH YOUR USE OF THE PROGRAM
OR RELATED SERVICES, INCLUDING (BUT NOT LIMITED TO) 
LIABILITY FOR BREACH OF CONTRACT, TORT (INCLUDING 
NEGLIGENCE), UNDER ANY INDEMNITY IN THIS AGREEMENT, 
MISREPRESENTATION (WHETHER TORTIOUS OR STATUTORY), BREACH OF
STATUTORY DUTY, BREACH OF WARRANTY, CLAIMS BY THIRD PARTIES 
FROM ANY REPUDIATORY, MATERIAL OR OTHER BREACH (HOWEVER 

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

MINOR) OF THIS AGREEMENT (WHETHER OR NOT INTENTIONAL), FROM 
WILFUL MISCONDUCT OR OTHERWISE, EXCEED AN AMOUNT EQUAL TO 
THE LICENSE OR SERVICE FEES PAID FOR THE PROGRAM OR SERVICES
GIVING RISE TO THE CLAIM.

7.4.3 FOR THE AVOIDANCE OF DOUBT, LICENSORS OF SOFTWARE 
COMPONENTS INCLUDED IN SAP PRODUCTS SHALL NOT BE LIABLE TO 
YOU IN ANY CIRCUMSTANCES FOR DAMAGES (WHETHER DIRECT OR 
INDIRECT).

7.4.4 NOTWITHSTANDING ANY OTHER CLAUSE IN THIS AGREEMENT, 
SAP DOES NOT EXCLUDE OR LIMIT ITS LIABILITY FOR DEATH OR 
PERSONAL INJURY CAUSED BY ITS NEGLIGENCE OR FOR ANY 
LIABILITY WHICH CAN NOT BE EXCLUDED BY LAW.

b) General (Section 9.2): The following replaces the terms 
of Section 9.2 in its entirety and adds Section 9.2.1:

9.2 This Agreement is the entire agreement between the 
parties and supersedes and extinguishes all previous and 

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

contemporaneous communications, representations, 
arrangements, understandings, collateral contracts, 
agreements or draft agreements (both oral and written) 
regarding the subject matter hereof and no representation, 
term, condition, understanding or agreement of any kind, 
oral or written, shall be binding upon the parties unless 
incorporated herein. Each party acknowledges and agrees that
it does not enter into this Agreement on the basis of and 
does not rely and has not relied upon any oral or written 
statements, collateral or other warranties, assurances, 
undertakings or representations which were made by or on 
behalf of the other party in relation to the subject matter 
of this Agreement at any time before its signature (whether 
negligently or innocently made) (together Statements), 
except those expressly set out in this Agreement Each party 
hereby waives all rights and remedies which might otherwise 
be available to it in relation to such Statements, but for 
Section 9.2.Nothing in this Section 9.2 shall operate to 
limit or exclude the liability of either party arising out 
of its fraud, fraudulent concealment or fraudulent 

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

misrepresentation.

9.2.1 This Agreement may be modified only in writing signed 
by both parties.  Purchase Orders shall be binding as to the
products and services ordered, the fees due and the site for
installation or performance of services.  Other terms and 
preprinted terms on or attached to any Purchase Order shall 
be void even if SAP has acknowledged such Purchase Order.  
In the event of any conflict between the terms of an Exhibit
A or reseller order and a Purchase Order, the terms of the 
Exhibit A or reseller order shall prevail over the Purchase 
Order.

11. ABBREVIATIONS AND DEFINITIONS.

"Agreement" - This Software License Agreement, together with
each Exhibit A or reseller order, any applicable 
supplements, amendments, addenda, Product Specific License 
Terms, and each Purchase Order.


Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

"Application License" or "AP" - The limited right to install
the Program on any Server at the single physical location 
(or approved hosting site) specified for such license in the
applicable Order or reseller order.
"Chip" - Electronic circuitry containing one or more Cores, 
usually on a silicon wafer.
"Chip License", or "CH" - The limited right to Use the 
Program on a Chip in a production environment.
"Chip Development and Testing License" or "DH - The limited 
right to Use the Program on a Chip for development and 
testing purposes only and not in a parallel production 
environment.  See "Chip" and "Chip License".
"Chip Standby License" or "SH" - The limited right to access
and Use a Standby Copy of a Program licensed under a Chip 
License for the duration of an interruption in the operation
of the production Server. See "Chip", "Chip License".
"Cluster License", or "CL" - The limited right to Use the 
Program on any number of Servers at the single physical 
location specified for such license in the applicable Order 
or reseller order, but only if each such Server is part of a

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

load-balanced or failover configuration and in the aggregate
provides no greater access to the Program or any associated 
data than would be provided by a single Server operating 
alone.
"Concurrent User" or "CU"- A specific, identifiable, unique 
input/output device capable of directly or indirectly 
accessing and using a Program such as (without limitation) a
terminal, personal computer, single user workstation, 
personal digital assistant ("PDA"), wireless device or real 
time device.  See "Concurrent User License".
"Concurrent User License" - The limited right for a maximum 
number of Concurrent Users equal to the quantity of such 
licenses purchased, as indicated in the applicable Order or 
reseller order, to directly or indirectly access the Program
on a single specified licensed Server at any given instant 
in time.
"Core" - A functional unit within a computing device that 
interprets and executes software instructions.
"CPU" - The unit of measurement used in the CPU License type
(see "CPU License") and the Internet Access License type 

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

(see "Internet Access License").  Unless otherwise specified
on the Order, for SAP Programs, the number of CPUs is equal 
to the number of Processors or Cores on a Machine, and for 
iAnywhere Solutions Programs, the number of CPUs is equal to
the number of Chips on a Machine irrespective of the number 
of Processors or Cores.
"CPU Development and Testing License" or "DT" - The limited 
right to Use the Program on a Machine on which the number of
CPUs is no greater than the number of licenses purchased, as
specified on the Order, and to Use such Program for 
development and testing purposes only and not in a parallel 
production environment.  See "CPU" and "CPU License".
"CPU License" or "CP" - The limited right to Use the Program
on a Server on which the number of CPUs is no greater than 
the number of licenses purchased, as specified on the Order 
or reseller order.  The number of Seats that may access the 
Program shall be limited only by the capacity of the 
licensed CPUs, and may include internal usage by Seats 
within the Customer's organization, and external usage by 
Seats outside of the Customer's organization accessing the 

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

Program via the Internet ("Internet Users").  Internet Users
may not Use the Program to develop or modify applications or
perform other programming tasks, and may only Use the 
Program in conjunction with Customer's applications.  The 
license fee payable by Customer for the copy or copies of 
the Program shall be determined by multiplying the number of
CPUs on the Server or Servers Using the Program by the 
applicable rate, each as specified on the Order or reseller 
order.  In the event that the number of CPUs on a Server is 
increased, Customer shall report such increase, execute a 
new Exhibit A and pay an additional amount determined by 
multiplying the incremental CPUs by the then applicable rate
per CPU set forth in the Price List.
"Data Storage Unit" or "DSU" - The unit of measurement used 
in the Storage License types which quantifies the volume of 
data stored inside the main database of a Program.  Certain 
Programs tend to compress data to an amount less than the 
raw data.  The amount of compression applied to the data may
vary depending on the characteristics of the data and the 
data types Used in the Program.

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

"Documentation" - Installation instructions and user manuals
supplied with the Program.
"ESD" in the column entitled "Media" - means Electronic 
Software Download.
"Exhibit A"- a standard form purchase authorization document
made available by SAP containing order information for each 
Customer order.
"Floating License" or "FL" - The limited right to install 
the Program on any number of workstation Machines, provided 
that at any given instant in time the total number of such 
workstation Machines on which Customer is permitted to Use 
the Program simultaneously may not exceed the number of 
licenses purchased.
"Internet Access License" or "IC" - The limited right to 
permit "External Internet Seats" to access a licensed 
Program, provided the number of CPUs on the Server Using the
licensed Program is   no greater than the quantity of such 
licenses purchased, as specified on the Order or reseller 
order.  The number of "External Internet Seats" shall be 
limited only by the capacity of the licensed CPUs.  

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

"External Internet Seats" shall mean Seats which access the 
specified Program via the Internet; provided that the person
at such Seat is not acting in the capacity of an employee, 
agent or independent contractor of Customer.  External 
Internet Seats may query the Program database and update 
such database to the extent allowed by Customer's 
application, but may not Use the Program to develop or 
modify applications or perform other programming tasks. 
Customer may not Use the specified Program in connection 
with a website hosted by Customer on behalf of third 
parties.  An Internet Access License does not cover intranet
usage or other internal usage and Customer must acquire the 
necessary Seat licenses for all internal usage of the 
Program.  If Customer purchases (or renews) Support for a 
Program for which an Internet Access License has been 
obtained, Customer shall purchase the same level of Support 
for the Internet Access License as for such Program. The 
license fee payable by Customer for the copy or copies of 
the Program shall be determined by multiplying the number of
CPUs on the Server or Servers by the applicable rate, each 

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

as specified on the Order or reseller order.  In the event 
that the number of CPUs on a Server is increased, Customer 
shall report such increase, execute a new Exhibit A and pay 
an additional amount determined by multiplying the 
incremental CPUs by the then applicable rate per CPU set 
forth in the Price List.
"Machine" - A single computer hardware system identified on 
the applicable Order or reseller order (or in the event no 
single computer hardware system is identified in the Order 
or reseller order, the single computer hardware system where
the Program is in Use).running a single copy of the 
Operating System Software.
"Mainframe Base" or "MB" - The basic license fee applicable 
for certain mainframe Programs based upon the mainframe 
Machine model set forth in the applicable Order or reseller 
order.  For each copy of a Program designated as license 
type MB, Customer shall also pay the applicable MSU License 
fee based upon the then current MSU rating of the mainframe 
Machine.  See also "MSU (Millions of Service Units) 
License".

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

"Major Version" - A major release of a Program containing 
new features and functions.
"MSU (Millions of Service Units) License" or "MU" - The 
license fee payable by Customer for each copy of the Program
shall be determined by multiplying the number of MSUs for 
the Machine by the applicable rate and adding the applicable
Mainframe Base rate thereto, all as specified in the 
applicable Order or reseller order. In the event that the 
number of MSUs for the Machine is increased, Customer shall 
report such increase, execute a new Exhibit A, and pay an 
additional amount determined by multiplying the incremental 
number of MSUs by the then applicable MSU rate for the 
Program and adding any incremental base rate fee thereto, 
all as set forth in the Price List.  The number of users 
shall be limited only by the capacity of the licensed MSUs, 
and may include internal users within the Customer's 
organization, and external users outside of the Customers 
organization accessing the Program via the Internet 
("Internet Users").  Internet Users may not Use the Program 
to develop or modify applications or perform other 

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

programming tasks, and may only Use the Program in 
conjunction with Customer's applications.
"Multi-core Coefficient or Multi-core Scaling Coefficient" -
The scaling coefficient set forth in the Price List which is
applied to License and Support Price to determine the List 
Price for eligible License Types and Machines.
"Networked License" - The limited right for the number of 
Seats equal to the quantity of such licenses purchased, as 
specified in the Order or reseller order, to directly or 
indirectly Use a Program through licensed Server or Servers,
in a network..
"Networked Seat" - see "Seat".
"Operating System Software" - The operating system software 
on which the Program is licensed to be Used, as specified on
the Order or reseller order.
"Order" - A Purchase Order or Exhibit A signed by Customer 
and accepted by SAP.
"OT" - denotes "other", for products or services included on
an Order or reseller order, which are not otherwise defined.
"Price List" - SAP's then current price list for the country

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

in which the Programs are installed.
"Primary Copy" - A licensed copy of the Program provided by 
SAP or made available by SAP for electronic download, 
including a copy provided initially as a trial copy.
"Processor" - means "Core".
"Program" -The object code version of the software 
product(s) listed in the Order or reseller order, as well as
any and all Updates and authorized copies.  Although the 
Program media may contain other software products, Customer 
is licensed to Use only the designated Program.
"Purchase Order" - A purchase order or other 
purchase-authorizing document issued by Customer for SAP 
products and/or services and accepted by SAP, as confirmed 
by a SAP invoice.
"Quantity of Licenses" - The number of a particular license 
type, such as (without limitation) Server or Seat, licensed 
for a particular Program pursuant to an Order or reseller 
order.
"SAP Group" - means SAP, SAP AG or any group company of SAP 
or SAP AG or any company under common control (i.e. more 

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

than 50% voting control) with SAP or SAP AG.
"Seat", or "ST" - A specific, identifiable, unique 
input/output device capable of directly or indirectly 
accessing and using a Program such as (without limitation) a
terminal, personal computer, single user workstation, 
personal digital assistant ("PDA"), wireless device or real 
time device.  See "Networked License".
"Secondary Copy" - A licensed copy of the Program reproduced
by Customer from the Primary Copy.
"Server" - A Machine containing software, which permits it 
to await and fulfill services to other computers and in case
of a cluster or grid computing environment, each node or 
host Machine is considered an individual Server.
"Server License" or "SR" - The limited right to Use the 
Program on a Server, for access solely by licensed Seats or 
licensed Concurrent Users, as applicable.
"Standalone Seat" or "SS" - The limited right to install the
Program on a single workstation Machine (and not a server 
Machine) for access solely by the single workstation Machine
upon which it resides.

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

"Standby Concurrent User License" or "SC" - The limited 
right to access and Use a Standby Copy of a Program licensed
under a Concurrent User License in the event of an 
interruption of a production copy of the same Program.  See 
"Concurrent User License".
"Standby Copy" - means the Use of a Program by a Server for 
the purpose of processing data for the durations of an n 
interruption in the operation of the production Server.
"Standby CPU License" or "SF" - The limited right to access 
and Use a Standby Copy of a Program licensed under a CPU 
License in the event of an interruption of the production 
environment on another Server.
"Standby Server License" or "SV" - The limited right to Use 
a Standby Copy of a Program licensed under a Server License 
for the duration of an interruption in the operation of the 
production Server.
"Storage License" or "TB" - The limited right to store data 
in a Program such that the quantity of DSUs Used is no 
greater than the number of DSUs licensed, as specified in 
the Order or reseller order.  The license fee payable by 

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

Customer shall be determined by multiplying the number of 
DSUs by the applicable rate, each as specified on the Order 
or reseller order.  In the event the number of DSUs in a 
Program is increased, Customer shall report such increase, 
execute a new Exhibit A and pay an additional amount 
determined by multiplying the incremental storage capacity 
by the then applicable rate per DSU set forth in the Price 
List.  Storage may only be licensed in whole DSUs, and the 
number of DSUs shall be rounded up to the next higher whole 
DSU when determining the number of Storage Licenses 
required.
"Storage Development and Testing License" or "DB" - The 
limited right to store data in a Program up to the number of
DSUs licensed, and to Use such data for development and 
testing purposes only and not in a parallel production 
environment.  See "DSU" and "Storage License".
"Storage Standby License" or "SB" - The limited right to 
store data in a Standby Copy of a Program up to the number 
of DSUs licensed, and to Use such data in the event of an 
interruption of a production copy of the same Program.  See 

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

"DSU" and "Storage License".
"Support" - The technical support plan selected by Customer.
"Updates" - means error corrections, maintenance releases 
and Major Versions of the Program made available to SAP 
customers under certain SAP Support plans.
"Upgrade" - means (i) transfer of the Program to a Machine 
of a higher SAP Machine Class, i.e. transfer to a Machine 
that provides greater processing capacity, or (ii) Customer 
migration from one edition of a Program to another edition 
with increased functionality, e.g. from Advanced Edition to 
Enterprise Edition.
"Use" or "Using" - means to install, load, view, print, 
update, access, utilize, or store the Program.








Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

General v.2 12-2013


General v.2 12-2013






15


                                                            
                                                            
                                                            
                                                            
                                                            
                                                            
                                                            

Press ENTER to read the text [Type 'back' and press ENTER to skip the text] 
   : 

                                                            
                     
I agree to the terms of the SAP license for the install location specified. 
   (Y/N): y



===============================================================================
Pre-Installation Summary
------------------------

Please Review the Following Before Continuing:

Product Name:
    SAP HANA Cloud, Data Lake IQ Client 1.0 (Build 17.1.04.00.2319) 

Install Folder:
    /home/hdl/hdl04

Product Features:
    Data Lake IQ Client,
    Data Lake IQ ODBC Driver,
    Data Lake IQ,
    Data Lake IQ Web Drivers,
    SAP jConnect

Disk Space Information (for Installation Target): 
    Required:  356,948,790 Bytes
    Available: 9,052,098,560 Bytes

PRESS <ENTER> TO CONTINUE: 



===============================================================================
Ready To Install
----------------

InstallAnywhere is now ready to install SAP HANA Cloud, Data Lake IQ Client 
1.0 (Build 17.1.04.00.2319)  onto your system at the following location:

   /home/hdl/hdl04

PRESS <ENTER> TO INSTALL: 



===============================================================================
Installing...
-------------

 [==================|==================|==================|==================]
 [------------------|------------------|------------------|------------------]



===============================================================================
Install Complete
----------------

The installation was successful. SAP HANA Cloud, Data Lake IQ Client 1.0 
(Build 17.1.04.00.2319)  has been installed to:

/home/hdl/hdl04

hdl@blizzard2:~/prod/ebf30098> 
