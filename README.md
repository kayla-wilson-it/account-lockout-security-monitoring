# Account Lockout & Security Monitoring

## Overview
This project demonstrates hands-on experience configuring account lockout policies and monitoring security events in a Windows Server Active Directory environment. The goal was to enforce account security and document verification through Event Viewer.

## Environment
- Oracle VirtualBox  
- Windows Server  
- Active Directory Domain Services  

## Objectives
- Configure account lockout policies at the domain level  
- Create test users and simulate lockouts  
- Verify enforcement using Security Event Viewer logs  
- Document security procedures with screenshots  

## Security Controls Implemented
- Account lockout threshold: 3 invalid login attempts  
- Account lockout duration: 15 minutes  
- Reset account lockout counter after 15 minutes  

## Why This Matters
Account lockout policies help prevent unauthorized access due to brute-force attacks or repeated invalid login attempts. Monitoring security events ensures administrators can respond to potential threats in a timely manner.

## Evidence
Screenshots included demonstrate:  
1. Account Lockout Policy configuration  
2. Test user creation and properties  
3. Account lockout enforcement  
4. Event Viewer log showing the lockout
