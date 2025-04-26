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

```lsblk```

```sudo dd if=/dev/sda of=/home/kali/disk.img bs=512```

```mmls ~/disk.img```

```sudo ls -lh disk.img```

```strings disk.img | less```

## OUTPUT:
Unallocated Space Analysis and Extracted Data Report

![1](https://github.com/user-attachments/assets/fc0ad707-8281-4006-8b26-0ae26a6d4cd1)

![2](https://github.com/user-attachments/assets/37f01de3-f552-46a7-9aa0-ed04fddc6926)

![3](https://github.com/user-attachments/assets/b477770d-6025-4f0f-a5cb-f834f7af5b7c)

![5](https://github.com/user-attachments/assets/589a4b0e-487d-4010-bd3d-7c989a5d1bc4)

![4](https://github.com/user-attachments/assets/5dece938-7e5a-40bb-9ba9-59794cf8aa6f)

## RESULT:
The unallocated space was successfully analyzed, data was extracted, and the digital investigation process was followed effectively.

