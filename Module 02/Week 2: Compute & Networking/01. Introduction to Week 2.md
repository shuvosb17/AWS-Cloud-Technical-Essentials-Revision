# 🚀 Week 2 Theme: **Compute & Networking**

So far, you’ve learned:

* What AWS is
* How global infrastructure works
* How to secure accounts with IAM
* How access & roles work

Now comes the natural next question:

> **Where does my application actually RUN?**

The answer is: **Compute**.

---

## 🧠 What “Compute” Means (Very Simple)

> **Compute = CPU + Memory + Network**

Compute gives your app:

* 🧮 Processing power (CPU)
* 🧠 Memory (RAM)
* 🌐 Networking (send/receive requests)

Without compute:
❌ No backend
❌ No API
❌ No web app

---

## 🖥️ You’ve Already Met One Compute Service

You already launched an instance using:

👉 **Amazon EC2**

### EC2 is:

* A **virtual server**
* Runs 24/7
* You manage:

  * OS
  * Updates
  * Security patches

Think of EC2 like:

> “Renting a computer in the cloud”

---

# 🧩 Compute Options You’ll Learn in Week 2

AWS gives you **multiple compute models**, because **one size never fits all**.

![Image](https://docs.aws.amazon.com/images/whitepapers/latest/aws-overview/images/compute-services.png)

![Image](https://fourtheorem.com/wp-content/uploads/2022/09/Choosing-AWS-Compute-Blog-Diagram-1.webp)

![Image](https://media.licdn.com/dms/image/v2/D5612AQEISaEi1o-w6g/article-cover_image-shrink_720_1280/article-cover_image-shrink_720_1280/0/1694318149269?e=2147483647\&t=FgDkn9U8-M8XUFj4U_1JXeGNz-KT398vSsLq91b9OkM\&v=beta)

---

## 1️⃣ **Amazon EC2** – Virtual Machines

Best when:

* You need full control
* Custom OS / software
* Long-running apps

---

## 2️⃣ **Amazon ECS** – Containers (Docker)

Best when:

* You use containers
* Want easier scaling than EC2
* Less OS management

---

## 3️⃣ **Amazon EKS** – Kubernetes

Best when:

* You already know Kubernetes
* Need portability
* Complex microservices

⚠️ Powerful but complex

---

## 4️⃣ **AWS Lambda** – Serverless

Best when:

* Event-driven apps
* No server management
* Pay per execution

Think:

> “Run code only when needed”

---

## 🎯 Big Goal of This Week

By the end of Week 2, you will be able to answer:

| Question                        | Confident Answer |
| ------------------------------- | ---------------- |
| Should I use EC2 or Lambda?     | ✅                |
| When do containers make sense?  | ✅                |
| Do I need Kubernetes?           | ✅                |
| How do I choose compute wisely? | ✅                |

🔥 This skill is **interview gold**.

---

# 🌐 But Compute Can’t Float in Space…

The instructor made a **VERY important point** 👇

> “We can’t just launch an EC2 instance into space.”

Every compute resource must live **inside a network**.

---

## 🏗️ Enter: AWS Networking

On AWS, networks are called:

👉 **Amazon VPC** (Virtual Private Cloud)

### VPC:

* Is your **private network**
* Holds:

  * EC2
  * Databases
  * Load balancers
* You control:

  * IP ranges
  * Traffic rules
  * Isolation

💡 Think of VPC as:

> “Your own data center network in AWS”

Don’t worry —
👉 **AWS networking will be taught gently and clearly**

---

# 📚 IMPORTANT ADVICE (Don’t Skip This)

The instructor says something smart:

> “Check the readings after the videos.”

Why?

* Extra use cases
* Features not shown in demos
* Exam-relevant details

📌 Videos = intuition
📌 Readings = depth

You need **both**.

---

# 🧭 What’s Coming in Week 2 (Preview)

You will:

* Deep dive into EC2
* Learn networking basics with VPC
* Compare compute services
* See real demos
* Build toward a real architecture

---

## ✅ Final Mental Model for Week 2

```
Application
   ↓
Compute (EC2 / ECS / EKS / Lambda)
   ↓
Network (VPC)
```

Everything in AWS follows this structure.

---

## 🚀 Ready to Continue?

👉 **Next lesson:**

### 🖥️ *Amazon EC2 – Virtual Servers in the Cloud*
