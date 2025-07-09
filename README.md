
# 🧾 Serverless AWS Invoice Scanner

A fully serverless invoice processing system built with AWS. Upload an invoice PDF to an S3 bucket, and it automatically extracts fields using Textract, stores them in DynamoDB, and sends you an email notification with the results.

---

## 🔧 Tech Stack

- **Amazon S3** – file upload trigger
- **AWS Lambda** – text extraction + orchestration
- **Amazon Textract** – invoice OCR
- **DynamoDB** – data storage
- **SNS** – email notification
- **CloudWatch** – logging & debugging

---

## 🚀 How It Works

1. Upload a `.pdf` invoice to the configured S3 bucket
2. S3 triggers a Lambda function
3. Lambda uses Textract to extract key-value pairs
4. Extracted data is stored in DynamoDB with a unique ID
5. An SNS email is sent with a summary of the fields

---

 fully serverless invoice processing system built with AWS. Upload an invoice PDF to an S3 bucket, and it automatically extracts fields using Textract, stores them in DynamoDB, and sends you an email notification with the results.
