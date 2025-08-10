# [EN-TH] Installation Windows 11 for Personal User

[Windows 11 IoT Enterprise LTSC](https://drive.massgrave.dev/en-us_windows_11_iot_enterprise_ltsc_2024_x64_dvd_f6b14814.iso)

---

## Windows 11 Setup
<img width="1024" height="768" alt="image" src="https://github.com/user-attachments/assets/46bd7272-6176-4e54-8826-00887db3d432" />

> Next > Next > ✅ I agree everything will be deleted including files, apps, and settings > Next > I don't have a product key > Windows 11 IoT Enterprise LTSC > Next > Accept

- Windows 11 IoT Enterprise LTSC is the lightest.
- Windows 11 IoT Enterprise LTSC เป็นตัวเบาที่สุด

---

### Disk partitioning — Clean Install
<img width="1024" height="768" alt="image" src="https://github.com/user-attachments/assets/70418288-5998-4ed4-a628-831e235399e0" />

> `Shift + F10`:

```cmd
diskpart
list disk
select disk <num>
clean
exit
exit
```
> Select disk <num> > Next

- There may be Disk 0, 1, 2, 3, etc., because you have more than one Storage Device.
- อาจจะมี Disk 0, 1, 2, 3 ฯลฯ เนื่องจากคุณมี Storge มากกว่าหนึ่งตัว

---

## Out Of Box Experience — Thailand

**DO NOT CONNECT TO THE INTERNET, IF YOU DON’T WANT THE LONG WINDOWS UPDATE!!!**

**อย่าต่ออินเตอร์เน็ต ถ้าคุณไม่อยากอัปเดตนาน !**

<img width="1024" height="768" alt="image" src="https://github.com/user-attachments/assets/e02c6dd8-a36f-4d45-b963-ea2eefbec425" />

> Thailand > Next > Yes > Add layout > Thai (Thailand) > Thai Kedmanee > Add layout > I don't have internet

<img width="1024" height="768" alt="image" src="https://github.com/user-attachments/assets/72b69298-deed-4082-911d-8dfa68dd3379" />

> Next > (? set password if you want) Next

**OS Directory Law — กฎไดเรกทอรีระบบ**
- Only use: 0-9, A-Z, a-z, Underscore (_), Hyphen (-), dot (.)
- ใช่แค่ 0-9, A-Z, a-z, สัญประกาศ (_), ยัติภังค์ (-), มหัพภาค (.)

<img width="1024" height="768" alt="image" src="https://github.com/user-attachments/assets/9db4e559-9075-48ba-82a1-c0d2e57c9c6c" />

> If you don’t want to send device information, uncheck everything: Next

> ถ้าไม่ต้องการส่งข้อมูลให้กับไมโครซอฟท์ ติ้กออกให้หมด : Next > Accept

**Submitting data to Microsoft**
- Pros: Microsoft can solve more user problems
- Cons: Devices work harder to write reports

**การส่งข้อมูลให้แก่ไมโครซอฟท์**
- ข้อดี : ไมโครซอฟท์แก้ปัญหาของผู้ใช้ได้มากขึ้น
- ข้อเสีย : อุปกรณ์ทำงานหนักขึ้น เพื่อเขียนรายงาน

## Windows Update — Phase I

- **Connect the internet**
- **ต่ออินเตอร์เน็ต**

<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/f7287405-4f27-4e7b-9fd0-44c0e84d3fa3" />

> `Super Key` > "Settings" > Windows Update > Check for updates

<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/5bd1394d-71d7-4e63-835e-7a3e1f94e1f8" />

> Advanced options > Optional updates > ✅ > Download & install

## Enhanced Windows Security
### Microsoft Edge
> `Super Key` > "Microsoft Edge" > Open > Start without your data > Confirm and continue > Confirm and continue > Continue without this data > Confirm and start browsing > "edge://settings"

<img width="850" height="2400" alt="edge__settings_privacy" src="https://github.com/user-attachments/assets/ba5a664c-e53f-4ccb-8f12-c3dd4376c3f9" />

> Privacy, search, and services

<img width="850" height="900" alt="edge__settings_system" src="https://github.com/user-attachments/assets/069e1650-9a66-459e-b46b-d0c67000853f" />

> System and performance

### Microsoft Defender Antivirus
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/09cc74d6-4cee-45c7-b608-1c68553249e3" />

> `Super Key` > "Windows Security" > Open > App & browser control > Reputation-based protection settings > ✅

<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/d1b8ea4f-49b4-4569-9e84-405ce76437f5" />

> Device security > Core isolation details > ✅

### Data Execution Prevention
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/3b762322-aca2-4e26-8177-f8a4101fbf76" />

> `Super Key + R` > "SystemPropertiesAdvanced" > OK > Performance > Data Execution Prevention > Turn on DEP for all programs and services except those I select > OK > OK > OK

### User Access Control
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/887d5337-1646-496b-be32-abe0a27333bb" />

> `Super Key` > "Control Panel" > Open > "Control Panel\User Accounts\User Accounts" > Change User Account Control settings > Always notify > OK > Yes

## Microsoft Store && Microsoft Office
### Microsoft Store

<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/35e51f52-1c63-4aee-ad4c-570d2ee86c0b" />

`Super Key` > "Command Prompt" > Run as administrator > Yes

```cmd
wsreset -i
exit
```

### Microsoft Office
[Office C2R Installers](https://gravesoft.dev/office_c2r_links)

<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/abdc6ebf-e45b-4db7-a342-7f9cbc530332" />

Select <Office.img> > Mount > Open > Setup.exe > Open > Run > Run > Run > Yes
