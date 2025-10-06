# CAN Bus Dataset for Predictive Maintenance

This repository includes a sample dataset of **500 rows** derived from CAN Bus signals.

The data was collected for a study carried out within the scope of the **TÜBİTAK-TEYDEB 1501 Program** (A Turkish governmental R&D support program).

---

## 📂 File Description

- `dataset.csv`: The main data file, containing 500 rows and 52 columns.

---

## 📑 Columns

The table below lists all 52 columns, their English translations, and the corresponding units or descriptions.

| Turkish Column Name | English Translation | Unit / Description |
| :--- | :--- | :--- |
| **AracID** | **Vehicle ID** | Anonymized |
| **DepoSeviyesi** | **Fuel Tank Level** | (%) |
| **DepoSıcaklığı** | **Fuel Tank Temperature** | (°C) |
| **MotorYağBasıncı** | **Engine Oil Pressure** | (bar) |
| **MotorYağSeviyesi** | **Engine Oil Level** | (%) |
| **Fren\_ArkaSağ2** | **Brake Rear Right 2** | Pressure (sensor 2) |
| **Fren\_ArkaSol2** | **Brake Rear Left 2** | Pressure (sensor 2) |
| **Fren\_ArkaSol1** | **Brake Rear Left 1** | Pressure (sensor 1) |
| **Fren\_ÖnSağ** | **Brake Front Right** | Pressure |
| **Fren\_ÖnSol** | **Brake Front Left** | Pressure |
| **Fren\_ArkaSol3** | **Brake Rear Left 3** | Pressure (sensor 3) |
| **Fren\_ArkaSağ3** | **Brake Rear Right 3** | Pressure (sensor 3) |
| **Fren\_ArkaSağ1** | **Brake Rear Right 1** | Pressure (sensor 1) |
| **YardımcıBasınç** | **Auxiliary Brake Pressure** | |
| **Frenİkincil** | **Secondary Brake Pressure** | |
| **FrenBirincil** | **Primary Brake Pressure** | |
| **KompresörDurumu** | **Compressor Status** | Operating status (0/1) |
| **İçSıcaklık\_Ön** | **Interior Temperature Front** | (°C) |
| **İçSıcaklık\_Arka** | **Interior Temperature Rear** | (°C) |
| **AraçHızı** | **Vehicle Speed** | (km/h) |
| **RetarderTorkYüzdesi** | **Retarder Torque Percentage** | (%) |
| **YakıtTüketim** | **Fuel Consumption** | (L/100km) |
| **FrenPedalı** | **Brake Pedal Position** | (%) |
| **MotorYükYüzdesi** | **Engine Load Percentage** | (%) |
| **GazPedalı** | **Accelerator Pedal Position** | (%) |
| **TurboÇıkış** | **Turbo Outlet Pressure** | (bar) |
| **MotorTorkYüzdesi** | **Engine Torque Percentage** | (%) |
| **SürücüTork** | **Driver Requested Torque** | (%) |
| **MotorHız** | **Engine Speed** | (RPM) |
| **OrtamSıcaklığı** | **Ambient Temperature** | (°C) |
| **EgzozSıcaklığı** | **Exhaust Temperature** | (°C) |
| **HavaGiriş** | **Air Intake Pressure** | (bar) |
| **VitesSeçili** | **Selected Gear** | |
| **VitesAktif** | **Active Gear** | |
| **DPF\_Çıkış** | **DPF Outlet Temperature** | (°C) |
| **ŞarjVolt** | **Charging Voltage** | Alternator output (V) |
| **AküVolt** | **Battery Voltage** | (V) |
| **ŞanzımanYağ** | **Transmission Oil Temperature** | (°C) |
| **SürüşModu** | **Driving Mode** | (Automatic, Manual, etc.) |
| **DepoSeviye** | **Fuel Tank Level** | Redundant sensor |
| **HavaGirişSıcaklığı** | **Air Intake Temperature** | (°C) |
| **ToplamYakıt** | **Total Fuel Consumed** | (L) |
| **OdoYüksek** | **Odometer Reading** | Vehicle mileage |
| **YokuşKalkış** | **Hill Start Assist Status** | (0/1) |
| **DurmaFren** | **Parking Brake Status** | (0/1) |
| **MotorÇalışmaSüresi** | **Total Engine Operating Hours** | (hours) |
| **ÖnAksAğırlığı** | **Front Axle Weight** | (kg) |
| **MotorAlarm** | **Engine System Alarms** | |
| **SoğutucuSıcaklığı** | **Engine Coolant Temperature** | (°C) |
| **YakıtMotorSıcaklığı** | **Fuel Engine Temperature** | (°C) |
| **MotorYağSıcaklığı** | **Engine Oil Temperature** | (°C) |
| **HavaDebisi** | **Air Flow Rate** | (g/s) |
| **TurboTürbin** | **Turbo Turbine Temperature** | (°C) |
| **FrenAlarm** | **Brake System Alarms** | |
| **AksAlarm** | **Axle System Alarms** | |
| **SanzımanAlarm** | **Transmission System Alarms** | |

---

## 🔒 License

This dataset is published under the **CC BY 4.0** license.


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
