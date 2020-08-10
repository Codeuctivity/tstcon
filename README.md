# TSTCON Sample: ActiveX Control Test Container

![Showcase](tstcon.gif)

The TSTCON sample implements an ActiveX control container using MFC support for OLE embedding. You can use TSTCON to test ActiveX controls, change their properties, and invoke their methods. You can write scripts using the VBScript language to automate the testing of the controls. TSTCON can keep a log of the events and property change notifications fired by a control.
Note

TSTCON also demonstrates several MFC programming topics, including the following topics:

* CCheckListBox: A list box with a check box next for each item.
* CDragListBox: A list box in which you can drag the items to rearrange their order.
* Implementing an Active Scripting Engine host (VBScript).
* Implementing context-sensitive help for dialog boxes.

## Security Note

This sample code is provided to illustrate a concept and should not be used in applications or Web sites, as it may not illustrate the safest coding practices.

## History of this code

ActiveX Testcontainer, is a copy of VCSamples from <https://github.com/Microsoft/VCSamples/tree/master/VC2010Samples/MFC/ole/TstCon>. If you dont know what tstcon is, you probably wont need it. I missed it when I needed to migrate/analyse some realy old legacy project... but havent used it in the last. Tstscon was a tool from microsoft that was used to test ActiveX controls realy long time ago.

Read <https://devblogs.microsoft.com/cppblog/activex-test-container-application-is-still-available/> and <https://docs.microsoft.com/en-us/previous-versions/f9adb5t5(v=vs.100)?redirectedfrom=MSDN> for more details.

This repo keeps the migrated source code and the built bins in place.
