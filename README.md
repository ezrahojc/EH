# EH
Ethical Hacking Assignment for Cybersecurity and Digital Forensics Diploma in Ngee Ann Polytechnic.

The main exploit we used was EternalBlue, which was leaked by Shadow Brokers on 14th April 2017. This was used in the WannaCry ransomware attack of 2017.
It takes advantage of a vulnerability seen in Microsoft implementation of the Server Message Board (SMB) Protocol. This is more primarily used in offices than home as it creates a connection between client and server by sending responses and requests. As houses does not often have servers, most home users would not have known about such a protocol.
This exploit allows illegitimate data packets into a legitimate network, containing trojans, ransomware or other similar programs.
As of 2020, findings show that 73,763 detections were made of the specific samples known to use EternalBlue

The other exploit used was Polkit.
This vulnerability has been around for 7 years and is only recently made known public.
It is formerly known as PolicyKit, evaluating specific Linux activities require higher privileges than those currently available (e.g. create root account).
It is triggered by the dbus-send command, killing it mid-process of the request, leading it to ask the UID of a connection that no longer exist since the connection was killed. 
This vulnerability enables an unprivileged local user to get a root shell on the system. 

