
My notes from the chapters that i thought would be useful for my research. 

Chapter 1 - Overview of the Current State of Cybersecurity in the Automotive
Industry 

	- The Automotive industry gradually introduces the notion of connected and autonomous vehicles w around 2010 with Advanced driver assistance systems (ADAS) 
	- They often rely on external entities and partially control vehicle functionality. 
	- The main focus of these systems, besides safety and capabilities, is the need for security.
	- As more software is included in vehicles, there is a risk of introducing software bugs and vulnerabilities that, if abused by malicious attackers, could potentially have disastrous consequences on safety, privacy, and operation of the vehicles.
	- Because of the volume of software, cybersecurity is an ever-increasing important topic that the automotive industry must seriously consider. 
	- Pg 7, Cybersecurity monitoring services or tools that give alerts on new vulnerabilities can be used to provide input to an automotive security operations center (SOC). Using the information stores in the ALM/PLM systems allows for organizations to identify the impact of certain newly identified vulnerability. It is necessary to asses which software versions are affected by the identified vulnerability, as well as the exploitability and impact of said vulnerability. 
	- Pg 9, sixty-two percent say that a malicious or proof-concept attack against the automotive technologies or systems developed by their organizations is likely or very likely in the next 12 months.
	- However, a technical challenge that 61% of the organizations face is being able to address critical security vulnerabilities in a timely manner through a software update delivery model. 
		○ My insight: so we need more Threat Intelligence like CVE - MITRE attack mapping for efficient VM management across all industry especially Automotive industry, '
	- Pg 13th, Second, organizations must have the understanding that software bugs and vulnerabilities will be detected in their automotive systems after vehicles have been released and that such vulnerabilities need to be addressed in a timely manner. 
	- Pg 18th, a third example is regarding open source software, in particular focusing on known vulnerabilities in such software used in automotive systems that can be exploited by attackers. 
		○ My insight: we use a lot of 3rd party libraries in development. Leverage CVE of different vuln, and map it to MITRE for better and faster risk management process. 
	

IEEE Citation:  

D. K. Oka, “Overview of the Current State of Cybersecurity in the Automotive Industry,” in Building secure cars: Assuring the Automotive Software Development Lifecycle, Hoboken, NJ: Wiley, 2021. 

Chapter 4 - Need for Automated Security Solutions in the Automotive Software Development Lifecycle

	- From the remediation perspective…
	- Once the developed software for the automotive system  is more or less functional, organizations can perform vulnerability scanning using known attacks and attack patterns to identify vulnerabilities in the software. 
		○ My insight: use the CVE mapping to better find vuln too,
	- Pg 60, for example security teams can actively search for newly identified vulnerabilities that are published online, and actively monitor and process information gathered from deployed vehicles to detect attack patterns. 
	- AUTO ISAC (Automotive Information Sharing and Analysis Center). 
	- Vulnerability Management involves identifying how critical a certain threat or vulnerability is in regards to the specific products. 
	


IEEE Citation: 
D. K. Oka, “Need for Automated Security Solutions in the Automotive Software Development Lifecycle,” in Building secure cars: Assuring the Automotive Software Development Lifecycle, Hoboken, NJ: Wiley, 2021. 

Chapter 12 - Continuous Cybersecurity  Monitoring, Vulnerability Management, Incident Response, and Secure OTA Updates. 

	- The challenge in Automotive Security is the need for Continuous cybersecurity monitoring. The automotive industry has traditionally not had defined processes for cybersecurity monitoring to actively monitor for threats, vulnerabilities and attacks on their vehicles. 
	- The increase in connectivity capabilities and advanced software in vehicles, it is likely that more vehicles will be targeted and thus will be requiring automotive organizations to establish cybersecurity monitoring process. 
	- However, in march 2018, within just five months after the software package was released, three critical vulnerabilities in curl had been CVE-2017-8817, CVE-2017-8817, CVE-2018-1000120. If we have a proper continuous cybersecurity monitoring process is not in place, an automotive organization would not be aware of any critical vulnerabilities that may be discovered shortly after the software is released. 



IEEE Citation: 
D. K. Oka, “Continuous Cybersecurity Monitoring, Vulnerability Management, Incident Response, and Secure OTA Updates,” in Building secure cars: assuring the automotive software development lifecycle, Hoboken, NJ: Wiley, 2021. 

