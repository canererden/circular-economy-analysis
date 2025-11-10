# Datasets

Bu depo, Eurostat, OECD ve World Bank veri setlerini içerir. Tüm Eurostat veri setleri için doğrudan indirilebilir linkler verilmiştir. README, tarayıcıdan tek tıkla `.tsv.gz` veya `.csv` dosyalarını indirmenize olanak sağlar.

📂 Klasör Yapısı
```
Circular_Economy_Dataset/
├── Eurostat/
│   ├── cei_pc/       # Production and consumption
│   ├── cei_wm/       # Waste management
│   ├── cei_srm/      # Secondary raw materials
│   ├── cei_cie/      # Competitiveness and innovation
│   ├── cei_gsr/      # Global sustainability and resilience
│   ├── t_isoc/       # Digital economy & ICT indicators
│   └── env_tax/      # Environmental Tax Revenues
├── OECD/
│   └── patents/      # Green patents & EPO data
└── WorldBank/
    └── CSV files & ZIPs
```

---

## Circular Economy Dataset - Eurostat

Bu depo, Eurostat’un Circular Economy Indicators (CEI) veri setlerini içerir. Tüm tablolar `.tsv.gz` formatında ve doğrudan indirilebilir linklerle sağlanmıştır.

---

### 📊 Production and consumption (cei_pc)
| Table Name | Eurostat Code | Direct Download |
|------------|---------------|----------------|
| Material footprint | cei_pc020 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/cei_pc020?format=TSV&compressed=true) |
| Resource productivity | cei_pc030 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/cei_pc030?format=TSV&compressed=true) |
| Waste generation per capita | cei_pc034 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/cei_pc034?format=TSV&compressed=true) |
| Generation of waste excluding major mineral wastes per GDP unit | cei_pc032 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/cei_pc032?format=TSV&compressed=true) |
| Generation of municipal waste per capita | cei_pc031 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/cei_pc031?format=TSV&compressed=true) |
| Food waste | cei_pc035 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/cei_pc035?format=TSV&compressed=true) |
| Generation of packaging waste per capita | cei_pc040 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/cei_pc040?format=TSV&compressed=true) |
| Generation of plastic packaging waste per capita | cei_pc050 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/cei_pc050?format=TSV&compressed=true) |

---

### 📊 Waste management (cei_wm)
| Table Name | Eurostat Code | Direct Download |
|------------|---------------|----------------|
| Recycling rate of municipal waste | cei_wm011 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/cei_wm011?format=TSV&compressed=true) |
| Recycling rate of all waste excluding major mineral waste | cei_wm010 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/cei_wm010?format=TSV&compressed=true) |
| Recycling rate of packaging waste by type of packaging | cei_wm020 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/cei_wm020?format=TSV&compressed=true) |
| Recycling rate of WEEE separately collected | cei_wm060 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/cei_wm060?format=TSV&compressed=true) |

---

### 📊 Secondary raw materials (cei_srm)
| Table Name | Eurostat Code | Direct Download |
|------------|---------------|----------------|
| Circular material use rate | cei_srm030 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/cei_srm030?format=TSV&compressed=true) |
| Contribution of recycled materials to raw materials demand - EOL-RIR | cei_srm010 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/cei_srm010?format=TSV&compressed=true) |
| Trade in recyclable raw materials | cei_srm020 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/cei_srm020?format=TSV&compressed=true) |
| Recyclable secondary raw materials - prices | cei_srm040 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/cei_srm040?format=TSV&compressed=true) |

---

### 📊 Competitiveness and innovation (cei_cie)
| Table Name | Eurostat Code | Direct Download |
|------------|---------------|----------------|
| Private investment and gross added value related to circular economy sectors | cei_cie012 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/cei_cie012?format=TSV&compressed=true) |
| Persons employed in circular economy sectors | cei_cie011 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/cei_cie011?format=TSV&compressed=true) |
| Patents related to recycling and secondary raw materials | cei_cie020 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/cei_cie020?format=TSV&compressed=true) |

---

