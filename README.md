# Convert-CSV-file-to-JSON-file-using-AWS-Glue-ETL
Glue Crawler + ETL CSV → JSON conversion project 


# 🔄 AWS Glue ETL: Convert CSV to JSON in S3

This project showcases how to use **AWS Glue Crawlers and ETL Jobs** to transform CSV data stored in Amazon S3 into JSON format.

---

## 🧰 Tech Used

- AWS S3
- AWS Glue (Crawler + Visual ETL Job)
- AWS IAM (Permissions)
- AWS Glue Data Catalog

---

## 📁 Input Data

A CSV file containing sales data:

```csv

customer_id,product_name,sales
1,mobile,250000
1,refrigerator,30000
1,washing,35000
2,mobile,250000
2,refrigerator,30000
2,washing,35000
3,mobile,250000
3,refrigerator,30000
3,washing,35000
4,mobile,250000
4,refrigerator,30000
4,washing,35000
5,mobile,250000
5,refrigerator,30000
5,washing,35000
6,mobile,250000
6,refrigerator,30000
6,washing,35000
