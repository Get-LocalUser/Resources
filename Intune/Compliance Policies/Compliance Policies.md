# COMPLIANCE POLICY SETTINGS

The following settings are configured in the compliance policy for Windows 10/11.

## 1. Basics

| **Property**       | **Value**                                      |
|--------------------|------------------------------------------------|
| **Name**           | DVC - WIN - Windows 10/11 Compliance Policy    |
| **Description**    | Windows 10/11 compliance policy                |
| **Platform**       | Windows 10 and later                           |
| **Profile Type**   | Compliance policy                              |

## 2. Compliance Settings

| **Setting**                                              | **Requirement** |
|----------------------------------------------------------|-----------------|
| **Device Health**                                        | Required        |
| **BitLocker**                                            | Required        |
| **System Security**                                      | Required        |
| **Require Encryption of Data Storage on Device**         | Required        |
| **Firewall**                                             | Required        |
| **Microsoft Defender Antimalware Security Intelligence** | Up-to-date      |
| **Real-time Protection**                                 | Required        |

## 3. Actions for Noncompliance

| **Action**                  | **Schedule**  |
|---------------------------- |---------------|
| Mark device as noncompliant | Immediately   |
