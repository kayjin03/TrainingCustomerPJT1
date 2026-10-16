## Project template
Template for initializing project sources.

/!\ Publish any updates to JFROG /!\
More information here: https://webdoc/eskerondemand/cv_ly/en/manager/startpage.htm#../../Consulting/Content/5TASA7nejJ1F.html

## 🔽 Project specific below 🔽
## Overview
This repository only contains:
- customization script libraries.
- custom resources
Any process layout changes, such as adding a new field, should be noted in this readme.
Customization script libraries should only be added to the repository after the first change is made (i.e., the removal of the "_sample" designation).
## Process Layout Changes

## Vendor invoice --
 -- Header fields --
List any new fields added to the header here.
- Z_InternalComment__ (Internal comment): multi-line text, optional, manual input. Exported in invoice.xml. [DEV]
- Z_SupplierType__ (Supplier type): combobox P=Preferred, R=Regular, O=Occasional, read-only, filled from the vendors table via GetVendorCustomFields. [DEV]

 -- LineItems__ --
List any new fields added to the line items table here.

## AP - Vendors__ (S2P - Suppliers table) --
- Z_SupplierType__ (Supplier type): combobox P=Preferred, R=Regular, O=Occasional. [DEV]

## AP - Application Settings Wizard / AP - Application Settings__ --
- Z_BlockAPWorkflowEdit__ (Block AP Specialists from editing the workflow): checkbox in the Customizations step, stored in the settings table. [DEV]

## Customer Order Processing --
 -- Header fields --
List any new fields added to the header here.
 -- Product_List__ --
List any new fields added to the line items table here.