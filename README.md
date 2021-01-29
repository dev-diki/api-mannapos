# API Mannapos -> permission to ask

## Cari data berdasarkan id_store

Kalau saya mau cari berdasarkan id_store gimana contoh : "id_store": "JK15500378K", hasilnya

![alt text](https://github.com/diki-hit/api-mannapos/blob/master/data/assets/detailASK3.png?raw=true "Hasilnya...")

## Menampilkan data API Mannapos secara kesluruhan

Tampil data API secara keseluruhan

https://manna.asia/api2/report?key=ae8573e4cdd78b260699d8c328e39dc9&code=kb&code_merchant=kalbar&id=41

## Filter pencarian

Filter pencarian berdasarkan tanggal [fromDate], [toDate] dan [id_store],

https://manna.asia/api2/report?key=ae8573e4cdd78b260699d8c328e39dc9&code=kb&code_merchant=kalbar&id=41&fromDate=2021-01-01&toDate=2021-01-29&id_store=JK15500378K

![alt text](https://github.com/diki-hit/api-mannapos/blob/master/data/assets/detailask4.PNG?raw=true "Detailnya...")

hasilnya dari hasil filter tanggal di atas tersebut tampilnya nama store HIT atau store yang lain sesuai id_store yang di inputkan dari tanggal 01-01-2021 sampai 29-01-2021...

![alt text](https://github.com/diki-hit/api-mannapos/blob/master/data/assets/detailask1.PNG?raw=true "Inputan")

contoh result yang di harapkan di program

![alt text](https://github.com/diki-hit/api-mannapos/blob/master/data/assets/detailask5.PNG?raw=true "Detailnya...")

NB. hasil result tersebut baru di masukkin manual yaitu tanggal 26, seharusnya yang tampil datanya mulai dari tanggal 01-01-2021 sampai 29-01-2021

contoh data seperti ss dibawah ini...

![alt text](https://github.com/diki-hit/api-mannapos/blob/master/data/assets/detailask6.PNG?raw=true "Result Contoh")

## Contoh Table Data hasil narik dari API Mannapos

Contoh Table Data API Mannapos dari tanggal `01-01-2021 sampai 29-01-2021`

| tanggal    |      lastsync       |  id_store   | t_pajak | t_penjualan | t_faktur |
| ---------- | :-----------------: | :---------: | :-----: | :---------: | -------: |
| 2021-01-01 | 2021-01-01 23:55:24 | JK15500378K |   500   |   500000    |   500000 |
| 2021-01-02 | 2021-01-02 23:55:24 | JK15500378K |  1500   |   1500000   |  1500000 |
| 2021-01-03 | 2021-01-03 23:55:24 | JK15500378K |  2200   |   2200000   |  2200000 |
| 2021-01-04 | 2021-01-04 23:55:24 | JK15500378K |  5500   |   5500000   |  5005000 |
| 2021-01-05 | 2021-01-05 23:55:24 | JK15500378K |  6500   |   6500000   |  6500000 |
| 2021-01-06 | 2021-01-06 23:55:24 | JK15500378K |  8000   |   8000000   |  8000000 |
| 2021-01-07 | 2021-01-07 23:55:24 | JK15500378K |  4000   |   4000000   |  4000000 |
| 2021-01-08 | 2021-01-08 23:55:24 | JK15500378K |  5000   |   5000000   |  5000000 |
| 2021-01-09 | 2021-01-09 23:55:24 | JK15500378K |  8500   |   8500000   |  8500000 |
| 2021-01-10 | 2021-01-10 23:55:24 | JK15500378K |  9000   |   9000000   |  9000000 |
| 2021-01-11 | 2021-01-11 23:55:24 | JK15500378K |  7500   |   7500000   |  7500000 |
| 2021-01-12 | 2021-01-12 23:55:24 | JK15500378K |  7500   |   7500000   |  7500000 |
| 2021-01-13 | 2021-01-13 23:55:24 | JK15500378K |  8500   |   8500000   |  8500000 |
| 2021-01-14 | 2021-01-14 23:55:24 | JK15500378K |  6500   |   6500000   |  6500000 |
| 2021-01-15 | 2021-01-15 23:55:24 | JK15500378K |  7000   |   7000000   |  7000000 |
| 2021-01-16 | 2021-01-16 23:55:24 | JK15500378K |  8500   |   8500000   |  8500000 |
| 2021-01-17 | 2021-01-17 23:55:24 | JK15500378K |  7900   |   7900000   |  7900000 |
| 2021-01-18 | 2021-01-18 23:55:24 | JK15500378K |  5500   |   5500000   |  5500000 |
| 2021-01-19 | 2021-01-19 23:55:24 | JK15500378K |  6500   |   6500000   |  6500000 |
| 2021-01-20 | 2021-01-20 23:55:24 | JK15500378K |  5500   |   5500000   |  5500000 |
| 2021-01-21 | 2021-01-21 23:55:24 | JK15500378K |  4000   |   4000000   |  4000000 |
| 2021-01-22 | 2021-01-22 23:55:24 | JK15500378K |  6500   |   6500000   |  6500000 |
| 2021-01-23 | 2021-01-23 23:55:24 | JK15500378K |  7500   |   7500000   |  7500000 |
| 2021-01-24 | 2021-01-24 23:55:24 | JK15500378K |  8000   |   8000000   |  8000000 |
| 2021-01-25 | 2021-01-25 23:55:24 | JK15500378K |  5500   |   5500000   |  5500000 |
| 2021-01-26 | 2021-01-26 23:55:24 | JK15500378K |  6500   |   6500000   |  6500000 |
| 2021-01-27 | 2021-01-27 23:55:24 | JK15500378K |  5500   |   5500000   |  5500000 |
| 2021-01-28 | 2021-01-28 23:55:24 | JK15500378K |  8000   |   8000000   |  8000000 |
| 2021-01-29 | 2021-01-29 23:55:24 | JK15500378K |  7000   |   7000000   |  7000000 |

ini untuk bulan januari dari tanggal 1 sampai tanggal 29 contohnya, seterusnya bulan februari, maret, april, mei.. dst juga ada hampir sama... tergatung data realnya seperti apa...

## NB

tambahin parameter atau key

- `created_at[transaction_date]` dan `updated_at`
- `is_lunas` = true ["is_lunas": true]

untuk metode pembayaran "is_lunas" jika pembayaran secara "TUNAI" true, dan jika tidak bayar secara tunai ...contohnya nyicil

id_store jadi acuan untuk get berdasarkan id atau nampilkan data cuma 1 data...

result API :

```
{
"error": "false",
"data": [
            {
                "id": "121597",
                "id_store": "JK15500378K",
                "transaction_code": "OD488210126040038",
                "transaction_date": "2021-01-01T14:01:51+07:00",
                "updated_at" : "2021-01-01T14:01:51+07:00",
                "is_lunas": true,
                "total_price_product": "3000",
                "total_tax": "500",
                "service_charge": "0",
                "total_price_sales": "5000",
                "total_quantity": "1.00",
                "grand_total": "5500",
                "metode": "TUNAI",
                "store": "HIT",
                "city": "Kota Pontianak",
                "business": "Jasa Layanan",
                "state": "Kalimantan Barat",
                "detail_product":
                 [
                    {
                        "product_sku": "1234",
                        "product": "Kecap",
                        "category": "Hotel",
                        "price_product": "3000",
                        "price_sales": "5000",
                        "quantity": "1.00"
                    }
                ]
            }
        ]
}
```

## License

Released under the terms of the MIT license.
