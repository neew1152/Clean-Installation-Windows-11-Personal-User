# [EN-TH] Installation Windows 11 for Personal User

[Windows 11 IoT Enterprise LTSC](https://drive.massgrave.dev/en-us_windows_11_iot_enterprise_ltsc_2024_x64_dvd_f6b14814.iso)

---

## Windows 11 Setup
<img width="1024" height="768" alt="image" src="https://github.com/user-attachments/assets/46bd7272-6176-4e54-8826-00887db3d432" />
Next > Next > ✅ I agree everything will be deleted including files, apps, and settings > Next > I don't have a product key > Windows 11 IoT Enterprise LTSC > Next > Accept

> Windows 11 IoT Enterprise LTSC is the lightest.

> Windows 11 IoT Enterprise LTSC เป็นตัวเบาที่สุด

### Disk partitioning — Clean Install
<img width="1024" height="768" alt="image" src="https://github.com/user-attachments/assets/70418288-5998-4ed4-a628-831e235399e0" />

> Shift + F10:

```cmd
diskpart
list disk
select disk <num>
clean
exit
exit
```

Select disk <num> > Next

> There may be Disk 0, 1, 2, 3, etc., because you have more than one Storage Device.

> อาจจะมี Disk 0, 1, 2, 3 ฯลฯ เนื่องจากคุณมี Storge มากกว่าหนึ่งตัว

## Windows Out of Box Experience — Thailand

**DO NOT CONNECT TO THE INTERNET, IF YOU DON’T WANT THE LONG WINDOWS UPDATE!!!**

**อย่าต่ออินเตอร์เน็ต ถ้าคุณไม่อยากอัปเดตนาน !**

<img width="1024" height="768" alt="image" src="https://github.com/user-attachments/assets/e02c6dd8-a36f-4d45-b963-ea2eefbec425" />
Thailand > Next > Yes > Add layout > Thai (Thailand) > Thai Kedmanee > Add layout > I don't have internet

<img width="1024" height="768" alt="image" src="https://github.com/user-attachments/assets/72b69298-deed-4082-911d-8dfa68dd3379" />
Next > (? set password if you want) Next

**OS Directory Law — กฎไดเรกทอรีระบบ**
>  Only use: 0-9, A-Z, a-z, Underscore (_), Hyphen (-), dot (.)

> ใช่แค่ 0-9, A-Z, a-z, สัญประกาศ (_), ยัติภังค์ (-), มหัพภาค (.)

<img width="1024" height="768" alt="image" src="https://github.com/user-attachments/assets/9db4e559-9075-48ba-82a1-c0d2e57c9c6c" />
If you don’t want to send device information, uncheck everything: Next

ถ้าไม่ต้องการส่งข้อมูลให้กับไมโครซอฟท์ ติ้กออกให้หมด: Next > Accept

**Submitting data to Microsoft**
> Pros: Microsoft can solve more user problems

> Cons: Devices work harder to write reports

**การส่งข้อมูลให้แก่ไมโครซอฟท์**
> ข้อดี: ไมโครซอฟท์แก้ปัญหาของผู้ใช้ได้มากขึ้น

> ข้อเสีย: อุปกรณ์ทำงานหนักขึ้น เพื่อเขียนรายงาน
