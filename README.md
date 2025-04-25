# Reviewing-Unallocated-Space-Extracting-Data-with-Tools-Digital-Investigation-Processes
## AIM:
To review unallocated space in a disk image, extract data using forensic tools, and understand the digital investigation process.

## DESIGN STEPS:
### Step 1:
Use tools like Autopsy or Sleuth Kit (blkls, icat) to identify and analyze unallocated space.

### Step 2:
Extract data from unallocated space and examine for hidden or deleted content.

### Step 3:
Document and interpret findings as part of the digital investigation process.

## PROGRAM:
Data Extraction and Investigation Tool Usage
```bash
lsblk
```

```bash
sudo dd if=/dev/sda of=/home/kali/disk.img bs=512
```

```bash
mmls ~/disk.img  (sleuth-kit)
sudo fdisk -l ~/disk.img (GNU)

```
```bash
sudo ls -lh disk.img
```
```bash
strings disk.img | less

```

## OUTPUT:
![image](https://github.com/user-attachments/assets/f7f3f622-8f58-4031-81fa-145674e5f1f2)

![image](https://github.com/user-attachments/assets/8cf804af-ce71-47b3-8484-27da904598ea)

![image](https://github.com/user-attachments/assets/727dadea-d82b-4166-9f48-cd9604b8f84b)

![image](https://github.com/user-attachments/assets/be95f49a-4da0-4574-a8d2-b873492e9fe9)

![image](https://github.com/user-attachments/assets/d4e1eb7a-7cdb-4453-89e3-cf55d4c6db74)

![image](https://github.com/user-attachments/assets/b554582b-abdf-4659-b9fe-326f7da9f7cc)


## RESULT:
The unallocated space was successfully analyzed, data was extracted, and the digital investigation process was followed effectively.
