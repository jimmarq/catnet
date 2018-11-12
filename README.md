# CatNet

CatNet is the name for a network of virtual machines used to learn cyber security skills. This repository contains hands-on exercises that used the CatNet network. The exercises complement Network+ and Security+ curriculum. The labs were originally created by Dr. Jim Marquardson, Assistant Professor of Information Assurance/Cyber Defense at Northern Michigan University.

# Quick Start

The lessons have been designed with flexibility in mind. To the extent possible lessons were created without inter-lesson dependencies so that they can be performend in any order. Before starting the lessons, the lab must be configured.

## Lab Setup

| **Lesson**        | **Description**     |
|-----------------|-------------------|
|[Intro to Catnet](https://github.com/jimmarq/catnet/blob/master/Intro-1-Catnet/CatNet%20v2%20Overview.adoc)                 |                   | Describes how the lab is configured and the goals of the lessons.|
|[VirtualBox Introduction](https://github.com/jimmarq/catnet/blob/master/Intro-2-VirtualBox-Setup/VirtualBox%20Introduction%20Instructions.adoc)                 |Installation, setup, and configuration of VirtualBox.                   |
|[Windows Server Setup](https://github.com/jimmarq/catnet/blob/master/CatNet-Windows-Server-2016-Installation/Setup%20Windows%20Server%202016.adoc)                 | Installation of Windows Server 2016.                  |
|[Metasploitable Setup](https://github.com/jimmarq/catnet/blob/master/CatNetSetup-Metasploitable%20Installation/Metasploitable%20Installation%20Instructions.adoc) | Metasploitable is a useful for testing exploits.|
|[Kali Linux Installation](https://github.com/jimmarq/catnet/blob/master/CatNetSetup-Kali-Installation/Kali%20Linux%20Installation%20Instructions.adoc)|Kali Linux comes with  many security tools.|

## Suggested Lesson Order

| **Lesson**     | **Description** |
|--------------|--------------|
|[Text Editors in Linux](https://github.com/jimmarq/catnet/blob/master/Intro-3-Linux-Text-Editing/Linux%20Text%20Editors.adoc) | A basic overview of editing text in Linux. A major goal of this lesson is to confirm that CatBet is configured properly in VirtualBox.

# Philosophy

Creating hands-on labs in cyber security is challenging. Many books explain terms and definitions, but fewer resources give students hands-on experience with the tools they read about in books. The labs in this repository tend to go just deep enough to give students experience to understand core cyber security principles. The labs should also give students a foundation for continued learning. For example, a lab to install Active Directory on Windows Server covers only the most critical aspects of an Active Directory deployment. Students who wanted to achieve an intermediate or advanced skill level with Active Directory could use the same tools to conitnue their education.

# Technology Tools

Almost all exercises require virtual machines running in VirtualBox. The exercises should work well with VMWare Workstation Player. VirtualBox was preferred because it is open source.

The following virtual machines are used in the labs

* Kali Linux: Linux distribution focused on security tools
* pfSense: Firewall
* Untangle: Firewall
* Windows Server: Microsoft's server operating system
* Windows Client: Modern desktop operating system from Microsoft
* Metasploitable: Linux distribution built to be insecure for security testing purposes
* Other Linux virtual machines as needed for specific exercises

Instructors can configure the virtual machines in virtual box, then copy the virtual machines to a hard drive for distribution to students.

# Licensing

These exercises are licensed using the Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)  - https://creativecommons.org/licenses/by-sa/4.0/

You are free to use these exercises for personal use or in the classroom.

If you find errors or have suggestions for improvements, please open issues or submit pull requests.
