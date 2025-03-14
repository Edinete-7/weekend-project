## 🏗️ AWS CloudFormation Automation Project

This repository contains CloudFormation templates to automate the deployment of AWS infrastructure. It demonstrates my ability to design, deploy, and manage cloud resources using Infrastructure-as-Code (IaC).

---

## 📌 Project Overview

The project covers the following tasks:

1. **Deploy a Virtual Private Cloud (VPC) and Security Group**  
2. **Add an Amazon S3 Bucket to the CloudFormation Stack**  
3. **Deploy an Amazon EC2 Instance with Security Configuration**  
4. **Automate Infrastructure Teardown by Deleting the Stack**

Each task is performed using CloudFormation YAML templates to provision AWS resources in a consistent and repeatable manner.

---

## 📂 Files in the Repository

| File         | Description                                        |
|--------------|----------------------------------------------------|
| `task1.yaml` | Creates a VPC and a Security Group.                |
| `task2.yaml` | Updates the stack to include an Amazon S3 bucket.  |
| `task3.yaml` | Further updates to deploy an Amazon EC2 instance.  |

---

## 🛠️ AWS Services Used

- **Amazon VPC** – Virtual Private Cloud for isolated networking
- **Amazon S3** – Secure object storage for static content
- **Amazon EC2** – Virtual servers to run applications
- **AWS CloudFormation** – Infrastructure-as-Code automation
- **AWS Systems Manager Parameter Store** – Manage AMI references

---

## 🚀 Getting Started

### Prerequisites

Ensure you have the following:

- An active **AWS account**.
- **AWS Management Console** access.
- Basic knowledge of **CloudFormation** and **YAML syntax**.

### Step 1: Deploy the Initial CloudFormation Stack

1. Go to the **AWS Management Console** and navigate to **CloudFormation**.
2. Click **Create Stack** → **With new resources (standard)**.
3. Choose **Upload a template file** and select `task1.yaml`.
4. Enter a **Stack Name** (e.g., `MyCloudFormationLab`).
5. Leave default CIDR values unless customization is required.
6. Click **Next** and acknowledge any resource creation warnings.
7. Click **Create Stack** and wait for the status to change to `CREATE_COMPLETE`.

### Step 2: Add an Amazon S3 Bucket

1. Download and edit the `task2.yaml` file if needed.
2. In the **CloudFormation** console, select the existing stack.
3. Click **Update** → **Replace current template**.
4. Upload the updated `task2.yaml` and proceed through the steps.
5. Confirm the **Add S3 Bucket** change and click **Update Stack**.

### Step 3: Deploy an Amazon EC2 Instance

1. Modify and upload the `task3.yaml` file as before.
2. Follow the **Update Stack** process.
3. Ensure the EC2 instance is created successfully.

### Step 4: Delete the Stack (Clean Up Resources)

1. Select your stack in the **CloudFormation** console.
2. Click **Delete** and confirm the deletion.
3. Wait until the status changes to `DELETE_COMPLETE`.

---

## 📊 Project Structure Explained

- **Parameters** – Collect user inputs (e.g., CIDR range, AMI ID).
- **Resources** – Define AWS services (VPC, S3, EC2, Security Groups).
- **Outputs** – Provide key details (e.g., Security Group ID, S3 Bucket).

Each template follows a modular approach to allow easy updates and extensions.

---

## 📈 Key Learnings and Skills Demonstrated

- **Infrastructure as Code (IaC)** – Manage AWS resources with CloudFormation.
- **Automation** – Minimize manual intervention with automated provisioning.
- **Resource Dependency Management** – Ensure the correct creation order.
- **Template Updates** – Modify and expand infrastructure without downtime.
- **Cloud Best Practices** – Secure and scalable resource deployment.

---

## 🗺️ Future Improvements

- Add an **Auto Scaling Group** for EC2 instances.
- Implement **CloudWatch** monitoring for logging and metrics.
- Enhance **IAM roles** for fine-grained access control.

---

## 📬 Contact & Feedback

If you have questions or suggestions:

- **Email**: your.email@example.com
- **GitHub**: [your-username](https://github.com/your-username)
- **LinkedIn**: [Your LinkedIn Profile](https://linkedin.com/in/your-profile)

Feel free to fork, open issues, and contribute!

---

## 📜 License

This project is licensed under the **MIT License** – you're free to use, modify, and distribute it.

 weekend-project
