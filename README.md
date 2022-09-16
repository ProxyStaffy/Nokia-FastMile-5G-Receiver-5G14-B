# Nokia-FastMile-5G-Receiver-5G14-B

CVE-2022-38788

CVSS v3.1 Vector:AV:A/AC:L/PR:N/UI:R/S:U/C:L/I:L/A:L (5,5)

[Description]

An issue was discovered in Nokia FastMile 5G Receiver 5G14-B
with software version 1.2104.00.0281.

Bluetooth on the Nokia ODU uses outdated pairing mechanisms, allowing
an attacker to passively intercept a paring handshake and (after
offline cracking) retrieve the PIN and LTK (long-term key).

![test1WS](https://user-images.githubusercontent.com/113522001/190152812-dc105dc3-c0f5-43c9-9eb2-4cc607ea065a.png)
![test1](https://user-images.githubusercontent.com/113522001/190152891-ee34032c-4301-4667-bf0f-6bc33a973203.png)


------------------------------------------

[Vulnerability Type]

Incorrect Access Control

------------------------------------------

[Vendor of Product]

Nokia

------------------------------------------

[Affected Product Code Base]

Nokia FastMile 5G Receiver 5G14-B

Found in Software Version:
1.2104.00.0281

Pathed in:
1.2202.00.0266

-------------------------

[Attack Type Other]

Bluetooth

------------------------------------------

[Impact Information Disclosure]

true

------------------------------------------

[Has vendor confirmed or acknowledged the vulnerability?]

true

------------------------------------------

[Reference]

https://www.nokia.com/notices/responsible-disclosure/

Product page:
https://www.nokia.com/networks/products/fastmile-5g-receiver/

------------------------------------------

[Discoverer]

Daniel Wong

