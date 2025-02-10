Grafik Sinir Ağları (GNN) ile Kredi Kartı Dolandırıcılık Tespiti

📊 Proje Özeti

Bu proje, Grafik Sinir Ağları (GNN) kullanarak kredi kartı işlemlerindeki dolandırıcılık faaliyetlerini tespit etmeye odaklanmaktadır. İşlem verilerini bir grafik olarak temsil ederek, kullanıcılar, kartlar ve işlemler arasındaki gizli ilişkileri ortaya çıkarabiliriz.

🚀 Özellikler

Veri ön işleme ve özellik mühendisliği

NetworkX ile grafik oluşturma

PyTorch ile GNN modeli geliştirme

Dolandırıcılık tespiti için performans değerlendirmesi

📂 Veri Kümesi

Veri kümesi, aşağıdaki gibi anonimleştirilmiş kredi kartı işlemlerini içermektedir:

Kullanıcı

Kart

Tutar

Zaman

Dolandırıcılık mı? (Etiket)

⚙️ Kurulum

# Depoyu klonlayın
git clone https://github.com/your-repo/gnn-fraud-detection.git
cd gnn-fraud-detection

# Gerekli kütüphaneleri yükleyin
pip install -r requirements.txt

🗃️ Veri Hazırlığı

Veri kümesini yükleyin: credit_card_transactions-ibm_v2.csv

Eksik verileri temizleyin ve kategorik değişkenleri kodlayın

Özellik mühendisliği (örneğin, zaman özelliklerinin çıkarılması)

🧠 Model Geliştirme

İşlemleri ve kullanıcıları temsil eden bir grafik oluşturun

PyTorch kullanarak GNN modelini uygulayın

Modeli eğitin ve performansını değerlendirin


