🌌 CyroOS: The Ecosphere
CyroOS, .NET C# mimarisi üzerine inşa edilmiş, fütüristik bir mikroservis ekosistemidir. Bu proje, merkezi güvenlik (Auth), gerçek zamanlı izleme (Node) ve akıllı otomasyonu (Flow) tek bir marka kimliği altında birleştiren bir Amiral Gemisi (Flagship) çalışmasıdır.

🏛️ Mimari Katmanlar
Ekosistem, birbirleriyle asenkron ve güvenli bir şekilde haberleşen üç ana karakoldan oluşur:

CyroAuth Master (The Heart): Merkezi kimlik doğrulama ve veri mühürleme üssü.

AES-256 & SHA-256: Endüstriyel standartlarda kriptografik güvenlik katmanı.

Double-Gate Protocol: Master Key doğrulaması ile yüksek güvenlikli veri kasası (Vault).

CyroNode Monitor (The Eye): Ağın sağlık durumunu ve servisler arası trafiği izleyen görsel radar.

Live Network Map: Nivalis fütüristik tasarım diliyle servis durumlarının görselleştirilmesi.

Real-time Sync: Diğer tüm servislerin (6060 & 8080) sağlık durumunu 2 saniyelik periyotlarla denetler.

CyroFlow Engine (The Brain): Sistemdeki olayları yakalayan ve mühürleyen akıllı otomasyon motoru.

Event Listener: Auth üzerindeki girişleri ve kasa hareketlerini pasif olarak dinler.

Unified Logging: Tüm sistem hareketlerini merkezi bir veri havuzuna mühürleyerek analize hazır hale getirir.

🛠️ Teknik Spektrum
Backend: .NET 10 / C# (Microservices Architecture)

Security: Cryptography (AES-256, SHA-256 Key Derivation)

Frontend: Futuristic Web UI (HTML5, CSS3, JavaScript)

Data Strategy: Scalable JSON-based Flat-File Storage

💎 Marka ve Vizyon (CyroTech)
Bu proje, CyroTech markasının minimal ve sade gelecek vizyonunu taşır.

🚀 Kurulum ve Çalıştırma
Projeyi yerel makinenizde ayağa kaldırmak için aşağıdaki port yapısını takip edin:

CyroFlow_Engine: http://localhost:8080 (Önce bunu başlatın)

CyroAuth_Service: http://localhost:6060 (Merkezi servis)

CyroNode_Monitor: http://localhost:7070 (Görsel Dashboard)

Hızlı Başlatma (Batch Script)
Ana dizinde bir .bat dosyası oluşturarak ekosistemi tek tıkla ateşleyebilirsiniz:

Kod snippet'i
start cmd /k "cd CyroFlow_Engine && dotnet run"
start cmd /k "cd CyroAuth_Service && dotnet run"
start cmd /k "cd CyroNode_Monitor && dotnet run"
