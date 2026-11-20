# Shoong! 개인정보 처리방침

시행일: 2026년 11월 20일

Shoong!(이하 "앱")는 이용자의 개인정보를 서버로 수집하거나 외부로 전송하지 않습니다. 이 방침은 Android 앱, iOS(iPhone) 앱, PC 앱(Windows·macOS)이 사용하는 정보와 권한을 설명합니다.

## 1. 수집하는 정보

앱은 개인정보를 수집하지 않습니다. 앱을 쓰며 입력한 할 일, 날짜, 루틴, 설정은 **이용자의 기기 안에만 저장**되며 개발자나 제3자에게 전송되지 않습니다. 이용자가 동기화를 직접 켠 경우에만 이용자 본인의 클라우드 저장 공간(Google Drive, iCloud 등)에 파일로 저장됩니다(아래 "동기화" 항목). 앱에는 광고, 분석(통계) 도구, 회원가입이 없습니다.

## 2. 앱이 요청하는 권한과 사용 목적 (Android)

| 권한 | 사용 목적 |
|---|---|
| 알림 | 오늘 할 일 목록을 알림창과 잠금화면에 표시합니다. |
| 캘린더 읽기·쓰기 | 이용자가 **직접 켠 경우에만** 사용합니다. 할 일을 기기 캘린더에 일정으로 등록하고(앱 → 캘린더), 기기 캘린더의 일정을 할 일로 가져옵니다(캘린더 → 앱). 캘린더 정보는 기기 안에서만 처리되며 외부로 전송되지 않습니다. |
| 정확한 알람·리마인더, 포그라운드 서비스(미디어 재생), 진동 | 이용자가 `알람`을 붙인 할 일의 시각에 알람음과 진동을 울리고, 끄거나 다시 알림을 받을 때까지 유지합니다. 소리 재생에만 쓰며 마이크·위치 등은 쓰지 않습니다. |
| 부팅 완료 수신 | 기기를 다시 켠 뒤 알림을 다시 표시합니다. |
| 백업 파일(선택) | 이용자가 설정에서 직접 고른 파일에만 할 일·메모·설정을 JSON 으로 저장합니다. 그 파일을 구글 드라이브 폴더에 두는 경우의 전송은 해당 서비스를 따르며, 앱이 별도 서버로 보내지 않습니다. |

캘린더 권한은 이용자가 설정에서 캘린더 연동을 켤 때에만 요청하며, 거부해도 나머지 기능은 모두 사용할 수 있습니다.

## 3. 동기화 (선택, 모든 기기)

이용자가 설정에서 켠 경우에만, 할 일과 메모를 `sync.json` 파일 하나에 써서 이용자의 다른 기기와 맞춥니다. 개발자 서버는 없으며 개발자는 이 파일에 접근할 수 없습니다. 스크린샷 이미지 파일은 동기화하지 않습니다.

- **Android**: 이용자가 직접 고른 파일(예: Google Drive 안의 파일)에만 읽고 씁니다.
- **iOS**: 이용자 본인의 iCloud(앱 전용 iCloud Drive 폴더), 또는 이용자가 직접 고른 파일(예: Google Drive 안의 파일)을 씁니다.
- **PC**: 이용자가 고른 동기화 폴더(예: Google Drive·OneDrive 폴더) 안의 파일, macOS에서는 iPhone과 같은 iCloud Drive 파일을 씁니다.

파일이 클라우드로 전송·보관되는 과정은 해당 서비스(Google, Apple, Microsoft)의 약관과 개인정보처리방침을 따릅니다. 동기화를 끄고 그 파일을 지우면 삭제됩니다.

## 4. 결제 (Android)

