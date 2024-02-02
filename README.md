# Trafik İzleme ve Hız Radar Sistemi

Bu proje, trafikteki araçları gerçek zamanlı olarak tespit eder, hızlarını ölçer ve belirlenen hız limitini aşan araçların fotoğraflarını kaydeder. OpenCV ve Python kullanılarak geliştirilmiştir. Bu sistem, trafik güvenliğini artırmak ve hız limitlerine uymayan sürücüleri tespit etmek amacıyla tasarlanmıştır.

## Özellikler

- Gerçek zamanlı araç tespiti ve hız ölçümü
- Belirlenen hız limitini aşan araçların fotoğraflarının kaydedilmesi
- Trafik geçiş kayıtlarının `TrafficRecord` klasöründe saklanması

## Başlangıç

Bu bölümde, projenin nasıl kurulacağı ve çalıştırılacağına dair adımlar yer almaktadır.

### Gereksinimler

- Python 3.8 veya üzeri
- OpenCV
- Numpy

### Kurulum

1. Gerekli kütüphaneleri yükleyin:
    ```bash
    pip install opencv-python numpy
    ```

2. Projeyi yerel bilgisayarınıza klonlayın:
    ```bash
    git clone https://github.com/[KullanıcıAdınız]/trafik-izleme-ve-hiz-radar-sistemi.git
    ```

### Kullanım

Proje dizininde aşağıdaki komutu çalıştırarak sistemi başlatabilirsiniz:

```bash
python SpeedRadar2.py

