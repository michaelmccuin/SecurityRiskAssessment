<h1>Security Risk Assessment</h1>

<h2>Description</h2>

📊 **Overview**
  - Conducted a comprehensive risk assessment to enhance data security practices within an organization.

🔍 **Key Points**
  - Assessment: Develop and document risk mitigation strategies based on audit findings [NIST SP 800-53](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-53r5.pdf) 3.1 Media Protection family (MP-1 through MP-8).
  - Prioritization: Objectively identify high-priority risks and effectively communicate them to the organization, fostering an informed and proactive risk management strategy.
  - Frameworks: Employed the assessment scales outlined in [NIST SP 800-30](https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-30r1.pdf), providing a quantifiable framework for identifying and prioritizing risks.

🚀 **Objectives**
  - Combine threat modeling results with existing Standard Operating Procedures (SOP) and System Security Plan (SSP) to understand the organization's risks.
  - Tailor risk explanations to resonate with a non-technical audience.
  - Develop strategies to mitigate identified risks.

<h2>Project Walk-Through:</h2>

For the purpose of this project, I will be using the findings from the [Practical Audit](https://github.com/michaelmccuin/PracticalAuditing) I conducted, combined with threat modeling, to understand the risks involved with the organization.

**Step 1: Understanding Control Status**  
Based on [NIST SP 800-53](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-53r5.pdf), my disposition was that control MP-1 (Media Protection Policy and Procedures) was not in place.
<img src="https://i.imgur.com/Ki7wr8F.jpg" /> <br/>
Based on the interview with Director of IT, Frank Reynolds, the review of the SOP and SSP, and the threat modeling conducted prior to the audit, I determined that the biggest risk for not having Media Protection policies and procedures in place is unauthorized access.  
<img src="https://i.imgur.com/U5gOVCG.jpg" />

**Step 2: Identifying Mitigating Factors**  
From the evidence I gathered in the interview, I can say that a mitigating factor for this risk is "Tribal knowledge in place" for people within the organization.  
<img src="https://i.imgur.com/jHrbQZq.jpg" />

**Step 3: Quantitative Risk Assessment**  
I then used [NIST SP 800-30](https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-30r1.pdf) assessment scales for quantitative determination of impact and likelihood of this risk. Understanding these values allows me to consistently determine the risk for each control.  
<img src="https://i.imgur.com/GgFlIRM.png" height="50%" width="50%" /> <br/>
Using these values, I can objectively determine that the likelihood of unauthorized access would be a 5 (low), and the impact if it were to happen would also be a 5 (low); the overall impact for this risk is 25/100 (low).  
<img src="https://i.imgur.com/XTFfHp4.jpg" />

**Step 4: Objective Risk Explanation**  
My objective, defensible explanation for this risk: "Staff do not know what expectations or standards are, and no process around media protection, storage, or sanitization is documented, so may not be done properly. Without standards and policy, no process can be repeated consistently, and staff will develop their own individual processes."  
<img src="https://i.imgur.com/i5c0MYk.jpg" />

**Step 5: Repetition for Each Control**  
After completing the risk assessment for Media Access control MP-1, I repeated steps 1-4 for controls MP-2 through MP-8.  
<img src="https://i.imgur.com/ImcETjV.png" height="50%" width="50%" /> <br/>
(reference image for evidence gathering as seen in [Practical Auditing](https://github.com/michaelmccuin/PracticalAuditing) project)  
<img src="https://i.imgur.com/J5Gd4OG.png" height="50%" width="50%" /> <br/>

**Step 6: Prioritizing Risks**  
I then sorted the spreadsheet by overall risk to prioritize the controls that have the highest risk.  
<img src="https://i.imgur.com/FzZVLZO.png" height="50%" width="50%" /> <br/>
Now that I had an organized list of the risks, I created an executive report to effectively communicate the risks with the organization.  
<img src="https://i.imgur.com/kKK1s9r.png" height="50%" width="50%" /> <br/>

<p align="center">
  <span style="font-size: 2em;"><a href="https://docs.google.com/spreadsheets/d/17zRvzwwiNtiXcRV9rU4kEA-JNNDUuKhEi1iBXxCatS0/edit?usp=sharing" target="_blank">Risk Assessment Spreadsheet</a></span>
</p>

**Optional Step: Providing Mitigation Recommendations**  
The risk assessment could also include next steps to mitigate the risks in scope. Perhaps the organization I work for offers a solution to mitigate a specific risk, then I could include it in the risk assessment and add additional value for the organization.


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