### 📊 Global sustainability and resilience (cei_gsr)
| Table Name | Eurostat Code | Direct Download |
|------------|---------------|----------------|
| Consumption footprint | cei_gsr010 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/cei_gsr010?format=TSV&compressed=true) |
| Greenhouse gases emissions from production activities | cei_gsr011 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/cei_gsr011?format=TSV&compressed=true) |
| Material import dependency | cei_gsr030 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/cei_gsr030?format=TSV&compressed=true) |
| EU self-sufficiency for raw materials | cei_gsr020 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/cei_gsr020?format=TSV&compressed=true) |

---

## Environmental Tax Revenues

### 📊 Environmental taxes (t_env_eta)
| Indicator | Eurostat Code | Direct Download |
|-----------|--------------|----------------|
| Environmental tax revenues as share of total taxes | ten00141 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/ten00141?format=TSV&compressed=true) |
| Energy taxes | ten00139 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/ten00139?format=TSV&compressed=true) |
| Implicit tax rate on energy | ten00120 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/ten00120?format=TSV&compressed=true) |


---

## Digital Technology and Innovation Indicators

### ICT Usage in Households and Individuals (t_isoc_i)
| Indicator | Eurostat Code | Direct Download |
|-----------|---------------|----------------|
| Level of internet access - households | tin00134 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/tin00134?format=TSV&compressed=true) |

### Internet Use (t_isoc_iiu)
| Indicator | Eurostat Code | Direct Download |
|-----------|---------------|----------------|
| Internet use by individuals | tin00028 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/tin00028?format=TSV&compressed=true) |
| Individuals frequently using the internet | tin00092 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/tin00092?format=TSV&compressed=true) |
| Individuals regularly using the internet | tin00091 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/tin00091?format=TSV&compressed=true) |
| Individuals who have never used the internet | tin00093 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/tin00093?format=TSV&compressed=true) |
| Individuals using the internet for sending/receiving e-mails | tin00094 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/tin00094?format=TSV&compressed=true) |
| Individuals using the internet for social networks | tin00127 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/tin00127?format=TSV&compressed=true) |
| Individuals using the internet for finding information about goods/services | tin00095 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/tin00095?format=TSV&compressed=true) |
| Individuals using the internet for health-related information | tin00101 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/tin00101?format=TSV&compressed=true) |
| Individuals using the internet for internet banking | tin00099 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/tin00099?format=TSV&compressed=true) |
| Individuals using the internet for selling goods/services | tin00098 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/tin00098?format=TSV&compressed=true) |
| Individuals using the internet for job search/application | tin00102 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/tin00102?format=TSV&compressed=true) |
| Individuals using the internet for online consultations/voting | tin00129 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/tin00129?format=TSV&compressed=true) |
| Individuals using the internet for online courses | tin00103 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/tin00103?format=TSV&compressed=true) |

### E-commerce (t_isoc_iec)
| Indicator | Eurostat Code | Direct Download |
|-----------|---------------|----------------|
| Individuals using the internet for buying goods or services | tin00096 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/tin00096?format=TSV&compressed=true) |

### ICT Usage in Enterprises (t_isoc_e)
| Indicator | Eurostat Code | Direct Download |
|-----------|---------------|----------------|
| Enterprises having received orders online (≥1%) | tin00111 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/tin00111?format=TSV&compressed=true) |
| Share of enterprises' turnover on e-commerce | tin00110 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/tin00110?format=TSV&compressed=true) |
| Share of enterprises using any business software (ERP, CRM, BI) | tin00116 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/tin00116?format=TSV&compressed=true) |

### Digital Skills (t_isoc_sk)
| Indicator | Eurostat Code | Direct Download |
|-----------|---------------|----------------|
| Individuals with basic or above basic digital skills (by sex) | tepsr_sp410 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/tepsr_sp410?format=TSV&compressed=true) |

### ICT Sector (t_isoc_se)
| Indicator | Eurostat Code | Direct Download |
|-----------|---------------|----------------|
| Percentage of ICT sector in Gross Value Added | tin00074 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/tin00074?format=TSV&compressed=true) |
| Percentage of ICT sector personnel in total employment | tin00085 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/tin00085?format=TSV&compressed=true) |
| Percentage change of value added by ICT sector at current prices | tin00086 | [Download](https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/data/tin00086?format=TSV&compressed=true) |


