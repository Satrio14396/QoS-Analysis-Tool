# Hasil Analisis QoS

## Tujuan
Analisis kualitas layanan untuk situs `https://akademik.unsri.ac.id` menggunakan Wireshark.

## Metrik QoS
- **Latency**: Waktu respons rata-rata.
- **Packet Loss**: Persentase paket yang hilang.

## Tabel Latency
| Permintaan  | Waktu Permintaan (ms) | Waktu Respons (ms) | Latency (ms) |
|-------------|------------------------|---------------------|---------------|
| Request 1   | 1.666205             | 2.856003          | 1,1         |
| Request 2   | 2.856003            | 2.928949         | 0,7          |
| Request 3    | 2.928949            | 2.976992         | 0,4         |
| Request 4   | 30.838013         | 31.066776           | 0,2         | 
| Request 5   | 31.06676       | 73.947104            |   42,8          |
| Request 6   |73.956671           | 74.459175           |  0,5         |
| request 7   | 88.286225           |91.047165          |  2,7         | 
dst.

## Packet Loss
Packet Loss Rate= Jumlah Paket Hilang : Jumlah Paket Dikirim x 100% 
                = 519 : 8751 x 100% = 5,9 %
                
![Screenshot 2024-10-06 133135](https://github.com/user-attachments/assets/327e994f-04ce-41ac-988c-bfd7316a2047)



## Througputh

![Screenshot 2024-10-06 132314](https://github.com/user-attachments/assets/7e994a92-d71d-423b-bb43-4f01e7b999aa)
