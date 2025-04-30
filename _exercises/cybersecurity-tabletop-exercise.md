---
layout: exercises
title: Operation Dark Horizon
subtitle: A Cybersecurity Tabletop Exercise for MSSPs
author: joe
---
# Operation Dark Horizon: A Cybersecurity Tabletop Exercise for MSSPs

## Exercise Overview

**Title:** Operation Dark Horizon  
**Duration:** 4 hours (recommended)  
**Target Audience:** SOC analysts, incident responders, security engineers, management team  
**Difficulty:** Moderate to Advanced  
**Objective:** Test the organization's incident response capabilities during a sophisticated multi-stage attack targeting both the MSSP and its clients simultaneously.

## Learning Objectives

1. Evaluate team coordination during complex incident response
2. Test technical response capabilities across different attack vectors
3. Assess communication protocols both internally and with clients
4. Practice decision-making under pressure with limited information
5. Identify gaps in current incident response plans

## Exercise Structure

### Preparation Phase (2 weeks prior)

1. **Facilitator Selection:** Appoint 1-2 individuals to lead the exercise
2. **Participant Selection:** Identify key stakeholders from various teams
3. **Resource Preparation:** Ready the necessary documentation, communication channels, and simulated environments
4. **Pre-Exercise Briefing:** Conduct a short session explaining exercise rules and expectations

### Exercise Roles

1. **Exercise Facilitator:** Controls exercise flow, introduces injects, evaluates responses
2. **Players:** SOC analysts, incident responders, security engineers, management
3. **Observers:** Document actions, decisions, and potential improvement areas
4. **Client Representatives:** (Optional) Can participate to add realism to client communications

## Exercise Materials

### Required Documents

1. Incident response plan
2. Communication templates
3. Client contact information
4. Escalation procedures
5. Technical documentation of systems
6. Exercise evaluation forms

### Technical Setup (Optional)

1. Isolated test environment for simulated forensic analysis
2. Communication channels (separate from production)
3. Timer display
4. Digital collaboration tools

## Scenario Background

MegaGuard Security Solutions is a well-established MSSP providing security monitoring and incident response services to over 50 clients across various industries. Among their key clients are:

- NexBank Financial (financial sector)
- MedCore Systems (healthcare)
- PowerGrid Utilities (critical infrastructure)
- TechNova Enterprises (technology)

MegaGuard uses a SOC platform that aggregates logs and alerts from client environments, with a centralized dashboard for monitoring and response.

## Exercise Narrative

A sophisticated threat actor has identified MegaGuard as a prime target for a supply chain attack. Their objective is to compromise MegaGuard's infrastructure to gain access to high-value clients. The attack will unfold in multiple stages over the course of the exercise.

## Exercise Timeline and Injects

### Phase 1: Initial Compromise (0:00-1:00)

**Setting the Scene (0:00-0:10)**
- Facilitator introduces the day as a normal operating day at MegaGuard SOC
- Teams are at their regular stations performing routine monitoring

**Inject 1 (0:10): Suspicious Login Alert**
- A SIEM alert shows an unusual successful authentication to the SOC platform from an unrecognized IP address
- The login credentials belong to a junior SOC analyst who is currently on vacation
- The login occurred outside normal business hours

*Expected Actions:*
- Investigate the alert
- Check user account status
- Review login source and patterns
- Begin documenting the incident

**Inject 2 (0:30): Discovery of Suspicious Activity**
- The compromised account has been observed running unusual queries in the SOC platform
- Queries focused on gathering information about client connections, particularly for NexBank and PowerGrid
- Several permission elevation attempts were detected

*Expected Actions:*
- Escalate the incident to senior team members
- Consider isolating potentially affected systems
- Begin preparing initial client communication if necessary
- Start assembling an incident response team

**Inject 3 (0:45): Malicious Tool Detection**
- A detection system identifies a potential data exfiltration tool installed on an internal system
- The tool appears to have been installed using the compromised credentials
- Initial evidence suggests sensitive data about client network topologies may have been accessed

*Expected Actions:*
- Activate formal incident response procedures
- Assign roles and responsibilities to team members
- Begin deeper forensic investigation
- Consider whether to notify clients at this stage

### Phase 2: Escalation (1:00-2:00)

**Inject 4 (1:00): Client Alert - NexBank**
- NexBank SOC team calls reporting suspicious activities in their environment
- They've detected scanning activity coming from an IP address associated with MegaGuard's management infrastructure
- The scanning appears to be targeting their financial transaction processing systems

