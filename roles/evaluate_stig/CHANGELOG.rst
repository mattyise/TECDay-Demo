=========================================================
ADP Evaluate STIG Role "Evaluate STIG Tool" Release Notes
=========================================================

.. contents:: Topics

v1.0.0
======

Release Summary
---------------

This is the initial release of the ADP Evaluate STIG role that leverages ADP canes-sustainment-software Package Registry to sync the 
Evaluate STIG PowerShell tool and the PowerShell tar files required to execute the tool. The role has been tested to execute and
generate reports against RHEL 7, RHEL 8, RHEL 9, and Windows systems.
Completion date: 14 JAN 2025.

Major Changes
-------------

- dynamic_execution - Implemented execution of the evaluate STIG and tested against RHEL 7, RHEL 8, RHEL 9, and Windows systems.

New Plugins
-----------

Lookup
~~~~~~

- sequence - generate a list based on a number sequence

New Modules
-----------

- apt_key - Add or remove an apt key
