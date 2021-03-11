.. _softwarebasedencryption:

-------------------------
Software Based Encryption
-------------------------

Data at Rest Encryption is a critical platform security capability:

- Ensures that user data does not leave data centers via failed disk drives
- Protects at-rest data against drive theft
- Required for compliance in many Federal, Healthcare, Financial, and Legal environments

Nutanix provides a number of different options for delivering Data at Rest Encryption.

.. figure:: images/1.png

Software-based encryption with Nutanix's integrated key management service (KMS) can provide a frictionless experience for enabling encryption without impacting performance.

.. figure:: images/2.png

Enabling software-based encryption is a one time operation at a per cluster level, so cannot be performed in a shared, lab environment. However, the brief, narrated video below walks you through the few steps required to enable this feature.

.. raw:: html

  <center><iframe width="640" height="360" src="https://www.youtube.com/embed/-6fIL3FJjN8?rel=0&amp;showinfo=0&amp;t=53" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></center>

Audit Logs
++++++++++

System auditing is not only a good practice but often a security compliance requirement. Getting the history of changes or accesses made to a system (files, directories, system resources and system calls) into a service which can present those logs in a legible format is something your customers are going to want to do, and most likely within the first week of deploying their Nutanix cluster.

Nutanix can forward detailed system events to a syslog server in a few short minutes. In this narrated video you will learn what audit logs are available, where to configure a syslog server and what actions you can take to troubleshoot common problems.

.. raw:: html

  <center><iframe width="640" height="360" src="https://www.youtube.com/embed/YuhC5nWd5Is?rel=0&amp;showinfo=0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></center>

VM Secure Boot
++++++++++++++

New in AOS 5.16, Secure Boot for user VMs is a security feature in which AHV checks that the guest OS boot loader is signed with a cryptographic key authorized by a database contained in the UEFI firmware, verifying and trusting the integrity of the OS boot loader.

.. figure:: images/3.png

In 5.16, Secure Boot is not yet available through the Prism interface. In this brief, narrated video you will learn how to enable this feature for a VM using ``acli``.

.. raw:: html

  <center><iframe width="640" height="360" src="https://www.youtube.com/embed/dRs5QpFke2U?rel=0&amp;showinfo=0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></center>

Takeaways
+++++++++

- Nutanix is committed to providing a secure platform out of the box, including:

   - Automated application and remediation of STIGs
   - Multiple options for providing Data at Rest Encryption, including a simple to enable software-based option
   - Audit logging, including the ability to ship system and Flow logs to an external syslog server
   - Trusted boot technology for guest VMs running on AHV
