# Chapter 10: Cross-platform Endpoint Security

## Table of Contents

- [Introduction](#chapter-10---introduction)
- [Structure](#chapter-10---structure)
- [Objectives](#chapter-10---objectives)
- [Author’s experience in Defender Cross Platform team](#chapter-10---authors-experience-in-defender-cross-platform-team)
- [MDE backend platform virtualization insight](#chapter-10---mde-backend-platform-virtualization-insight)
- [Apple’s licensing restriction and COGS management](#chapter-10---apples-licensing-restriction-and-cogs-management)
- [Apple Mac Pros](#chapter-10---apple-mac-pros)
  - The following is the reference of Apple’s Mac Pro Old generation and New Generation hardware reference and team started running MBA on the following old generation hardware and then we switched to Mac Mini to save cost:
- [Public MacOS datacenters](#chapter-10---public-macos-datacenters)
- [Security or cross platform terminologies](#chapter-10---security-or-cross-platform-terminologies)
- [Dynamic analysis](#chapter-10---dynamic-analysis)
- [Static analysis](#chapter-10---static-analysis)
- [Comparison of static vs. dynamic MBA](#chapter-10---comparison-of-static-vs-dynamic-mba)
- [Behavioural patterns and anomalies](#chapter-10---behavioural-patterns-and-anomalies)
- [Reporting and mitigation](#chapter-10---reporting-and-mitigation)
- [MBA of Zip file (XPlode)](#chapter-10---mba-of-zip-file-xplode)
- [Public MBA vendors available in market](#chapter-10---public-mba-vendors-available-in-market)
- [Clean or historical samples](#chapter-10---clean-or-historical-samples)
- [Security research](#chapter-10---security-research)
- [Native engine support in cross platform](#chapter-10---native-engine-support-in-cross-platform)
- [NE general availability and Bit Defender replacement](#chapter-10---ne-general-availability-and-bit-defender-replacement)
- [Microsoft software release and cycles](#chapter-10---microsoft-software-release-and-cycles)
  - [Release rings](#chapter-10---release-rings)
  - [Release stages](#chapter-10---release-stages)
- [Microsoft mobile threat defense cross platform solution](#chapter-10---microsoft-mobile-threat-defense-cross-platform-solution)
  - [Intune app protection policy settings](#chapter-10---intune-app-protection-policy-settings)
    - To leverage App protection policies, you need to enable the Application Protection in MS Intune portal, and we have covered such details in Chapter 14, Practical Configuration Examples and Case Studies, and kept it here for quick reference in respect to cross platform work that happened around us.
  - The following figure shows the Intune reference page showcasing App Protection policy settings:
- [Create app configuration policies for MTD](#chapter-10---create-app-configuration-policies-for-mtd)
- [Microsoft tunnel and VPN for cross platform](#chapter-10---microsoft-tunnel-and-vpn-for-cross-platform)
  - [Requirement of Tunnel software for MTD](#chapter-10---requirement-of-tunnel-software-for-mtd)
  - [MAM Tunnel for unregistered devices or for guests](#chapter-10---mam-tunnel-for-unregistered-devices-or-for-guests)
  - [Microsoft Tunnel gateway architecture](#chapter-10---microsoft-tunnel-gateway-architecture)
  - [Microsoft's Leadership in the MTD Area](#chapter-10---microsofts-leadership-in-the-mtd-area)
  - [Comprehensive server setup configuration for Intune Administrators](#chapter-10---comprehensive-server-setup-configuration-for-intune-administrators)
  - [Microsoft Tunnel VPN integration for mobile](#chapter-10---microsoft-tunnel-vpn-integration-for-mobile)
- [Microsoft cloud native protection platform](#chapter-10---microsoft-cloud-native-protection-platform)
- [Conclusion](#chapter-10---conclusion)

