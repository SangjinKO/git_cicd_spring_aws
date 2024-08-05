# Git-AWS CI/CD Test

- Automatically deploy when a main branch is pushed
- Add a CI workflow(workflow-job-step) on Git >> Build and run test
  - name: Checkout
  - name: Set up JDK 17
  - name: Grant execute permission for gradlew
  - name: gradlew bootJar
  - name: copy jar to server
  - name: SSH Commands
- Deploy to AWS(EC2)

![cicd_aws_img](https://github.com/user-attachments/assets/9340beb1-e823-452c-bd63-43bfc8da9c20)
