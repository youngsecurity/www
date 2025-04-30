---
layout: exercises
title: Vault Breach
subtitle: A Casino Heist-Themed Cybersecurity Tabletop Exercise
author: joe
---
# Vault Breach: The Inside Job
## A Casino Heist-Themed Cybersecurity Tabletop Exercise - Part 2

## Exercise Overview

**Title:** Vault Breach: The Inside Job  
**Duration:** 4 hours (recommended)  
**Target Audience:** Security Analysts, Fraud Investigators, IT Security Teams, Management  
**Difficulty:** Intermediate to Advanced  
**Objective:** Test your organization's ability to detect and respond to insider threats targeting financial systems and sensitive data, with a focus on privileged user compromise.

## Learning Objectives

1. Evaluate team response to sophisticated insider threat scenarios
2. Test detection capabilities for unusual privileged account behavior
3. Assess coordination between security, IT, and management during internal investigations
4. Practice sensitive internal threat containment without business disruption
5. Identify gaps in monitoring and controls for high-privilege users

## Exercise Structure

### Preparation Phase 

1. **Exercise Coordinator Selection:** Appoint 1-2 individuals to lead the scenario
2. **Team Selection:** Identify key personnel from security, IT, fraud, and management teams
3. **Resource Preparation:** Ready necessary monitoring tools, communication channels, and simulated environments
4. **Pre-Exercise Briefing:** Conduct orientation explaining the scenario parameters

### Exercise Roles

1. **Exercise Coordinator:** Controls scenario flow, introduces events, evaluates responses
2. **Security Analysts:** Personnel responsible for detecting and investigating anomalies
3. **Fraud Investigation Team:** Specialists focused on unusual financial activity
4. **IT Security Team:** Technical specialists who implement containment measures
5. **Management Team:** Decision-makers balancing security with business continuity
6. **Observers:** Record actions, decisions, and improvement opportunities

## Scenario Background

Following the external heist attempt from Exercise 1, your organization has implemented enhanced security controls and monitoring. However, the threat landscape has shifted to a potentially more dangerous vector: a trusted insider with administrative access to critical systems. The exercise simulates a senior system administrator whose credentials have been compromised or who may have been recruited by external threat actors.

## Exercise Timeline

### Phase 1: Initial Indications (0:00-1:00)

**Setting the Scene (0:00-0:10)**
- Coordinator introduces the scenario as a routine day at the organization
- Teams review the administrator's background, role, and system access privileges

**Event 1 (0:10): Unusual Login Patterns**
- Security monitoring flags authenticated access to administrative systems outside normal hours
- The credentials belong to a senior system administrator with access to critical infrastructure
- Login locations show inconsistent geographic patterns

*Expected Actions:*
- Begin low-key investigation of the anomalous login pattern
- Review recent admin activities without alerting the subject
- Determine if activity could have legitimate explanation
- Start documenting observations in security incident log

**Event 2 (0:30): Database Configuration Changes**
- Monitoring detects subtle changes to database security configurations
- Changes include modified logging parameters and new account creation
- Changes were properly authenticated using valid administrative credentials

*Expected Actions:*
- Escalate investigation priority
- Engage database team for technical assessment
- Consider enhanced monitoring of the administrator's activities
- Begin preparing for potential insider threat response

**Event 3 (0:45): Data Access Anomalies**
- Data loss prevention tools flag unusual access to customer financial data
- The administrator is accessing records outside their typical job function
- Small batches of high-value customer data are being accessed systematically

*Expected Actions:*
- Activate formal insider threat response procedures
- Brief senior management about the potential situation
- Begin preparing containment options
- Consider whether to involve HR and legal teams

### Phase 2: Escalation (1:00-2:00)

**Event 4 (1:00): Attempted Data Exfiltration**
- Security tools detect attempted data transfers to external storage
- The transfers use encrypted channels that bypass standard monitoring
- Attempts appear to specifically target high-value customer financial information

*Expected Actions:*
- Implement covert monitoring of the administrator's activities
- Consider options for access restriction without alerting the subject
- Brief executive team on the developing situation
- Prepare for potential account takeover procedures

**Event 5 (1:20): Privileged Account Manipulation**
- Security monitoring detects the creation of new administrative accounts
- The accounts are created with minimal logging and monitoring flags
- Accounts have been granted extensive system access

*Expected Actions:*
- Document all created accounts and privileges
- Develop plan to monitor and potentially disable these accounts
- Update executive team on escalating threat
- Prepare for potential law enforcement involvement

