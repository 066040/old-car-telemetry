# Old Car Telemetry

GPS-based digital dashboard and trip logger for classic cars without OBD — built for a 1990 Tofaş Toros and running on an old Huawei P9 Lite. No wires to the car, nothing to install: it is a single HTML page that runs in the phone's browser.

**Live:** https://066040.github.io/old-car-telemetry/

## Features
- **Drive:** large live speed readout (GPS Doppler speed), trip average, distance, duration and max speed
- **Average-speed corridors (EDS):** save corridors on the road or add them by coordinates; entering one opens a panel with the running average and a voice warning; suggested speed never exceeds the road limit
- **Fuel:** log fill-ups and get real L/100 km from the second fill onward
- **Automatic trips:** a trip starts after a few seconds above 10 km/h and is saved after 5 minutes without movement; data is persisted every 10 s
- **Damaged-screen support:** a slider hides an unusable strip at the bottom of the display

## Usage
1. Open the live link in Chrome on the phone and allow location access
2. Menu → "Add to Home screen"
3. Set the screen timeout to the maximum — the browser pauses GPS while the screen is off

## Roadmap
- ESP32 sensor box (RPM, coolant temperature, battery voltage) over BLE — no wires cut, everything plug-and-play
- Server + web panel for routes, trip summaries and fuel history

---

## Türkçe

OBD'si olmayan klasik araçlar için GPS tabanlı dijital gösterge ve yolculuk kaydedici. 1990 model Tofaş Toros için, eski bir Huawei P9 Lite üzerinde çalışacak şekilde yapıldı. Araca kablo bağlanmaz, kurulum gerekmez: telefonun tarayıcısında çalışan tek bir HTML sayfası.

- **Sürüş:** büyük anlık hız, yolculuk ortalaması, mesafe, süre, maksimum hız
- **EDS koridorları:** koridora girince ortalama hız paneli ve sesli uyarı
- **Yakıt:** dolumları kaydet, ikinci dolumdan itibaren gerçek L/100 km
- **Otomatik yolculuk:** hareket edince başlar, 5 dk durunca kaydedilir
- **Bozuk ekran desteği:** ekranın alttaki kullanılamayan kısmı gizlenebilir

Kullanım: linki Chrome'da aç, konum izni ver, "Ana ekrana ekle" de, ekran zaman aşımını en uzuna al.

## Author
Ahmet Furkan Göktaş — [@066040](https://github.com/066040)
