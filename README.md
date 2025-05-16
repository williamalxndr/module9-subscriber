### 1. What is amqp?
> AMQP (Advanced Message Queuing Protocol) adalah protokol komunikasi terbuka yang digunakan untuk mengatur antrian pesan antara sistem secara terstruktur. Protokol ini memungkinkan aplikasi saling bertukar pesan tanpa harus terhubung langsung, biasanya lewat message broker seperti RabbitMQ.

### 2. What does it mean? guest:guest@localhost:5672 , what is the first guest, and what is the second guest, and what is localhost:5672 is for?
> guest:guest@localhost:5672 adalah format URL untuk menghubungkan aplikasi ke RabbitMQ melalui protokol AMQP. Kata guest pertama adalah username default, sedangkan guest kedua adalah password default yang diberikan oleh RabbitMQ. localhost menunjukkan bahwa broker RabbitMQ berjalan di komputer lokal, dan 5672 adalah port standar yang digunakan untuk koneksi AMQP. Format ini dipakai agar aplikasi bisa mengautentikasi dan berkomunikasi dengan broker pesan dengan benar.

### Simulation Slow Subscriber
![ss-slow-subscriber](assets/images/ss-slow-subscriber.png)