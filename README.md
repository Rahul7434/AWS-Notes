# AWS
### What Is AWS Cloud?
```
AWS (Amazon Web Services) is a cloud computing platform
AWS (Amazon Web Services) is like a powerful toolbox on the internet.
Companies use it to build websites, store data, run apps, and much more—without needing physical servers.

### Client-Server Model
Imagine you’re using a banking app on your smartphone:
You (Client): Open the app to check your balance, transfer money, or pay bills.
Bank’s Server (Server): Stores all the data, processes your requests, keeps your account info secure.
Every time you tap a button, your phone sends a request to the bank’s central server. That server does the work (like checking your balance) and sends the result back to your app. 🏦📲

🕸️ In Cloud Computing
Now, imagine that server isn’t in one physical bank location—it’s in the cloud, managed by platforms like AWS:
The cloud makes it scalable (can serve millions of users).
It’s available 24/7, backed by data centers worldwide.
Easy to update and secure.
💡 Key Insight
One server, many clients. You don’t need your own server at home. You simply connect and use the service—fast, secure, and convenient.
```

----------------------------------------------------------------------------------------------------------------------------------------------------------

🌐 What Is Cloud Computing?
```
Think of cloud computing like ordering food from a restaurant instead of cooking at home:
You don't need a kitchen (servers).
You just order what you need, and the restaurant (cloud provider) delivers it.
You pay only for what you eat — not for the whole kitchen setup.

💻 In Tech Terms
Cloud computing means:
You use computing power, storage, apps, etc. over the internet.
No need to buy expensive hardware or install software manually.
Services come from big cloud providers like AWS, Microsoft Azure, or Google Cloud.

💰 Pay-as-You-Go = Smart Spending
Instead of buying a full server that may sit unused:
You pay only when you run something.
No hidden costs. No overpaying.
Super helpful for startups and businesses that want flexibility.

✨ Real-Life Examples
Watching Netflix? The videos stream from the cloud.
Uploading pics to Google Photos? That’s cloud storage.
Using Gmail or Outlook? Your emails live in the cloud.
```

------------------------------------------------------------------------------------------------------------------------------------------------------------

### Deployment Models 
```
There are three different kinds of deployment 
models: 
1. Cloud-based 
2. On-premises 
3. Hybrid
☁️ Cloud-Based Deployment
Services are hosted entirely on the cloud.
You access everything via the internet.
No need to buy or manage your own physical hardware.
Real-life example: A startup hosts its website on AWS, stores files in Google Drive, and uses Salesforce CRM — all cloud-based.

🖥️ On-Premises Deployment
Everything runs on servers located within your organization.

You buy and maintain your own hardware and infrastructure.

Offers complete control, but requires more effort and cost.

Real-life example: A hospital stores patient data on its internal servers to follow strict privacy rules and regulations.

🔄 Hybrid Deployment
Mix of cloud + on-premises.

Critical data stays in-house, while less-sensitive tasks run on the cloud.

Offers flexibility and balance.

Real-life example: A bank keeps customer transaction records on-site but uses the cloud for mobile banking apps and email services.
```
---------------------------------------------------------------------------------------------------------------------------------------------
### AWS Cloud Benefits
```
There are many reasons for going with the cloud.
Cloud computing enables benefits such as:

1.Cost savings
2.Security
3.Scalability
4.Flexibility

Why Choose Cloud Computing?

Benefit              : How It Helps You
---------------------:----------------------------------------------------------
Cost Savings         : No need to invest in expensive data centers or servers.
                       Pay only for what you use.

Security             : Major cloud providers offer built-in security tools,
                       monitoring, and compliance.

Scalability          : Start small and grow effortlessly—scale up or down
                       based on demand.

Flexibility          : Work from anywhere. Use resources when needed.
                       Supports remote teams and apps.

Payment Model        : Pay-as-you-go approach: only pay when you're using
                       services. Budget-friendly.

Fewer Operations     : Less time managing hardware—focus on what matters:
                       innovation and customers.

Flexible Capacity    : Avoid under- or over-utilization. Cloud adjusts
                       resources automatically as needed.
```
--------------------------------------------------------------------------------------------------------------------------------------------
### AWS Cloud EC2
```
Amazon EC2 is a virtual machine in the cloud, just like a computer you’d have at home or work. The difference is:
It's hosted by AWS, so you don’t need any physical hardware.
You can choose how powerful it is (CPU, memory, storage).
You can access it from anywhere over the internet.
It runs 24/7 if you want—or just when needed.
You can install software, run applications, store files—just like a regular PC.
🧠 Think of it as a computer you rent remotely, but you still control everything inside.

1. AWS EC2 Instance Types
    There are different instance types.
    Which one to use depends on the needs.

The types are best used for different things.
Therefore, when selecting an instance type, consider the needs.
For example, needs can be a requirement for compute, memory, or storage.

1. Application servers
2. Gaming servers
3. Backend servers for companies
4. Small and medium databases
EC2 Instance Types - Summary
----------------------------

1. General Purpose
- Balanced in CPU, memory, and networking.
- 💡 Use for: Web servers, small databases, gaming servers.

2. Compute Optimized
- High-performance CPU for fast processing.
- 💡 Use for: Scientific modeling, gaming, web apps.

3. Memory Optimized
- More memory for handling large data sets.
- 💡 Use for: Big databases, in-memory caching, real-time analytics.

4. Accelerated Computing
- Uses GPUs or accelerators for complex tasks.
- 💡 Use for: Video rendering, machine learning, graphics apps.

5. Storage Optimized
- High-speed and large local storage.
- 💡 Use for: File systems, data warehouses, large transaction systems.

----------------------------

AWS EC2 Pricing Models
----------------------

1. On-Demand Instances
- No upfront cost.
- Pay only for usage.
- Best for short-term or unpredictable workloads.

2. Savings Plan
- Commit for 1 or 3 years.
- Get discounts for consistent usage.
- Extra usage charged at on-demand rates.
- Use AWS Cost Explorer to plan usage.

3. Reserved Instances
- Reserve instances for 1 or 3 years.
- Lower cost than On-Demand.
- Ideal for predictable workloads.

4. Spot Instances
- Use spare AWS capacity.
- Up to 90% discount.
- Can be interrupted—best for flexible tasks.

5. Dedicated Hosts
- Entire physical server is yours.
- Use existing software licenses.
- Most expensive option.
------------------------------
Key Concepts of EC2 Auto Scaling:
------------------------------
Automatic Instance Management: Adds or removes EC2 instances based on demand, preventing overloads and outages.

Dynamic Scaling: Reacts in real time to traffic spikes or drops.

Predictive Scaling: Uses machine learning to forecast demand and schedules scaling actions in advance.
-------------
AWS EC2 Auto Scaling monitors your application and automatically adjusts the number of EC2 instances to keep up with demand:

🔄 How It Works
Scale Up: When traffic increases (like more users visiting your app), Auto Scaling adds new instances to handle the load.

Scale Down: When demand drops (like late at night or on weekends), it terminates unneeded instances to save costs.

⚙️ Based on:
Dynamic Scaling: Reacts to actual usage metrics (like CPU, memory, or request count).

Predictive Scaling: Uses historical trends to prepare ahead of time (like adding instances before the usual Wednesday peak).

```
---------------------------------------------------------------------------------------------------------------------------------------
```

```
---------------------------------------------------------------------------------------------------------------------------------------------



