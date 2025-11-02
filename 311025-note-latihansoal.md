# latihan soal aws restart 311025

# AWS skill builder trivia - mock exam ccp

#### 1. Which IAM entity can be used for assigning permissions to AWS services?
- [x] IAM role ✅



[Image of AWS IAM Role architecture diagram]


#### 2. After an organization has migrated several servers into AWS, they are unsure as to what they must directly manage themselves. Which cost is the company's direct responsibility?
- [x] Cost of application software licenses ✅

#### 3. An organization is considering implementing a new workload in the AWS Cloud. However, the company first wants to forecast costs. Which tool should the company use to estimate the cost of the workload?
- [x] AWS Pricing Calculator ✅

#### 4. Which of the following are advantages of the AWS Cloud? (Select TWO)
- [x] Users can stop guessing about resource capacity ✅
- [x] Users can stop spending money on the maintenance of data centers ✅

#### 5. A user needs a quick way to determine if any Amazon EC2 instances have ports that allow unrestricted access. Which AWS service will support this requirement?
- [x] AWS Trusted Advisor ✅

#### 6. Which of the following are advantages of the AWS Cloud? (Select TWO)
- [x] Launch globally in minutes ✅
- [x] High economies of scale ✅

#### 7. What AWS service decouples application components so that they can run independently ?
- [x] Amazon Simple Queue Service (Amazon SQS) ✅



> Amazon Simple Queue Service (Amazon SQS) = message broker 
> Amazon Simple Notification Service (Amazon SNS) = mirip 
> Amazon Simple Workflow Service (Amazon SWF) = udah ga ada 
> AWS Glue
> 
> AWS CloudWatch Logs => buat mantau/monitor resource aws
> 
> AWS cloudtrail => buat mantau jejak activity user ketika memakai semua service aws

#### 8. Which authentication method is used to authenticate programmatic calls to AWS services?
- [x] Access keys ✅
- [ ] Server certificate
- [ ] Key pair
- [ ] Console password 

> note: 
> kalo ada programmatic calls, itu dipake di CLI dan SDK 

#### 9. Which AWS service provides a cloud-based integrated development environment (IDE) that lets you write, run, and debug your code with just a browser, without needing to install any software or configure servers ?
- [x] AWS Cloud9 ✅
- [ ] Amazon WorkSpaces
- [ ] AWS CodeStar
- [ ] AWS CodeBuild

> AWS CodeBuild(buat CI doang)

#### 10. An IT company has deployed its infrastructure on the AWS cloud. There must be a database that supports reads with a latency of under a millisecond for critical applications. Which AWS service will meet this requirement?
- [ ] Amazon RDS
- [ ] AWS Glue
- [x] Amazon ElastiCache ✅
- [ ] Amazon EMR

> note: 
> amazon emr itu pake framework etl, hadop, spark. mirip aws glur juga. karena ada kata kunci "supports reads with a latency of under a millisecond", artinya butuh cepet bgt. Database biasa itu ga cepet bgt. jadi perlu amazon elasticache butuh yg cepet bgt

#### 11. Which AWS service supports an in-memory data structure store, compatible with Redis, that delivers sub-millisecond latency for use cases such as caching, session stores, and real-time analytics?
- [ ] Amazon RDS
- [ ] Amazon DynamoDB
- [ ] Amazon Redshift
- [x] Amazon MemoryDB ✅

> note: 
> dalam bentuk memori keyword "in-memory data structure store, compatible with Redis", redis itu termasuk db yg nyimpennya di ram. Redis itu sering dipake di devops. amazon RDS buat SQL only. amazon DynamoDB buat NoSQL. amazon redshift buat data warehouse. jadi yg bener amazon memoridb 

#### 12. Which Amazon EC2 pricing model is the most cost-effective for an always-up, right-sized database server running a project that will last 1 year?
- [ ] On-Demand Instances
- [ ] Spot Instances
- [x] Standard Reserved Instances ✅
- [ ] Convertible Reserved Instances



> note:
> pelajari lagi modul aws elastic: compute 
> 
> kalo pake Standard Reserver Instances
> "right-sized"=ukuran klop/fix, atau ga diubah
> "server running a project that will last 1 year?"=buat setahun, artinya buat jangka panjang  
> diskon jg lebih besar
> 
> kalo pake Convertible Reserved Instances, kayak misal kita butuh server perlu diubah2, diskon lebih kecil, 
> 
> kalo pake On Demand Instance:
> buat short term, misal pake 1,2,3 jam 
> 
> kalo pake Spot Instance:
> ini mirip ngelelang/ngejual rugi service AWS ke user lain. Analoginya, Misal kita nyewa 5 kamar kos ke ibu kos selama 1 tahun. misal 1 tahun 1 kamar = 1juta, berarti 1 tahun 5 kamar = 5 juta. Nah misal kita nyewain kamar itu ke 5 orang, trus ada masalah, 1 orang di bulan 8 itu keluar dan ga nyewa kamar ke kita. Nah kan rugi tu kita. Nah, kita ngjualin ke orang lain dengan harga jual rugi 800rb aja. Daripada rugi 1 juta mending rugi 200 ribu aja.Artinya Spot Instance ini service buat ngejual rugi service AWS kita ke user lain 

#### 13. How can an organization track resource inventory and configuration history for the purpose of security and regulatory compliance ?
- [ ] Implement Amazon GuardDuty
- [x] Configure AWS Config with the resource types ✅
- [ ] Create an Amazon CloudTrail trail
- [ ] Run a report with AWS Artifact

> note: 
> Amazon CloudTrail itu lebih ke ngetrack activity.

#### 14. How does the AWS global infrastructure offer high availability and fault tolerance to customers?
- [ ] AWS allows users to choose AWS Regions and data centers so that users can select the closest data centers in different Regions
- [x] The AWS infrastructure consists of isolated AWS Regions with independent Availability Zones that are connected with low-latency networking and redundant power supplies ✅
- [ ] The AWS infrastructure is made up of multiple AWS Regions within various Availability Zones located in areas that have low flood risk and are interconnected with low-latency networks and redundant power supplies
- [ ] The AWS infrastructure consists of subnets containing various Availability Zones with multiple data centers located in the same geographic location



#### 15. A company has a mission critical Linux-based application. The application must run every Monday from 6 AM until 10pm. As the application is critical, it cannot be interrupted. Which Amazon EC2 instance purchasing option meets these requirements MOST cost-effectively?
- [ ] Spot Instances
- [ ] Dedicated Hosts
- [ ] Regional Reserved Instances
- [x] On-Demand Capacity Reservation with Savings Plan ✅

> note: 
> Regional Reserved Instances = ini buat 24 jam

#### 16. An organization moves a workload to Amazon EC2 instances on AWS. Cost-effectiveness is the key to running the workload properly in the Cloud. What can the company do to meet this requirement?
- [ ] Use AWS CloudFormation to deploy the infrastructure
- [ ] Use multiple AWS accounts and consolidated billing
- [x] Rightsize all the EC2 instances that are used in the deployment ✅
- [ ] Use AWS Key Management Service (AWS KMS)

> note: 
> AWS cloudformation = buat automation, ini bikin mahal
> AWS Key Management Service (AWS KMS) = ini buat encript





