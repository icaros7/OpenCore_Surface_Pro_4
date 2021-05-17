# OpenCore 0.6.9 for Surface Pro 4
Based on [@bigsadan's hackintosh](https://github.com/bigsadan/surface-pro-4-hackintosh)

# 한국어 - Korean
## 1. 안내
OpenCore 0.6.9과 [@bigsadan 씨의 hackintosh](https://github.com/bigsadan/surface-pro-4-hackintosh)를 기반으로 만들어진 최신 버전의 OpenCore 부트로더 입니다.

macOS 11.3.x를 사용 하는 경우 구버전의 OpenCore 사용 불능으로 인하여 제작하게 되었습니다.

Surface Pro 4 모델에 해킨토시 설치 및 실사용 가능 합니다.

<span style="color:red">**기본 시리얼 넘버 및 UUID가 `0`으로 설정**</span> 되어있으므로 [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) 앱 등으로 생성 후 사용 가능 합니다.

## 2. 테스트 환경
다음과 같은 환경에서 테스트 되었습니다.

- macOS 11.3.x
- Surface Pro 4
    - i5 6300U
    - 8GB RAM
    - 256GB (도시바 MLC)
- rEFInd 를 통한 멀티 부트 환경

## 3. 설정
다음과 같은 설정을 포함하고 있습니다.

- 기본 언어 : 한국어
- 기본 키보드 배열 : 쿼티 (설치 과정 중에만 해당)
- 자동 부팅 : 5초
- 자동 부팅 선택 : 가능 (OpenCore 부트로더 항목에서 `Ctrl + 엔터`를 누를 경우 설정 가능)
- 보안 정책 : 비활성화 (macOS 11.3 업데이트 이후 SecureBoot 사용 불능한 것으로 추정)
- MacBook Pro 13인치 논터치바 2016년 후기 기본형 모델 (`MacBookPro13,1`)
- 기타 부트 옵션 숨김

# English - 영어
## 1. Information
The laest version of OpenCore that based on OpenCore 0.6.9 & [@bigsadan's hackintosh](https://github.com/bigsadan/surface-pro-4-hackintosh)

I made this variation, because if you use macOS 11.3.x, you can't use older version OpenCore.

You can use this bootloader for hackintosh install & daily-use

<span style="color:red">**Please change serial number and UUID from `0`**</span> by way of SMBIOS Generator like [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)

## 2. Tested Environment
Successfully working following environment.

- macOS 11.3.x
- Surface Pro 4
    - i5 6300U
    - 8GB RAM
    - 256GB (Toshiba MLC)
- Multi-boot environment via rEFInd

## 3. Configuration
Include following configuration

- Default Language : Korean (You can choose other language at installation step)
- Default Keyboard Layout : Qwerty
- Boot Timeout : 5 Sec.
- Set Default : Enabled
- SecurityPolicy : Disabled
- MacBook Pro 13-Inch Late 2016 i5 Model (`MacBookPro13,1`)
- Hide Auxiliary : Enabled