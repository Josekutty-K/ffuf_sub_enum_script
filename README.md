# ffuf-sub-enum
[![GitHub stars](https://img.shields.io/github/stars/Josekutty-K/ffuf_sub_enum_script)](https://github.com/Josekutty-K/ffuf_sub_enum_script)

> Automated Subdomain Enumeration with ffuf using Jason Haddix's 2M subdomains wordlist

## 📦 Installation
```bash
git clone https://github.com/Josekutty-K/ffuf_sub_enum_script.git
cd ffuf-sub-enum
chmod +x ffuf_sub_enum.sh
./ffuf_sub_enum.sh

```
## 🔧 Usage

```
./ffuf_sub_enum

(*_*)
Enter the domain or subdomain you want to fuzz: vulnweb.com
(*_*)


Starting ffuf...


        /'___\  /'___\           /'___\
       /\ \__/ /\ \__/  __  __  /\ \__/
       \ \ ,__\\ \ ,__\/\ \/\ \ \ \ ,__\
        \ \ \_/ \ \ \_/\ \ \_\ \ \ \ \_/
         \ \_\   \ \_\  \ \____/  \ \_\
          \/_/    \/_/   \/___/    \/_/

       v2.1.0-dev
________________________________________________

 :: Method           : GET
 :: URL              : http://FUZZ.vulnweb.com
 :: Wordlist         : FUZZ: /home/josekutty/2m-subdomains.txt
 :: Output file      : subs-vulnweb.com.json
 :: File format      : json
 :: Follow redirects : false
 :: Calibration      : false
 :: Timeout          : 10
 :: Threads          : 40
 :: Matcher          : Response status: 200,302
________________________________________________

www                     [Status: 200, Size: 4018, Words: 482, Lines: 74, Duration: 278ms]
```
