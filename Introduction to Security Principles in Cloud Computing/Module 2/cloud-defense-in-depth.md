# Cloud Defense-in-Depth 

## Overview

- Just like you might help someone you care about cross a busy street, in the world of cybersecurity, different strategies are used to protect data and assets, especially sensitive ones.
- The more valuable an asset is, the more advanced the security protecting it should be.
- Today, you'll learn about a strategy that’s used to protect critical assets: the defense-in-depth model.
- Using this model can help protect cloud resources.
- It can also improve an organization’s ability to manage its defense of assets and data, which is an organization’s security posture.

## Key Concepts

### 1. Defense in Depth

- Defense in depth is a layered approach to vulnerability management that reduces risk.
- Defense in depth uses multiple security controls to protect assets.
- The combination of these controls create a more robust defense strategy for your organization.

### 2. Security Controls

- Security controls are safeguards that reduce security risks.
- Common types of controls used in the cloud include:
  1. Identity controls
  2. Protective controls
  3. Network controls
  4. Detective controls
  5. Responsive controls
  6. Recovery controls

### 3. Types of Security Controls

#### A. Identity Controls

- An identity control is a measure that helps authenticate a user before they access resources, like networks or storage.
- Identity controls are becoming a lot more common, so it’s possible you’ve encountered them before.
- One of the most common examples of an identity control is when your email provider asks you to add another email or a phone number to verify your identity.
- This is an example of an identity control known as multi-factor authentication, which adds an additional layer of security to the authentication process.

#### B. Protective Controls

- A protective control is a measure that protects access to resources and shields against malicious attacks.
- Other examples of protective controls are:
  - Installing antivirus software on individual VMs.
  - Web application firewalls.
  - Organization and infrastructure as code policies.

#### C. Network Controls

\- A network control, like a firewall, is a measure that helps protect access through network paths.

#### D. Detective Controls

- A detective control is a measure used to identify suspicious activity if it occurs.
- An example of a detective control is an intrusion detection system that monitors system activity and alerts analysts if there’s a possible intruder.
- Google Cloud’s Security Command Center is an example of an intrusion detection system that can alert cloud security professionals of malicious activity.

#### E. Responsive Controls

- A responsive control is an application or tool that uses automation to respond to security events.
- For example, responsive controls could automatically notify you through email or other systems in response to a detected threat.

#### F. Recovery Controls

- After detecting and responding to threats, analysts use recovery controls.
- A recovery control is a measure that restores access and functionality in the event of failures.
- The most common example of a recovery control is where you can revert to a backup of a system you stored after an attack.

## Key Application: Community Garden Example

Think of the controls working together like a security system for a community garden.

- Identity controls determine who is able to access the garden.
- Installing a fence around the garden’s perimeter acts as a protective control.
- You protect access to the garden by only giving authorized people a key to the gate, like using network controls.
- Using a detective control, you install a camera to monitor suspicious activity.
- Then, if there’s suspicious activity, you’ll use a responsive control to receive an automatic text message.
- Last, using a recovery control, you can re-establish the security of the garden by mending any failures in the fence.

