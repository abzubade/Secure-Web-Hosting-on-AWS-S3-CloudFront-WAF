# Secure-Web-Hosting-on-AWS-S3-CloudFront-WAF
This project demonstrates how to build a secure, serverless website on AWS for a restaurant using Amazon S3, CloudFront, and AWS WAF, focusing on global performance, access control, and protection against common web threats like SQL injection, XSS, and DDoS attacks.

---

### 🗺️ **Scenario Overview**  
A fast-growing restaurant, wants to launch its online website to showcase menus, offers, and customer reviews. The business needs the site to be **globally accessible, fast, and most importantly secure** from cyber threats like SQL injection (SQLi), cross-site scripting (XSS), and DDoS attacks.

---

### ✅💡 **Solution**  
A serverless and secure website hosted on Amazon S3, delivered globally using Amazon CloudFront, and protected by AWS WAF. To ensure best practices, we’ll enforce Origin Access Control (OAC) to restrict direct S3 access, apply least-privilege IAM policies, and use CloudWatch for monitoring and logging.

---

### 🪜 Steps to Be Performed
1. Creating and configuring an **S3 bucket** for website hosting
2. Securing the bucket using **Origin Access Control (OAC)**
3. Setting up a **CloudFront distribution** with HTTPS enforced
4. Attaching **AWS WAF** for web application security
5. Enabling **CloudWatch/CloudTrail** for monitoring and compliance
---

### 🧰 Services Used
<li> Amazon S3 → Store and serve static website files (HTML, CSS, images) </li>
<li> Amazon CloudFront → Distribute content globally with low latency and HTTPS</li>
<li> AWS WAF → Protect against SQLi, XSS, bots, and malicious requests</li>
<li> AWS IAM → Manage least-privilege permissions for access control</li>
<li> Amazon CloudWatch & CloudTrail → Monitor logs, track user actions, and detect anomalies </li>

### Architectural Diagram### 