*Expected Actions:*
- Acknowledge the potential connection to the earlier compromise
- Collaborate with the client's security team
- Investigate potential pivot from MegaGuard systems to client network
- Update incident documentation and escalate internally

**Inject 5 (1:20): Malware Detection**
- Analysis of the compromised system reveals a sophisticated, previously unseen backdoor
- The backdoor provides persistent access and has anti-forensic capabilities
- Evidence shows the malware has been present for approximately 30 days

*Expected Actions:*
- Perform detailed malware analysis
- Begin investigating patient zero and initial infection vector
- Consider implications for other systems and clients
- Update incident response team and management

**Inject 6 (1:40): Detection Evasion**
- The threat actor begins deleting logs and evidence from compromised systems
- Attempts to modify monitoring rules to avoid future detection are observed
- A ransomware binary is discovered but not yet executed

*Expected Actions:*
- Take steps to preserve evidence before it's destroyed
- Implement additional monitoring to track attacker movements
- Consider system isolation measures
- Update risk assessment based on ransomware discovery

### Phase 3: Crisis Management (2:00-3:00)

**Inject 7 (2:00): Critical Infrastructure Alert**
- PowerGrid reports unusual connection attempts to their SCADA systems
- The attempts are coming from trusted MegaGuard monitoring servers
- PowerGrid has disconnected MegaGuard's access as a precaution

*Expected Actions:*
- Acknowledge the severity of the situation
- Implement crisis communication procedures
- Coordinate with PowerGrid's security team
- Prepare for potential regulatory reporting requirements

**Inject 8 (2:20): Executive Involvement**
- MegaGuard's CEO requests an immediate briefing on the situation
- Several other clients have begun calling with concerns
- Media outlets have reached out asking about a potential breach

*Expected Actions:*
- Prepare a concise executive summary
- Organize information for efficient decision-making
- Advise on potential public relations strategies
- Continue technical response activities

**Inject 9 (2:40): Ransom Demand**
- A ransom note appears on several compromised systems
- The attackers claim to have exfiltrated client data and threaten to publish it
- They demand $2 million in cryptocurrency within 48 hours

*Expected Actions:*
- Document the ransom demand
- Assess legitimacy of the attacker's claims
- Discuss potential response options with leadership
- Consider law enforcement notification
- Prepare for potential data breach notifications

### Phase 4: Resolution and Recovery (3:00-4:00)

**Inject 10 (3:00): Attacker TTPs Identified**
- Forensic analysis reveals the complete attack path and techniques used
- Digital evidence points to a known threat actor with state-sponsored connections
- A vulnerability in the SOC platform's VPN is identified as the initial entry point

*Expected Actions:*
- Document all findings for post-incident analysis
- Develop a comprehensive remediation plan
- Prioritize critical security gaps for immediate fixing
- Prepare technical details for affected clients

**Inject 11 (3:20): Containment Decision Point**
- The incident response team must decide on final containment actions
- Options include temporary shutdown of the SOC platform vs. aggressive monitoring
- Each option has different impacts on service delivery and recovery time

*Expected Actions:*
- Evaluate pros and cons of each option
- Make a decision based on risk assessment
- Communicate the decision and rationale to stakeholders
- Begin implementing the chosen approach

**Inject 12 (3:40): Recovery Planning**
- With the immediate threat contained, focus shifts to recovery
- Multiple clients are requesting detailed incident reports
- Regulatory reporting deadlines are approaching

*Expected Actions:*
- Develop a prioritized recovery sequence
- Create a communication plan for different stakeholders
- Prepare initial regulatory notifications
- Begin documenting lessons learned

### Conclusion (3:50-4:00)

- Facilitator declares the end of the exercise
- Brief initial feedback from participants
- Schedule a formal debrief session for the following day

## Exercise Evaluation

### Evaluation Metrics

1. **Detection Effectiveness**
   - Time to detect initial compromise
   - Ability to identify related security events
   - Thoroughness of investigation

2. **Response Efficiency**
   - Time from detection to initial response
   - Appropriateness of response actions
   - Resource allocation and utilization

3. **Communication Effectiveness**
   - Internal communication clarity and timeliness
   - Client communication appropriateness
   - Management updates and escalations

4. **Decision Quality**
   - Risk assessment accuracy
   - Decision-making under pressure
   - Balance between security and business continuity

### Post-Exercise Activities

1. **Hot Wash (Immediately following exercise)**
   - Quick round-table discussion of initial impressions
   - Identification of major strengths and challenges
   - Collection of immediate feedback

2. **Formal Debrief (1-2 days after exercise)**
   - Structured review of exercise timeline and decisions
   - Analysis of major decision points
   - Documentation of lessons learned

