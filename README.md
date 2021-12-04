# **Antilock Braking System in Carsim**

An anti-lock braking system (ABS) is a safety anti-skid braking system used on aircraft and on land vehicles, such as cars, motorcycles, trucks, and buses. ABS prevents longitudinal slippage from exceeding allowable limits. In this project, I built a controller for the ABS system and simulated it on Carsim.

[![Carsim](https://img.shields.io/static/v1?label=Carsim&message=v2017.1&color=96D1AA&logo=github)](https://www.carsim.com/)
[![Contributors](https://img.shields.io/github/contributors/NguyenTuChung01/AntilockBrakingSystemInCarsim)](https://github.com/NguyenTuChung01/AntilockBrakingSystemInCarsim/graphs/contributors)
[![Pull Requests](https://img.shields.io/github/issues-pr-closed/NguyenTuChung01/AntilockBrakingSystemInCarsim?color=g&logoColor=0)](https://github.com/NguyenTuChung01/AntilockBrakingSystemInCarsim/pulls)
[![Commit Activity](https://img.shields.io/github/commit-activity/m/NguyenTuChung01/AntilockBrakingSystemInCarsim)](https://github.com/NguyenTuChung01/AntilockBrakingSystemInCarsim/pulse)

[![stars](https://img.shields.io/github/stars/NguyenTuChung01/AntilockBrakingSystemInCarsim?style=social)](https://github.com/NguyenTuChung01/AntilockBrakingSystemInCarsim/stargazers)
[![forks](https://img.shields.io/github/forks/NguyenTuChung01/AntilockBrakingSystemInCarsim?style=social)](https://github.com/NguyenTuChung01/AntilockBrakingSystemInCarsim/fork)
[![Follow](https://img.shields.io/github/followers/NguyenTuChung01?style=social)](https://github.com/NguyenTuChung01)

# Table of contents
1. [Introduction](#introduction)
2. [Key Features of MOBATSim](#keyfeatures)
3. [Requirements](#requirements)
4. [Citation](#citation)
5. [Contributing to MOBATSim](#contribution)
6. [Release Notes](#releasenotes)
7. [Getting Started](#gettingstarted)

<a name="introduction"></a>
## Introduction
Hệ thống phanh chống bó cứng (ABS: Antilock Braking System) là một trong những bộ phận chính và đóng vai trò quan trọng trong việc điều khiển ô tô trên đường. Là một thiết bị phụ trợ điện tử giúp xe không bị trượt trong các điều kiện lái xe bất thường. Hệ thống này sẽ chống hiện tượng bị hãm cứng của bánh xe bằng cách điều khiển và thay đổi áp suất dầu tác dụng lên các cơ cấu phanh. Project này sẽ xây dựng On-Off Controller, Fuzzy PID Controller và đánh giá hiệu quả phanh của chúng.
