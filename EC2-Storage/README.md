# **AWS Storage & Backup – Real-World EC2/EBS/EFS Scenarios (Hands-On)**

![alt text](diagram-export-11-12-2025-6_10_01-pm.png)

This project covers core AWS storage operations used daily in production environments.
Each scenario focuses on high availability, backup strategies, cost optimization, and shared storage architecture.

---

## **Scenario 1: Extend C Drive Space by 10GB and Create AMI Snapshot (Rollback Ready)**

* Modify existing EBS volume size from console
* Extend partition inside EC2
* Create AMI snapshot for rollback
* Understand impact on root volumes

---

## **Scenario 2: EBS snapshot, create a volume out of EBS snapshot and attach it to an instance.**

* Take snapshot of an EBS volume
* Create volume from snapshot (new availability zone)
* Attach and mount to EC2
* Validate restored data

---

## **Scenario 3: EBS Archive & Restore + Recycle Bin + Fast Snapshot Restore (FSR)**

* Archive snapshot for cost savings
* Restore archived snapshot
* Enable Recycle Bin protection policy
* Configure Fast Snapshot Restore (FSR)

---

## **Scenario 4: Copy EBS snapshot across regions (cross-region snapshot copy).**

* Copy snapshots to another region
* Understand DR strategy
* Validate the copy by creating a volume in the target region

---

## **Scenario 5: EC2 Instance Store (Ephemeral Storage for High-Speed Processing)**

* Understand ephemeral high-speed NVMe storage
* Compare Instance Store vs EBS
* Real use cases: caching, temp DBs, distributed processing
* Important: **Data lost on stop/terminate**

---

## **Scenario 6: EFS File System – Multi-AZ Shared Storage Across EC2 Instances**

* Create EFS file system
* Attach mount targets across AZs
* Mount on two EC2 instances
* Validate shared storage (same data visible everywhere)

---
