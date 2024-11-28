# Config Server

[Github](https://github.com/dccelik/Config-Server)
---

## Config Server
- Mikroservislerin konfigürasyonlarının merkezi bir yerde yönetmek için kullandığımız bir yapıdır.
- Bu config-server yapısı : Merkezi bir alan için de Config Server üzerinden yapılandırmaları dinmaik olarak alır.


## Sprint Cloud(Config Client)
- Spring Cloud serverdan konfigürasyonları almak için kullanılan istemcidir.
- Mikroservisler genellikle Config Client olarak yapılandırılır.
- Config Client Config Servera bağlanır ve merkezi olarak yönetilen konfigürasyon dosyalarını alır.
- Eğer uygulamamız merkezi olarak yönetilen konfigürasyonları almak için Spring Cloud servera bağlanacaksa biz Config Client ekliyoruz.

## Sprint Cloud(Config Server)
- Merkezi bir konfigürasyon yönetim sunuculuğunu yapar. 
- Bir ve ya daha fazla mikroservislerin konfigürasyon dosyalarını merkezi bir yerde sunar