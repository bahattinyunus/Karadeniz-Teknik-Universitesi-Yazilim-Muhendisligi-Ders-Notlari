name: 📚 Ders Notu / Kaynak Talebi
description: Eksik olan bir ders veya kaynak için talep oluşturun.
title: "[KAYNAK TALEBİ]: <Ders Adı>"
labels: ["kaynak talebi", "eksik döküman"]
body:
  - type: markdown
    attributes:
      value: |
        KTÜ Yazılım Mühendisliği gelişimi için katkınıza teşekkürler!
  - type: input
    id: course-name
    attributes:
      label: Dersin Adı
      placeholder: Örn: Nesne Yönelimli Programlama
    validations:
      required: true
  - type: dropdown
    id: year
    attributes:
      label: Sınıf
      options:
        - 1. Sınıf
        - 2. Sınıf
        - 3. Sınıf
        - 4. Sınıf
    validations:
      required: true
  - type: textarea
    id: details
    attributes:
      label: Talep Detayı
      description: Eksik olan döküman tipi (vize, final, ders notu vb.) nedir?
      placeholder: Örn: 2021 yılı vize soruları eksik.
    validations:
      required: true
