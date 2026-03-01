# Task 3: Attach EBS Volume from Different AZ using Snapshot

Objective:
To understand how EBS snapshots allow cross-Availability Zone volume creation.

Steps Performed:
1. Created snapshot from existing EBS volume.
2. Created new volume from snapshot in different Availability Zone.
3. Launched EC2 instance in that AZ.
4. Attached new volume to EC2 instance.
5. Mounted volume successfully in Linux.

Result:
Successfully attached and mounted EBS volume across Availability Zones using snapshot.