3. **Improvement Planning (1-2 weeks after exercise)**
   - Development of specific action items
   - Assignment of responsibilities for improvements
   - Timeline for implementing changes

4. **Follow-up Exercise (3-6 months later)**
   - Targeted scenario to test improvements
   - Focus on previously identified weaknesses
   - Validate effectiveness of changes

## Facilitator Guidelines

### Pre-Exercise Preparation

1. **Scenario Customization**
   - Adjust technical details to match your organization's environment
   - Modify client names and industries as appropriate
   - Ensure technical injects are realistic for your tools and processes

2. **Information Control**
   - Determine what information is available to participants at each stage
   - Prepare answers for likely questions from participants
   - Create physical or digital information cards for injects

3. **Environment Setup**
   - Arrange the exercise space to facilitate team communications
   - Test any technical systems or simulations
   - Prepare backup plans for technical failures

### During Exercise Facilitation

1. **Maintaining Realism**
   - Introduce complications that might occur in real incidents
   - Provide realistic time pressures
   - Limit information as would happen in real scenarios

2. **Adaptability**
   - Be prepared to adjust scenario pacing based on participant progress
   - Have additional injects ready if teams resolve issues quickly
   - Be willing to provide hints if teams get completely stuck

3. **Observation**
   - Take notes on key decisions and actions
   - Identify teaching moments for the debrief
   - Document specific areas for improvement

### Post-Exercise Activities

1. **Facilitating Discussion**
   - Use open-ended questions to promote reflection
   - Focus on process improvements rather than assigning blame
   - Highlight both strengths and areas for improvement

2. **Documentation**
   - Compile observations and participant feedback
   - Prepare a comprehensive after-action report
   - Develop specific, actionable recommendations

## Appendix: Detailed Technical Injects

### Technical Details for Inject 1
- Username: james.wilson
- Source IP: 185.156.73.42 (Location: Eastern Europe)
- Timestamp: 03:27 AM local time
- Access method: VPN followed by web portal login
- Failed attempts: None (successful on first try)

### Technical Details for Inject 2
- SQL queries executed:
  ```sql
  SELECT client_id, client_name, industry, primary_contact FROM clients WHERE priority_level = 'High'
  SELECT connection_string, access_credentials, network_diagram FROM client_access WHERE client_id = 'NB001'
  SELECT * FROM user_accounts WHERE access_level = 'Administrator'
  ```
- Permission escalation attempt:
  - Use of built-in diagnostic tool with known privilege escalation vulnerability
  - Attempt to add account to administrative security group

### Technical Details for Inject 3
- Malicious tool details:
  - Name: svchost64.exe (disguised as legitimate Windows process)
  - Location: C:\ProgramData\Microsoft\Windows\Services\
  - Behavior: Establishes encrypted connection to C2 server at 45.67.231.188
  - Data accessed: Client configuration database, network diagrams, firewall rules

### Technical Details for Inject 5
- Malware characteristics:
  - Custom-built backdoor with elements similar to known APT group "BlackMamba"
  - Uses DNS tunneling for command and control
  - Anti-forensic capabilities including log deletion and timestamp modification
  - Loads directly into memory to avoid disk-based detection
  - Command and control domains:
    - status-update-service.com
    - cdn-delivery-network.net
    - system-verification.org

### Technical Details for Inject 7
- PowerGrid SCADA connection attempts:
  - Target systems: Substation management controllers
  - Access attempts using legitimate MegaGuard service account
  - Commands attempted include configuration changes to power management settings
  - Source: MegaGuard monitoring server 192.168.24.56

### Technical Details for Inject 9
- Ransom note text:
  ```
  ATTENTION MEGAGUARD SECURITY:
  
  Your security has been compromised. We have exfiltrated 2.3TB of data including:
  - Client network diagrams
  - Access credentials
  - Confidential client data
  
  If you want to prevent this data from being published, send 35 Bitcoin to the following address:
  1Hf7iBvhjZU4RfTft72uLnRRWvbcXioLEP
  
  You have 48 hours. The clock is ticking.
  
  For proof, check folder C:\Evidence on your security director's workstation.
  ```

### Technical Details for Inject 10
- Attack path:
  1. Initial access via exploited vulnerability in VPN service (CVE-2023-XXXX)
  2. Credential theft using memory scraping technique
  3. Lateral movement via compromised administrative account
  4. Persistence established through modified scheduled tasks and backdoored DLL
  5. Defense evasion using timestomp and log deletion
  6. Command and control via encrypted DNS tunneling
  7. Data exfiltration via chunked, encrypted transfers to changing destinations
