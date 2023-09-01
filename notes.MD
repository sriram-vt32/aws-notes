# AWS notes

## 29th august

The delivery of cloud type computer services is cloud computing.
**Benefits:**
-	Reduce costs.
-	Global scale
-	Performance
-	Security
-	Speed
-	Productivity
-	Reliability (disaster recovery)

Who the users for cloud computing:
•	Organizations (all types)
There are 4 cloud deployment types.
•	Public cloud
•	Private cloud
•	Hybrid cloud
•	Community cloud
Public cloud: 
•	Any1 can access.
•	Most of org use public cloud along with security policies.
Adv
•	Low cost
•	Service providers manage all the infrastructure
•	Reduced wait times
•	Enough space provided.
Disadv
•	The data breach security risk
•	Network performance
•	Lack of customization because its predefined

Private cloud
•	It’s used to avoid data breach risks.
Adv
•	Customization
•	Data security is very high and controlled along with ownership.
•	Legacy systems (features to integrate or support legacy applications)
Disadv
•	High costs
•	Limited scalability

Community cloud
•	It’s almost like a private cloud
•	For a set of users
•	Eg for community cloud: salesforce

Adv 
•	Cost benefits
•	Its user acc based.
•	Data sharing and collab
disadv
•	Limited storage and bandwidth
Hybrid cloud
2 or more cloud combinations
Public cloud to data side for most scenarios
Financial org use these
Advs:
•	Flexibility and control
•	Cost benefits
•	Agility 
Disadv
•	Maintenance and challenging integrations
Cloud computing models
•	Infra as a service (everything done from scratch)
•	Platform as a service
•	Software as a service
Cloud share responsibility model
shared responsibility defines the security of this model.
paas responsibilities are less.
iaas responsibilities are more.
sas services responsibilities are minimal.

interview q/a
How do we select cloud service?
Ans: select cloud service provider.
* Consider business and process
* Check if there is Administration support
* Look up the technical capabilities and its process
* Then we look its security aspects
Pricing models
•	pay as u go.
•	On demand
•	Spot instance

31st august
 Aws acc and organizations
•	Aws or any cloud service provider  gives some free tier acc ( $300 aws free tier)
•	Have 3 accounts : Management acc, dev acc and prod acc
Landing zone
This allows us to quickly set up a cloud env by automation with best config along with security.
•	Its scalable
•	Multi acc management is easy.
•	Helps us in keeping things organized.
Benefits:
•	Improved security control
•	Central user management
•	Data isolation to prevent data breaches in multiple environments.
•	Better visibility in services and control aspects
•	We can set limitations.
•	It adapts well architecture and can quickly deploy new applications.
How do we create a landing zone:
•	Service based landing zone: aws control tower , a gui tool with predefined scripts used to create a landing zone.
•	IAC (cloud formation )
•	Third party IAC tool : terraform. 

AWS well arch and the 6 pillars
•	Aws well architected  calls for key concepts, principles  and practices for running in cloud
Six Pillars:
•	Operational excellency
o	 We use this to manage cicd.
o	We perform operations as code,
o	 We need to anticipate failure and refines the operations procedures frequently .
o	Learn from failures.
•	Security
o	to protect data and cloud. 
o	IAM 
o	Tracing (in vpc we have CloudTrail)
o	Tight security and automated is always preferred.
o	 Data needs to be always protected even when in rest or transit.
o	Give access to authorized ppl only. 
o	Prepare for any security threats.
•	Reliability
o	Focus on workload performance(utilization included).
o	 
o	
•	Performance efficiency 
•	Cost optimizations 
•	sustainability
AWS lenses provide suggestions for architecture based on data collected.
AWS has their own CDN(cloud delivery network) CloudFront. 







