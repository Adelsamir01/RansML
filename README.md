# RansML

## Overview

RansML is an innovative security solution designed to detect ransomware on Linux systems. It combines the efficiency of eBPF with the predictive power of machine learning to offer real-time protection. This approach allows for dynamic analysis and immediate threat response, all while maintaining minimal system impact.

## Functionality

RansML functions by integrating eBPF programs with critical system calls and user-space operations. These programs activate in response to specific triggers, such as file manipulations or encryption processes, enabling comprehensive system surveillance. The gathered information undergoes processing and analysis via machine learning algorithms to identify potential ransomware signatures.

### Primary Attributes

- **Instantaneous Surveillance**: Utilizes eBPF programs linked to various kernel and user-space access points for immediate ransomware activity detection.

- **Efficient Performance**: Leverages eBPF's streamlined approach to enhance kernel capabilities without requiring additional modules or system alterations.

- **AI-Driven Analysis**: Employs supervised machine learning techniques to categorize events and pinpoint ransomware based on observed data patterns.

- **Community-Driven Development**: Maintains an open-source codebase, fostering transparency, collaborative improvement, and ongoing evolution within the cybersecurity community.

