# Smart Fruit Freshness Monitor (IoT)
ESP32 + MQ-135 gas sensor + DHT11 -> HTTPS -> Node/Express dashboard on Render.
- `POST /api/data?key=...` : device uploads a JSON reading
- `GET  /`                 : live dashboard
