## Week 53 :house_with_garden:

## Stretch goal on Q1 [Jan - Mar 2022] :muscle:
**What is new on next version:**
 - Release improve all speed issues for PGA show (API 398 + AIR 398)
 - Release new feature for CPS Air (smart card, coupon feature, daily note and add happy hour)
 - Implement new web APIs on new architecture wit CPS Air new version
      - PaymentMethod API
      - Credit Card APIs
      - Reference Table APIs
      - Create Course APIs
      - Sale Tab APIs 
      - Printer APIs 
      - PskUser APIs 
      - Time Keeper APIs 
      - Member APIs
  - Release App and APIs developer document system
  - Other (CPS GO 398 with APIv4)

## On-going work :runner:
| Mark | Priority | Type | Task | Status | 
| ------ | ------ | ------ | ------ | ------ |
| :white_large_square: | High	| **Enhancement** | CPSAIR-307716 No Smart Cards credits are available! CPS Air PDT	| Unresolved	| 
| :white_large_square: | Low	| **Enhancement** | CPSAIR-309488 Make the Daily Note store Specific	| Unresolved	|
| :runner: | High	| **New Feature** | CPSAIR-154898 Smart Card Redeem Support for CPSair	| **In Progress** |
| :white_large_square: | High	| **New Feature** | CPSAIR-218886 Coupon Support	| Unresolved	|
| :white_large_square: | Medium	| **New Feature** | CPSAIR-170288 Add happy hour functionality to CPS Air	| Unresolved	| 
| :white_large_square: | High	| Bug	| CPSAIR-336067 CPS Air: Cancel Split Payment After CC Charge - CC Charge is Lost	| Unresolved	|
| :white_large_square: | Medium	| Bug	| CPSAIR-312219 Smart Card Issue show price $0.00 on sale screen	| Unresolved	|
| :white_large_square: | High	| Email	| CPSAIR-325251 GRAND NATIONAL FOOD 6/16/21	| Unresolved	|
| :runner: | High	| Quality Check	| CPSAIR-341212 Rewrite & refactor teesheet control and reservation process and we were hoping it would be much faster with APIV4.	| **In Progress**	|
| :white_large_square: | High	| Task	| CPSAIR-307216 APIV4 - Created TerminalApi	| Unresolved	|
| :white_large_square: | High	| Task	| CPSAIR-307218 APIV4 - Created VersionApi	| Unresolved |
| :white_large_square: | Low	| Task	| CPSAIR-341652 SH Improve efficiency Member Class / Member Type 	| Unresolved	|
| :runner: | Medium	| Task	| CPSAIR-338684 Quality Check - Split Check Item QTY's Do Not Update When Combining Checks After An Item has Been Added To One Of The Checks	| **In Progress** |
| :white_large_square: | Low	| Task	| CPSGO-341213 Copy code GO API v396 Search Tee Time Error issue to APIV4 v398	| Unresolved |

## Work completed :ballot_box_with_check:

