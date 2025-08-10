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

Next

> There may be Disk 0, 1, 2, 3, etc., because you have more than one Storage Device.

> อาจจะมี Disk 0, 1, 2, 3 ฯลฯ เนื่องจากคุณมี Storge มากกว่าหนึ่งตัว
