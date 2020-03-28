### Homework Description
#### Write two rules in test.rules
If snort sees two packets in a flow, the first of which contains "login" or "Initial" in payload, with destination port - 3399, and the second packet has "IPv4Address:Port" string in payload, with destination port - 3399, output a alert with msg "bot founded" and sid 1000001.
