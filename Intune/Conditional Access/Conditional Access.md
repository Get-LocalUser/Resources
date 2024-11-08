# CONDITIONAL ACCESS

The following Conditional Access (CA) policies are enabled.

# Change Log

11/08/2024: Added  
GLB - USR - CA - Require sign-in every 4 hours on BYOD  
GLB - USR - CA - Require Phishing-Resistant MFA for Admin roles  
GLB - USR - CA - Require MFA for registering security info  
GLB - USR - CA - Require MAM for iOS & Android

## 1. Policy List

- **GLB - USR - CA - Block all legacy sign-ins that don't support MFA**  
  This policy blocks all legacy sign-ins that are not capable of multi-factor authentication (MFA).

- **GLB - USR - CA - Denied Countries**  
  This policy restricts access to company resources to users based only in the USA and CANADA, leveraging "Named Locations" based on GPS coordinates.

- **GLB - USR - CA - Require MAM for iOS & Android**  
  MAM is required for iOS and Android.

- **GLB - USR - CA - Require MFA and a password change when high-risk users are detected**  
  This policy requires MFA and a password change if a high-risk user is detected within the system.

- **GLB - USR - CA - Require MFA for admins**  
  This policy mandates MFA for all administrative users to enhance security.

- **GLB - USR - CA - Require MFA for external and guest users**  
  This policy requires MFA for external and guest users attempting to access company resources.

- **GLB - USR - CA - Require MFA for registering security info**  
  Exactly what the title says.

- **GLB - USR - CA - Require MFA when risky sign-ins are detected**  
  This policy enforces MFA whenever risky sign-in activities are detected by the system.

- **GLB - USR - CA - Require Phishing-Resistant MFA for Admin roles**  
  For 365 roles that end in 'Administrator' Phishing Resistant MFA is required.

- **GLB - USR - CA - Require sign-in every 3 hours on BYOD**  
  Sign-in is required every 4 hours for users on BYOD/unregistered devices.