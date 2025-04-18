from pathlib import Path

# Whitepaper içeriği
whitepaper_content = """
# Tether USD Bridged ZED20 — Whitepaper

## 1. Giriş
Tether USD Bridged ZED20 (sembol: **USDT.z**), gerçek Tether protokolünü temel alan ancak farklı bir blok zincirinde (BEP-20) çalışan, stablecoin benzeri bir tokendir. Kullanıcılar için yüksek hız, düşük işlem maliyeti ve merkezi kontrol esnekliği sunar.

## 2. Teknik Özellikler
- **Blockchain Ağı:** Binance Smart Chain (BEP-20)  
- **Token Adı:** Tether USD Bridged ZED20  
- **Sembol:** USDT.z  
- **Desimal:** 18  
- **Toplam Arz:** 1,000,000,000 (1 Milyar)  
- **Sözleşme Adresi:** `0x...`  *(Güncel adres buraya eklenebilir)*

## 3. Kullanım Alanları
- Cüzdanlar arası transfer  
- DApp ödemeleri  
- Swap ve takas işlemleri  
- Merkeziyetsiz finans (DeFi) protokollerinde kullanım  
- Stablecoin işlemleri için referans varlık

## 4. Merkezî Kontrol ve Güvenlik
USDT.z, yükseltilebilir (proxy destekli) mimariye sahip bir akıllı kontrat kullanır. Bu sayede:
- Yeni işlevler eklenebilir
- Karaliste (blacklist)
- Bakiye dondurma (freeze)
- Yeni arz (mint) gibi kontroller uygulanabilir.

Bu yapı, düzenleyici uyumluluk ve güvenliği ön planda tutar.

## 5. Dağıtım ve Rezerv Yapısı
- **%60**: Genel dolaşım (kullanıcılara)  
- **%20**: Rezerv fon  
- **%10**: Geliştirici ekibi  
- **%5**: Pazarlama ve promosyon  
- **%5**: Likidite kilitli (DEX kullanımı için)

## 6. Gelecek Planlar
- Trust Wallet ve diğer popüler cüzdanlara logo entegresi  
- CoinMarketCap ve CoinGecko listelemeleri  
- Merkezi borsa (CEX) başvuruları  
- DeFi platformları ile entegrasyon  
- Topluluk odaklı teşvik programları

## 7. Yasal Uyarı
Bu token, resmi Tether Limited şirketiyle ilişkili değildir. Tether USD Bridged ZED20, bağımsız bir projedir ve "flash" kullanım amaçlarına özel geliştirilmiştir.
"""

# Dosyayı kaydet
file_path = Path("/mnt/data/tetherusd-bridged-zed20-whitepaper.md")
file_path.write_text(whitepaper_content, encoding="utf-8")

file_path.name
