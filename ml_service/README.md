# California Housing — Model as a Service (Flask + Docker)

โปรเจกต์ให้บริการโมเดล Machine Learning (RandomForestRegressor) สำหรับทำนายราคาบ้านในรัฐแคลิฟอร์เนียผ่านเว็บแอปพลิเคชัน Flask และบรรจุใน Docker Container

## วิธี Build และ Run ด้วย Docker

1. **Build Docker Image**
   ```bash
   docker build -t ds-ml-service .