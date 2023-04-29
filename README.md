# Benchmark CPU

## Install Library
Untuk installasi library silahkan mengunjungi link berikut [Tutorial Installasi Library](https://github.com/Yayasan-Satriabudi-Dharma-Setia/BioinfoTraining/wiki/2.-Persiapan-Cloud)


## Tutorial Menjalankan Benchmark
* [Login Ke Terminal](https://github.com/Yayasan-Satriabudi-Dharma-Setia/BioinfoTraining/wiki/2.-Persiapan-Cloud)
* Jalankan Perintah Berikut :
```jupter-notebook --ip=0.0.0.0```
* akses melalui browser!
![image](https://user-images.githubusercontent.com/127930643/230828486-3f818c9f-b204-4186-89f2-0faf2a03f20e.png)
* ganti 127.0.0.1:8888 dengan ip address server, contoh 110.239.66.155:8888
* Pilih / Klik benchmark_script.ipynb
![image](https://user-images.githubusercontent.com/127930643/230828891-c4360c4c-ff9c-43f8-98ce-37de55d94f25.png)
* Pilih Menu Cell dan Klik Run All
![image](https://user-images.githubusercontent.com/127930643/230829320-897f4307-ff02-4a88-a6af-ce53dc4f0773.png)


## Hasil Benchmark

| Cloud Server  | Spesifikasi Server |Benchmark Script                          | Harga Per hWGS | Durasi Waktu | Ram Used | CPU Used                        |
|-------------|---|-------------------------------|-----------------------------|-----------------------------|-----------------------------|-----------------------------|
|Alibaba|  |`'benchmark_scrpit.ipynb'`            |            |
|Google| |`'benchmark_scrpit.ipynb'`            |            |
|Huawei| Saat Konfigurasi: BW 10MB, 2vCPU 	Intel Ice Lake 2.6GHz,RAM 4GB |`'benchmark_scrpit.ipynb'`||


# Benchmark GPU
## Tutorial Menjalankan Benchmark
https://github.com/Yayasan-Satriabudi-Dharma-Setia/BioinfoTraining/wiki/5.-Clara-Parabricks-Sequencing

## Hasil Benchmark

| Cloud Server  | Spesifikasi Server | Harga Per hWGS | Durasi Waktu | Ram Used | CPU Used                        | GPU Used |
|-------------|---|-------------------------------|-----------------------------|-----------------------------|-----------------------------|-----------------------------|
|Huawei| Saat Konfigurasi: BW 100MB, 8vCPU 	Intel Cascade Lake 3.0GHz,RAM 64GB GPU A100 40GB | |59 Menit| 2GB | 2Core | |
|Huawei| Saat Konfigurasi: BW 1MB, 8vCPU 	Intel Cascade Lake 3.0GHz,RAM 64GB GPU A100 40GB | |18 Menit 19Detik| All | All | All |
