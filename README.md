nginx_lab_guide
# 目次
- [目次](#目次)
- [目的](#目的)
- [注意点](#注意点)
- [Trial license 取得方法](#trial-license-取得方法)
- [ラボガイド](#ラボガイド)
  - [NGINX技術解説 基本編](#nginx技術解説-基本編)
  - [NGINX技術解説 応用編](#nginx技術解説-応用編)
  - [これから始めるNGINX技術解説 セキュリティ編 `NAP WAFのみ`](#これから始めるnginx技術解説-セキュリティ編-nap-wafのみ)
  - [NGINX Plus Ansible](#nginx-plus-ansible)
  - [NGINX Plus Performance](#nginx-plus-performance)
  - [NGINX Plus Kubernets Ingress Controller](#nginx-plus-kubernets-ingress-controller)
  - [NGINX Plus Service Mesh](#nginx-plus-service-mesh)
  - [NGINX Kubernetes Observability](#nginx-kubernetes-observability)
  - [NGINX Kubernetes API Gateway](#nginx-kubernetes-api-gateway)
  - [NGINX Plus Container 基礎](#nginx-plus-container-基礎)
  - [NGINX Plus Container NGINX App Protect](#nginx-plus-container-nginx-app-protect)
  - [NGINX Plus Container NGINX App Protect & AWAF](#nginx-plus-container-nginx-app-protect--awaf)

# 目的
- こちらのページではNGINX Productの各種ラボガイドの情報をまとめております
- 適宜必要となるラボガイド、ラボ環境をご利用ください

# 注意点
- 資料は適宜更新しています。誤りがあった場合ご指摘ください
- ラボガイドの内容がラボ環境で動作するか適宜確認ください
- 各種ライセンスが必要な場合、別途トライアルライセンスを手配ください

# Trial license 取得方法
https://f5j-nginx-plus-trial.readthedocs.io/en/latest/

# ラボガイド

## NGINX技術解説 基本編

|項目||
| - | - | 
|主な内容|NGINX Plus基本動作、listen / server_name directive、Proxy、LB、TLS|
|Guide| https://f5j-nginx-plus-lab1.readthedocs.io/en/latest/index.html |
|UDF Template| NGINX: Basic_Lab_JP  |

## NGINX技術解説 応用編

|項目||
| - | - | 
|主な内容|NGINX Plusによる 流量制限、認証、LB、冗長構成、ステータス同期|
|Guide| https://f5j-nginx-plus-lab2.readthedocs.io/en/latest/index.html |
|UDF Template| NGINX: Basic_Lab_JP  |


## これから始めるNGINX技術解説 セキュリティ編 `NAP WAFのみ`

|項目||
| - | - | 
|主な内容|NGINX App Protect WAF |
|Guide| https://f5j-nginx-plus-lab2-security.readthedocs.io/en/latest/ |
|UDF Template| NGINX: Basic_Lab_JP  |
- 今後 NAP DoS追加します

## NGINX Instance Manager 

|項目||
| - | - | 
|主な内容|NGINX Instance Manager の各種インストール方法や、基本的な機能の解説 |
|Guide| https://f5j-nginx-nim.readthedocs.io/en/latest/ |
|UDF Template| NGINX: Kubernetes_Lab_JP |

## NGINX Plus Ansible
 
|項目||
| - | - | 
|主な内容|Ansibleを利用してNGINX Plus/NAP WAF/NAP Dosのインストール・アンインストール、インストール時の設定追加|
|Guide| https://f5j-nginx-ansible.readthedocs.io/ |
|UDF Template| NGINX: Basic_Lab_JP  |

## NGINX Plus Performance
 
|項目||
| - | - | 
|主な内容|パフォーマンステストによる NGINX Plus/NGINX Unit/Apacheの比較、NGINX Plusのパフォーマンスチューニング|
|Guide| https://f5j-nginx-performance.readthedocs.io/ |
|UDF Template| NGINX: Performance_Lab_JP  |

## NGINX Plus Kubernets Ingress Controller 

|項目||
| - | - | 
|主な内容|NGINX Ingress Controllerのデプロイ、VS/VSR、OIDC、NGINX App Protect|
|Guide| https://f5j-nginx-ingress-controller-lab1.readthedocs.io/en/v2.1.0-r3/ |
|UDF Template| NGINX: Kubernetes_Lab_JP |

その他参考情報：https://thinkit.co.jp/article/18771

## NGINX Plus Service Mesh 

|項目||
| - | - | 
|主な内容|基本的なサービスメッシュのデプロイ方法、その他設定方法|
|Guide|https://f5j-nginx-service-mesh.readthedocs.io/en/latest/index.html|
|UDF Template| NGINX: Kubernetes_Lab_JP |

## NGINX Kubernetes Observability  

|項目||
| - | - | 
|主な内容|NGINX Plus Ingress Controller + NGINX Service Mesh をデプロイした環境でGrafana、Prometheus、Grafana Loki、Jaegerを使ってステータスを確認する方法のまとめ、HELMの使い方の習得|
|Guide|https://f5j-nginx-k8s-observability.readthedocs.io/en/latest/index.html|
|UDF Template| NGINX: Kubernetes_Lab_JP |

## NGINX Kubernetes API Gateway 

|項目||
| - | - | 
|主な内容|NIC/NSMを使って、Kubernetes環境におけるAPI Gatewayのユースケースに対応する方法。設定サンプルと動作確認。|
|Guide|https://f5j-nginx-k8s-apigw.readthedocs.io/|
|UDF Template| NGINX: Kubernetes_Lab_JP |

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
