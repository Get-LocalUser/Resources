# CONDITIONAL ACCESS
The following CA policies are enabled.  

### Policy name  

_`GLB - USR - CA - Block all legacy sign-ins that don't support MFA`_  
_`GLB - USR - CA - Denied Countries`_  
_`GLB - USR & DVC - EDGE - Require MAM Edge for Office Apps`_  
_`GLB - USR - CA - Require MFA and a password change when high-risk users are detected`_    
_`GLB - USR - CA - Require MFA for admins`_  
_`GLB - USR - CA - Require MFA for external and guest users`_    
_`GLB - USR - CA - Require MFA when risky sign-ins are detected`_  

### Policy Explanation  

_`Denied Countries`_  
Denied Countries blocks access to company resources unless the user is based in the USA or CANADA and determines the location GPS Coordinates. Utilizes "Named Locations"  

_`Require MAM Edge for Office Apps`_  
Requires a App Protection Policy to be applied to web based sessions of Office in MS Edge. Excludes Corporate owned devices that are Compliant.