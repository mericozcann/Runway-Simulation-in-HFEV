# Runway Simulation for Energy Consumption Analysis in Hydrogen Fueled Electric Vehicle
## Overview
### This project analyzes energy consumption across different segments of a track resembling Shell Eco-marathon routes. The simulation includes key factors such as slope, turn angle, vehicle dynamics, and speed profiles to optimize energy efficiency.

## Key Features

Track Analysis: Simulates a track divided into segments, each with specific slope percentages, lengths, and turn angles.

Vehicle Parameters: Models vehicle characteristics, including weight, drag coefficient, rolling resistance, and battery capacity.

Energy Breakdown: Computes energy consumed due to incline, rolling resistance, and aerodynamic drag for each segment.

Speed Profiles: Compares energy consumption for slow, medium, and fast speed scenarios.

Visualization: Provides detailed graphical representations of energy consumption trends.

## Formulas Used
### Total Force: 𝐹 total = 𝐹 incline + 𝐹 rolling + 𝐹 aerodynamic 
 
### Energy Consumption: 𝐸 = 𝐹 total X length / efficiency
​
## Requirements

### Programming Language: 
Python 3.x

### Libraries:

pandas: Data handling

matplotlib: Data visualization

numpy: Mathematical operations

ipywidgets: Interactive widgets (optional)

## Usage

Input: Track data and vehicle parameters.

Output: Energy consumption by segment, total energy used, and graphical analysis.

## Potential Applications

Automotive Design: Optimizing vehicle efficiency for competitive events like Shell Eco-marathon.

Educational Tools: Demonstrating real-world energy principles.

Simulation Platforms: Extending the model to include additional dynamics.


# Hidrojen Yakıtlı Elektrikli Araçta Enerji Tüketim Analizi için Pist Simülasyonu
## Genel Bakış
### Bu proje, Shell Eco-marathon tarzı parkurlardaki farklı segmentlerde enerji tüketimini analiz etmektedir. Simülasyon, eğim, dönüş açısı, araç dinamikleri ve hız profilleri gibi önemli faktörleri içermekte ve enerji verimliliğini optimize etmeyi hedeflemektedir.

## Ana Özellikler

Parkur Analizi: Eğim yüzdesi, uzunluk ve dönüş açısı gibi belirli özelliklere sahip segmentlere ayrılmış bir parkur simülasyonu.

Araç Parametreleri: Araç ağırlığı, aerodinamik sürtünme katsayısı, yuvarlanma direnci ve batarya kapasitesini modelleme.

Enerji Dağılımı: Her segment için eğim, yuvarlanma direnci ve aerodinamik sürtünme nedeniyle tüketilen enerjinin hesaplanması.

Hız Profilleri: Yavaş, orta ve hızlı hız senaryolarına göre enerji tüketiminin karşılaştırılması.

Görselleştirme: Enerji tüketimi eğilimlerini detaylı grafiklerle sunma.

## Kullanılan Formüller

### Toplam Kuvvet: 𝐹 toplam = 𝐹 eğim + 𝐹 yuvarlanma + 𝐹 aerodinamik

### Enerji Tüketimi: 𝐸 = 𝐹 toplam X uzunluk / verimlilik 
 
## Gereksinimler
### Programlama Dili: 
Python 3.x

### Kütüphaneler:

pandas: Veri işleme

matplotlib: Veri görselleştirme

numpy: Matematiksel işlemler

ipywidgets: Etkileşimli widgetlar (isteğe bağlı) 

## Kullanım

Girdi: Parkur verileri ve araç parametreleri.

Çıktı: Segmentlere göre enerji tüketimi, toplam enerji kullanımı ve grafiksel analizler.

## Potansiyel Uygulamalar

Otomotiv Tasarımı: Shell Eco-marathon gibi yarışmalar için araç verimliliğini optimize etmek.

Eğitim Araçları: Gerçek dünya enerji prensiplerini göstermek.

Simülasyon Platformları: Modele ek dinamikler dahil ederek genişletmek.