| Priority | Type | Task | Status | Fail |
| ------ | ------ | ------ | ------ | ------ |
| Critical	| **New Feature**	| CPSAIR-323253 Cash Count Support For CPSair	| Pending merge to TAG 4.0	| 0 |
| High	| **New Feature**	| CPSAIR-255498 New Quicksale button design and setup	| Unit Test Pending	| 5 |
| High	| **New Feature**	| CPSAIR-329501 CPSAPI endpoint to return all items with prices	| QA Testing Passed	| 0 |
| High	| **New Feature**	| CPSAIR-330335 New Quicks Sale button design (APP)	| Unit Test Pending	| 0 |
| Low	| **New Feature**	| CPSAIR-292483 Add IBX to CPS Air	| QA Testing Passed	| 4 |
| Low	| **New Feature**	| CPSAIR-319090 cart agreement via cps air	| Unit Test Pending	| 2 |
| Medium	| **New Feature**	| CPSAIR-328057 Add Cash count configure to Online Options	| Pending merge to TAG 4.0	| 0 |
| Medium	| **New Feature**	| CPSAIR-337064 Page 1:  Add Receipt Item Agreements to Online Web Settings	| QA Test Pending	| 0 |
| Critical	| Bug	| CPSAIR-332817 Online Options settings don't approve and some options don't match to local options	| QA Testing Passed	| 0 |
| Critical	| Bug	| CPSAIR-334635 Numerous Disconnects While QA Testing	| QA Passed - File not posted	| 0 |
| Critical	| Bug	| CPSAIR-335985 Cps air sales tab disappeared.	| Complete	| 0 |
| High	| Bug	| CPSAIR-317708 V4:Cannot payment by GiftCard. Show warning Expire date.	| QA Passed - File not posted	| 0 |
| High	| Bug	| CPSAIR-329985 Quick sale button can click although no stock in store.	| QA Passed - File not posted	| 0 |
| High	| Bug	| CPSAIR-332232 Tee Sheet Will Not Load in Dev Channel of CPS Air	| QA Testing Passed	| 0 |
| High	| Bug	| CPSAIR-332257 Normal rate of class incorrect	| QA Passed - File not posted	| 1 |
| High	| Bug	| CPSAIR-332357 CPSAir Error - Cannot Process In-Use sales Tab, Object reference not set  	| Complete	| 0 |
| High	| Bug	| CPSAIR-334704 CPS Air sales not showing on Statement but are showing in Customer Statement	| Complete	| 0 |
| High	| Bug	| CPSAIR-336009 Auto seat option is causing 2 major issues when activated. 	| QA Testing Passed	| 0 |
| High	| Bug	| CPSAIR-337279 Unable to connect to server on local product on Ann server	| Complete	| 0 |
| High	| Bug	| CPSAIR-337808 CPSAir Not Tracking Sales of Inventory Properly when Using Beverage Cart Mode	| Cannot Reach Customer	| 0 |
| High	| Bug	| CPSAIR-338042 CPS Air Allows Other Users to Sell Checked Out Inventory Item	| QA Testing Passed	| 0 |
| High	| Bug	| CPSAIR-339000 CPS Air F&B tableview remote printing not including items	| Duplicate	| 0 |
| High	| Bug	| CPSAIR-339230 Table View Will Not Load	| QA Testing Passed	| 0 |
| High	| Bug	| CPSAIR-339716 The table turns green as soon as you save a tab.	| QA Testing Passed	| 0 |
| High	| Bug	| CPSAIR-340396 Reservation can't change rate	| Unit Test Pending	| 0 |
| High	| Bug	| CPSAIR-340749 Show empty message box on reservation screen.	| Unit Test Pending	| 0 |
| High	| Bug	| CPSAIR-340797 "Could not InitialSale - Object reference not set to an instance of an object" error occurs when using F&B 	| QA Testing Passed	| 0 |
| High	| Bug	| CPSAIR-340853 block - doesn't appear to work at all now	| QA Passed - File not posted	| 0 |
| Low	| Bug	| CPSAIR-310627 Set Class on CPS Air	| QA Passed - File not posted	| 4 |
| Low	| Bug	| CPSAIR-323542 V4: The app freeze when re-enter SH screen without default course selected.	| QA Testing Passed	| 1 |
| Low	| Bug	| CPSAIR-328743 V4: The status of blocking quick sale button is not shown	| Complete	| 0 |
| Low	| Bug	| CPSAIR-328745 V4: Can't print receipt even though there is a sale number on tblAPIPrinterQueue.	| QA Test Pending	| 1 |
| Low	| Bug	| CPSAIR-330572 Seats disappear after combine tabs	| QA Testing Passed	| 0 |
| Low	| Bug	| CPSAIR-330575 The app crashes when tap on an unassigned seat item.	| QA Testing Passed	| 0 |
| Low	| Bug	| CPSAIR-331550 Issuing Rain Check on Booking with Deposit Does Not Work on CPS Air	| Complete	| 2 |
| Low	| Bug	| CPSAIR-331895 V4: AutoGratuity option does not work.	| QA Passed - File not posted	| 1 |
| Low	| Bug	| CPSAIR-332464 Unable to Retrieve Credit Card Version Number	| Cannot Reproduce	| 0 |
| Low	| Bug	| CPSAIR-332855 CPSAIR Waitlist allows booking ontop of blocked cell	| QA Testing Passed	| 0 |
| Low	| Bug	| CPSAIR-332862 CPSAIR add Tips will allow Gift Card to go into negatives	| QA Passed - File not posted	| 1 |
| Low	| Bug	| CPSAIR-332881 CPSAir Rain Check Email Receipts Not Sending	| QA Passed - File not posted	| 1 |
| Low	| Bug	| CPSAIR-333070 Can't reserve dynamic price	| Complete	| 1 |
| Low	| Bug	| CPSAIR-333210 App Left Open Overnight Results in Sale Number Discrepancy	| QA Passed - File not posted	| 1 |
| Low	| Bug	| CPSAIR-334993 Gratuity incorrect on split check screen.	| Complete	| 0 |
| Low	| Bug	| CPSAIR-335105 Last name field spacing issue when adding a write in	| QA Testing Passed	| 0 |
| Low	| Bug	| CPSAIR-335286 When Items are checked in or out, it does not appear in the receive product page.	| Complete	| 0 |
| Low	| Bug	| CPSAIR-335733 The connection requires HTTPS:// to be added	| QA Testing Passed	| 0 |
| Low	| Bug	| CPSAIR-336313 Can not finalize saved tabs to credit cards on CPSair	| QA Test Pending	| 0 |
| Low	| Bug	| CPSAIR-336689 Status Code: 500 when accessing tee sheet module 	| QA Testing Passed	| 0 |
| Low	| Bug	| CPSAIR-338398 The app generate empty row in item list when bring it back from suspended state.	| Complete	| 0 |
| Low	| Bug	| CPSAIR-338825 The app never bring a user back to table layout after clearing sale.	| QA Passed - File not posted	| 1 |
| Low	| Bug	| CPSAIR-338923 When user clean all message on "Search Member" text box, Progress Indicators still running	| QA Passed - File not posted	| 0 |
| Low	| Bug	| CPSAIR-338928 Overlapping display of floor layers	| QA Testing Passed	| 0 |
| Low	| Bug	| CPSAIR-340719 Add value GiftCard Error	| Complete	| 0 |
| Low	| Bug	| CPSAIR-340720 SaleItem empty	| Unit Test Pending	| 0 |
| Low	| Bug	| CPSAIR-340984 Price and quantity of the saleItem disappear.	| Complete	| 0 |
| Low	| Bug	| CPSAIR-341010 CPS Air Format isn't correct when player column is set to 1	| QA Passed - File not posted	| 2 |
| Low	| Bug	| CPSAIR-341112 Loading SH screen without course is error.	| QA Test Pending	| 0 |
| Low	| Bug	| CPSAIR-341211 SH Player list disappear after select player	| Unit Test Pending	| 0 |
| Low	| Bug	| CPSAIR-341566 SH unable to loading block template	| Unit Test Pending	| 0 |
| Medium	| Bug	| CPSAIR-319145 V4: Inventory screen app crash when delete list.	| QA Testing Passed	| 1 |
| Medium	| Bug	| CPSAIR-331363 Can't load save tab from v3 on table layout	| QA Testing Passed	| 0 |
| Medium	| Bug	| CPSAIR-332340 App Loses Connection With Timeout	| QA Testing Passed	| 1 |
| Medium	| Bug	| CPSAIR-333132 CPS Air - Cash Out Report Overstates Tips (And Count) For Split Payment Transactions	| Update Pending - Reassigned to Technician	| 0 |
| Medium	| Bug	| CPSAIR-334500 Unable to Finalize Sale Adding Value to Gift Card	| Cannot Reproduce	| 0 |
| Medium	| Bug	| CPSAIR-337538 "Cannot finalize" popup when trying to charge to a member account 	| Cannot Reproduce	| 0 |
| Medium	| Bug	| CPSAIR-337578 Fixed searching golfer error	| QA Testing Passed	| 0 |
| Medium	| Bug	| CPSAIR-338604 Show empty value on the first row on sale list, after checkin	| Complete	| 0 |
| Medium	| Bug	| CPSAIR-339113 Bug - Missing of NumCustomer Updating on Combine SaleTab	| QA Testing Passed	| 0 |
| Medium	| Bug	| CPSAIR-340983 QuickSale Item duplicate	| Unit Test Pending	| 0 |
| High	| Change Request	| CPSAIR-332844 Auto log off, use auto seat, all payment methods and store code options missing from online options web	| QA Testing Passed	| 1 |
| High	| Email	| CPSAIR-330588 Fwd: CPS Air issue with sales showing closed when they arnt	| Complete	| 0 |
| Medium	| Email	| CPSAIR-327378 Club prophet report - Out of balance	| Update Completed	| 0 |
| High	| Investigation	| CPSAIR-330366 Error : Transaction (Process ID 605) was deadlocked on lock resources with another process and has been chosen as the deadlock victim	| Update Completed	| 3 |
| High	| Investigation	| CPSAIR-334763 Benchmarks comparing almost all functions 3.98 is much slower than 3.96. 	| QA Test Pending	| 2 |
| High	| Investigation	| CPSAIR-339120 CPS AIR on live DB (Amazon east) server slow on first load	| QA Testing Passed	| 0 |
| Low	| Investigation	| CPSAIR-329205 Double the Amount of Expected Receipts Printing for Split Payment Transactions using CPSAir	| QA Passed - File not posted	| 0 |
| Low	| Investigation	| CPSAIR-334569 Closing CPS Air During Signature causing Error - Cannot Finalize	| Issue NOT clearly defined - Need More Info	| 0 |
| Low	| Investigation	| CPSAIR-335795 paid cells are getting moved when they shouldn't be	| Complete	| 0 |
| Low	| Investigation	| CPSAIR-340514 No data show when click select cart.	| Unit Test Pending	| 0 |
| Low	| Investigation	| CPSAIR-340620 User Logon Stopped Working in CPSAir	| QA Testing Passed	| 0 |
| Medium	| Investigation	| CPSAIR-331220 CPS Air: Could not Add SaleNum: Sale number is duplicate (ccm 3.98)	| Update Completed	| 0 |
| Medium	| Investigation	| CPSAIR-335107 "guest of" button on reservation screen doesnt appear to be working	| QA Testing Passed	| 0 |
| Medium	| Investigation	| CPSAIR-335694 CPS Air: Duplicate Kitchen Ticket	| Complete	| 0 |
| High	| Quality Check	| CPSAIR-317440 Continuous Integration Improvement with Sonar	| Unit Testing In Progress	| 0 |
| High	| Quality Check	| CPSAIR-335194 Improve benchmarks and performance on SH	| QA Passed - File not posted	| 0 |
| High	| Quality Check	| CPSAIR-335195 Improve benchmarks and performance on FB	| Merge Code Pending & Code reviews	| 0 |
| High	| Quality Check	| CPSAIR-335196  Improve benchmarks and performance on Sale	| QA Passed - File not posted	| 1 |
| High	| Quality Check	| CPSAIR-338816 Improve performance on SH (Check-in)	| QA Passed - File not posted	| 0 |
| High	| Quality Check	| CPSAIR-338817 Improve performance on SH (Search name while booking)	| QA Passed - File not posted	| 0 |
| High	| Quality Check	| CPSAIR-340850 move paste tee time - 10 seconds need improve performance to 3 seconds	| QA Passed - File not posted	| 0 |
| High	| Quality Check	| CPSAIR-340851 edit time - 5 seconds need improve performance to 3 seconds	| QA Passed - File not posted	| 0 |
| High	| Quality Check	| CPSAIR-340852 change player 4 seconds need improve performance to 3 seconds	| QA Passed - File not posted	| 0 |
| High	| Quality Check	| CPSAIR-340854 reserve time - 8 seconds from clicking green reserve button from booking screen - need  improve performance to 3 seconds	| QA Passed - File not posted	| 1 |
| High	| Quality Check	| CPSAIR-340855 I wasn't able to enable Food and Beverage on this test site so there could be functions there that also need work	| QA Testing Passed	| 0 |
| High	| Quality Check	| CPSAIR-341315 Full test all feature on CPS AIR (SH module) and check speed issue for PGA show	| Unit Testing In Progress	| 0 |
| Low	| Quality Check	| CPSAIR-328854 FB Split check process.	| QA Passed - File not posted	| 1 |
| Low	| Quality Check	| CPSAIR-336480 Credit Card Version Not Displaying in Options	| QA Testing Passed	| 0 |
| Low	| Quality Check	| CPSAIR-336963 Clear variable on app cache when user changed api server and database.	| Complete	| 0 |
| Medium	| Quality Check	| CPSAIR-337699 Improve performance on FB (Table Layout > Finalize and back to FB screen)	| QA Test Pending	| 1 |
| Medium	| Quality Check	| CPSAIR-337700 The customer name search has changed from the previous one.	| Won't Fix	| 1 |
| Medium	| Quality Check	| CPSAIR-338603 Improve performance on SH (It does appear to be faster on teesheet 3 seconds to load each day...blank teesheets I haven't booked anything)	| QA Passed - File not posted	| 0 |
| High	| Support Request	| CPSAIR-334562 Tax Exempt Details Report Not Showing Some Sales	| QA Passed - File not posted	| 0 |
| High	| Support Request	| CPSAIR-335993 CPS Air: Credit Card Charged, Sale Not Recorded	| Update Pending - Reassigned to Technician	| 0 |
| Low	| Support Request	| CPSAIR-332614 please post App 3.96(1547681204)	| QA Test Pending	| 0 |
| Low	| Support Request	| CPSAIR-333273 Please post CPS Air 3.96(1567483017) 	| QA Testing Passed	| 0 |
| Medium	| Support Request	| CPSAIR-332141 please post  App Build number 3.96(1525526160) Dan	| Complete	| 0 |
| High	| Task	| CPSAIR-334991 Modify CI&CD for support multiple schemes for CPS Air 	| Complete	| 0 |
| High	| Task	| CPSAIR-339857 Pin code screen slow on production server (Amazon)	| QA Testing Passed	| 0 |
| High	| Task	| CPSAIR-341675 Apple Developer Enterprise Program expired Or license agreement update	| Task Pending - Reassigned to Technician	| 0 |
| High	| Task	| CPSAIR-341706 Add note slow on production 	| Merge Code Pending & Code reviews	| 0 |
| Low	| Task	| CPSAIR-238971 Review Test Case for Automation Script: Package Module	| Cannot Reproduce	| 0 |
| Low	| Task	| CPSAIR-330693 Failed pipeline for 3.9.8 | QA Testing Passed	| 0 |
| Low	| Task	| CPSAIR-337942 Do we need to use /gwair for cpsair connection, it seems to work without it just 	| QA Testing Passed	| 0 |
| Medium	| Task	| CPSAIR-331934 deploy - get_certificates lane failed on auto build	| QA Testing Passed	| 0 |
| Medium	| Task	| CPSAIR-339990 Cancel process slow on production server	| QA Testing Passed	| 0 |
| Medium	| Task	| CPSAIR-341209 Cannot run code coverage and deploy app	| Unit Testing Passed	| 0 |
| High	| Bug	| CPSGO-341216 CPSGO Cart Price Missing	| Update Pending - Reassigned to Technician	| 0 |
| Low	| Bug	| CPSGO-340435 CPSGO v3.96 Search Tee Time Error	| Complete	| 2 |
| Medium	| Bug	| SHiOS-332090 App crashes when moving and pasting a reservation 	| QA Testing Passed	| 0 |


## Topics CPS USA team discussed with our team of this week.
- **Cory**
  * Performance issue and updated status
  * Apple develop enterprise expired 
  * Full test CPS AIR (SH Module) for PGA Show on next year
- **Jason**
  * Split check Item QTY issue
  * Reserve time speed issue
  * Benchmarks comparing speed v398 and v396 issue
  * Food and Beverages User Rules issue
  * Cancel Split Payment After CC Charge issue

## Thank you team :trophy:
@annfuuuu,@champ.mycos,@ByteKridsada,@rawipas02
