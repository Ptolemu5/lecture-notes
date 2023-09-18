---
title: "Pusat Informasi dan Pengolahan Data"
date: 2023-09-18T10:22:00+07:00
authors: ['Billah']
tags: ['xx1000']
draft: false
math: true
url: "0048"
---
{{< toc >}}

Selamat Datang! Ini merupakan web akses terbatas yang hanya bisa
diakses oleh para agen intelijen Badan Intelijen Negara. Terdapat beberapa
fitur yang dapat digunakan oleh para agen untuk mengumpulkan informasi, mengolah data
dan membuat laporan yang sesuai dengan kebutuhan.

## LaTex
Digunakan untuk menghitung peluang kemungkinan terjadinya sesuatu

P(A) = n(A)/n(S)

## Mermaid
{{< mermaid >}}
flowchart LR
    B --> I --> P --> O --> E
    B(("Unsur Utama Keterangan"))
    I(("Perencanaan"))
    P(("Pengumpulan Bahan Keterangan"))
    O(("Pengolahan"))
    E(("Distribusi"))
{{< /mermaid >}}

## Chart JS
Grafik informasi yang dapat dikumpulkan dari tiap - tiap bidang per pekanan.

{{< chart 90 200 >}}
{
    type: 'bar',
    data: {
        labels: ['Ekonomi', 'Politik', 'Internasional', 'Hiburan', 'Teknologi', 'Sosial'],
        datasets: [{
            label: 'Bar Chart',
            data: [12, 19, 18, 14, 20, 11],
            backgroundColor: [
                'rgba(255,99,132,0.2)',
                'rgba(54,162,235,0.2)',
                'rgba(255,206,86,0.2)',
                'rgba(75,192,192,0.2)',
                'rgba(153,102,255,0.2)',
                'rgba(255,159,64,0.2)'
            ],
            borderColor: [
                'rgba(255,99,132,1)',
                'rgba(54,162,235,1)',
                'rgba(255,206,86,1)',
                'rgba(75,192,192,1)',
                'rgba(153,102,255,1)',
                'rgba(255,159,64,1)'
            ],
            borderWidth: 1
        }]
    },
    options: {
        maintainAspectRatio: false,
        scales: {
            yAxes: [{
                ticks: {
                    beginAtZero: true
                }
            }]
        }
    }
}
{{< /chart >}}

## Perkejadian
No. | Tanggal | Kejadian
:-: | :-:| :-
1| 17/09 | Harga Dollar terhadap Rupiah melemah
2| 15/09 | Terjadinya bencana alam di Maroko
3| 10/09 | Presiden Republik Indonesia siap menyambut tamu
4| 08/09 | Pasukan Khusus dikerahkan dalam pengamanan KTT Asean

## Youtube
{{< youtube K0eY7IdEnsw >}}

## Quote Paragraph
Jangan pernah berhenti berharap, karena dengan harapan kita bisa terus hidup

## Tugas
Dalam melaksanakan fungsi intelijen yakni LIDPAMGAL, intelijen memiliki tugas - tugas
+ Penyelidikan :
 - Kegiatan yang dilakukan untuk mengumpulkan informasi
+ Pengamanan :
 - Kegiatan yang dilakukan untuk mengamankan personil maupun materil
+ Penggalangan :
 - Kegiatan yang dilakukan untuk mempengaruhi target agar bertindak sesuai dengan yang diarahkan

## Image
![](https://runsystem.id/wp-content/uploads/2022/03/medium-shot-man-with-hoodie-holding-laptop-e1646646997479.jpg)

## Link 
[Google](https://www.google.com)

[Github](https://www.github.com)

## animation with svg
{{< html >}}
<svg width="200" height="200" xmlns="http://www.w3.org/2000/svg">
  <!-- Rectangle with animation -->
  <rect x="10" y="10" width="50" height="50" fill="blue">
    <animate attributeName="width" from="50" to="150" dur="2s" begin="0s" repeatCount="indefinite" />
    <animate attributeName="height" from="50" to="150" dur="2s" begin="0s" repeatCount="indefinite" />
    <animate attributeName="fill" values="blue;red;green;blue" dur="4s" begin="0s" repeatCount="indefinite" />
  </rect>
</svg>
{{< /html >}}

## List
Item
 - Satu
 - Dua

Item Lain

Item Lain Lagi


## complex svg
{{< html >}}
<svg width="400" height="300" xmlns="http://www.w3.org/2000/svg">
  <!-- Rectangle with gradients -->
  <defs>
    <linearGradient id="grad1" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:rgb(255,0,0);stop-opacity:1" />
      <stop offset="100%" style="stop-color:rgb(0,0,255);stop-opacity:1" />
    </linearGradient>
  </defs>

  <rect x="20" y="20" width="200" height="100" fill="url(#grad1)" stroke="green" stroke-width="3" />

  <!-- Text element -->
  <text x="30" y="160" font-family="Arial" font-size="24" fill="black">Complex SVG</text>

  <!-- Circle with animation -->
  <circle cx="250" cy="150" r="20" fill="orange">
    <animate attributeName="r" from="20" to="50" dur="2s" begin="0s" repeatCount="indefinite" />
  </circle>
</svg>
{{< /html >}}