**Event 6 (1:40): Covering Tracks**
- Evidence emerges of log deletion and modification
- Security audit trails show gaps in coverage for critical systems
- Anti-forensic tools have been installed on key servers

*Expected Actions:*
- Implement additional out-of-band monitoring
- Secure preservation of available evidence
- Consider timing for direct intervention
- Begin preparing for post-incident forensic investigation

### Phase 3: Crisis Management (2:00-3:00)

**Event 7 (2:00): Financial System Access**
- The administrator accesses financial transaction processing systems
- Unusual commands and queries are executed against payment processing databases
- Evidence suggests preparation for fraudulent transaction injection

*Expected Actions:*
- Elevate response to critical status
- Consider immediate containment vs. continued monitoring
- Engage fraud team for financial system protection
- Prepare for potential interruption of the administrator's access

**Event 8 (2:20): Executive Decision Point**
- Management must decide on direct intervention timing
- Balancing evidence collection with risk of financial loss
- Incident is escalating beyond internal security capabilities

*Expected Actions:*
- Prepare containment plan with specific steps
- Brief legal counsel on situation and planned response
- Consider when to engage law enforcement
- Prepare communications for staff and potential customers

**Event 9 (2:40): Confrontation Planning**
- Teams must develop a coordinated response to confront the administrator
- Physical and digital access must be addressed simultaneously
- Evidence preservation becomes critical

*Expected Actions:*
- Coordinate timing between physical and digital teams
- Prepare for potential business disruption
- Develop precise timeline for credential revocation
- Prepare for forensic preservation of all relevant systems

### Phase 4: Resolution and Recovery (3:00-4:00)

**Event 10 (3:00): Containment Execution**
- Teams execute the coordinated containment plan
- Administrator's access is revoked across all systems
- Forensic preservation of workstations and accounts begins

*Expected Actions:*
- Document all containment actions precisely
- Implement backup authentication for critical systems
- Begin assessment of affected systems
- Prepare for potential business continuity challenges

**Event 11 (3:20): Damage Assessment**
- Teams begin thorough assessment of potential damage
- Focus on both data compromise and system integrity
- Financial systems require immediate validation

*Expected Actions:*
- Prioritize critical business systems for verification
- Validate financial transaction integrity
- Identify all potentially compromised data
- Begin preparing breach notification assessment

**Event 12 (3:40): Recovery Planning**
- With containment achieved, focus shifts to recovery
- Need to restore secure operations without original administrator
- Regulatory and customer communications become priority

*Expected Actions:*
- Develop communication plan for different stakeholders
- Create prioritized recovery checklist
- Address immediate security gaps
- Begin formal documentation for compliance requirements

### Conclusion (3:50-4:00)

- Coordinator declares the end of the exercise
- Brief initial feedback from participants
- Schedule formal debrief session for the following day

## Exercise Evaluation

### Evaluation Metrics

1. **Detection Effectiveness**
   - Time to detect suspicious insider activities
   - Ability to correlate subtle indicators of compromise
   - Thoroughness of investigation without alerting the subject

2. **Response Efficiency**
   - Time from detection to containment decision
   - Appropriateness of escalation procedures
   - Resource coordination during sensitive internal investigation

3. **Communication Effectiveness**
   - Discretion in internal communications
   - Management briefing clarity and timeliness
   - Preparation of external communications

4. **Decision Quality**
   - Risk assessment accuracy during evolving situation
   - Decision-making regarding intervention timing
   - Balance between evidence gathering and threat containment

### Appendix: Technical Details

**Admin Account Profile:**
- Username: sysadmin.roberts
- Access Level: Enterprise Administrator (Tier 3)
- Systems: Core Infrastructure, Financial Databases, Security Systems
- Normal Working Pattern: Monday-Friday, 8am-6pm, Occasional Weekend Maintenance
- Employment: 7 Years, Previously Cleared All Security Checks

**Technical Indicators:**
- Login Locations: Office IP (Normal), Home IP (Normal), Three Unknown Locations (Abnormal)
- Database Modifications: Logging Reduction, Authentication Bypass, Monitoring Exclusions
- Data Access Pattern: Sequential Access to High-Value Records, Outside Job Requirements
- Exfiltration Method: Encrypted HTTPS to File Sharing Service, Steganography Suspected

**Created Accounts:**
- svc_audit_system (Hidden Administrative Privileges)
- db_maintenance_usr (Database SA Permissions)
- netsec_monitor (Network Security Bypass Capabilities)

**Systems Targeted:**
- Customer Financial Information Database
- Payment Processing Middleware
- Transaction Authorization System
- Fraud Monitoring Platform
