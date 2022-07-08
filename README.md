## TechStack
ENSP

## General Info
Repo ini merupakan tugas dari mata kuliah Computer Network Management di semester 6. Materi yang diujikan adalah melakukan konfigurasi OSPF, RIP, dan BGP. Goals dari tugas ini adalah Router 1 dan 7 bisa menyebarkan informasi massing-masing network ke seluruh router.

## Topologi

- Topologi ini terdiri dari 7 router 
- Router 1, 2, dan 3 masuk ke dalam BGP123 (menggunakan routing protocol RIP)
- Router 4, 5, dan 6 masuk ke dalam BGP456 (menggunakan routing protocol OSPF)
- Router 7 masuk dalam BGP7
- as-number yang sama neighborship dengan menggunakan IP Loopback, sedangkan as-number yang berbeda neighborship dengan menggunakan IP Physical
- Router 1 dapat menyebarkan informasi network 10.10.10.10 ke seluruh router
- Router 7 dapat menyebarkan informasi network 70.70.70.70 ke seluruh router
