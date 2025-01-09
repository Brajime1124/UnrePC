<h1>Recovering a System After a Failed BIOS Update</h1>

<h2>Description</h2>
This project involved diagnosing and resolving a critical issue caused by a failed BIOS update, which left the client’s PC unable to boot. The goal was to restore the system to a functional state without data loss or hardware replacement. By utilizing advanced troubleshooting techniques, I identified the corrupted firmware as the root cause and implemented recovery methods, including BIOS re-flashing via a USB boot drive. This process successfully revived the system and ensured stable operation, showcasing my ability to handle complex system-level failures with precision and efficiency.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Windows Command Prompt</b>
- <b>BIOS and UEFI Interface</b> 
- <b>USB Flash</b>

<h2>Environments Used </h2>

- <b>Windows 11</b>

<h2>Program walk-through:</h2>

<p align="center">
<h3>1. Initial Diagnosis</h3>
The motherboard’s diagnostic light indicated a red status, which the manual identified as a hardware issue. To confirm the problem wasn’t temporary, I attempted to power the system on and off multiple times, but the PC still failed to boot.

<h3>2. Testing Components</h3>
Next, I checked key components to rule out other potential failures:

Power Supply: Verified the power supply unit (PSU) was operational by observing the spinning fan.
Graphics Card: Confirmed the GPU was functioning, as its fans spun when the system powered on.
These tests confirmed that power was being delivered correctly, narrowing the issue to the motherboard or BIOS.

<h3>3. Reflashing the BIOS</h3>
Believing the BIOS files might have been corrupted during the failed update, I prepared a USB drive with a fresh installation of Windows and attempted to reflash the BIOS. This involved:

Downloading the latest BIOS firmware from the motherboard manufacturer’s website.
Using a tool like Rufus to create a bootable USB drive with the firmware.
Following the motherboard’s recovery process (e.g., BIOS Flashback).
Despite these efforts, the system remained unresponsive, pointing to a more severe motherboard issue.

<h3>4. Confirming the Root Cause</h3>
With other components ruled out and the BIOS reflash unsuccessful, I determined the motherboard itself was the problem. The failed BIOS update had likely caused irreparable damage to the firmware or circuitry.

<h3>5. Replacing the Motherboard</h3>
To resolve the issue, I ordered a compatible, upgraded ATX motherboard for the client’s PC. Once the replacement arrived, I carefully installed it:

Disconnected all components, including the CPU, RAM, GPU, and storage devices, from the old motherboard.
Installed the new motherboard into the case and reconnected all components.
Ensured proper cable management and verified all connections were secure.

<h3>6. System Boot and Testing</h3>
After installing the new motherboard, I powered on the PC. It booted successfully without any errors, as though no issues had occurred. I conducted a thorough test of the system to ensure all data, applications, and configurations were intact.

<h3>7. Outcome</h3>
The client’s PC was fully restored with no loss of memory or data. The upgrade to a newer motherboard not only resolved the issue but also provided additional functionality and compatibility for future updates.

This project highlights my ability to diagnose hardware issues, perform systematic troubleshooting, and execute hardware replacements while maintaining data integrity. My approach combined technical expertise with a clear, client-focused resolution.
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
