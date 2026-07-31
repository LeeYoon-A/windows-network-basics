# 🌐 DNS

## 📖 What is DNS?

DNS(Domain Name System)는
도메인 이름을 IP 주소로 변환해 주는 서비스입니다.

예를 들어 `www.google.com`과 같은 도메인 이름을
컴퓨터가 이해할 수 있는 IP 주소로 변환하여 통신할 수 있도록 합니다.

---

## 🔑 Why is DNS Important?

IP 주소는 숫자로 이루어져 있어 기억하기 어렵습니다.

DNS를 이용하면 사용자는 도메인 이름만 입력해도
자동으로 해당 IP 주소를 찾아 접속할 수 있습니다.

---

## 💼 In Practice

IT 운영에서는 특정 웹사이트에 접속되지 않을 경우
DNS가 정상적으로 도메인 이름을 IP 주소로 변환하는지 확인합니다.

Windows에서는 `nslookup` 명령어를 사용하여 확인할 수 있습니다.

---

## 📷 Practice Screenshot

`nslookup google.com` 명령어를 실행하여
도메인 이름이 IP 주소로 변환되는 것을 확인했습니다.

![DNS Result](../images/dns-result.png)

---

## ✅ What I Learned

DNS는 사람이 이해하기 쉬운 도메인 이름을
컴퓨터가 사용하는 IP 주소로 변환하는 서비스라는 것을 이해했습니다.

---

## 🎤 Interview Answer

### Q. DNS란 무엇인가요?

> DNS(Domain Name System)는 도메인 이름을 IP 주소로 변환해 주는 서비스입니다. 사용자는 `www.google.com`처럼 도메인 이름을 입력하지만, 실제 통신은 IP 주소를 이용하므로 DNS가 이를 변환하는 역할을 합니다.