---

## 📊 OECD Data Green/Patent-related Indicators

OECD patent verileri, çeşitli veri tabanlarını içerir. Tüm veriler **https://tinyurl.com/IP202503** üzerinden indirilebilir. İndirme sırasında şifre olarak `BpUXXqryx4gU` girilmelidir.

| Database | Reference / Citation |
|----------|--------------------|
| Triadic Patent Families (TPF) | “OECD Triadic Patent Families database, February 2025” |
| Patent Citations | “OECD Citations database, February 2025” |
| HAN database | “OECD HAN database, February 2025” |
| Patent Quality Indicators | “OECD Patent Quality Indicators database, February 2025” |
| REGPAT database | “OECD, REGPAT database, May 2025” |

**Notes:**
- Tüm veri dosyaları doğrudan indirilip klasör içerisinde saklanabilir.
- REGPAT veya TPF gibi tablolar, çevre ve geri dönüşüm ile ilgili patent analizleri için kullanılabilir.


---

## 📊 World Bank Data

| Table Name             | File Name / Notes                                                |
| ---------------------- | ---------------------------------------------------------------- |
| GDP (current USD)      | `GDP_current_USD.csv`                                            |
| GDP per capita (PPP)   | `GDP_per_capita_PPP.csv` (from `GDP_per_capita_PPP.zip`)         |
| Services Value Added   | `Services_Value_Added.csv` (from `Services_Value_Added.zip`)     |
| Employment in Services | `Employment_in_Services.csv` (from `Employment_in_Services.zip`) |
| Urban Population       | `Urban_Population.csv` (from `Urban_Population.zip`)             |

---

## Notes
Kullanım Notları

.tsv.gz dosyalarını açmak için Python’da pandas.read_csv(..., compression='gzip', sep='\t') kullanılabilir.

.csv dosyaları standart pandas.read_csv() ile açılır.

**Not:** Büyük veri dosyaları `Circular_Economy_Dataset/` klasöründe yer alır fakat bu depo içinde GIT tarafından takip edilmeyecektir. Veri dosyaları çok büyük olabileceği için repoya dahil edilmemiştir. Veri setlerini elde etmek için:

1. `1-datasets.ipynb` notebook'unu çalıştırın (internet bağlantısı gerektirir).
2. Veya README'de sağlanan "Direct Download" linklerini kullanarak ilgili `.tsv.gz` veya `.csv` dosyalarını indirin.

Lütfen veri dosyalarını repoya eklemeyin.

## 📊 EUROSTAT Veri Setleri

### Kategori: cei_pc (Döngüsel Ekonomi - Üretim ve Tüketim)
* **cei_pc020_Material_footprint** (Malzeme ayak izi)
    * **Sütunlar/Zaman:** `['freq,unit,material,indic_env,geo\\TIME_PERIOD', '2000 ', '2001 ', ..., '2024 ']`
    * **Şekil:** `(31, 26)`
* **cei_pc030_Resource_productivity** (Kaynak verimliliği)
    * **Sütunlar/Zaman:** `['freq,unit,geo\\TIME_PERIOD', '2000 ', '2001 ', ..., '2024 ']`
    * **Şekil:** `(103, 26)`
* **cei_pc034_Waste_generation_per_capita** (Kişi başına atık üretimi)
    * **Sütunlar/Zaman:** `['freq,unit,hazard,nace_r2,waste,geo\\TIME_PERIOD', '2004 ', '2006 ', ..., '2022 ']`
    * **Şekil:** `(39, 11)`
* **cei_pc032_Waste_per_GDP_unit** (GSYİH birimi başına atık)
    * **Sütunlar/Zaman:** `['freq,unit,geo\\TIME_PERIOD', '2004 ', '2006 ', ..., '2022 ']`
    * **Şekil:** `(38, 11)`
* **cei_pc031_Municipal_waste_per_capita** (Kişi başına belediye atığı)
    * **Sütunlar/Zaman:** `['freq,wst_oper,unit,geo\\TIME_PERIOD', '2000 ', '2001 ', ..., '2023 ']`
    * **Şekil:** `(38, 25)`
