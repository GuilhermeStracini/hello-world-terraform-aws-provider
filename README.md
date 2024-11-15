# Hello World Terraform AWS Provider

📚 A repository to explore and learn **[Terraform](https://www.terraform.io/)** using the **AWS Provider**, enabling infrastructure as code (IaC) for creating, managing, and scaling AWS resources.

---

## Overview

This repository is designed as a learning resource to:

- Understand the basics of **Terraform** and its declarative configuration syntax.
- Gain hands-on experience with the **AWS Provider** to provision cloud infrastructure.
- Serve as a starting point for building more advanced Terraform configurations.

---

## Features

- **Beginner-Friendly Setup**:
  - Demonstrates a simple **Hello World** example using Terraform.
  - Includes configurations for deploying basic AWS resources.

- **Infrastructure as Code (IaC)**:
  - Focus on reproducible and version-controlled infrastructure.
  - Practice applying, destroying, and modifying resources.

---

## Getting Started

Follow these steps to set up and use the repository.

### Prerequisites

- Install **Terraform**: [Download and Installation Guide](https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli)
- An **AWS Account**: Set up [AWS CLI](https://aws.amazon.com/cli/) and configure credentials.
  ```bash
  aws configure
  ```
- Basic knowledge of AWS services.

### Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/GuilhermeStracini/hello-world-terraform-aws.git
   cd hello-world-terraform-aws
   ```

2. **Initialize Terraform**:
   - Initialize the working directory and download the AWS Provider:
     ```bash
     terraform init
     ```

3. **Preview and Apply the Configuration**:
   - Preview the infrastructure changes:
     ```bash
     terraform plan
     ```
   - Apply the configuration to create resources:
     ```bash
     terraform apply
     ```

4. **Destroy the Resources** (Optional):
   - To clean up and avoid charges:
     ```bash
     terraform destroy
     ```

---

## Helpful Links

Expand your learning with these resources:

- [Top 5 Terraform Projects for AWS to Boost Your Resume](https://towardsaws.com/top-5-terraform-projects-for-aws-to-boost-your-resume-easy-intermediate-expert-levels-with-59c5cc67c3e0)
- [Terraform AWS Provider Documentation](https://registry.terraform.io/providers/hashicorp/aws/latest/docs)
- [Terraform Tutorials by HashiCorp](https://developer.hashicorp.com/terraform/tutorials)

---

## Contribution

Contributions are welcome!  
If you have suggestions or want to extend this project with additional examples, feel free to fork the repository, open issues, or submit pull requests.

---

## License

This project is licensed under the [MIT License](LICENSE).
