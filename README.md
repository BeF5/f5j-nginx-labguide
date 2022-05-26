nginx_lab_guide
# 目次
- [目次](#目次)
- [目的](#目的)
- [注意点](#注意点)
- [Trial license 取得方法](#trial-license-取得方法)
- [ラボガイド](#ラボガイド)
  - [これから始めるNGINX技術解説 基本編](#これから始めるnginx技術解説-基本編)
  - [これから始めるNGINX技術解説 セキュリティ編 `作成予定`](#これから始めるnginx技術解説-セキュリティ編-作成予定)
  - [NGINX Plus Container 基礎](#nginx-plus-container-基礎)
  - [NGINX Plus Container NGINX App Protect](#nginx-plus-container-nginx-app-protect)
  - [NGINX Plus Container NGINX App Protect & AWAF](#nginx-plus-container-nginx-app-protect--awaf)
  - [NGINX Controller Application Security (ADC / AppSec)](#nginx-controller-application-security-adc--appsec)
  - [NGINX Plus Kubernets Ingress Controller](#nginx-plus-kubernets-ingress-controller)
  - [NGINX Plus Service Mesh `作成予定`](#nginx-plus-service-mesh-作成予定)

# 目的
- こちらのページではNGINX Productの各種ラボガイドの情報をまとめております
- 適宜必要となるラボガイド、ラボ環境をご利用いただください

# 注意点
- 資料は適宜更新しています。誤りがあった場合ご指摘ください
- ラボガイドの内容がラボ環境で動作するか適宜確認ください
- 各種ライセンスが必要な場合、別途トライアルライセンスを手配ください

# Trial license 取得方法
https://f5j-nginx-plus-trial.readthedocs.io/en/latest/

# ラボガイド

## これから始めるNGINX技術解説 基本編

|項目||
| - | - | 
|主な内容|NGINX Plus基本動作、listen / server_name directive、Proxy、LB、TLS|
|Guide| https://f5j-nginx-plus-lab1.readthedocs.io/en/latest/index.html |
|UDF Template| PartnerTraining_2021_BASIC_JP  |

## これから始めるNGINX技術解説 セキュリティ編 `作成予定`

|項目||
| - | - | 
|主な内容|Rate Limit、OIDC、NGINX App Protect WAF / DoS|
|Guide| - |
|UDF Template| PartnerTraining_2021_BASIC_JP  |

## NGINX Plus Container 基礎
 
|項目||
| - | - | 
|主な内容|コンテナの利用方法、NGINX Plusコンテナイメージの作成方法|
|Guide| https://github.com/hiropo20/partner_nap_workshop/tree/main/no2 |
|UDF Template| PartnerTraining_2021_Microservices_nap_JP  |

## NGINX Plus Container NGINX App Protect
 
|項目||
| - | - | 
|主な内容|NGINX App Protect コンテナ作成方法、NGINX App Protect動作確認|
|Guide| https://github.com/hiropo20/partner_nap_workshop/tree/main/no3 |
|UDF Template| PartnerTraining_2021_Microservices_nap_JP  |

## NGINX Plus Container NGINX App Protect & AWAF
 
|項目||
| - | - | 
|主な内容|NGINX App Protect動作確認、NGINX App Protect Signatureの更新、AWAFのPolicyのコンバート|
|Guide| https://github.com/hiropo20/partner_nap_workshop/tree/main/no4 |
|UDF Template| PartnerTraining_2021_Microservices_nap_JP  |

## NGINX Controller Application Security (ADC / AppSec)

Cloud Docsの書式で、すでにUDF template内のLab Guideから参照できるよう変更済み

|項目||
| - | - | 
|主な内容|NGINX Controller ADCの基本、各種設定オブジェクトの解説、ADC設定、WAF設定、および各種モニター機能の確認|
|Guide| https://f5j-nginx-controller-lab.readthedocs.io/en/latest/index.html |
|UDF Template| NGINX Controller: Application Delivery and Security (Lab)_JP  |


## NGINX Plus Kubernets Ingress Controller 

|項目||
| - | - | 
|主な内容|NGINX Ingress Controllerのデプロイ、VS/VSR、OIDC、NGINX App Protect|
|Guide| https://f5j-nginx-ingress-controller-lab1.readthedocs.io/en/v2.1.0-r3/ |
|UDF Template| NGINX: Kubernetes_Lab_JP |

その他参考情報：https://thinkit.co.jp/article/18771

## NGINX Plus Service Mesh `作成予定`

|項目||
| - | - | 
|主な内容|基本的なサービスメッシュのデプロイ方法、その他設定方法|
|Guide|https://f5j-nginx-service-mesh.readthedocs.io/en/latest/index.html|
|UDF Template| NGINX: Kubernetes_Lab_JP |
