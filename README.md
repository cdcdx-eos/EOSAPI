# EOSAPI
EOS Mainnet API URLs

# 主网ID

## aca376f206b8fc25a6ed44dbdc66547c36c6c33e3a119ffbeaef943642f0e906

可以使用的api_endpoint & ssl_endpoint

HowTo get available EOS api_endpoint & ssl_endpoint?

1. cleos -u https://api.eosnewyork.io system listproducers  
get BPs urls
2. curl https://bp.eosnewyork.io/bp.json  
```
{
  "producer_account_name": "eosnewyorkio",
  "producer_public_key": "EOS6GVX8eUqC1gN1293B3ivCNbifbr1BT6gzTFaQBXzWH9QNKVM4X",
  "org": {
    "candidate_name": "EOS New York",
    "website": "https://www.eosnewyork.io",
    "code_of_conduct": "https://steemit.com/eos/@eosnewyork/eos-new-york-code-of-conduct",
    "ownership_disclosure": "https://steemit.com/eos/@eosnewyork/eos-new-york-ownership-disclosure-and-corporate-structure",
    "email": "community@eosnewyork.io",
    "branding": {
      "logo_256": "https://bp.eosnewyork.io/Logo_256.jpg",
      "logo_1024": "https://bp.eosnewyork.io/Logo_1024.jpg",
      "logo_svg": "https://bp.eosnewyork.io/eosnewyorkio.svg"
    },
    "location": {
      "name": "Cook Islands",
      "country": "CK",
      "latitude": -18.857952,
      "longitude": -159.785278
    },
    "social": {
      "steemit": "eosnewyork",
      "twitter": "eosnewyork",
      "youtube": "UCg7aeCSXUTP49w_elxgYIXA",
      "facebook": "eosnewyorkBP",
      "github": "eosnewyork",
      "reddit": "eosnewyork",
      "keybase": "d3ck",
      "telegram": "eosnewyorkchat",
      "wechat": "kevineosnewyork"
    }
  },
  "nodes": [
    {
      "location": {
        "name": "primary",
        "country": "BR",
        "latitude": -23.5505,
        "longitude": -46.6333
      },
      "is_producer": true,
      "p2p_endpoint": "node1.eosnewyork.io:6987",
      "api_endpoint": "http://api.eosnewyork.io",
      "ssl_endpoint": "https://api.eosnewyork.io"
    }
  ]
}
```
3. get p2p_endpoint and ssl_endpoint URL

---
http://node1.zbeos.com:8888  
http://node2.zbeos.com:8888  
https://mainnet.eoscannon.io  
https://mainnet.eoscannon.io  
http://119.254.15.39:8888  
http://119.254.15.40:8888  
http://api.eosnewyork.io  
https://api.eosnewyork.io  
http://publicapi-mainnet.eosauthority.com  
https://publicapi-mainnet.eosauthority.com  
http://api-mainnet.eosgravity.com/  
http://api.cypherglass.com:8888  
https://api.cypherglass.com  
http://node2.liquideos.com:80  
https://node2.liquideos.com:443  
http://node2.liquideos.com:80  
https://node2.liquideos.com:443  
http://mainnet.eoscanada.com  
https://mainnet.eoscanada.com  
http://api.eos.store  
https://api.eos.store  
http://api.eos.store  
https://api.eos.store  
https://mainnet-us.meet.one  
https://mainnet-jp.meet.one  
https://mainnet-sg.meet.one  
http://bp.cryptolions.io:8888  
https://bp.cryptolions.io  
http://fn.eossweden.se  
https://fn.eossweden.se  
http://api.eosbeijing.one  
https://api.eosbeijing.one  
http://eu1.eosdac.io  
https://eu1.eosdac.io  
http://eu2.eosdac.io  
https://eu2.eosdac.io  
http://api.helloeos.com.cn  
https://api.helloeos.com.cn  
https://api.helloeos.com.cn  
https://api.helloeos.com.cn  
https://api1.eosasia.one/  
https://api1.eosasia.one/  
http://eos.greymass.com  
https://eos.greymass.com  
https://api.eosargentina.io:8888  
http://api-mainnet.starteos.io  
http://api-mainnet1.starteos.io  
http://br.eosrio.io:8080  
http://api.eosrio.io:8080  
http://mainnet.eoscalgary.io  
http://209.41.67.115:9115  
http://api.jeda.one:8888  
http://jhb.eosio.africa:8088  
http://cpt.eosio.africa:8088  
http://api.eosn.io  
https://api.eosn.io  
http://eu-west-nl.eosamsterdam.net:80  
https://eu-west-nl.eosamsterdam.net:443  
http://api.bitmars.one  
https://rpc.eosys.io:443  
http://mars.fn.eosbixin.com:80  
http://user-api.eoseoul.io  
https://user-api.eoseoul.io  
http://user-api.eoseoul.io  
https://user-api.eoseoul.io  
http://api.proxy1a.sheos.org  
https://lb1.sheos.org  
http://api2.eos.ren:8883  
http://api2.eos.ren:8883  
http://eos.genesis-mining.com:8443  
http://eos.genesis-mining.com:8443  
http://mainnet.genereos.io  
https://mainnet.genereos.io  
https://api.eoslaomao.com  
http://node0.eosblocksmith.io:8888  
https://node0.eosblocksmith.io:443  
https://eosapi.blockmatrix.network  
http://api1.eosdublin.io  
https://api1.eosdublin.io  
http://api2.eosdublin.io  
https://api2.eosdublin.io  
http://api.main-net.eosnodeone.io  
https://api.main-net.eosnodeone.io  
http://api1.eosnairobi.io:8898  
https://api1.eosnairobi.io:8899  
http://api2.eosnairobi.io:8898  
https://api2.eosnairobi.io:8899  
http://api.bp.fish  
http://api.bp.fish  
http://fn001.eossv.org:80  
https://fn001.eossv.org:444  

---

搜集自  
https://docs.google.com/spreadsheets/d/1HLAIZ242dc0R8IcHnTRjVur4-wguQ6AjRxzXia-2esU  

---

https://api.superone.io  
http://13.230.91.225:8889  
https://api.mainnet.eospace.io  
https://fn001.eossv.org:444  
https://api.eoseco.com  
https://api.helloeos.com.cn  
http://api.mainnet.eos.cybex.io:28888  
https://mainnet.eoscannon.io  
http://api.eosthu.com:8082  
http://mars.fn.eosbixin.com:80  
http://mainnet-eos.wancloud.cloud:55588  
http://api.eos.store:80  
https://api.eos.store:443  
http://api.eosbeijing.one  
http://api.eospalliums.org:8888  
http://api.jeda.one:8888  
https://user-api.eoseoul.io  
http://user-api.eoseoul.io  
https://api.main-net.eosnodeone.io  
http://boot.eostitan.com:8889  
http://209.41.67.115:9115  
http://mainnet.eoswz.com  
http://mainnet.bepal.io  
http://mainnet.eosarabia.org:2052  
https://rpc.eosys.io  
https://api.eosio.cr  
https://api.eosio.cr  
https://api.eosdetroit.io:443  
https://eos.saltblock.io  
https://bp.geos.one  
https://eos-rpc.tc.ink  
