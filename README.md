# Lunaris-AOSP for Lenovo Legion Y700 2023 (TB320FC)

Lenovo Legion Y700 2023 (TB320FC, 코드네임 asphalt)용 비공식 Lunaris-AOSP 롬입니다.

- 현재 LTbox를 통한 KernelSU설치가 안됩니다 차후 재빌드 해서 지원하도록 할 예정입니다.
- magisk는 30.7 버젼으로 가능합니다
- Android 16 / Lunaris 3.13, GMS 포함
- 펌웨어 기준: ZUI 17.0.373 (TB320FC_ROW_OPEN_USER_Q00031.0_V_ZUI_17.0.373_ST_260912)

## 다운로드

[Releases](https://github.com/kandilmh/Unoffical-Y702-tb320fc-global-romlunaris-project/releases/latest)에서 받습니다.

- `ltbox_asphalt_*.7z.001`, `.002` : LTBox EDL 설치 패키지
- `*.zip.part1`, `.part2` : 시스템 업데이트(OTA)용 파일입니다. 직접 받을 필요는 없습니다.

## 설치

설치는 [LTBox](https://github.com/miner7222/LTBox)를 사용합니다. 자세한 방법은 패키지 안의 `README_KO.txt`를 참고하세요.

1. `.7z.001`을 압축 해제합니다. 분할 파일이 함께 풀립니다.
2. LTBox 고급 메뉴의 "단순 펌웨어 플래싱"에서 `image` 폴더를 지정합니다.
3. 순정 롬이나 다른 롬에서 넘어오는 경우 첫 부팅 전에 리커버리에서 Format data를 실행합니다.

## 주의

- **부트로더를 다시 잠그지 마세요.** 커스텀 롬이 설치된 상태에서 잠그면 부팅되지 않습니다.
- 패키지에 포함된 abl을 다른 abl로 바꾸지 마세요.
- ZUI 17.0.373보다 새로운 순정 펌웨어로 업데이트한 기기에는 설치하지 마세요.

## 업데이트

V1부터 설정 > 시스템 > 시스템 업데이트에서 새 버전을 받을 수 있습니다. 데이터는 유지됩니다.

## 면책

비공식 빌드입니다. 설치로 생기는 문제는 사용자 책임입니다.