* **cei_pc035_Food_waste** (Gıda atığı)
    * **Sütunlar/Zaman:** `['freq,wst_oper,waste,nace_r2,unit,geo\\TIME_PERIOD', '2020 ', '2021 ', ..., '2023 ']`
    * **Şekil:** `(30, 5)`
* **cei_pc040_Packaging_waste** (Ambalaj atığı)
    * **Sütunlar/Zaman:** `['freq,waste,wst_oper,unit,geo\\TIME_PERIOD', '2000 ', '2001 ', ..., '2023 ']`
    * **Şekil:** `(31, 25)`
* **cei_pc050_Plastic_packaging_waste** (Plastik ambalaj atığı)
    * **Sütunlar/Zaman:** `['freq,waste,wst_oper,unit,geo\\TIME_PERIOD', '2000 ', '2001 ', ..., '2023 ']`
    * **Şekil:** `(31, 25)`

---

### Kategori: cei_wm (Döngüsel Ekonomi - Atık Yönetimi)
* **cei_wm011_Recycling_municipal** (Belediye atığı geri dönüşümü)
    * **Sütunlar/Zaman:** `['freq,wst_oper,unit,geo\\TIME_PERIOD', '2000 ', '2001 ', ..., '2023 ']`
    * **Şekil:** `(38, 25)`
* **cei_wm010_Recycling_all_waste** (Tüm atıkların geri dönüşümü)
    * **Sütunlar/Zaman:** `['freq,wst_oper,unit,geo\\TIME_PERIOD', '2010 ', '2012 ', ..., '2022 ']`
    * **Şekil:** `(28, 8)`
* **cei_wm020_Recycling_packaging** (Ambalaj geri dönüşümü)
    * **Sütunlar/Zaman:** `['freq,waste,unit,geo\\TIME_PERIOD', '2000 ', '2001 ', ..., '2023 ']`
    * **Şekil:** `(186, 25)`
* **cei_wm060_Recycling_WEEE** (Elektronik atıkların geri dönüşümü)
    * **Sütunlar/Zaman:** `['freq,unit,geo\\TIME_PERIOD', '2005 ', '2006 ', ..., '2023 ']`
    * **Şekil:** `(31, 20)`

---

### Kategori: cei_srm (Döngüsel Ekonomi - İkincil Hammaddeler)
* **cei_srm030_Circular_material_use** (Döngüsel malzeme kullanım oranı)
    * **Sütunlar/Zaman:** `['freq,unit,geo\\TIME_PERIOD', '2004 ', '2005 ', ..., '2023 ']`
    * **Şekil:** `(28, 21)`
* **cei_srm010_EOL_RIR** (Ömür Sonu Geri Dönüşüm Girdi Oranları)
    * **Sütunlar/Zaman:** `['freq,rawmat,unit,geo\\TIME_PERIOD', '2013 ', '2016 ', '2019 ', '2022 ']`
    * **Şekil:** `(30, 5)`
* **cei_srm020_Trade_recyclable_materials** (Geri dönüştürülebilir malzemelerin ticareti)
    * **Sütunlar/Zaman:** `['freq,rawmat,stk_flow,unit,geo\\TIME_PERIOD', '2004 ', '2005 ', ..., '2024 ']`
    * **Şekil:** `(2344, 22)`
* **cei_srm040_Recyclable_prices** (Geri dönüştürülebilir malzeme fiyatları)
    * **Sütunlar/Zaman:** `['freq,rawmat,stk_flow,unit,geo\\TIME_PERIOD', '2004 ', '2005 ', ..., '2024-12 ']`
    * **Şekil:** `(72, 94)`

---

### Kategori: cei_cie (Döngüsel Ekonomi - Rekabetçilik ve İnovasyon)
* **cei_cie012_Private_investment** (Döngüsel ekonomi sektörlerinde özel yatırımlar)
    * **Sütunlar/Zaman:** `['freq,indic_env,unit,geo\\TIME_PERIOD', '2005 ', '2006 ', ..., '2023 ']`
    * **Şekil:** `(116, 20)`
