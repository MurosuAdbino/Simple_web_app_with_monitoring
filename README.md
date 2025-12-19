# Deployment Web Application, Reverse Proxy, dan Monitoring menggunakan Docker

## Author: Muhammad Robbi Sukarno  

---

Implementasi **aplikasi web berbasis Yii 2.0** yang dijalankan menggunakan **Docker dan Docker Compose**, dilengkapi dengan **reverse proxy menggunakan NGINX** serta **sistem monitoring menggunakan Prometheus, Grafana, dan exporter**.

Arsitektur dibagi menjadi **tiga fase utama**:

1. **Fase 1** – Deployment aplikasi dan database
2. **Fase 2** – Reverse proxy dan manajemen domain
3. **Fase 3** – Monitoring sistem dan database

Seluruh service dijalankan dalam satu **Docker custom bridge network** agar komunikasi antar container stabil dan menyerupai environment real/production. 
Detail dalam "Docs/*.pdf."

<img width="1918" height="1016" alt="image" src="https://github.com/user-attachments/assets/8c0a003f-f692-4845-8bc3-f40ed3f526e5" />
<img width="1701" height="550" alt="image-6" src="https://github.com/user-attachments/assets/2da23497-4491-4826-a92b-11b8aaa5d906" />
<img width="1913" height="1007" alt="image-2" src="https://github.com/user-attachments/assets/0067f93b-f411-4054-8a56-1b508c5def4d" />

<img width="1916" height="1011" alt="image-3" src="https://github.com/user-attachments/assets/f8918a22-c551-428f-b0ee-39ec91c6db4c" />
<img width="1908" height="966" alt="image-4" src="https://github.com/user-attachments/assets/10243e7a-6e55-4a00-85eb-efdb5e79eb93" />
<img width="1919" height="1019" alt="image-8" src="https://github.com/user-attachments/assets/58d55167-f017-4224-a165-2a0b3f3a3ebf" />
<img width="1918" height="1021" alt="image-9" src="https://github.com/user-attachments/assets/b5d9a349-1b2a-43ee-91d7-02c7ba473665" />
<img width="1914" height="1019" alt="image-10" src="https://github.com/user-attachments/assets/f8cc3afc-88bf-4416-a7ab-7304b66e909e" />
