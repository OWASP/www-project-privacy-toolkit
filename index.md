---

layout: col-sidebar
title: OWASP Privacy Toolkit
tags: example-tag
level: 2
type: 
pitch: A browser plugin for users' Privacy

---


The OWASP Privacy toolkit represents a pioneering endeavor within the realm of online security. Designed as a browser extension, it caters to a diverse audience comprising end-users and auditors alike. Its primary objective is to foster heightened awareness regarding privacy concerns while also furnishing comprehensive reports on pertinent browsing activities.

## Objectives

The problem we want to solve: Unauthorized code such as 3rd Party JS accessing sensitive information might affect its confidentiality and integrity.

We are working on 3 possible scenarios: 
- The Application stores data in globally accessible variables.(e.g. global, document, etc) 
- The Application stores data in globally storage (Eg localStorage, sessionStorage … )
- Web applications may receive/send too many information unnecessary to the app purposes.

**Pattern Identification Approach:**
- Listing all user-defined variables in the DOM.
- Extracting all data for analysis.
- Inferring or requesting sensitive data categorization (e.g., Personal Identifiable Information - PII) using regular expressions.
- Listing all sensitive data accessible to arbitrary code.
- Hooking the storage API with the Proxy pattern to monitor access and modifications.
- Identifying and hooking JSON deserialization APIs to track data flow.
- Hooking/Proxying object data getters/setters to control data access.
- Correlating received data with used data to identify unnecessary data exchanges (e.g., data tainting or I/O correlation).

## Project roadmap

June 2024: Launch of First Version at the OWASP AppSec Lisbon!
- Pre-Launch Preparation:
-- Finalize the development and testing of the first version of the plugin.
-- Prepare comprehensive documentation and user guides.

Launch Activities:
- Officially release the first version of the OWASP Privacy plugin.
- Engage with online security communities, forums, and social media to spread awareness.
- July 2024 - January 2025: Feedback Gathering and Iteration
- Feedback Collection:
-- Monitor online forums and social media for unsolicited feedback and discussions.
- Analysis and Planning:
-- Regularly review the feedback to identify common issues, desired features, and areas for improvement.
- Iterative Development:
-- Engage with the community through blog posts or forums to keep them updated on progress and upcoming features.

February 2025: Launch of Version 2
- Pre-Launch Preparation for V2:
- Finalize the development and testing of the second version, incorporating user feedback and new functionalities.
- Update documentation and user guides to reflect the new features and improvements.

V2 Launch Activities:
-- Release the second version of the OWASP BCPrivacy plugin.
-- Organize a webinar or online event to showcase the new features and improvements, highlighting how user feedback has been instrumental in shaping this version.

Post-Launch:
- Continue the cycle of feedback collection, analysis, and iterative development for future versions.
- Plan for regular updates and feature releases to keep the plugin relevant and useful for the community.
- Continuous Engagement and Improvement
- Maintain open channels of communication with the user community for ongoing feedback and support.
- Monitor the cybersecurity landscape for emerging threats and adapt the plugin accordingly to address new challenges.

This plan ensures that the development and evolution of the OWASP BCPrivacy plugin are driven by user feedback and the changing dynamics of online security, ensuring its relevance and effectiveness for its intended audience.

## User Benefits

- **Enhanced Privacy:** Users gain increased control and visibility over their personal and sensitive data while browsing, reducing the risk of unauthorized access and potential data breaches.

- **Informed Browsing:** End-users and auditors receive detailed reports on browsing activities, helping to identify and mitigate privacy risks in real-time.

- **Proactive Protection:** By identifying and addressing potential vulnerabilities related to data storage and exchange, users can proactively safeguard their information against emerging threats.

- **Educational Insight:** The toolkit educates users about data privacy, encouraging safer browsing habits and better understanding of online privacy challenges.

- **Customized Security:** The ability to categorize and monitor sensitive data according to user-defined parameters allows for personalized privacy protection that aligns with individual security needs.

## Next Talk: OWASP AppSec Lisbon!

<p align="center">
   <img src="https://github.com/OWASP/www-project-privacy-toolkit/blob/a9c0bdac84c35120e02917ab944c66b95ca09044/assets/images/Lisbon%20Logo.png?raw=true" width=600/> 
</p>

[Martino Lessio and Stefano Di Paola ](https://owaspglobalappseclisbon2024.sched.com/event/1VdCN/owasp-privacy-toolkit-bringing-privacy-awareness-in-the-digital-age) will talk about the project next 27th June, 2024 <br>
When: 27th June, 2024  WEST- 1.15-2.00 PM <br>
Where: Lisbon, Portugal <br>
<br>

## Past Talk: OWASP Italy at Security Summit in Milan
[Martino Lessio](https://securitysummit.it/milano-2024/seminario-owasp) did a talk about the project last 21st March, 2024 <br>
<br>

<p align="center">
   <img src="https://github.com/OWASP/www-project-privacy-toolkit/blob/b7ca58f1dcc2a5c6c2d3b0b16d6919bc4896f69c/assets/images/MArtinoSecSummit24.jpeg?raw=true" width=600/> 
</p>


  [You can download the slide here](https://github.com/OWASP/www-project-privacy-toolkit/blob/b168e612b7bc452f1bd8c65fb1af655d461ac5e8/assets/images/Martino%20Lessio%20-%20OWASP%40SecSummit%202024-03-21.pdf) 


## Publications
To see the complete list of publications, please visit [https://testable.eu/publications/](https://testable.eu/publications/).

## Project partners

- [CISPA](https://cispa.de/)
- [Eurecom](https://www.eurecom.fr/en/)
- [Technical University of Braunschweig](https://www.tu-braunschweig.de/)
- [UC3M](https://www.uc3m.es/)
- [SAP SE](https://www.sap.com/)
- [ShiftLeft](https://www.shiftleft.io/)
- [IMQ Minded Security](https://mindedsecurity.com/)
- [NortonLifeLock](https://www.nortonlifelock.com/)
- [Pluribus One](https://www.pluribus-one.it/)

## Acknowledgements

This project received funding from the European Union's Horizon 2020 research and innovation programme under grant agreement No. 101019206.

<br>
<p align="center">
<a href="https://testable.eu"><img src="https://owasp.org/www-project-testability-patterns-for-web-applications/assets/images/eu_flag.png" alt="EU Flag"/></a>
</p>