* **cei_cie011_Employment** (Döngüsel ekonomi sektörlerinde istihdam)
    * **Sütunlar/Zaman:** `['freq,indic_env,unit,geo\\TIME_PERIOD', '2005 ', '2006 ', ..., '2023 ']`
    * **Şekil:** `(58, 20)`
* **cei_cie020_Patents** (Döngüsel ekonomi ile ilgili patentler)
    * **Sütunlar/Zaman:** `['freq,cpatc,unit,geo\\TIME_PERIOD', '2000 ', '2001 ', ..., '2020 ']`
    * **Şekil:** `(65, 22)`

---

### Kategori: cei_gsr (Döngüsel Ekonomi - Küresel Sürdürülebilirlik ve Dayanıklılık)
* **cei_gsr010_Consumption_footprint** (Tüketim ayak izi)
    * **Sütunlar/Zaman:** `['freq,cons_fp,unit,geo\\TIME_PERIOD', '2010 ', '2011 ', ..., '2023 ']`
    * **Şekil:** `(1428, 15)`
* **cei_gsr011_GHG_emissions** (Sera gazı emisyonları)
    * **Sütunlar/Zaman:** `['freq,airpol,nace_r2,unit,geo\\TIME_PERIOD', '2000 ', '2001 ', ..., '2023 ']`
    * **Şekil:** `(33, 25)`
* **cei_gsr030_Material_import_dependency** (Malzeme ithalat bağımlılığı)
    * **Sütunlar/Zaman:** `['freq,material,unit,geo\\TIME_PERIOD', '2000 ', '2001 ', ..., '2024 ']`
    * **Şekil:** `(36, 26)`
