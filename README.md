# Real-Time Data Processing (AWS Data Engineering Project)

<img width="340" height="340" alt="aws data badge" src="https://github.com/user-attachments/assets/a69f32b6-e0d9-4957-8716-d9d29933bbdf" />


📖 **Proje Açıklaması**  
Bu proje, rüzgar türbinlerinden gelen sensör verilerini gerçek zamanlı (real-time) işlemek için AWS üzerinde geliştirilmiş bir mimari örneğidir.  
Amaç, gelen veriyi güvenilir şekilde toplamak, anormallikleri tespit etmek ve bakım ekibini otomatik olarak bilgilendirmektir. 

<img width="1694" height="953" alt="Real-Time Data Processing" src="https://github.com/user-attachments/assets/7ef82683-21ec-4f21-99cd-7922a98b397a" />

🏗️ **Mimari**  
Real-Time Data Processing Flow  
- Wind Turbine → Amazon Kinesis Data Streams  
- Amazon Managed Apache Flink → Veri işleme ve anomaly detection  
- AWS Lambda → DynamoDB’ye kayıt  
- Amazon DynamoDB → Normal veriler ve anomaly tabloları  
- Amazon SNS → Anomali bildirimi (e-posta / mesaj)  

⚙️ **Kullanılan Servisler**  
- Amazon Kinesis Data Streams  
- Amazon Managed Apache Flink  
- AWS Lambda  
- Amazon DynamoDB  
- Amazon SNS  

🎯 **Öğrenim Hedefleri**  
- Real-time streaming data ingestion sürecini öğrenmek  
- Apache Flink ile anomaly detection uygulamak  
- Lambda fonksiyonları ile veriyi DynamoDB’ye yazmak  
- SNS üzerinden otomatik bildirim mekanizması kurmak  

🚀 **Sonraki Adımlar**  
- Amazon Kinesis Data Analytics ile gelişmiş anomaly detection eklenebilir  
- Veriler Amazon Redshift veya S3 + Athena ile analiz edilip BI raporlamada kullanılabilir  
- CloudWatch ve EventBridge ile otomatik ölçeklenebilirlik eklenebilir  
