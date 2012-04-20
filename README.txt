This is a installer which handles installation of the Quickbooks merge module. It is used by the nullsoft installer for both the Eaglesoft->Quickbooks Deposit utilty as well as the Eaglesoft Timesheet -> Quickbooks Utility

This is done since Intuit says we can only distribute the SDK via the merge module. We cannot distribute the individual .dll files, so it is not possible to wrap them up in a nullsoft installer.

My ultimate plan is to create a windows installer to do the installation, but I just knew how to use NSI so I used that instead.


This references QBSDK QBFC11_0 merge module. You will need to download the SDK and install it from Intuit website. After that you will need to adjust the reference to the installation location of where you installed the SDK. Consult the Intuit docs for more information.
