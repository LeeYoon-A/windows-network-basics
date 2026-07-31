# 🌐 Network Troubleshooting

## 📖 What is Network Troubleshooting?

Network Troubleshooting은
네트워크 문제가 발생했을 때 원인을 찾고 해결하는 과정입니다.

IT 운영에서는 문제를 빠르게 해결하기 위해
순서대로 점검하는 것이 중요합니다.

---

## 🔑 Basic Troubleshooting Process

### 1. Check Network Configuration

```cmd
ipconfig
```

확인 항목

- IPv4 Address
- Subnet Mask
- Default Gateway

---

### 2. Check Network Connectivity

```cmd
ping google.com
```

확인 항목

- 응답 여부
- 응답 시간
- 패킷 손실

---

### 3. Check DNS

```cmd
nslookup google.com
```

확인 항목

- 도메인이 IP 주소로 정상 변환되는지

---

### 4. Trace Network Route

```cmd
tracert google.com
```

확인 항목

- 목적지까지의 경로
- 지연이 발생하는 구간

---

## 💼 In Practice

IT 운영에서는 네트워크 장애가 발생하면 다음과 같은 순서로 점검합니다.

1. `ipconfig`
2. `ping`
3. `nslookup`
4. `tracert`

이러한 순서로 확인하면 기본적인 네트워크 문제를 효율적으로 진단할 수 있습니다.

---

## ✅ What I Learned

이번 학습을 통해 Windows의 기본 네트워크 명령어를 사용하여
네트워크 설정 확인, 연결 상태 점검, DNS 확인, 경로 추적까지
기본적인 네트워크 문제를 단계적으로 진단하는 방법을 익혔습니다.

---

## 🎤 Interview Answer

### Q. 인터넷이 안 된다고 하면 어떤 순서로 점검하시겠습니까?

> 먼저 `ipconfig`를 실행하여 IP 주소, Subnet Mask, Default Gateway가 정상인지 확인합니다. 이후 `ping`으로 네트워크 연결 상태를 확인하고, `nslookup`으로 DNS가 정상적으로 동작하는지 점검합니다. 마지막으로 `tracert`를 사용하여 목적지까지의 네트워크 경로를 확인하고 어느 구간에서 문제가 발생하는지 분석합니다.
