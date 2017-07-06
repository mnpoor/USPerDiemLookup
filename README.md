# USPerDiemLookup

US (GSA) Per Diem Lookup via API

Quickie program demonstrating inventory.data.gov API interaction. Program is written in C# (Visual Studio 2017) using WPF.

Host publishes data in JSON format. Application uses Newtonsoft.Json library for deserialization.

Attached .PNG screen shots show various elements of the WPF implementation, RESTful services library, and Access Forms/VBA implementation.

Red arrows highlight elements of the Interop, including System.Runtime.Interop inclusion, relevant attributes, functionality for referencing the library, use of methods and objects, and accessing elements of a collection. Settings in the library are designed for VBA Intellisense.

.MSI installs on Windows 10 and Windows 7, but does not install on Windows XP. One Windows 10 installation was on a tablet, and executed sucessfully via WiFi networking.

.zip contains an .ACCDB with the form shown in the screen shots, as well as an .MSI that installs the WPF form and library.  It is necessary to install the WPF form in order to get the library installed in the right folder.

At present the code is all 'debug enabled'.  These are not 'final release' versions of the executables.
