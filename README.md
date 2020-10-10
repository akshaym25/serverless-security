## Serverless Security Solution

This repository intends to provide platform agnostic solution for the following domains related to Security when it comes to serverless applications.
Relevant doamins to be addressed
### 1) Inventory
Inventory will pull all the functions and associated meta data such as function name/id(along with full resource path), source code path, active/inactive, assicated service account/identity 
### 2) Function Code Scanning
All functions should under go static code scanning post any changes in code
### 3) Run time security checks
Provide python library for doing run time checks for function code
### 4) Identity and Access Management Policy
Use function inventory data to identify Identity and access management gaps in permissions associated with a particular function.