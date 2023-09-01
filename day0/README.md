# Simple design 
Design environment => Docker Image => Docker registry => (Default VPC) EC2 Environment 

![Alt text](simpledesign.svg)

## Pros
1)	Deployment is simple.
2)	Suitable for vanilla use cases not advisable for mission critical designs.
## Cons
1)	Vulnerable to malicious attacks.
2)	Single point failure if EC2 machine gets down.
3)	Recovery time will be higher.
## Conclusion
Only to be opt for testing purpose.
