# CONDITIONAL ACCESS

The following Conditional Access (CA) policies are enabled.

## 1. Policy List

- **GLB - USR - CA - Block all legacy sign-ins that don't support MFA**  
  This policy blocks all legacy sign-ins that are not capable of multi-factor authentication (MFA).

- **GLB - USR - CA - Denied Countries**  
  This policy restricts access to company resources to users based only in the USA and CANADA, leveraging "Named Locations" based on GPS coordinates.

- **GLB - USR & DVC - EDGE - Require MAM Edge for Office Apps**  
  This policy enforces a Mobile Application Management (MAM) App Protection Policy for Office apps accessed via Microsoft Edge. Corporate-owned compliant devices are excluded.

- **GLB - USR - CA - Require MFA and a password change when high-risk users are detected**  
  This policy requires MFA and a password change if a high-risk user is detected within the system.

- **GLB - USR - CA - Require MFA for admins**  
  This policy mandates MFA for all administrative users to enhance security.

- **GLB - USR - CA - Require MFA for external and guest users**  
  This policy requires MFA for external and guest users attempting to access company resources.

- **GLB - USR - CA - Require MFA when risky sign-ins are detected**  
  This policy enforces MFA whenever risky sign-in activities are detected by the system.