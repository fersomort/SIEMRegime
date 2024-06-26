<h1> Sprint 1</h1>

<h2>SIEM REGIME CAPSTONE PROJECT</h2>

<h4>Plan of Action Milestone:</h4>

<h5>Project Goals:</h5>
<li>What makes a good SOC</li>
<li>What tools are available</li>
<li>Architecture overview</li>
<li>Deployment strategy</li>

<h5>Project Scope:</h5>
<li> Log Ingestion</li>
<li>Log Analysis</li>
<li>Backend Storage</li>
<li>Visualization</li>
<li>Intelligence Enrichment</li>
<li>Case Management</li>
<li>Automate Automate Automate</li>
<li>Investigate</li>
<li>Health Monitoring</li>

<h5>AWS Cloud Tools</h5>
<li>Route 53</li>
<li>Aws Shield</li>
<li>Web Application Firewall (WAF)</li>
<li>CLOUDFRONT</li>
<li>ELASTIC LOAD BALANCER</li>
<li>S3 BUCKET (For EC2 & DB)</li>
<li>CLOUDWATCH</li>
<li>SNS (Simple Notification Service)</li>
<li>AWS GuardDuty</li>
<li>EC2 instances) and DNS logs</li>
<li>RDS (Relational Database Service)</li>

<h5>Plan of Action Milestone:</h5>
<p>Design and Implementation of a Cloud-based SIEM <br>
Team: Emmanuel, Fernanda, Shantericka, Greta
Team Lead: Emmanuel
Project Manager: Shantericka
</p>

<h5>Project Goals:</h5>
<p>This project is to design and implement a cloud-based SIEM <br>
Our goals are: <br>
</p>

<li>What makes a good SOC</li>
<li>What tools are available</li>
<li>Architecture overview</li>
<li>Deployment strategy</li>

<h5>Project Scope:</h5>

<ul>Log Ingestion
  <li>Collect logs ongoing on endpoint devices and network devices</li>
  <li>Normalize log fields to a universal name so that faster searching and better visualization can be built</li>
  <li>Ensure caching of logs if backend storage is busy or offline</li>
</ul>

<ul>Log Analysis
  <li>Analyze logs received from endpoints/services</li>
  <li>Determine the severity of the logs ingested via log analysis. Supported ability for custom rules.</li>
  <li>Ability to discard noisy alerts to limit overflow of unnecessary data.</li>
</ul>

<ul>Backend Storage
  <li>Store received logs for periods of time.</li>
  <li>Fast searching and viewing of data.</li>
  <li>Ability to provide access control to stored logs.</li>
</ul>

<ul>Visualization
  <li>Ability to view logs via widgets/dashboards/etc.</li>
  <li>Fast searching and viewing of data.</li>
  <li>Support the ability to read from multiple log storages.</li>
</ul>

<ul>Intelligence Enrichment
  <li>Enrich your received log with threat intelligence gathered from various providers.</li>
  <li>Ability to parse and store selected responses so that only crucial data is stored.</li>
  <li>Automated so that your SOC analysts are not having to manually attempt to enrich received logs.</li>
</ul>

<ul>Case Management
  <li>Platform to view and react to HIGH severity events.</li>
  <li> Allow collaboration with multiple SOC analysis.</li>
  <li>Allow responsive actions so that analysis can trigger events on their endpoints.</li>
</ul>

<ul>Automate Automate Automate
  <li>SOAR platform.</li>
  <li> Ability to automate workflows in response to critical alerts, failed health checks, or ticket analysis.</li>
  <li>Fully customizable and fast.</li>
</ul>

<ul>Investigate
  <li>Incident Response</li>
  <li>Quarantine a device</li>
  <li>Ability to remotely collect endpoint forensics.</li>
</ul>

<ul>Health Monitoring
 <li>Monitor resources consumed on endpoints.</li>
 <li>Monitor services/processes whose stoppage would cause operational impact</li>
 <li>Ability to alert in real-time when health check thresholds are met.</li>
</ul>

<ul>Target Audience
 <li>For mid-sized businesses and enterprises with limited IT resources, a Cloud-based SIEM provides adequate security capabilities with manageable and cost-effective solutions</li>
 <li>Managed Security Service Providers leverage cloud-based SIEM to manage and monitor services for clients</li>
 <li>Due to organizations working remotely from various locations, they tend to focus more on availability and lack of securing their devices. Cloud-based SIEM provides flexibility and scalability solutions.</li>
 <li>The compliance feature on the Cloud-based SIEM regulates and benefits industries like finance, healthcare, and government institutions.</li>
 <li>In summary, cloud-based SIEM, provides scalability, cost-effectiveness, readily deployable security monitoring, and threat detection.</li>
</ul>

<h5>Success Metrics:</h5>
<p>Organizations use these measures for the effectiveness of their Cloud-based SIEM Implementation. </p>
<li>Threat detection and response: An effective SIEM provides a faster detection and response time to security incidents</li>
<li>Reduction in security incidents: Cloud-based SIEM measures the reduction in incidents.</li>
<li>Track the number of security incidents before and after.</li>
<li>Incident response effectiveness: Track the metrics of mean time to respond (MTTR) and mean time to resolve (MTTR) by measuring the effectiveness of the incident response process.</li>
<li>Compliance adherence: Compare the organization’s compliance to industry regulation, then track the number of compliance violations and actions taken.</li>
<li>User satisfaction: User satisfaction is measured through surveys to ensure cloud-based SIEM meets organization’s needs and expectations.</li>
<li>Cost-effectiveness: Measure cost savings achieved by the organization by comparing cloud-based Siem to on-premises solutions.</li>
<li>Scalability and flexibility: Consider the ability of a cloud-based SIEM to scale with organization’s needs, and then adapt to changing security requirements.</li>

