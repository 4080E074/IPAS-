# 學習主題
```
1.1 熟悉底下[惡意程式malware]
Given a scenario, analyze indicators of compromise and determine the type of malware.
■■  ■ Viruses 病毒
 https://www.mdpi.com/journal/viruses
 ■ Crypto-malware 加密惡意軟件
 https://www.lastline.com/blog/crypto-malware-a-look-at-the-latest-malware-threat/
 ■ Ransomware 勒索軟體 Ransomware
 https://blog.trendmicro.com.tw/?tag=%E5%8B%92%E7%B4%A2%E8%BB%9F%E9%AB%94
 https://en.wikipedia.org/wiki/Ransomware
 
 McAfee Ransomware Recover (Mr2)
 https://www.mcafee.com/enterprise/zh-tw/downloads/free-tools/ransomware-decryption.html
 
 ■ Worm 蠕蟲
 ■ Trojan 特洛伊
■ Rootkit 攻擊者偽裝成『根』目錄的使用者，它源自於 UNIX 系統，指『獲得電腦 root 權限的 kit (軟體工具組)』
https://blogs.technet.microsoft.com/twsecurity/2013/01/06/rootkit/
■ Keylogger 鍵盤紀錄器
https://baike.baidu.com/item/KeyLogger/5502946
■ Adware 廣告軟件
https://www.malwarebytes.com/adware/
■ Spyware 間諜軟體
https://blog.trendmicro.com.tw/?p=143
■ Bots 機器人
https://www.cloudflare.com/learning/bots/what-is-a-bot/
■ RAT 老鼠
■ Logic bomb 邏輯炸彈
http://hk.norton.com/security_response/glossary/define.jsp?letter=l&word=logic-bomb
■ Backdoor 後門

1.2 熟悉各種攻擊模式  Compare and contrast types of attacks.

社交攻擊模式Social engineering
  Social engineering 社交工程
https://blog.trendmicro.com.tw/?p=101
■ Phishing 網路釣魚
https://blog.trendmicro.com.tw/?p=136
■ Spear phishing 魚叉式網頁釣魚
https://blog.trendmicro.com.tw/?p=15888
■ Whaling
■ Vishing 語音釣魚
https://blog.trendmicro.com.tw/?p=2091
   Tailgating  又稱piggybacking，尾隨
   Impersonation

■ Dumpster diving垃圾搜尋
■■ Shoulder surfing肩隙偷覽
■■ Hoax惡作劇病毒
■■ Watering hole attack水坑攻擊
https://blog.trendmicro.com.tw/?p=3328
■■ Principles (reasons for effectiveness)社會工程原理
    Authority權威
    Intimidation恐嚇
    Consensus共識/社會證明
    Scarcity缺乏
    Urgency緊急程度
    Familiarity熟悉/喜歡
    Trust 信任
    https://blogs.getcertifiedgetahead.com/social-engineering-principles/

Application/service attacks
■■ DoS阻斷服務攻擊
■■ DDoS分散式阻斷服務攻擊
https://zh.wikipedia.org/wiki/%E9%98%BB%E6%96%B7%E6%9C%8D%E5%8B%99%E6%94%BB%E6%93%8A
■■ Man-in-the-middle中間人攻擊
https://zh.wikipedia.org/wiki/%E4%B8%AD%E9%97%B4%E4%BA%BA%E6%94%BB%E5%87%BB
■■ Buffer overflow緩衝區溢位
https://zh.wikipedia.org/wiki/%E7%BC%93%E5%86%B2%E5%8C%BA%E6%BA%A2%E5%87%BA
■■ Injection注入式攻擊
https://www.vscan.com.tw/blog/injection-attack/
■■ Cross-site scripting跨站腳本攻擊
https://blog.davidh83110.com/%E8%B3%87%E8%A8%8A%E5%AE%89%E5%85%A8/%E9%A7%AD%E5%AE%A2%E6%8A%80%E8%A1%93/owasp%20top10/2016/10/10/xss.html
■■ Cross-site request forgery (CSRF) 跨站請求偽造
https://zh.wikipedia.org/wiki/%E8%B7%A8%E7%AB%99%E8%AF%B7%E6%B1%82%E4%BC%AA%E9%80%A0
■■ Privilege escalation特權提升
https://zh.wikipedia.org/wiki/%E7%89%B9%E6%9D%83%E6%8F%90%E5%8D%87
■■ ARP poisoning ARP掛馬攻擊
https://www.informationsecurity.com.tw/article/article_detail.aspx?aid=4927
■■ Amplification放大攻擊
https://www.hkcert.org/my_url/zh/blog/14022401
■■ DNS poisoning網域伺服器汙染
https://zh.wikipedia.org/wiki/%E5%9F%9F%E5%90%8D%E6%9C%8D%E5%8A%A1%E5%99%A8%E7%BC%93%E5%AD%98%E6%B1%A1%E6%9F%93
■■ Domain hijacking域名劫持
https://www.acunetix.com/blog/articles/domain-hijacking-domain-spoofing/
■■ Man-in-the-browser瀏覽器中間人攻擊
■■ Zero day零時差攻擊
https://zh.wikipedia.org/wiki/%E9%9B%B6%E6%97%A5%E6%94%BB%E5%87%BB
■■ Replay重送攻擊
https://en.wikipedia.org/wiki/Replay_attack
■■ Pass the hash傳遞雜湊
傳遞雜湊是一種利用竊取而來的憑證所施行的攻擊技術，常被用於進階的攻擊並對組織造成重大的風險。
■■ Hijacking and related attacks ????????????
■■ Clickjacking 簡單來說就是將使用者在瀏覽網頁的點擊動作進行綁架，讓點擊動作產生非使用者所預期的行為。
■■ Session hijacking 連線劫持
https://en.wikipedia.org/wiki/Session_hijacking


1.3 Explain threat actor types and attributes.
Types of actors
■■ Script kiddies腳本小子
■■ Hacktivist激進駭客
■■ Organized crime[有組織的犯罪集團]
■■ Nation states/APT[國家級]
■■ Insiders[內部攻擊者]
■■ Competitors[競爭對手]

Attributes of actors
■■ Internal/external內部外部
■■ Level of sophistication???????????????
■■ Resources/funding資源資金
■■ Intent/motivation强调动机/强调目的性
■■ Use of (open-source intelligence)公開來源情報

1.4 Explain [penetration testing滲透測試] concepts.
■■ Active reconnaissance
■■ Passive reconnaissance
■■ Pivot
■■ Initial exploitation
■■ Persistence
■■ Escalation of privilege


■■ Black box
■■ White box
■■ Gray box

■■ Pen testing vs. vulnerability scanning

1.5 Explain [vulnerability scanning漏洞掃描] concepts.
Passively test security controls
Identify vulnerability
Identify lack of security controls
Identify common misconfigurations
Intrusive vs. non-intrusive
Credentialed vs. non-credentialed
False positive


1.6 Explain the impact associated with types of vulnerabilities.
■■ Race conditions
■■ Vulnerabilities due to:     End-of-life systems  Embedded systems    Lack of vendor support
■■ Improper input handling
■■ Improper error handling
■■ Misconfiguration/weak configuration
■■ Default configuration
■■ Resource exhaustion
■■ Untrained users
■■ Improperly configured accounts
■■ Vulnerable business processes
■■ Weak cipher suites and implementations

Memory/buffer vulnerability
   Memory leak
   Integer overflow
   Buffer overflow
   Pointer dereference
   DLL injection

System sprawl/undocumented assets
Architecture/design weaknesses
■■ New threats/zero day
■■ Improper certificate and key management
```
