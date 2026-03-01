# Network Modernization Proposal — Yage Botanicals

**Prepared by:** Tim Johnston | 0x2A Security  
**Date:** July 6, 2025  

---

> *This document is a portfolio sample created as part of cybersecurity training. The organization and scenario are fictional and used for educational purposes only.*

---

## Overview

This proposal outlines a five-step network modernization strategy for Yage Botanicals, addressing immediate security gaps, planned cloud migration, and long-term operational stability. The recommendations are designed to be practical, budget-conscious, and executable within an acquisition timeline.

---

## Step 1 — Asset Identification

Before any security improvements can be implemented, Yage Botanicals must establish a complete and accurate picture of its environment.

**Recommended approach:**

| Method | Purpose |
|---|---|
| Automated network discovery | Identify all networked devices and IP addresses |
| Physical asset audit | Walk-through documentation of all hardware |
| System software analysis | Scan systems for installed software, versions, and dependencies |

A complete asset inventory is the foundation of every subsequent step — you cannot protect what you cannot see.

---

## Step 2 — Implement Basic Security Measures

**Priority actions:**

**Patch management:**
Prioritize patching all systems with available updates to eliminate known vulnerabilities. Establish a regular patching cadence going forward.

**Network segmentation for unpatchable systems:**
For systems that cannot be patched, isolate them immediately using:
- VLANs to separate traffic by function and risk level
- Strict firewall rules to limit exposure
- Access controls preventing lateral movement from compromised segments

**Backup and recovery:**
Maintain regular, tested backups of all systems to support data protection and enable swift recovery following a security incident. Validate backup integrity on a scheduled basis.

---

## Step 3 — Cloud Migration Strategy

Migrating to a cloud environment will improve data accessibility, optimize resource utilization, and streamline operations while supporting scalability as the business grows.

### Phase 1 — Discovery and Assessment

- Document current server configurations across all 12 servers (OS, applications, dependencies)
- Map network connections and identify interdependencies
- Identify business-critical applications requiring priority migration planning
- Calculate resource requirements (CPU, memory, storage) for accurate cloud sizing

### Phase 2 — Cloud Environment Preparation

- Set up cloud account with baseline security controls
- Configure virtual network to replicate on-premises structure
- Provision virtual machines matching physical server specifications
- Configure cloud storage to match current data structures

### Phase 3 — Migration Execution

- Begin with non-critical servers to validate the migration process
- Create server images and snapshots as backup before each migration
- Transfer data and applications to cloud servers
- Configure applications for the cloud environment
- Test functionality to verify proper operation before proceeding

### Phase 4 — Cutover and Optimization

- Schedule a maintenance window for the final switchover
- Update DNS and network routing to direct traffic to new cloud infrastructure
- Monitor performance closely during and after cutover
- Decommission old physical servers only after confirming successful migration

---

## Step 4 — Establish Ongoing Security Monitoring

**Recommendation:** Engage a reputable SOC firm for daily security monitoring.

This approach provides:
- Immediate professional security oversight addressing buyer concerns
- 24/7 monitoring without the overhead of building an internal team
- Budget alignment with acquisition timeline constraints
- Scalable coverage that grows with the organization

A managed SOC engagement ensures that threats are detected and responded to in real time while Yage Botanicals focuses on core business operations.

---

## Step 5 — Stabilize Ongoing Business Operations

Three prioritized actions to strengthen the security baseline:

| Action | Solution | Rationale |
|---|---|---|
| Strengthen privileged access | Implement MFA for all privileged accounts | Credential-based attacks are the most common initial access vector |
| Enforce BYOD security | Deploy a SaaS MDM solution | Formally enforces BYOD policies and improves endpoint protection across all devices |
| Establish security framework | Implement CIS Controls | Prioritized, scalable, cost-effective framework for essential security measures |

**CIS Controls rationale:** The CIS Controls framework is specifically designed for organizations building or maturing a security program. It provides prioritized guidance that delivers maximum risk reduction with available resources — well suited to Yage Botanicals' current stage and budget constraints.

---

## Summary Roadmap

| Step | Action | Priority |
|---|---|---|
| 1 | Asset identification — automated discovery, physical audit, software analysis | Immediate |
| 2 | Basic security — patch management, network segmentation, backup validation | Immediate |
| 3 | Cloud migration — four-phase execution across discovery, prep, migration, cutover | Short-term |
| 4 | SOC engagement — managed security monitoring and incident response | Short-term |
| 5 | Business stabilization — MFA, MDM, CIS Controls implementation | Ongoing |

---

## Conclusion

This five-step modernization roadmap provides Yage Botanicals with a structured path from its current state to a secure, scalable, cloud-ready infrastructure. By addressing immediate vulnerabilities first, executing a phased cloud migration, and establishing professional security monitoring, the organization can significantly reduce its risk exposure while supporting long-term business growth and acquisition readiness.

---

*Prepared by Tim Johnston | 0x2A Security | cybersafe3000@gmail.com*  
*CompTIA Security+ | TripleTen Cybersecurity Bootcamp Graduate*
