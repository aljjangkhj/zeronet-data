# Zero-Net (제로-넷) 개인정보처리방침 / Privacy Policy

시행일 / Effective date: 2026-11-14
문의 / Contact: kimpresent54@gmail.com

[한국어](#한국어) · [English](#english)

---

## 한국어

Zero-Net(이하 "앱")은 인터넷이 끊긴 재난·비상 상황에서도 휴대폰 센서와 기기 안의 데이터만으로 동작하는 생존 도구예요. 앱에는 회원 가입이나 로그인이 없고, **개발자는 자체 서버를 두지 않으며 이름·연락처·위치·ICE 카드 같은 개인정보를 받지 않아요.** 다만 앱 품질을 위해 인터넷에 연결될 때 오류 기록과 이용 통계를 Google Firebase로 보내요(아래 3번).

### 1. 기기 안에만 저장하는 정보
아래 정보는 사용자의 휴대폰 안(앱 전용 저장 공간)에만 저장되고, 개발자에게 전송되지 않아요. 앱을 삭제하면 모두 지워져요.
- **위치**: 가까운 대피소·병원 등까지의 거리와 방향을 계산하는 데만 써요. 위치 기록을 저장하거나 외부로 보내지 않아요(아래 4번의 '위치 첨부'를 직접 켠 경우 제외).
- **ICE(응급 연락) 카드**: 이름, 혈액형, 알레르기, 비상 연락처 등 사용자가 직접 입력한 정보. 사진첩 저장은 사용자가 저장 버튼을 누를 때만 해요.
- 생존 배낭 체크리스트·유통기한, 사용자가 등록한 거점, 앱 설정(언어·단위 등), 내려받은 비상 데이터 팩.

### 2. 사용하는 권한
| 권한 | 용도 |
| --- | --- |
| 위치 | 레이더 화면의 거리·방향 계산(기기 안에서만) |
| 카메라 | 손전등(모스 부호 신호)만 켜요. 사진·영상을 찍거나 저장하지 않아요 |
| 알림 | 유통기한 임박 알림(기기 안에서 예약하는 로컬 알림) |
| 사진 저장 | ICE 카드 이미지를 사진첩에 저장(사용자가 누를 때만) |
| 블루투스·와이파이 근처 기기 | 인터넷 없이 근처 휴대폰과 메시지·데이터 팩을 주고받는 근거리 메쉬 기능 |

### 3. 인터넷에 연결될 때
- **비상 데이터 팩 다운로드**: 사용자가 다운로드를 누르면 GitHub(raw.githubusercontent.com)에서 대피소 등 공개 데이터를 받아요. 이때 GitHub이 접속 기록(IP 주소 등)을 처리할 수 있으며 [GitHub 개인정보처리방침](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement)이 적용돼요. 개발자에게는 아무 정보도 전달되지 않아요.
- **광고(Google AdMob)**: 데이터 팩을 받을 때 사용자가 고르면 보상형 광고가 나와요. Google은 광고 제공·측정·부정 방지를 위해 광고 ID, IP 주소, 기기 정보 등을 수집할 수 있어요. 자세한 내용은 [Google이 파트너 사이트·앱의 정보를 사용하는 방법](https://policies.google.com/technologies/partner-sites)을 확인하세요. 유럽경제지역·영국·스위스 사용자에게는 광고 전에 동의 창이 나와요. 휴대폰 설정에서 광고 ID를 재설정하거나 삭제(맞춤 광고 끄기)할 수 있어요.
- **제휴 링크(아마존 어소시에이트)**: 생존 배낭 화면의 '둘러보기'를 누르면 외부 브라우저에서 아마존 사이트가 열리고, 그 이후에는 아마존의 개인정보처리방침이 적용돼요. 앱은 구매 정보를 받지 않아요.

- **개발자 응원하기(인앱 결제)**: 앱 정보 화면에서 사용자가 응원 상품을 고르면 Apple App Store 또는 Google Play가 결제를 처리해요. 결제 수단·카드 정보는 각 스토어가 관리하고 개발자에게 전달되지 않으며, 앱은 결제가 완료됐는지만 확인해요. 응원해도 앱 기능은 똑같아요.
- **광고 지역**: 데이터 팩 광고는 대한민국에서만 보여요(위치는 기기 안에서만 판단하고 서버로 보내지 않아요).
- **오류 기록·이용 통계(Google Firebase Crashlytics·Analytics)**: 앱 오류를 고치고 기능을 개선하려고 써요.
  - 수집 항목: 앱이 비정상 종료되거나 오류가 날 때의 오류 내용(기기 모델, OS·앱 버전, 오류가 난 코드 위치), 앱 이용 기록(앱 실행·첫 실행, 본 화면(탭), 이용 시간 같은 기본 이벤트), 앱 설치마다 만들어지는 식별자(앱 인스턴스 ID, Crashlytics 설치 ID), 대략적인 지역(IP 주소로 추정, IP 주소 자체는 보관하지 않음). 안드로이드에서는 휴대폰 설정에 따라 광고 ID가 함께 수집될 수 있어요.
  - 보내지 않는 것: 이름·연락처, GPS 위치, ICE 카드, 체크리스트·거점, 메쉬 대화 내용.
  - 받는 곳·국외 이전: Google LLC(미국 등 Google 데이터센터). 인터넷에 연결될 때 암호화된 통신으로 수시로 전송돼요. 인터넷이 없으면 기기에 잠시 두었다가 연결되면 보내요.
  - 보관 기간: 이용 통계는 수집 후 최대 14개월, 오류 기록은 90일이 지나면 Google이 자동으로 지워요.
  - 거부: 지금은 앱 안에 끄는 설정이 없어요. 원하지 않으면 앱을 삭제하거나 아래 문의처로 삭제를 요청할 수 있어요. 안드로이드는 휴대폰 설정에서 광고 ID를 삭제할 수 있어요.
  - 판매·광고 목적으로 쓰거나 다른 회사와 공유하지 않아요. [Firebase 개인정보 보호](https://firebase.google.com/support/privacy) 안내를 함께 확인하세요.

### 4. 근거리 메쉬(인터넷 없이 근처 휴대폰과 통신)
- 메시지와 데이터 팩은 서버를 거치지 않고 근처(약 100m) 휴대폰에 직접 전달되고, 다른 휴대폰을 거쳐 더 멀리 전달될 수 있어요.
- 주변에서 앱을 켠 사람은 누구나 메시지를 볼 수 있어요. 민감한 정보는 보내지 마세요.
- 대화 내용은 앱이 켜져 있는 동안 메모리에만 있고, 앱을 끄면 사라져요.
- 사용자가 '위치 첨부'를 켠 메시지에만 현재 좌표가 함께 전달돼요.

### 5. 아동
앱은 13세 미만 아동을 대상으로 하지 않아요.

### 6. 정보 삭제
개발자가 직접 보관하는 정보는 없어요. 기기 안의 모든 정보는 앱을 삭제하면 지워져요. Firebase로 보낸 오류 기록·이용 통계는 위 보관 기간이 지나면 자동으로 지워지고, 그 전에 지우고 싶으면 아래 문의처로 요청해 주세요. 광고와 관련된 정보는 위 Google 안내에 따라 관리할 수 있어요.

### 7. 변경
방침이 바뀌면 이 페이지에 시행일과 함께 알려요.

### 8. 문의
kimpresent54@gmail.com

---

## English

Zero-Net ("the app") is a survival tool that works with your phone's sensors and on-device data, even when the internet is down. The app has no sign-up or login. **The developer runs no server of its own and never receives personal data such as your name, contacts, location or ICE card.** To improve quality, the app sends crash reports and usage statistics to Google Firebase when you are online (section 3).

### 1. Data stored only on your device
The following stays in the app's private storage on your phone and is never sent to the developer. Uninstalling the app deletes all of it.
- **Location**: used only to calculate distance and direction to nearby shelters, hospitals, etc. Location history is not stored or sent anywhere (except when you turn on "attach location" in section 4).
- **ICE (emergency) card**: name, blood type, allergies, emergency contacts and other details you enter. It is saved to your photo library only when you tap Save.
- Bag checklist and expiry dates, waypoints you add, app settings (language, units), and downloaded emergency data packs.

### 2. Permissions
| Permission | Purpose |
| --- | --- |
| Location | Distance and direction on the radar screen (on-device only) |
| Camera | Flashlight only (Morse signal). No photos or videos are taken or stored |
| Notifications | Expiry reminders (local notifications scheduled on the device) |
| Save photos | Save the ICE card image to your photo library (only when you tap) |
| Bluetooth / Wi-Fi nearby devices | Nearby mesh: exchange messages and data packs with nearby phones without the internet |

### 3. When you are online
- **Emergency data packs**: when you tap Download, public data (shelters, etc.) is downloaded from GitHub (raw.githubusercontent.com). GitHub may process access logs such as your IP address under the [GitHub Privacy Statement](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement). Nothing is sent to the developer.
- **Ads (Google AdMob)**: when downloading a data pack, a rewarded ad is shown if you choose to watch it. Google may collect the advertising ID, IP address and device information to serve and measure ads and prevent fraud. See [How Google uses information from sites or apps that use its services](https://policies.google.com/technologies/partner-sites). Users in the EEA, UK and Switzerland see a consent form before ads. You can reset or delete your advertising ID (opt out of personalised ads) in your phone settings.
- **Affiliate links (Amazon Associates)**: tapping "Browse" on the bag screen opens Amazon in your browser, where Amazon's privacy notice applies. The app does not receive any purchase information.

- **Supporting the developer (in-app purchase)**: if you choose a support item on the About screen, the payment is processed by the Apple App Store or Google Play. Payment methods and card details are handled by the store and are never shared with the developer; the app only checks whether the purchase was completed. All features stay the same whether or not you support.
- **Ad regions**: data pack ads are shown only in the Republic of Korea (this is decided on the device; your location is not sent to any server).
- **Crash reports and usage statistics (Google Firebase Crashlytics and Analytics)**: used to fix errors and improve the app.
  - Data collected: crash and error details (device model, OS and app version, where in the code the error happened), app usage events (app opens, first open, screens (tabs) viewed, engagement time), per-install identifiers (app instance ID, Crashlytics installation ID), and approximate region (derived from the IP address; the IP address itself is not stored). On Android, the advertising ID may also be collected depending on your phone settings.
  - Not sent: your name or contacts, GPS location, ICE card, checklists or waypoints, or mesh messages.
  - Recipient and international transfer: Google LLC (Google data centers, including in the United States). Data is sent over encrypted connections whenever you are online; while offline it is kept briefly on the device and sent later.
  - Retention: usage statistics up to 14 months after collection; crash reports are deleted automatically by Google after 90 days.
  - Opting out: there is currently no in-app switch. If you do not want this, you can uninstall the app or ask us to delete the data using the contact below. On Android you can delete your advertising ID in your phone settings.
  - This data is not sold, used for advertising or shared with other companies. See also [Privacy and Security in Firebase](https://firebase.google.com/support/privacy).

### 4. Nearby mesh (offline, phone to phone)
- Messages and data packs go directly to nearby phones (about 100 m) without any server and may be relayed further by other phones.
- Anyone nearby using the app can read messages. Do not send sensitive information.
- Conversations are kept in memory only while the app is open and are lost when it closes.
- Your coordinates are included only in messages where you turn on "attach location".

### 5. Children
The app is not directed to children under 13.

### 6. Deleting data
The developer keeps no data about you directly. Uninstalling the app deletes everything on your device. Crash reports and usage statistics sent to Firebase are deleted automatically after the retention periods above; to have them deleted sooner, contact us below. Ad-related data can be managed as described in Google's notice above.

### 7. Changes
If this policy changes, the new version will be posted here with its effective date.

### 8. Contact
kimpresent54@gmail.com
