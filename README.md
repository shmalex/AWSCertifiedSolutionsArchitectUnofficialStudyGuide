> AWS Learning Links Series
- Informal AWS Certified Solutions Architect - Associate Exam Guide http://bit.ly/saaguide
- Informal AWS Certified Solutions Architect - Professional Exam Guide http://bit.ly/sapcertguide
- Unofficial AWS Certified Developer - Associate Exam Guide http://bit.ly/devcertguide
- Collection of AWS security related contents http://bit.ly/seccontents

# Informal AWS Certified Solutions Architect - Associate (February 2018) Admissions Guide (bit.ly/saaguide)

> This document is based on the contents of AWS Certified Solutions Architect Associate Certification (SAA) Examination Guide, and is based on the Korean language materials on AWS's homepage, blog, and Slideshare related links.

> Short URL: http://bit.ly/saaguide

## Basic exam information
- [Exam Guide] (https://d1.awsstatic.com/training-and-certification/docs-sa-assoc/AWS%20Certified%20Solutions%20Architect%20-%20Associate_Exam%20Guide_v1.5b_FINALKO.pdf): Many people You do not read this properly, but it is a very important document to prepare for the exam, so you should read it carefully. This document is based on this examination guide.
- [Test page] (https://aws.amazon.com/certification/certified-solutions-architect-associate/)
- [Application for Exam] (https://www.webassessor.com/wa.do?page=publicHome&branding=AMAZON)
- [AWS-based architecture design] (https://aws.amazon.com/en/training/course-descriptions/architect/): This is a three-day lecture and hands-on lesson, It becomes the scope of examination of the architect qualification examination.
- [Attend trial workshop] (https://www.aws.training/home?courseid=10&&language=en-US&view=table&source=web_en_certified-sa-assoc)
- [Sample question (new)] (https://d1.awsstatic.com/training-and-certification/docs-sa-assoc/AWS_Certified_Solutions%20Architect_Associate_Feb_2018_Sample%20Questions_v1.0.pdf): English and 10 questions are provided.
- [Sample Question (s)] (https://d0.awsstatic.com/International/en_US/AWS_certified_solutions_architect_associate_examsample_en.pdf): 8 sample questions. It is a good reference for the new type examination.
- [How to request additional English test time] (http://edu.supertrack.co.kr/community/news.php?ptype=view&idx=5177&page=1&code=news): If you take the test in English, You can add. **caution! You must apply for additional exam time before you apply for the exam **!

Test preparation tips
 
- First, the test itself does not grow. If you look at the link house, you have a lot of scope. The problem is focused on understanding and using services rather than simple memorizing expressions.
- Exam coverage is consistent with [AWS-based architecture design lessons] (https://aws.amazon.com/ko/training/course-descriptions/architect/), so taking lessons is a great way to prepare for exams.
- It is recommended that you read the documents listed here in the order of AWS Overview -> White Paper -> Each Service FAQ -> Best Practices.
- The exam will solve 70 questions in 130 minutes. Time management is very important because you have to solve many problems in a short time.
- Most of the exams are in the FAQ document of the service. You must read the documentation thoroughly and identify best practices.
- If you are confident in English, you can apply for an extension of the examination time and take an examination in English.
- Free sample questions and $ 20 paid test exams. Because the actual exam score and sink rate are high, examinations with a feeling of mock exam are very helpful for preparing for the exam.

# AWS Official Documents for Exam Scope

### all
- [AWS Korean Manuals List] (https://aws.amazon.com/en/blogs/en-documentation/)
- [AWS white paper] (https://aws.amazon.com/whitepapers/)
  - [Overview of Amazon Web Services] (https://d1.awsstatic.com/International/en_US/whitepapers/aws-overview.pdf)
  - [Architecting for the Cloud] (https://d1.awsstatic.com/whitepapers/AWS_Cloud_Best_Practices.pdf)
  - [AWS Security Best Practices] (https://d1.awsstatic.com/whitepapers/Security/AWS_Security_Best_Practices.pdf)
  - [AWS Storage Services Overview] (https://d1.awsstatic.com/whitepapers/Storage/AWS%20Storage%20Services%20Whitepaper-v9.pdf)
  - [AWS Well-Architected Framework] (https://d1.awsstatic.com/International/en_US/whitepapers/Well-Architected%20Framework%20Whitepaper.pdf)
  - [Architectural Design for the Cloud: AWS Best Practices] (https://d1.awsstatic.com/whitepapers/AWS_Cloud_Best_Practices.pdf)
  - [Serverless Architecture with AWS Lambda] (https://d1.awsstatic.com/whitepapers/serverless-architectures-with-aws-lambda.pdf)
- [AWS Architecture Center] (https://aws.amazon.com/architecture/)


### Zone 1: Resilient architecture design
- Understanding the AWS Global Infrastructure
  - [AWS Global Infrastructure] (https://aws.amazon.com/about-aws/global-infrastructure/)
  - [EC2 Region and Availability Zone Selection] (http://docs.aws.amazon.com/en_US/AWSEC2/latest/UserGuide/using-regions-availability-zones.html)
  - [Amazon CloudFront Global Edge Network] (https://aws.amazon.com/cloudfront/details/)
- How to design a cloud service
  - [AWS Advanced Architecture Methodology] (http://www.slideshare.net/awskorea/aws-cloud-track-2-advanced)
  - [Implementation of AWS-based micro-service architecture] (http://www.slideshare.net/awskorea/micro-service-oriented-architecture-on-aws-piljoong-kim)
- Services to implement loose coupling
  - [ELB FAQ] (https://aws.amazon.com/en/elasticloadbalancing/faqs/)
  - [SQS FAQ] (https://aws.amazon.com/sqs/faqs/)
- Planning and design
  - [Architectural Design for the Cloud - Best Practices] (https://enz.kr/pdf/Architecture_Best_Practices_draft-EN.pdf)
  - [AWS Customer Case Studies] (https://www.awsseoul.in/images/content/aws-korea-customer-cases-2016.pdf)
- Choose stable, resilient storage
  - [EC2 Storage] (https://docs.aws.amazon.com/en_US/AWSEC2/latest/UserGuide/Storage.html)
  - [EC2 Instance Store] (https://docs.aws.amazon.com/en_US/AWSEC2/latest/UserGuide/InstanceStorage.html)
  - [EBS FAQ] (https://aws.amazon.com/en/ebs/faqs/)
  - [EFS FAQ] (https://aws.amazon.com/en/efs/faq/)
  - [S3 FAQ] (https://aws.amazon.com/s3/faqs/)
  - [Galcier FAQ] (https://aws.amazon.com/ko/glacier/faqs/)
  - [Storage Gateway FAQ] (https://aws.amazon.com/storagegateway/faqs/)

- Best practices
  - [EC2 Best Practices] (http://docs.aws.amazon.com/en_US/AWSEC2/latest/UserGuide/ec2-best-practices.html)
  - [RDS Best Practices] (http://docs.aws.amazon.com/en_US/AmazonRDS/latest/UserGuide/CHAP_BestPractices.html)
- Develop client specifications, including price / cost (eg on demand versus reservations vs. spot, RT-
