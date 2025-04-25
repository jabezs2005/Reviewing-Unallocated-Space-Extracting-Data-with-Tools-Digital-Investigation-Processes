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
![ex3](https://github.com/user-attachments/assets/89e81e44-5898-483c-915b-69fe1ba45eec)
![2](https://github.com/user-attachments/assets/c4e0e8fc-0d67-409b-89f0-81989177d0c1)
![3](https://github.com/user-attachments/assets/f1c2c41f-8adc-44a3-97a5-366ad21bb57e)
![4](https://github.com/user-attachments/assets/3a756102-adaf-43bc-865c-08f51459f743)
![5](https://github.com/user-attachments/assets/6a1c4f0c-56e1-4fb8-a737-6df0593b1d5b)
![6](https://github.com/user-attachments/assets/35f2de7d-9570-4981-bc6d-534f6846095f)
![7](https://github.com/user-attachments/assets/588f6de2-79fd-486e-acd9-9306fad8a276)

## RESULT:
The unallocated space was successfully analyzed, data was extracted, and the digital investigation process was followed effectively.

