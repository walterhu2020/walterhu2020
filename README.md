## Hi there 👋

<!--
**walterhu2020/walterhu2020** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->




Username: root

Root Password: NE3lh4g58M39GzmUBe

SSH Port 22

1mO9KuElcAR1st6

------

1. ssh-keygen -t ed25519 -C "alterhu2020@gmail.com"

1.1 ~/.ssh/id_ed25519.pub

ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIPuwaySXZvrLRhp56X5G10MBi+X9HIBzTlLCcpFmnAAd changyhu@LCNHKVD45G7CV

1.2 ~/.ssh/id_ed25519

-----BEGIN OPENSSH PRIVATE KEY-----
b3BlbnNzaC1rZXktdjEAAAAABG5vbmUAAAAEbm9uZQAAAAAAAAABAAAAMwAAAAtzc2gtZW
QyNTUxOQAAACD7sGskl2b6y0Yaeel+RtdDAYvl/RyAc05SwnKRZpwAHQAAAKBkFsIdZBbC
HQAAAAtzc2gtZWQyNTUxOQAAACD7sGskl2b6y0Yaeel+RtdDAYvl/RyAc05SwnKRZpwAHQ
AAAEA6ioiWdBDmV9rrd47k+1Z3dcpmnz2PegeS990uKMh5XfuwaySXZvrLRhp56X5G10MB
i+X9HIBzTlLCcpFmnAAdAAAAFmNoYW5neWh1QExDTkhLVkQ0NUc3Q1YBAgMEBQYH
-----END OPENSSH PRIVATE KEY-----



2. copy ~/.ssh/id_ed25519.pub content to server: ~/.ssh/authorized_keys

3. systemctl restart sshd

4. ssh -i ~/.ssh/id_ed25519 root@23.94.49.90





