
**1. Task 1: Sử dụng adb (android debug bridge)**

- Bật chế độ developer trên device: Settings->About	Phone->	bấm 6 đến 12 lần vào trường Build Number
- Run adb tại path: `C:\Program Files\Genymobile\Genymotion\tools`
```
C:\Program Files\Genymobile\Genymotion\tools>adb.exe devices
List of devices attached
192.168.56.101:5555     device
```
- Cài file apk vào điện thoại ảo bằng câu lệnh: `adb install /path/to/apkfile`
```
C:\Program Files\Genymobile\Genymotion\tools>adb.exe install C:\Users\Admin\Downloads\InsecureBankv2.apk
Performing Streamed Install
Success
``` 
- Để tải lên một file từ máy thật đến điện thoại ảo, gõ lệnh:
`adb push </path/to/file/pc> </path/to/file/device`
- Để tải một file từ điện thoại ảo xuống về máy thật, gõ lệnh:
`adb pull </path/to/file/device> </path/to/file/pc>`

**2. Task 2: Phân tích tĩnh**
- Sử dụng MobSF
- Cài đặt trên Windows:
```
git clone https://github.com/MobSF/Mobile-Security-Framework-MobSF.git
cd Mobile-Security-Framework-MobSF
setup.bat
run.bat
```

![image](https://github.com/m3dium/android/assets/72652376/2ac1454f-bec3-4c18-8278-4fa20043bfb6)

| Nội dung | Column 2 | 
| -------- | -------- |
| Kiểm tra phân quyền
| Kiểm tra các cấu hình trong file Manifest     | Text     |





