유료 기능(프리미엄)은 Google Play 결제를 통해 구매합니다. 결제 정보(카드 번호 등)는 Google이 처리하며 앱과 개발자는 이를 받지 않습니다. 앱은 구매 여부(프리미엄 상태)만 확인합니다. 결제와 관련한 정보 처리는 [Google Play 서비스 약관](https://play.google.com/about/play-terms/) 및 [Google 개인정보처리방침](https://policies.google.com/privacy)을 따릅니다.

## 5. 정보의 보관과 삭제 (Android)

모든 데이터는 기기에 저장되며, 앱을 삭제하거나 설정 → 앱 → Shoong! → 저장공간에서 데이터를 지우면 함께 삭제됩니다. 앱이 캘린더에 등록한 일정은 앱에서 지우거나 캘린더에서 직접 지울 수 있습니다.

## 6. iOS(iPhone) 앱

iOS용 앱도 같은 원칙입니다. 이용자의 정보를 서버로 보내지 않으며, 광고·분석(통계) 도구·회원가입·결제가 없습니다.

- **저장 위치**: 할 일·메모·스크린샷 이미지·설정은 기기 안의 앱 전용 공간에 저장되며, 앱을 삭제하면 함께 지워집니다.
- **알림**: 이용자가 적은 시각에 알림을 보내고, 설정에서 켠 경우 잠금화면·다이내믹 아일랜드에 남은 할 일을 보여 줍니다.
- **공유 확장**: 이용자가 다른 앱에서 공유로 보낸 이미지만 받아 스크린샷 메모로 저장합니다. 사진 보관함 전체에는 접근하지 않습니다.
- **위젯·단축어·Siri·제어 센터**: 같은 기기 안의 할 일 목록을 읽고 씁니다. 외부로 보내지 않습니다.
- **캘린더**: 앱에 캘린더 권한 안내가 포함되어 있으나, 현재 버전에서는 캘린더 연동 기능을 제공하지 않습니다. 이 기능을 열면 이 방침을 갱신합니다.

## 7. PC 앱 (Windows·macOS)

PC용 앱도 같은 원칙입니다. 이용자의 정보를 서버로 보내지 않으며, 광고·분석(통계) 도구·회원가입·결제가 없습니다.

- **저장 위치**: 할 일·메모·스크린샷 이미지·설정은 이용자 PC의 `%APPDATA%\Shoong` 폴더에만 저장됩니다. Microsoft Store로 설치한 앱은 Windows가 이 위치를 앱 전용 저장 공간으로 옮겨 저장할 수 있으며, 앱을 제거하면 저장된 데이터도 함께 지워질 수 있습니다. 제거하기 전에 설정 → 백업 → 내보내기로 파일을 남겨 두세요.
- **macOS 저장 위치**: 같은 데이터를 이용자 Mac의 사용자 폴더 안 앱 데이터 폴더에만 저장합니다.
- **전역 단축키**: 이용자가 정한 조합(입력창 열기, 목록 띄우기)이 눌렸을 때만 해당 창을 열거나 닫습니다. 다른 키 입력은 읽거나 기록하지 않습니다.
- **클립보드**: 입력창에서 이용자가 Ctrl+V를 눌렀을 때 클립보드의 이미지를 읽어 스크린샷 메모로 저장합니다. 클립보드에 글을 쓰는 것은 이용자가 메모의 복사 버튼을 눌렀을 때뿐입니다.
- **파일**: 이용자가 끌어 놓은 이미지 파일, 그리고 백업 내보내기·가져오기에서 직접 고른 파일만 읽고 씁니다.
- **알림·알람**: 이용자가 적은 시각에 Windows 알림과 알람 소리를 냅니다. 앱이 꺼져 있으면 울리지 않습니다.
- **시작 시 실행(선택)**: 이용자가 켠 경우에만 Windows 시작 때 앱이 실행됩니다.
- **같은 PC 안의 신호**: 앱을 한 번 더 실행했을 때 이미 켜진 창을 열기 위해, 이용자 PC 안(127.0.0.1)에서만 신호를 주고받습니다. 인터넷으로 나가지 않습니다.
- **Microsoft Store**: 설치·평점·오류 통계 등은 Microsoft가 Store 정책에 따라 처리합니다. 앱 자체는 사용 통계를 수집하지 않습니다.

## 8. 아동

앱은 아동으로부터 개인정보를 수집하지 않습니다.

## 9. 방침의 변경

방침이 바뀌면 이 문서를 갱신하고 시행일을 고칩니다.

## 10. 문의

문의: **freekofha@gmail.com**

---

# Shoong! Privacy Policy

Effective date: November 20, 2026

Shoong! ("the app") does not collect personal data or send it to any server. Tasks, dates, routines and settings you enter are stored **only on your device**. The app contains no ads, analytics, or account sign-up. If you turn on sync yourself, tasks and memos are written to a file in your own cloud storage (see Sync). This policy covers the Android app, the iOS (iPhone) app and the PC app (Windows and macOS).

**Permissions (Android)**
- *Notifications*: to show today's tasks in the notification shade and lock screen.
- *Calendar (read/write)*: used only if you turn on calendar sync in Settings, to add tasks to your device calendar and to import calendar events as tasks. Calendar data is processed on the device and is never transmitted.
- *Exact alarms, foreground service (media playback), vibration*: to ring and vibrate at the time of a task the user marked as an alarm, until dismissed or snoozed. Used only to play the alarm sound.
- *Receive boot completed*: to restore notifications after a restart.
- *Backup file (optional)*: tasks, memos and settings are written only to a file you pick yourself in Settings. The app sends nothing to any server.

**Sync (optional, all devices)**: only if you turn it on, tasks and memos are written to a single `sync.json` file to keep your devices in step. There is no developer server and the developer cannot access this file. Screenshot images are not synced.
- *Android*: only a file you pick yourself (for example, in Google Drive).
- *iOS*: your own iCloud (the app's iCloud Drive folder), or a file you pick yourself (for example, in Google Drive).
- *PC*: a file in a sync folder you choose (for example, Google Drive or OneDrive); on macOS, the same iCloud Drive file as the iPhone.
Transfer and storage in the cloud follow the terms and privacy policies of that service (Google, Apple, Microsoft). Turn sync off and delete the file to remove it.

**Purchases (Android)**: Premium features are purchased through Google Play. Google processes payments; the app only checks whether you own Premium.

**Deletion (Android)**: uninstalling the app or clearing its storage deletes all app data. Events the app added to your calendar can be deleted from the app or from your calendar.

**iOS (iPhone) app**: the same principles apply. Nothing is sent to any server, and there are no ads, analytics, sign-up or purchases.
- *Storage*: tasks, memos, screenshot images and settings are stored in the app's private space on the device and are deleted with the app.
- *Notifications*: at the time you wrote, and, if you turn it on, remaining tasks on the lock screen and Dynamic Island.
- *Share extension*: only images you share to the app from other apps. The app does not access your photo library.
- *Widgets, Shortcuts, Siri, Control Center*: read and write the task list on the same device only.
- *Calendar*: the app includes a calendar permission description, but this version does not offer calendar sync. We will update this policy if it is enabled.

**PC app (Windows and macOS)**: the same principles apply. Nothing is sent to any server, and there are no ads, analytics, sign-up or purchases.
- *Storage*: tasks, memos, screenshot images and settings are stored only in `%APPDATA%\Shoong` on your PC. For the Microsoft Store version, Windows may keep this data in an app-private location, and uninstalling the app may delete it. Export a backup in Settings before uninstalling.
- *macOS storage*: the same data is stored only in the app data folder inside your user folder on your Mac.
- *Global hotkeys*: the app listens only for the key combinations you choose (open the input window, show the list) to open or close that window. It does not read or record any other keystrokes.
- *Clipboard*: the app reads an image from the clipboard only when you press Ctrl+V in the input window, and writes text to the clipboard only when you press a memo's copy button.
- *Files*: only image files you drop onto the app and backup files you pick yourself.
- *Notifications and alarms*: shown at the time you wrote in a task, only while the app is running.
- *Run at startup (optional)*: only if you turn it on.
- *Local signal*: when you launch the app a second time, a loopback-only (127.0.0.1) signal brings the running window forward. It never leaves your PC.
- *Microsoft Store*: install, rating and crash statistics are handled by Microsoft under Store policies. The app itself collects no usage data.

**Children**: the app does not knowingly collect data from children.

**Contact**: freekofha@gmail.com