* **cei_gsr020_EU_self_sufficiency** (AB'nin hammadde kendi kendine yeterliliği)
    * **Sütunlar/Zaman:** `['freq,rawmat,indic_env,unit,geo\\TIME_PERIOD', '2011 ', '2012 ', ..., '2022 ']`
    * **Şekil:** `(36, 10)`

---

### Kategori: t_isoc (Bilgi Toplumu)
* **tin00134_Level_internet_access** (Hanehalkı internet erişim seviyesi)
    * **Sütunlar/Zaman:** `['freq,unit,hhtyp,geo\\TIME_PERIOD', '2013 ', '2014 ', ..., '2024 ']`
    * **Şekil:** `(39, 13)`
* **tin00028_Internet_use_individuals** (Bireylerin internet kullanımı)
    * **Sütunlar/Zaman:** `['freq,ind_type,unit,indic_is,geo\\TIME_PERIOD', '2013 ', '2014 ', ..., '2024 ']`
    * **Şekil:** `(156, 13)`
* **tin00092_Frequent_internet_use** (Bireylerin sık internet kullanımı)
    * **Sütunlar/Zaman:** `['freq,indic_is,unit,ind_type,geo\\TIME_PERIOD', '2013 ', '2014 ', ..., '2024 ']`
    * **Şekil:** `(39, 13)`
* **tin00091_Regular_internet_use** (Bireylerin düzenli internet kullanımı)
    * **Sütunlar/Zaman:** `['freq,indic_is,unit,ind_type,geo\\TIME_PERIOD', '2013 ', '2014 ', ..., '2024 ']`
    * **Şekil:** `(39, 13)`
* **tin00093_Never_used_internet** (Bireylerin hiç internet kullanmaması)
    * **Sütunlar/Zaman:** `['freq,indic_is,unit,ind_type,geo\\TIME_PERIOD', '2013 ', '2014 ', ..., '2024 ']`
    * **Şekil:** `(39, 13)`
* **tin00094_Email_use** (Bireylerin e-posta kullanımı)
    * **Sütunlar/Zaman:** `['freq,indic_is,unit,ind_type,geo\\TIME_PERIOD', '2013 ', '2014 ', ..., '2024 ']`
    * **Şekil:** `(39, 13)`
* **tin00127_Social_networks** (Bireylerin sosyal ağ kullanımı)
    * **Sütunlar/Zaman:** `['freq,unit,indic_is,ind_type,geo\\TIME_PERIOD', '2013 ', '2014 ', ..., '2024 ']`
    * **Şekil:** `(39, 13)`
* **tin00095_Info_goods_services** (Mal ve hizmetler hakkında bilgi arama)
    * **Sütunlar/Zaman:** `['freq,indic_is,unit,ind_type,geo\\TIME_PERIOD', '2013 ', '2014 ', ..., '2024 ']`
    * **Şekil:** `(39, 13)`
* **tin00101_Health_info** (Sağlık bilgisi arama)
    * **Sütunlar/Zaman:** `['freq,indic_is,unit,ind_type,geo\\TIME_PERIOD', '2011 ', '2013 ', ..., '2024 ']`
    * **Şekil:** `(39, 13)`
* **tin00099_Internet_banking** (İnternet bankacılığı kullanımı)
    * **Sütunlar/Zaman:** `['freq,indic_is,unit,ind_type,geo\\TIME_PERIOD', '2013 ', '2014 ', ..., '2024 ']`
    * **Şekil:** `(39, 13)`
* **tin00098_Selling_goods_services** (İnternet üzerinden mal/hizmet satışı)
    * **Sütunlar/Zaman:** `['freq,indic_is,unit,ind_type,geo\\TIME_PERIOD', '2013 ', '2014 ', ..., '2024 ']`
    * **Şekil:** `(39, 13)`
* **tin00102_Job_search** (İnternet üzerinden iş arama)
    * **Sütunlar/Zaman:** `['freq,indic_is,unit,ind_type,geo\\TIME_PERIOD', '2006 ', '2007 ', ..., '2023 ']`
    * **Şekil:** `(39, 13)`
* **tin00129_Online_consultations** (Çevrimiçi danışmanlık/oylama)
    * **Sütunlar/Zaman:** `['freq,unit,indic_is,ind_type,geo\\TIME_PERIOD', '2011 ', '2013 ', ..., '2024 ']`
    * **Şekil:** `(546, 10)`
* **tin00103_Online_courses** (Çevrimiçi kurs alma)
    * **Sütunlar/Zaman:** `['freq,indic_is,unit,ind_type,geo\\TIME_PERIOD', '2010 ', '2011 ', ..., '2024 ']`
    * **Şekil:** `(39, 13)`

---

### Kategori: t_isoc_iec (Bilgi Toplumu - E-ticaret)
* **tin00096_Buying_goods_services** (İnternet üzerinden mal/hizmet satın alma)
    * **Sütunlar/Zaman:** `['freq,ind_type,indic_is,unit,geo\\TIME_PERIOD', '2020 ', '2021 ', ..., '2024 ']`
    * **Şekil:** `(78, 6)`

---

### Kategori: t_isoc_e (Bilgi Toplumu - İşletmelerde BİT)
* **tin00111_Orders_online** (İşletmelerin çevrimiçi sipariş alması)
    * **Sütunlar/Zaman:** `['freq,size_emp,nace_r2,indic_is,unit,geo\\TIME_PERIOD', '2013 ', '2014 ', ..., '2024 ']`
    * **Şekil:** `(36, 13)`
* **tin00110_Ecommerce_turnover** (İşletmelerin e-ticaret cirosu)
    * **Sütunlar/Zaman:** `['freq,size_emp,nace_r2,indic_is,unit,geo\\TIME_PERIOD', '2013 ', '2014 ', ..., '2024 ']`
    * **Şekil:** `(35, 13)`
* **tin00116_Business_software** (İşletmelerin yazılım kullanımı)
    * **Sütunlar/Zaman:** `['freq,size_emp,nace_r2,indic_is,unit,geo\\TIME_PERIOD', '2023 ']`
    * **Şekil:** `(33, 2)`

---

### Kategori: t_isoc_sk (Bilgi Toplumu - Beceriler)
* **tepsr_sp410_Digital_skills** (Bireylerin dijital becerileri)
    * **Sütunlar/Zaman:** `['freq,ind_type,indic_is,unit,geo\\TIME_PERIOD', '2021 ', '2023 ']`
    * **Şekil:** `(111, 3)`

---

### Kategori: t_isoc_se (Bilgi Toplumu - BİT Sektörü)
* **tin00074_ICT_GVA** (BİT sektörünün GSYİH içindeki payı)
    * **Sütunlar/Zaman:** `['freq,nace_r2,geo\\TIME_PERIOD', '2011 ', '2012 ', ..., '2022 ']`
    * **Şekil:** `(114, 13)`
* **tin00085_ICT_personnel** (BİT sektöründeki personel)
    * **Sütunlar/Zaman:** `['freq,nace_r2,geo\\TIME_PERIOD', '2011 ', '2012 ', ..., '2022 ']`
    * **Şekil:** `(114, 13)`
* **tin00086_ICT_value_added** (BİT sektörünün katma değeri)
    * **Sütunlar/Zaman:** `['freq,nace_r2,geo\\TIME_PERIOD', '2011 ', '2012 ', ..., '2022 ']`
    * **Şekil:** `(114, 13)`

---

### Kategori: t_env_eta (Çevre Vergileri)
* **ten00141_Environmental_tax_revenues_share_total_taxes** (Çevre vergisi gelirlerinin toplam vergiler içindeki payı)
    * **Sütunlar/Zaman:** `['freq,tax,unit,geo\\TIME_PERIOD', '2012 ', '2013 ', ..., '2023 ']`
    * **Şekil:** `(63, 13)`
* **ten00139_Energy_taxes** (Enerji vergileri)
    * **Sütunlar/Zaman:** `['freq,tax,unit,nace_r2,geo\\TIME_PERIOD', '2012 ', '2013 ', ..., '2023 ']`
    * **Şekil:** `(35, 13)`
* **ten00120_Implicit_tax_rate_energy** (Enerji üzerindeki zımni vergi oranı)
    * **Sütunlar/Zaman:** `['freq,unit,geo\\TIME_PERIOD', '2012 ', '2013 ', ..., '2023 ']`
    * **Şekil:** `(30, 13)`

---
---

## 🏦 WORLD BANK (Dünya Bankası) Veri Setleri

* **GDP_current_USD** (GSYİH, cari ABD doları)
    * **Sütunlar:** `["Country Code", "Country Name", "gdp_usd"]`
    * **Şekil:** `(325, 3)`
* **GDP_per_capita_PPP** (Kişi başına GSYİH, Satın Alma Gücü Paritesi)
    * **Sütunlar:** `['Country Name', 'Country Code', 'Indicator Name', ..., '2024']`
    * **Şekil:** `(266, 39)`
* **Services_Value_Added** (Hizmet sektörü katma değeri)
    * **Sütunlar:** `['Series Name', 'Series Code', 'Country Name', ..., '2024 [YR2024]']`
    * **Şekil:** `(63, 19)`
* **Urban_Population** (Kentsel nüfus)
    * **Sütunlar:** `['Series Name', 'Series Code', 'Country Name', ..., '2024 [YR2024]']`
    * **Şekil:** `(63, 19)`
* **Employment_in_Services** (Hizmet sektöründe istihdam)
    * **Sütunlar:** `['Series Name', 'Series Code', 'Country Name', ..., '2024 [YR2024]']`
    * **Şekil:** `(63, 19)`

---
---

## 📈 OECD Veri Setleri

### Kategori: Patent_Citations (Patent Atıfları)
* **202501_EPO_CIT_COUNTS** (EPO Atıf Sayıları)
    * **Sütunlar:** `['ep_pub_nbr', 'ep_pub_date', 'ep_appln_id', ..., 'geo']`
    * **Şekil:** `(4396508, 37)`

---

### Kategori: Patent_Citations_Detail (Patent Atıf Detayları)
* **202501_EPO_CITATIONS** (EPO Atıfları)
    * **Sütunlar:** `['Citing_pub_nbr', 'Citing_pub_date', 'Citing_app_nbr', ..., 'PCT_Route']`
    * **Şekil:** `(17065618, 15)`

---

### Kategori: Patent_Equivalents (Patent Eşdeğerleri)
* **202501_EPO_Equivalent** (EPO Eşdeğerleri)
    * **Sütunlar:** `['Cited_appln_id', 'EP_eqv_appln_id', 'Eqv_app_nbr', 'Eqv_Pub_nbr', 'Eqv_total']`
    * **Şekil:** `(4269849, 5)`

Bu listeden belirli bir veri setini analiz etmemi veya bulmamı ister misiniz?