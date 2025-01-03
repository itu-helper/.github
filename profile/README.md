<div align="center">

# **ITU Helper**

</div>
    
<div align="left">
    <img src="https://raw.githubusercontent.com/itu-helper/home/main/images/logo.png" align="right"
     alt="ITU Helper Logo" width="180" height="180">
</div>
<div align="center">

_İTÜ'lüler için İTÜ'lülerden_

_ITU Helper_ İstanbul Teknik Üniversitesi öğrencilerine yardım etmek amacıyla ön şart görselleştirme, ders planı oluşturma ve resmi İTÜ sitelerini birleştirme gibi hizmetler sağlayan bir açık kaynaklı websitesidir.

_ITU Helper_'a [_bu adresten_](https://itu-helper.github.io/home/) ulaşabilirsiniz.

</div>

</br>
</br>
</br>

## Veri Güncellenme Durumu

<div align="center">

[![Refresh Lessons](https://github.com/itu-helper/data-updater/actions/workflows/refresh_lessons.yml/badge.svg)](https://github.com/itu-helper/data-updater/actions/workflows/refresh_lessons.yml)
[![Refresh Course Plans](https://github.com/itu-helper/data-updater/actions/workflows/refresh_course_plans.yml/badge.svg)](https://github.com/itu-helper/data-updater/actions/workflows/refresh_course_plans.yml)
[![Refresh Courses](https://github.com/itu-helper/data-updater/actions/workflows/refresh_courses.yml/badge.svg)](https://github.com/itu-helper/data-updater/actions/workflows/refresh_courses.yml)
[![Refresh Misc](https://github.com/itu-helper/data-updater/actions/workflows/refresh_misc.yml/badge.svg)](https://github.com/itu-helper/data-updater/actions/workflows/refresh_misc.yml)

</div>

## Repository Yapısı

### [1. itu-helper/data](https://github.com/itu-helper/data)

![GitHub Repo stars](https://img.shields.io/github/stars/itu-helper/data?style=flat)
![GitHub License](https://img.shields.io/github/license/itu-helper/data?style=flat)
![GitHub Repo size](https://img.shields.io/github/repo-size/itu-helper/data?style=flat)
![GitHub last commit](https://img.shields.io/github/last-commit/itu-helper/data)

Verilerin tutulduğu _repository_. [itu-helper/data-updater](https://github.com/itu-helper/data-updater) üzerinden güncellenen veriler, bu _repository_ üzerinde, `.txt` formatında saklanır.

### [2. itu-helper/data-updater](https://github.com/itu-helper/data-updater)

![GitHub Repo stars](https://img.shields.io/github/stars/itu-helper/data-updater?style=flat)
![GitHub License](https://img.shields.io/github/license/itu-helper/data-updater?style=flat)
![GitHub Repo size](https://img.shields.io/github/repo-size/itu-helper/data-updater?style=flat)
![GitHub last commit](https://img.shields.io/github/last-commit/itu-helper/data-updater)

Verilerin güncellenmesini sağlayan _Python_ kodları ve bu kodların otomatik olarak çalıştıran _GitHub Actions_ workflow'larını tutan _repository_.

### [3. itu-helper/sdk](https://github.com/itu-helper/sdk)

![GitHub Repo stars](https://img.shields.io/github/stars/itu-helper/sdk?style=flat)
![GitHub License](https://img.shields.io/github/license/itu-helper/sdk?style=flat)
![GitHub Repo size](https://img.shields.io/github/repo-size/itu-helper/sdk?style=flat)
![GitHub last commit](https://img.shields.io/github/last-commit/itu-helper/sdk)

ITU helper verilerine ([itu-helper/data](https://github.com/itu-helper/data)) erişilmesi ve işlenmesini kolaylaştırmak adına oluşturulmuş, SDK'lerden (Software Development Kit) oluşan bir _mono repository_.

### [4. itu-helper/home](https://github.com/itu-helper/home)

![GitHub Repo stars](https://img.shields.io/github/stars/itu-helper/home?style=flat)
![GitHub License](https://img.shields.io/github/license/itu-helper/home?style=flat)
![GitHub Repo size](https://img.shields.io/github/repo-size/itu-helper/home?style=flat)
![GitHub last commit](https://img.shields.io/github/last-commit/itu-helper/home)

_ITU Helper_ sitesinin [ana sayfası](https://itu-helper.github.io/home/). Bu sayfa üzerinden, hem İTÜ'nün resmi sitelerine, hem çeşitli öğrenci yapımı sitelere ve son olarak da _ITU Helper_'ın diğer sitelerine bağlantıları sağlanmakta.

### [5. itu-helper/prereq-scheduler](https://github.com/itu-helper/prereq-scheduler)

![GitHub Repo stars](https://img.shields.io/github/stars/itu-helper/prereq-scheduler?style=flat)
![GitHub License](https://img.shields.io/github/license/itu-helper/prereq-scheduler?style=flat)
![GitHub Repo size](https://img.shields.io/github/repo-size/itu-helper/prereq-scheduler?style=flat)
![GitHub last commit](https://img.shields.io/github/last-commit/itu-helper/prereq-scheduler)

_ITU Helper_'ın [_JavaScript SDK_](https://github.com/itu-helper/sdk)'sini kullanarak, derslerin önşartlarını görselleştiren bir [sayfa](https://github.com/itu-helper/prereq-scheduler).
