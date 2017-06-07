Name
~~~~~~~~~~~~~
OpenVAS — Open Vulnerability Assessment System
~~~~~~~~~~~~~
Description
~~~~~~~~~~~~~
OpenVAS (Open Vulnerability Assessment System, originally known as GNessUs) is a software framework of several services 
and tools offering vulnerability scanning and vulnerability management. 
All OpenVAS products are free software, and most components are licensed under 
the GNU General Public License (GPL).

The OpenVAS protocol structure aims to be well-documented to assist developers. 
The OpenVAS Compendium is a publication of the OpenVAS Project that delivers documentation on OpenVAS.
~~~~~~~~~~~~~
Reproduced
~~~~~~~~~~~~~
Version: 4.0.5 (corresponds to OpenVAS-9) Virtual machine

Download the virtual machine at:
http://dl.greenbone.net/download/VM/gsm_ce_4.0.5.iso

Fire it up and follow the instructions, when you come to a message that says you need to do "Update feed"
then go to "Maintenance --> Feed --> Update" The feed takes a long time to update, and it shows no progress bar
so just wait it out.

NOTE: You need internet access to do the feed update, and you can't use the machine without the update.

In case you need SSH access, go to "Setup --> Services --> SSH --> Enable"
~~~~~~~~~~~~~
Command line Interface (CLI)
~~~~~~~~~~~~~
CLI can be accsess via SSH or serial port.

All changes in the settings that are being performed in the CLI are not activated immediately. As soon as 
a setting is changed in the CLI the prompt changes and indicates that there is an unsaved change. 
An asterisk at the prompt indicates a change that is not activated yet.
"commit" or "rollback" allows the decision between accepting or reverting of a change.

In addition the get command shows if a variable is currently "get" This is indicated with 
an "s" at the beginning of the line. A "u" indicates that the variable currently is not set. 
Clearing of a variable is possible with the command "unset" Variables can be configured with "set"
~~~~~~~~~~~~~
Documentation
~~~~~~~~~~~~~
http://docs.greenbone.net/GSM-Manual/gos-3.1/en/
