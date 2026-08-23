# Lab 11

### Access Control List (ACL) in Linux

In Linux, file security is managed through two main systems: the traditional **standard permission policy** and the more flexible **Access Control Lists (ACLs)**.

* Use **Standard Permissions** for basic tasks where you only need one owner and one primary group.
* Use **ACLs** when a specific user or service account needs access to a file it does not own.

ACLs allow you to assign permissions to individual users or groups, even if they are not the original owner or owning group. This lets you build complex access scenarios without changing the application logic.

***

### Lab Exercise

#### Step 1 — Install the ACL Tools

Make sure ACL tools are installed on your Linux system.

```bash
sudo apt-get install acl
