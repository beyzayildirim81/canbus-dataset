# CAN-Bus Dataset for Predictive Maintenance
This repository includes a sample dataset of 500 rows derived from CAN Bus signals.
The data was collected for a study carried out within the scope of the TÜBİTAK-TEYDEB 1501 Program.

📂 File Description
dataset.csv: Main data file (500 rows, 52 columns).

📑 Columns
AracID: Vehicle ID (anonymized)
DepoSeviyesi: Fuel tank level (%)
DepoSıcaklığı: Fuel tank temperature (°C)
MotorYağBasıncı: Engine oil pressure (bar)
MotorYağSeviyesi: Engine oil level (%)
Fren_ArkaSağ2: Rear right brake pressure (sensor 2)
Fren_ArkaSol2: Rear left brake pressure (sensor 2)
Fren_ArkaSol1: Rear left brake pressure (sensor 1)
Fren_ÖnSağ: Front right brake pressure
Fren_ÖnSol: Front left brake pressure
Fren_ArkaSol3: Rear left brake pressure (sensor 3)
Fren_ArkaSağ3: Rear right brake pressure (sensor 3)
Fren_ArkaSağ1: Rear right brake pressure (sensor 1)
YardımcıBasınç: Auxiliary brake pressure
Frenİkincil: Secondary brake pressure
FrenBirincil: Primary brake pressure
KompresörDurumu: Compressor operating status (0/1)
İçSıcaklık_Ön: Front interior temperature (°C)
İçSıcaklık_Arka: Rear interior temperature (°C)
AraçHızı: Vehicle speed (km/h)
RetarderTorkYüzdesi: Retarder torque percentage (%)
YakıtTüketim: Fuel consumption (L/100km)
FrenPedalı: Brake pedal position (%)
MotorYükYüzdesi: Engine load percentage (%)
GazPedalı: Accelerator pedal position (%)
TurboÇıkış: Turbo outlet pressure (bar)
MotorTorkYüzdesi: Engine torque percentage (%)
SürücüTork: Driver requested torque (%)
MotorHız: Engine speed (RPM)
OrtamSıcaklığı: Ambient temperature (°C)
EgzozSıcaklığı: Exhaust temperature (°C)
HavaGiriş: Air intake pressure (bar)
VitesSeçili: Selected gear
VitesAktif: Active gear
DPF_Çıkış: Diesel particulate filter outlet temperature (°C)
ŞarjVolt: Alternator output voltage (V)
AküVolt: Battery voltage (V)
ŞanzımanYağ: Transmission oil temperature (°C)
SürüşModu: Driving mode (automatic, manual, etc.)
DepoSeviye: Fuel tank level (redundant sensor)
HavaGirişSıcaklığı: Air intake temperature (°C)
ToplamYakıt: Total fuel consumed (L)
OdoYüksek: Vehicle mileage (odo)
YokuşKalkış: Hill start assist status (0/1)
DurmaFren: Parking brake status (0/1)
MotorÇalışmaSüresi: Total engine operating hours (hours)
ÖnAksAğırlığı: Front axle weight (kg)
MotorAlarm: Alarms under the engine system
SoğutucuSıcaklığı: Engine coolant temperature (°C)
YakıtMotorSıcaklığı: Fuel engine temperature (°C)
MotorYağSıcaklığı: Engine oil temperature (°C)
HavaDebisi: Air flow rate (g/s)
TurboTürbin: Turbo turbine temperature (°C)
FrenAlarm: Alarms under the brake system
AksAlarm: Alarms under the axle system
SanzımanAlarm: Alarms under the transmission system

🔒 License
This dataset is published under the CC BY 4.0 license.


# CAN-Bus Dataset for Predictive Maintenance
Bu repository, CAN-Bus sinyallerinden elde edilen **500 satırlık** örnek veriseti içermektedir.  
Veri, **TÜBİTAK-TEYDEB 1501 Programı** kapsamında yürütülen çalışma için toplanmıştır.  

## 📂 Dosya Açıklaması
- `dataset.csv` : Ana veri dosyası (500 satır, 52 kolon).

