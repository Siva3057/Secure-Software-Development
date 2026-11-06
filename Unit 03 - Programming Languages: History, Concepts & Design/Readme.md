Summary post

Two peers reviewed my Smart University misuse case diagram. Both praised the pairing of Wi-Fi, attendance and CCTV functions with realistic threats, and the use of external and insider misusers. I agree this is the diagram’s strength, as misuse cases make each threat visible beside the function it endangers (Sindre and Opdahl, 2005).

Both challenged my phishing mitigation, and I partly agree. My narrative wrongly said data exfiltration counters phishing. In the diagram, the relationship runs the other way: exfiltration includes credential theft, because attackers usually need valid credentials first, while multi-factor authentication is the mitigation. The wording was misleading, and I have corrected it. I also accept the suggestion to add email filtering and staff awareness training, since a single technical control leaves human error unaddressed (Alexander, 2003).

I agree attendance spoofing needs expanding. A cloned smart card could register false attendance, so this misuse case should link to card cloning as well as sensor tampering, with mutual authentication and sensor integrity checks as mitigations (Garcia et al., 2008). Network segmentation, suggested by one reviewer, is already paired with patching against CCTV hijacking in my diagram.
I accept the point on denial of service. I listed it as future work, but disruption to the VLE or Wi-Fi would affect every user, so a revised diagram should include it.

On priority, I would address compromised credentials first. They enable several other misuse cases, and multi-factor authentication reduces risk across the VLE and student records. Attendance manipulation and CCTV hijacking can follow, ranked by likelihood and impact (Shostack, 2014).

Overall, the feedback improved the model in three ways: clearer mitigations, richer attendance threats and broader availability coverage. These changes strengthen traceability from threat to testable security requirement, though the diagram remains a qualitative model that would need risk scoring before implementation.

References

Alexander, I. (2003) ‘Misuse cases: use cases with hostile intent’, IEEE Software, 20(1), pp. 58–66.

Garcia, F.D., de Koning Gans, G., Muijrers, R., van Rossum, P., Verdult, R., Wichers Schreur, R. and Jacobs, B. (2008) ‘Dismantling MIFARE Classic’, in Jajodia, S. and Lopez, J. (eds.) Computer Security – ESORICS 2008. Lecture Notes in Computer Science, vol. 5283. Berlin: Springer, pp. 97–114. Available at: https://doi.org/10.1007/978-3-540-88313-5_7.

Shostack, A. (2014) Threat Modeling: Designing for Security. Indianapolis: Wiley.

Sindre, G. and Opdahl, A.L. (2005) ‘Eliciting security requirements with misuse cases’, Requirements Engineering, 10(1), pp. 34–44. Available at: https://doi.org/10.1007/s00766-004-0194-4.

