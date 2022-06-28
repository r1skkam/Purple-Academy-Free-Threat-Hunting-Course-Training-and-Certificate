[Purple Academy | Free Threat Hunting Course, Training, and Certificate](https://academy.picussecurity.com/course/foundations-of-threat-hunting-training-free-course-certification)

# Purple-Academy-Free-Threat-Hunting-Course-Training-and-Certificate
**Foundations of Threat Hunting** `By the end of this free course, you would have learned about challenges and culture shifts in detection, threat hunting fundamentals and goals, and the four steps of threat hunting with real-world examples.`

## 1. Introduction
### 1.1 Introduction
Hello.
Welcome to the Foundations of Threat Hunting course by Purple Academy.
This is the fourth course of the proactive Security Operation Center (SOC) learning path.

By the end of this course, you will have learned about: 
- Challenges and culture shift in detection 
- What is threat hunting, and where does it fit in security operations?
- What are the goals of threat hunting?

Moreover, you will learn the four steps of threat hunting with real-world examples. These steps are: 
- Create hypothesis
- Investigate by tools and techniques
- Uncover new patterns & TTPs 
- Inform & Enrich analytics

At the end of the course, you will be able to identify the threat hunting maturity level of your organization.

### 1.2 Challenges in Detection
Let me start with the challenges in threat detection to understand why we need threat hunting.
- The first challenge here is about the dwell time, the length of time an adversary remains undetected inside the network. Advanced adversaries can remain hidden for months before detection. 
- As the second challenge, every day, we see breaches in the news. So, we are struggling to stop adversaries from getting into our networks and systems.
- The third one is that we cannot fully understand our cybersecurity posture without knowing the current state of compromise.

These challenges emphasize that we need to operate under the "assume breach" mindset.

![image](https://user-images.githubusercontent.com/58542375/176231419-b934570c-87c0-4874-b4a1-638740bd0f5d.png)

### 1.3 Culture Shift in Detection
These challenges result in a culture shift in the detection of threats.
We are mostly operating on the firefighting level, responding to alerts that are generated in your organization. We are performing actions in reactions to notifications of security tools, such as SIEM, EDR, and IPS. This is completely understandable In case of those triggers are relevant and help us to address important issues.
Yet, the only plan cannot be sitting around and waiting for notifications about something bad happening. We should be proactive and find malicious activities happening in your environment.

Starting with the first antivirus software, we are traditionally detecting Atomic IOCs, such as hash values, IP addresses, and domain names. However, we must start to detect adversary behavior, tactics, techniques, and procedures (TTPs), and tools used by adversaries. At least, we have to detect their artifacts in network and hosts. 

Transitioning from reactive to proactive is slow. It can be difficult, and fallbacks to IOCs are understandable. So, how do we start climbing this pyramid and get away from solely focusing on IoC more towards to the top of the pyramid? The answer is threat hunting.

![image](https://user-images.githubusercontent.com/58542375/176232170-12a89926-bdfd-4b49-b6f3-160c1f247719.png)

![image](https://user-images.githubusercontent.com/58542375/176232427-e202a81d-b7e5-4ab5-8917-2a3801476077.png)
