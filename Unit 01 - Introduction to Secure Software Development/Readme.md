**Initial Post**

A smart university is a group of devices working towards shared goals: learning, safety and efficient operation. Wi-Fi, smart-card readers, attendance sensors, building management, CCTV and student records share one network. I chose it because it is open and heterogeneous: users bring their own devices, and many IoT nodes are constrained and rarely patched (Roman, Zhou and Lopez, 2013).

The diagram uses Sindre and Opdahl’s (2005) notation: misuse cases are black ovals, misusers have filled heads, and relationships are "threatens," "mitigates," and "includes." Modelling hostile goals alongside legitimate ones makes each threat visible beside the function it endangers and surfaces security requirements early (Alexander, 2003).

Seven use cases are each paired with a threat. Phishing threatens the VLE and is countered by data exfiltration, since attackers usually need valid credentials. A rogue access point threatens Wi-Fi and is countered by WPA3-Enterprise. Smart card cloning exploits known weaknesses (Garcia et al., 2008) and is mitigated by mutual authentication. Integrity logging is used to address attendance spoofing by manipulating sensor data. Unpatched firmware is a recurring IoT weakness (OWASP, 2018), as shown by the Mirai botnet (Antonakakis et al., 2017); CCTV hijacking also relies on it, so patching and segmentation mitigate both.

Two misusers reflect different threat sources. The external attacker acts remotely, whereas the malicious insider has legitimate access and physical proximity, so defences must differ (Shostack, 2014). Each threat maps to one security use case, giving traceable, testable requirements. The model is not exhaustive; denial of service and supply chain attacks remain future extensions.

**References**

Alexander, I. (2003) ‘Misuse cases: use cases with hostile intent’,** ** *IEEE Software* , 20(1), pp. 58–66.

Antonakakis, M. et al. (2017) 'Understanding the Mirai botnet',** ** *Proceedings of the 26th USENIX Security Symposium* , pp. 1093–1110. Available at:** **doi.org.

Garcia, F.D., de Koning Gans, G., Muijrers, R., van Rossum, P., Verdult, R., Wichers Schreur, R. and Jacobs, B. (2008) 'Dismantling MIFARE Classic', in Jajodia, S. and Lopez, J. (eds.)** ** *Computer Security – ESORICS 2008* . Lecture Notes in Computer Science, vol. 5283. Berlin: Springer, pp. 97–114. Available at:** **https://doi.org/10.1007/978-3-540-88313-5_7.

OWASP (2018).** ** *OWASP Internet of Things Top 10* . Available at:** **[https://owasp.org/www-project-internet-of-things/](https://owasp.org/www-project-internet-of-things/) (Accessed: 29 October 2026).

Roman, R., Zhou, J. and Lopez, J. (2013) 'On the features and challenges of security and privacy in distributed internet of things',** ** *Computer Networks* , 57(10), pp. 2266–2279. Available at: https://doi.org/10.1016/j.comnet.2012.12.018.

Shostack, A. (2014)** ** *Threat Modelling: Designing for Security* . Indianapolis: Wiley.

Sindre, G. and Opdahl, A.L. (2005) 'Eliciting security requirements with misuse cases',** ** *Requirements Engineering* , 10(1), pp. 34–44. Available at: https://doi.org/10.1007/s00766-004-0194-4.