### 📑 Kolonlar
- `AracID` : Araç kimliği (anonimleştirilmiş)  
- `DepoSeviyesi` : Yakıt deposu seviyesi (%)  
- `DepoSıcaklığı` : Yakıt deposu sıcaklığı (°C)  
- `MotorYağBasıncı` : Motor yağ basıncı (bar)  
- `MotorYağSeviyesi` : Motor yağ seviyesi (%)  
- `Fren_ArkaSağ2` : Arka sağ fren basıncı (sensör 2)  
- `Fren_ArkaSol2` : Arka sol fren basıncı (sensör 2)  
- `Fren_ArkaSol1` : Arka sol fren basıncı (sensör 1)  
- `Fren_ÖnSağ` : Ön sağ fren basıncı  
- `Fren_ÖnSol` : Ön sol fren basıncı  
- `Fren_ArkaSol3` : Arka sol fren basıncı (sensör 3)  
- `Fren_ArkaSağ3` : Arka sağ fren basıncı (sensör 3)  
- `Fren_ArkaSağ1` : Arka sağ fren basıncı (sensör 1)  
- `YardımcıBasınç` : Yardımcı fren basıncı  
- `Frenİkincil` : İkincil fren basıncı  
- `FrenBirincil` : Birincil fren basıncı  
- `KompresörDurumu` : Kompresör çalışma durumu (0/1)  
- `İçSıcaklık_Ön` : Ön iç ortam sıcaklığı (°C)  
- `İçSıcaklık_Arka` : Arka iç ortam sıcaklığı (°C)  
- `AraçHızı` : Araç hızı (km/h)  
- `RetarderTorkYüzdesi` : Retarder tork yüzdesi (%)  
- `YakıtTüketim` : Yakıt tüketimi (L/100km)  
- `FrenPedalı` : Fren pedalı konumu (%)  
- `MotorYükYüzdesi` : Motor yük yüzdesi (%)  
- `GazPedalı` : Gaz pedalı konumu (%)  
- `TurboÇıkış` : Turbo çıkış basıncı (bar)  
- `MotorTorkYüzdesi` : Motor tork yüzdesi (%)  
- `SürücüTork` : Sürücü talep edilen tork (%)  
- `MotorHız` : Motor devri (RPM)  
- `OrtamSıcaklığı` : Dış ortam sıcaklığı (°C)  
- `EgzozSıcaklığı` : Egzoz sıcaklığı (°C)  
- `HavaGiriş` : Hava giriş basıncı (bar)  
- `VitesSeçili` : Seçilen vites  
- `VitesAktif` : Aktif vites  
- `DPF_Çıkış` : Dizel partikül filtresi çıkış sıcaklığı (°C)  
- `ŞarjVolt` : Alternatör çıkış voltajı (V)  
- `AküVolt` : Akü voltajı (V)  
- `ŞanzımanYağ` : Şanzıman yağı sıcaklığı (°C)  
- `SürüşModu` : Sürüş modu (otomatik, manuel vb.)  
- `DepoSeviye` : Yakıt deposu seviyesi (tekrar sensör)  
- `HavaGirişSıcaklığı` : Hava giriş sıcaklığı (°C)  
- `ToplamYakıt` : Toplam yakıt tüketimi (L)  
- `OdoYüksek` : Araç kilometresi (odo)  
- `YokuşKalkış` : Yokuş kalkış desteği durumu (0/1)  
- `DurmaFren` : Park freni durumu (0/1)  
- `MotorÇalışmaSüresi` : Motorun toplam çalışma süresi (saat)  
- `ÖnAksAğırlığı` : Ön aks ağırlığı (kg)  
- `MotorAlarm` : Motor sistemi altında gelen alarmlar
- `SoğutucuSıcaklığı` : Motor soğutucu sıcaklığı (°C)  
- `YakıtMotorSıcaklığı` : Yakıt motor sıcaklığı (°C)  
- `MotorYağSıcaklığı` : Motor yağı sıcaklığı (°C)  
- `HavaDebisi` : Hava debisi (g/s)  
- `TurboTürbin` : Turbo türbin sıcaklığı (°C)  
- `FrenAlarm` : Fren sistemi altında gelen alarmlar  
- `AksAlarm` : Aks sistemi altında gelen alarmlar
- `SanzımanAlarm` : Şanzıman sistemi altında gelen alarmlar

## 🔒 Lisans
Bu veri seti **CC BY 4.0** lisansı altında yayınlanmaktadır.  
