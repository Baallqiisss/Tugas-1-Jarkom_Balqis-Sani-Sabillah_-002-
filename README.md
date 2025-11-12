# Tugas-1-Jarkom_Balqis-Sani-Sabillah_002

### VLSM 

### TOPOLOGI 

<img width="1853" height="803" alt="Screenshot 2025-11-12 102853" src="https://github.com/user-attachments/assets/94d37686-7e45-4aad-afa3-b7ed07f7eae0" />


|             Subnet               | Jumlah IP + 1 (alamat gateaway router) | Netmask | 
|:--------------------------------:|----------------------------------------|:-------:|
| Bidang Guru & Tendik             | 96 host                                | /25     | 
| Bidang Kurikulum                 | 221 host                               | /24     | 
| Bidang Sarana Prasarana          | 46 host                                | /26     |  
| Bidang Pengawas Sekolah (Branch) | 19 host                                | /27     |   
| Server & Admin                   |  7 host                                | /28     |   
| Sekretariat                      | 381 host                               | /23     |   
| A - E ( Router )                 | 6 host                                 | /29     |   
| F (Tunnel)                       | 2 host                                 | /30     |   
| TOTAL                            | 778 host                               | /22     |   

IP PREFIX = 10.42.0.0/22, /22 berarti ada 1024 host ( 0 - 1023) ,			
Jadi rentang besar awalnya dari 10.42.0.0 sampai 10.42.3.255		

modulus : 5027241002 % 256 = 42			


### POHON PEMBAGIAN 
<img width="496" height="604" alt="Screenshot 2025-11-12 095829" src="https://github.com/user-attachments/assets/b4cd7132-3b38-46d5-aa0c-32f832b228c5" />

### TABEL HASIL VLSM

|       Bidang Guru & Tendik       |      RANGE BLOK      |  10.42.3.0 – 10.42.3.127  |
|:--------------------------------:|:--------------------:|:-------------------------:|
|                                  |          NID         |         10.42.3.0         |   
|                                  |        NETMASK       |      255.255.255.128      |   
|                                  |   BROADCAST ADDRESS  |        10.42.3.127        |   
|                                  |    AVAILABLE HOST    |            126            |   
|                                  | RANGE AVAILABLE HOST |  10.42.3.1 – 10.42.3.126  |   
|                                  |                      |                           |   
|         Bidang Kurikulum         |      RANGE BLOK      |  10.42.2.0 – 10.42.2.255  |   
|                                  |          NID         |         10.42.2.0         |   
|                                  |        NETMASK       |       255.255.255.0       |   
|                                  |   BROADCAST ADDRESS  |        10.42.2.255        |   
|                                  |    AVAILABLE HOST    |            254            |   
|                                  | RANGE AVAILABLE HOST |  10.42.2.1 – 10.42.2.254  |   
|                                  |                      |                           |   
|      Bidang Sarana Prasarana     |      RANGE BLOK      | 10.42.3.128 – 10.42.3.191 |   
|                                  |          NID         |        10.42.3.128        |   
|                                  |        NETMASK       |      255.255.255.192      |   
|                                  |   BROADCAST ADDRESS  |        10.42.3.191        |   
|                                  |    AVAILABLE HOST    |             62            |   
|                                  | RANGE AVAILABLE HOST | 10.42.3.129 – 10.42.3.190 |   
|                                  |                      |                           |   
| Bidang Pengawas Sekolah (Branch) |      RANGE BLOK      | 10.42.3.192 – 10.42.3.223 |  
|                                  |          NID         |        10.42.3.192        |  
|                                  |        NETMASK       |      255.255.255.224      |   
|                                  |   BROADCAST ADDRESS  |        10.42.3.223        |   
|                                  |    AVAILABLE HOST    |             30            |   
|                                  | RANGE AVAILABLE HOST | 10.42.3.193 – 10.42.3.222 |   
|                                  |                      |                           |   
|          Server & Admin          |      RANGE BLOK      | 10.42.3.224 – 10.42.3.239 |   
|                                  |          NID         |        10.42.3.224        |   
|                                  |        NETMASK       |      255.255.255.240      |   
|                                  |   BROADCAST ADDRESS  |        10.42.3.239        |   
|                                  |    AVAILABLE HOST    |             14            |   
|                                  | RANGE AVAILABLE HOST | 10.42.3.225 – 10.42.3.238 |   
|                                  |                      |                           |   
|            Sekretariat           |      RANGE BLOK      |  10.42.0.0 – 10.42.1.255  |   
|                                  |          NID         |         10.42.0.0         |   
|                                  |        NETMASK       |       255.255.254.0       |   
|                                  |   BROADCAST ADDRESS  |        10.42.1.255        |   
|                                  |    AVAILABLE HOST    |            510            |   
|                                  | RANGE AVAILABLE HOST |  10.42.0.1 – 10.42.1.254  |   
|                                  |                      |                           |   
|         A - E ( Router )         |      RANGE BLOK      | 10.42.3.240 – 10.42.3.247 |   
|                                  |          NID         |        10.42.3.240        |   
|                                  |        NETMASK       |      255.255.255.248      |   
|                                  |   BROADCAST ADDRESS  |        10.42.3.247        |   
|                                  |    AVAILABLE HOST    |             6             |   
|                                  | RANGE AVAILABLE HOST | 10.42.3.241 – 10.42.3.246 |   
|                                  |                      |                           |   
|            F (Tunnel)            |      RANGE BLOK      | 10.42.3.248 – 10.42.3.251 |   
|                                  |          NID         |        10.42.3.248        |   
|                                  |        NETMASK       |      255.255.255.252      |   
|                                  |   BROADCAST ADDRESS  |        10.42.3.251        |   
|                                  |    AVAILABLE HOST    |             2             |   
|                                  | RANGE AVAILABLE HOST | 10.42.3.249 – 10.42.3.250 |   
|                                  |                      |                           |   
