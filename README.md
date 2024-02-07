<h1> Lesson 1.3: Authentication, Authorization, and Accounting (AAA)   </h1>
<h2> Summary</h2>

<p1>By the end of this lesson, students should be able to define and understand the concepts of authentication, authorization, and accounting and their significance in cybersecurity.</p1>
<br>

<h2>Learning Objectives</h2>
<ul>
<li>Compare and contrast identity and access management concepts.</li>
  <br>
<li>Understanding Trust.</li>
  
</ul>

<h2>Vocabulary and Acronyms</h2>

<ul>
<li>

  **AAA Framework**</li>
  
<li>

**SSO**</li>
  
<li>
  
**Authentication**</li>

<li>

**Accounting**</li>

<li>
	
**Authorization**</li>

<li>
	
**2FA**</li>
  
</ul>



<h2>Lesson Prerequisites</h2>
<p1>Previous experience with or understanding of cybersecurity is optional. We assume basic familiarity with computing and technology. </p1>
<br>


<h2>Introduction</h2>
<p1>The digital world is teeming with data, and with that comes the necessity to secure it. A significant security aspect is ensuring that only the right people can access the right resources. But how is this accomplished? Through three primary security fundamentals: Authentication, Authorization, and Accounting, often abbreviated as AAA.</p1>



<h2>Authentication</h2>

<ins>Definition</ins>: Authentication is verifying the identity of a user, system, or application trying to access a resource.

<h4>Examples</h4>
<ul>
	<li><ins>Usernames and Passwords</ins>: The most common form of authentication. When you log into a system, your username identifies who you are, and your password validates that you are that person.</li><br>
	<li><ins>Biometrics</ins>: Using physical characteristics like fingerprints, retina scans, or voice recognition.</li><br>
	<li><ins>Token-based authentication</ins>: To prove identity using a physical device, such as a smart card or security token.</li><br>
	<li><ins>Multifactor authentication (MFA)</ins>: Combines two or more forms of authentication for added security.</li>
</ul>

<ins>Importance:</ins> Without proper authentication, anyone can claim to be anyone else, leading to potential breaches, data theft, and other malicious activities.


<h2>Authorization</h2>

<ins>Definition:</ins> Once authenticated, authorization is the process that determines what the user, system, or application is allowed to do.

<h4>Examples</h4>
<ul>
	<li><ins>Access Control Lists (ACLs):</ins> Specify which users or systems are granted or denied access to particular resources.</li><br>
	<li><ins>Role-based Access Control (RBAC)</ins>: Users are given roles that define what actions they can perform or what data they can access.</li><br>
	<li><ins>File Permissions</ins>: In an operating system, you can read a file but not modify or delete it.</li>
	
</ul>

<ins>Importance:</ins>Authorization ensures that authenticated entities only access what they are supposed to, protecting data and resources from unauthorized access or manipulation.



<h2>Accounting</h2>

<ins>Definition:</ins> Accounting involves tracking and recording what the authenticated and authorized user does during their session. It's the process of keeping a log of all activities.

<h4>Examples</h4>
<ul>
	<li><ins>Network Logs</ins>: Records of which user accessed which resources, at what time, and for how long.</li><br>
	<li><ins>Billing Systems</ins>: In cloud services, accounting might track resource usage to bill customers accurately.</li><br>
	<li><ins>Audit Trails</ins>: Detailed records that can be analyzed later to understand user behavior or trace back in case of a security incident.</li>
	
</ul>

<ins>Importance:</ins> Accounting provides an audit trail that can be crucial for understanding user behavior, troubleshooting issues, or investigating a security breach.


<h2>Network Equipment and Services Protection</h2>
As we protect our data and applications, we must safeguard our network equipment and services. Network intruders often target routers, switches, and other devices. By employing AAA principles at the network level, we ensure only authorized personnel can make changes, monitor network activity, and access critical resources.


<h2>Varying Levels of Security</h2>
While the AAA framework provides a solid foundation, different situations may require different levels of security. Some environments require additional layers of protection, like MFA, while others might just need a simple username and password. It's crucial to assess the security needs of each scenario and apply the appropriate combination of AAA technologies.

<h2>Conculsion</h2>

To achieve absolute security, it's essential to implement Authentication, Authorization, and Accounting properly. By understanding and applying these three pillars, we can ensure that our digital systems, resources, and data remain secure, accessible only by those with the correct permissions, and continuously monitored for suspicious activity.

		 


<h2> Presentation</h2>

<a href="https://docs.google.com/presentation/d/1QsJje-K_u9yx7W-gz3QwT9eCaFgcl2p2/edit?usp=sharing&ouid=110228847857413878764&rtpof=true&sd=true"> AAA and Authentication</a>


<h2> Hands-On Labs</h2>



<h2> Additional Resources</h2>

<a href="https://howsecureismypassword.net/"> Password Minder </a> - Password Minder Infomercial featured on Ellen. <br>

<a href ="https://www.professormesser.com/security-plus/sy0-501/aaa-and-authentication/">Professor Messer’s AAA and Authentication </a> - Lecture: AAA and Authentication. <br>

<a href="https://www.professormesser.com/security-plus/sy0-501/identity-and-access-services/"> Professor Messer’s Identity and Access Services</a> - Discuss examples of Something You Are, Something You Have, Something You Know.
