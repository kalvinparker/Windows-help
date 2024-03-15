# Provenance & Nationality Assessment
```
Act as Provenance & Nationality Assessment, target [vendor] as the vendor, [https://www.website.com/] as the vendor’s website, [product] as the vendor’s product and [https://www.website.com/doc/] as the product’s webpage or location for documentation such as release notes/changelogs. I want you to provide links for each numbered bullet point below, ask me to clarify any questions and make sure to provide sources for your answers:
1.	Who developed the software?
2.	What were their goals?
3.	What country of origin is the vendor?  
4.	Is the product widely known and is it market leading?
5.	Are there existing uses of the software in (listed in order of importance), Government, the banking industry; specifically, UK/federal level and/or other reputable organisations such as AWS, and Red Hat.
6.	Include any case studies, adopters, and partners.
```
# Service and Supportability Assessment
```
Act as Service and Supportability Assessment, target [vendor] as the vendor, [https://www.website.com/] as the vendor’s website, [product] as the vendor’s product and [https://www.website.com/doc/] as the product’s webpage or location for documentation such as release notes/changelogs. I want you to provide links for each numbered bullet point below, ask me to clarify any questions and make sure to provide sources for your answers:
1.	Is the product GOTS or COTS or FOSS?
2.	What is the vendor/product support lifecycle?
a.	Keywords to look for are support, Long-term Support (LTS), lifecycle, release cycle, End of Life (EoL) policy, extended support;
b.	It is recommended to use LTS releases for production environments over the very latest as support is normally longer;
c.	Provide a link to a changelog and/or Release Notes, reference release notes as this is important for end-users during upgrades, highlight breaking changes in the release notes.;
d.	Align release cadence with support lifecycles;
e.	The “release and maintenance” documentation can be found on their website; use statement when applicable
f.	A predictable release cadence is good, use the table below to represent a picture of predictable release cycle;
3.	Create a table with the following heading: Major release version (example, 2024.x or 20.x), date released (example, 14 Mar 24), service support status (example, Ends 14 Mar 25 or Ended 14 Mar 23), security updates (example, Ends 14 Mar 25 or Ended 14 Mar 23) and latest or final version (example, 2024.0.1 (14 Mar 24)). 
a.	Green = fully supported;
b.	Amber = receives security updates but receives no service support;
c.	Red = no support received, including no security support.
4.	In a table state what Operating Systems or other platforms are supported including other applications/plugins etc Create a table with the following headers, Platform/OS (example, Windows or Chrome), version #1 (example, Win 10 (64-bit)), version #2 (example, Win 10 (32-bit)), version#3.:
5.	Is the product compatible with Windows 11? If so, provide a statement to the effect of: The software is compatible with Windows 11. 
6.	Document different tiers of support clearly (such as Active/Security/Extended);
a.	Clearly explain what each tier of support includes, such as critical security fixes;
b.	Customers paying for premium support should have access to additional support team and guaranteed SLA; for example
c.	Provide a clear and comprehensive explanation of what each level of support entails.
7.	List other documentation, guides, tutorials available: E.g. www.website.com/docs; docs.website.com; GitHub community page.
```
# Vulnerability Assessment
```
Act as Vulnerability Assessment, target [vendor] as the vendor, [https://www.website.com/] as the vendor’s website, [product] as the vendor’s product and [https://www.website.com/doc/] as the product’s webpage or location for documentation such as release notes/changelogs. I want you to provide links for each numbered bullet point below, ask me to clarify any questions and make sure to provide sources for your answers:
1.	What information is provided in the security advisories / bulletins published by the company regarding known vulnerabilities, 
a.	How are plugins assessed for trustworthiness.
2.	What are the security risks associated with using the software, 
a.	how these risks are mitigated.
3.	Does it publish security advisories 
a.	what is its time to fix?
4.	Create a table with the following headers, CVE ID, description, affected version, CVSS, Published date. Use the following external sources along any CVEs published on the[vendor] website to fill in the table to show examples of Common Vulnerabilities and Exposures (CVEs) reported in earlier versions of the software: 
a.	https://cve.mitre.org/;
b.	https://www.cvedetails.com/vulnerability-list; and
c.	https://nvd.nist.gov/vuln.
```
# Hardening Assessment
```
Act as Hardening Assessment, target [vendor] as the vendor, [https://www.website.com/] as the vendor’s website, [product] as the vendor’s product and [https://www.website.com/doc/] as the product’s webpage or location for documentation such as release notes/changelogs. I want you to provide links for each numbered bullet point below, ask me to clarify any questions and make sure to provide sources for your answers:
1.	What guidance does the company provide for implementing and hardening the software’s architecture?
2.	Applicable to hardware products only, does the product utilise Wi-Fi, web cam, microphone, Bluetooth technologies and/or geolocation technologies?
3.	Applicable to hardware products only, where will the hardware need to be located and what physical measures will need to be implemented to secure it?
4.	Create a table with the following headers, Use Case and Description.
5.	Is there any independent hardening available on Center for Internet Security (CIS) or Security Technical Implementation Guide (STIG).
a.	https://www.cisecurity.org/benchmark/; and
b.	https://www.stigviewer.com/; or 
c.	No independent hardening can be found on Center of Internet Security (CIS) or Security Technical Implementation Guide (STIG). Use statement if applicable.
Architecture Assessment
Act as Architecture Assessment, target [vendor] as the vendor, [https://www.website.com/] as the vendor’s website, [product] as the vendor’s product and [https://www.website.com/doc/] as the product’s webpage or location for documentation such as release notes/changelogs. I want you to provide links for each numbered bullet point below, ask me to clarify any questions and make sure to provide sources for your answers:
1.	What is the recommended architecture for a secure software solution, and how does it prevent malicious access to the software’s home directory and operations.
a.	Include diagrams and insert caption below it to link to List of Figures.
b.	[Product] is a standalone application. If applicable
2.	Is there, or will there be, onward connectivity to other systems? If so, the nature and value of the information must be considered.
a.	Is there any potential for the data to be accessed over the internet?
```
# Deployment Assessment
```
Act as Deployment Assessment, target [vendor] as the vendor, [https://www.website.com/] as the vendor’s website, [product] as the vendor’s product and [https://www.website.com/doc/] as the product’s webpage or location for documentation such as release notes/changelogs. I want you to provide links for each numbered bullet point below, ask me to clarify any questions and make sure to provide sources for your answers:
1.	What is the deployment process for [product]?
a.	Installation overview.
2.	What documentation is required for integrating with code repositories, secrets servers, infrastructure, and authentication platforms?
```
# Data Assessment
```
Act as Data Assessment, target [vendor] as the vendor, [https://www.website.com/] as the vendor’s website, [product] as the vendor’s product and [https://www.website.com/doc/] as the product’s webpage or location for documentation such as release notes/changelogs. I want you to provide links for each numbered bullet point below, ask me to clarify any questions and make sure to provide sources for your answers:
1.	What kind of data does the software platform hold, and how does it interact with other services to execute commands.
a.	Is there a data management plan?
b.	If so, where is the data held.
c.	What file formats does it handle?
2.	Security monitoring, how does the [Product name] collect and aggregate logs?
a.	IP connections between network and internet.
b.	Host-based activity
	At application layer.
	At network layer.
3.	Will information be made available to the supplier? (as a minimum; test data, data from operational technology systems, and information about system usage)
```
# Vendor Assessment
```
Act as Vendor Assessment, target [vendor] as the vendor, [https://www.website.com/] as the vendor’s website, [product] as the vendor’s product and [https://www.website.com/doc/] as the product’s webpage or location for documentation such as release notes/changelogs. I want you to provide links for each numbered bullet point below, ask me to clarify any questions and make sure to provide sources for your answers:
1.	Is the vendor widely known and is it market leading?
a.	Include any case studies, adopters, and partners.
2.	What do other reputable companies say about the vendor of the software?
a.	Sources: https://www.gartner.com/reviews
3.	What is the governance structure of the company’s organisation?
4.	How does the security team oversee the released builds for the open source platform?
```
# Accreditation and Certifications Assessment
```
Act as Accreditation and Certifications Assessment, target [vendor] as the vendor, [https://www.website.com/] as the vendor’s website, [product] as the vendor’s product and [https://www.website.com/doc/] as the product’s webpage or location for documentation such as release notes/changelogs. I want you to provide links for each numbered bullet point below, ask me to clarify any questions and make sure to provide sources for your answers:
1.	What commitment to secure software development practices or independent security certifications are achieved by the vendor, such as standards like NIST, ISO 27001 etc.
a.	What are their secure coding practices like?
b.	What are their vulnerability assessment procedures?
```
# Summary and Recommended Mitigations
```
Act as IT Security Consultant, target [vendor] as the vendor, [https://www.website.com/] as the vendor’s website, [product] as the vendor’s product and [https://www.website.com/doc/] as the product’s webpage or location for documentation such as release notes/changelogs. I want you to provide links for each numbered bullet point below, ask me to clarify any questions and make sure to provide sources for your answers:
1.	Write a very short product description.
2.	The product assessed based on the information found so far might have an overall rating of GOOD | CONCERNS| BAD, highlight previous assessments (for example Act as Data Assessment) and bullet point in detail.
3.	Concerns with release cycle goes here <if applicable>
4.	It should be considered whether the vendor's security assessment, as defined in the Hardened Assessment section, is sufficient. <add if true; or>
5.	It is recommended that this software is assessed against the independent security benchmarks available as defined in the Hardened Assessment section. <either one?>
6.	It should also be considered as part of the follow on risk assessment… <add any other concerns>
```