<p>
  These Success metrics allow organizations to evaluate the effectiveness of their cloud-based SIEM implementation, and then make informed decisions to improve their security posture.
</p>

<h2>CLOUD-BASED SIEM</h2>
<p>
  Automation reduces alert fatigue and faster incident response.
</p>

<h2>AWS CLOUD-BASED SIEM TOPOLOGY</h2>

![Screenshot_26-6-2024_154152_](https://github.com/fersomort/SIEMRegime/assets/111290379/96565b88-b8ec-42ad-8e8b-9b717344f77c)

<h4>AWS Cloud Tools and Their Functions:</h4>

<p><b>Route 53</b>  is the domain name system (DNS) web service provided by Amazon Web Services that is used for routing internet traffic to various resources; such as web servers, applications, and
other services. It is integrated with a SIEM to enhance security and monitoring capabilities for your organization's DNS infrastructure. The steps for implementing Route 53 on a SIEM are as follows: 

<ol>
  <li>Identify your organization’s DNS infrastructure</li>
  <li>Configure Route 53 for DNS logging to capture information about domain name resolution requests made within the organization.</li>
  <li>Setup alerts and notifications in the SIEM system for any suspicious activity</li>
  <li>Monitor DNS traffic by using the logs to look for patterns and trends that may indicate a security threat or issue.</li>
  <li>Integrate with other security tools such as intrusion detection systems (IDS) or threat intelligence platforms.</li>
  <li>Implement best security practices such as enabling encryption for proper access control.</li>
</ol>

The overall use of Route 53 is to protect against potential threats and incidents.</p>

<p><b>AWS Shield:</b> Inspects on-coming traffic to AWS services and applies a combination of traffic signatures. It protects against both known and emerging DDoS attacks and provides always-on detection and automatic in-line mitigation that minimize application downtime and litany, so can continue to operate during downtime. 

Benefits of AWS Shield:
<li>Traffic monitoring: AWS Shield inspects incoming traffic to your network and applies a combination of traffic signatures, anomaly algorithms, and other analysis techniques to detect malicious traffic. It sets some static thresholds for each of your resource types.</li>
<li>Web Application Firewall (WAF) is a SIEM system that enhances the security posture of an organization's web applications. WAF helps protect web applications from security threats such as SQL injections, cross-site scripting, and other vulnerabilities by filtering and monitoring HTTP traffic between web applications and the internet.</li>
<li>CLOUDFRONT: It provides high security with the “Content privacy “ feature. It facilitates GEO targeting service for content to specific end-users. HTTP and HTTPS protocols are used for faster delivery of content. It only charges for data transfer, hence its cost-effectiveness.</li>
<li>ELASTIC LOAD BALANCER: This feature distributes incoming traffic across numerous instances, ensuring that when one instance is down or overwhelmed with traffic, it directs traffic to the next AZ, while the primary instance is repaired to start back up. This increases your application’s availability and fault tolerance. ELB scales horizontally by automatically scaling the number of instances handling incoming traffic in response to demand. As traffic grows ELB spreads traffic to more instances.</li>
<li>S3 BUCKET (For EC2 & DB): S3 provides 99.99999 percent durability, data is tied in range of “storage classes” these classes are based on frequency and immediacy you require in accessing files, hence its low cost. For scalability, S3 charges for resources you only use. Availability is 99.9%. The flexibility of S3 is ideal for data storage, data backup, software delivery, data archiving, disaster recovery, website hosting, mobile applications, IoT devices, and much more. Most importantly for security, S3 offers an impressive range of access management tools and encryption features. You don’t have to be an IT genius to execute data transfer. The service revolves around simplicity and ease of use.</li>
<li>CLOUDWATCH: Enables you to monitor your complete stack ( applications, infrastructure, network, and services) and use alarms, logs, and event data to take automated actions and reduce mean time to resolution (MTTR). The metrics feature allows you to ensure primal performance and efficient resources utilization. This provides invaluable insights into the operation of AWS services, enabling real-time tracking of system health performance and usage patterns.</li>
<li>SNS (Simple Notification Service): This feature attached to Cloudwatch sends push notification via email or SMS when servers are down or compromised,</li>
<li>AWS GuardDuty: This service continually monitors your AWS accounts and workloads for malicious activity and delivers detailed security findings for visibility and remediation. It processes fundamental data sources, such as AWS cloudtrail management events, cloudtrail event logs, VPC flow logs (from EC2 instances), and DNS logs.</li>
<li>RDS (Relational Database Service): Managed SQL database which allows you to encrypt your database and also data at rest, using keys from AWS KMS (Key Management Service), as are its automated backups, read replicas, and snapshots.</li>


<a href="[url](https://trello.com/b/bheFPgYo/siem-re)"><h4>10 weeks sprint on Trello:</h4></a>

![Screenshot 2024-06-26 181449](https://github.com/fersomort/SIEMRegime/assets/111290379/1fd38dfc-ba56-4af6-ae0a-128a764f36ba)


