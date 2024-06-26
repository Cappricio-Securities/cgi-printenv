<div align="center">
  <img src="https://blogs.cappriciosec.com/uploaders/cgi-printenv-tool.png" alt="logo">
</div>


## Badges



[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
![PyPI - Version](https://img.shields.io/pypi/v/cgi-printenv)
![PyPI - Downloads](https://img.shields.io/pypi/dm/cgi-printenv)
![GitHub all releases](https://img.shields.io/github/downloads/Cappricio-Securities/cgi-printenv/total)
<a href="https://github.com/Cappricio-Securities/CVE-2023-27524/releases/"><img src="https://img.shields.io/github/release/Cappricio-Securities/cgi-printenv"></a>![Profile_view](https://komarev.com/ghpvc/?username=Cappricio-Securities&label=Profile%20views&color=0e75b6&style=flat)
[![Follow Twitter](https://img.shields.io/twitter/follow/cappricio_sec?style=social)](https://twitter.com/cappricio_sec)
<p align="center">

<p align="center">







## License

[MIT](https://choosealicense.com/licenses/mit/)



## Installation 

1. Install Python3 and pip [Instructions Here](https://www.python.org/downloads/) (If you can't figure this out, you shouldn't really be using this)

   - Install via pip
     - ```bash
          pip install cgi-printenv 
        ```
   - Run bellow command to check
     - `cgi-printenv -h`

## Configurations 
2. We integrated with the Telegram API to receive instant notifications for vulnerability detection.
   
   - Telegram Notification
     - ```bash
          cgi-printenv --chatid <YourTelegramChatID>
        ```
   - Open your telegram and search for [`@CappricioSecuritiesTools_bot`](https://web.telegram.org/k/#@CappricioSecuritiesTools_bot) and click start

## Usages 
3. This tool has multiple use cases.
   
   - To Check Single URL
     - ```bash
          cgi-printenv -u http://example.com 
        ```
   - To Check List of URL 
      - ```bash
          cgi-printenv -i urls.txt 
        ```
   - Save output into TXT file
      - ```bash
          cgi-printenv -i urls.txt -o out.txt
        ```
   - Want to Learn about [`cgi-printenv`](https://blogs.cappriciosec.com/cve/188/cgi-printenv%20-%20%20Exploration%20of%20a%20Legacy%20Script%20and%20its%20Enduring%20Security%20Implications)? Then Type Below command
      - ```bash
         cgi-printenv -b
        ```
     
<p align="center">
  <b>🚨 Disclaimer</b>
  
</p>
<p align="center">
<b>This tool is created for security bug identification and assistance; Cappricio Securities is not liable for any illegal use. 
  Use responsibly within legal and ethical boundaries. 🔐🛡️</b></p>


## Working PoC Video

[![asciicast](https://blogs.cappriciosec.com/uploaders/Screenshot%202024-06-17%20at%202.59.36%20PM.png)](https://asciinema.org/a/TWiyoRP01SMXw4TM5bPCSX3U7)




## Help menu

#### Get all items

```bash
👋 Hey Hacker
                                                          v1.0
              _                  _       __
  _________ _(_)     ____  _____(_)___  / /____  ____ _   __
 / ___/ __ `/ /_____/ __ \/ ___/ / __ \/ __/ _ \/ __ \ | / /
/ /__/ /_/ / /_____/ /_/ / /  / / / / / /_/  __/ / / / |/ /
\___/\__, /_/     / .___/_/  /_/_/ /_/\__/\___/_/ /_/|___/
    /____/       /_/

                              Developed By https://cappriciosec.com


cgi-printenv : Bug scanner for WebPentesters and Bugbounty Hunters

$ cgi-printenv [option]

Usage: cgi-printenv [options]
```


| Argument | Type     | Description                | Examples |
| :-------- | :------- | :------------------------- | :------------------------- |
| `-u` | `--url` | URL to scan | cgi-printenv -u https://target.com |
| `-i` | `--input` | filename Read input from txt  | cgi-printenv -i target.txt | 
| `-o` | `--output` | filename Write output in txt file | cgi-printenv -i target.txt -o output.txt |
| `-c` | `--chatid` | Creating Telegram Notification | cgi-printenv --chatid yourid |
| `-b` | `--blog` | To Read about cgi-printenv Bug | cgi-printenv -b |
| `-h` | `--help` | Help Menu | cgi-printenv -h |



## 🔗 Links
[![Website](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://cappriciosec.com/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/karthikeyan--v/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/karthithehacker)



## Author

- [@karthithehacker](https://github.com/karthi-the-hacker/)



## Feedback

If you have any feedback, please reach out to us at contact@karthithehacker.com
