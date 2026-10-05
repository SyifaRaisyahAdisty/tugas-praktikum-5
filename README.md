# tugas-praktikum-5
Syifa Raisyah Adisty_09011382530145
1. Lihat peralatan I/O, character device, yang ada pada sistem komputer.
<img width="800" height="600" alt="VirtualBox_ubuntu_05_10_2026_10_25_28" src="https://github.com/user-attachments/assets/3ae991e8-140b-43ff-8f5f-d43cc07faa84" />
<img width="800" height="600" alt="VirtualBox_ubuntu_05_10_2026_10_23_57" src="https://github.com/user-attachments/assets/fc0552e4-9f0d-4e36-9f9e-cea9fefb9580" />
2. Buatlah sub direktori januari, februari dan maret sekaligus pada direktori latihan 5.
<img width="800" height="600" alt="VirtualBox_ubuntu_05_10_2026_10_28_28" src="https://github.com/user-attachments/assets/ea9309b1-0267-4d93-8da0-be96c8960d46" />
3. Buatlah file dataku yang berisi nama, nim dan alamat anda pada sub direktori januari dan copy-kan file tersebut ke sub direktori februari dan maret.
<img width="800" height="225" alt="no 3" src="https://github.com/user-attachments/assets/2a08c87e-dccd-4c62-a174-facaabaf8984" />
<img width="800" height="600" alt="VirtualBox_ubuntu_05_10_2026_10_37_46" src="https://github.com/user-attachments/assets/5011d269-6649-4ebf-b264-5441592716fa" />
4.Ubahlah ijin akses file dataku pada sub direktori januari sehingga group dan others dapat melakukan write.
<img width="800" height="600" alt="no4" src="https://github.com/user-attachments/assets/f2ded985-30db-4e66-ae4e-b8a2793fb930" />
5. Ubahlah ijin akses file dataku pada sub direktori februari sehingga user dapat melakukan baik write, read maupun execute, tetapi group dan others hanya bisa read dan execute.
<img width="800" height="600" alt="VirtualBox_ubuntu_05_10_2026_10_59_08" src="https://github.com/user-attachments/assets/d02ebdb7-4503-4e80-85e6-0e8f2af0a314" />
6. Ubahlah ijin akses file dataku pada sub direktori maret sehingga semua dapat melakukan write, read dan execute.
<img width="800" height="600" alt="VirtualBox_ubuntu_05_10_2026_11_00_04" src="https://github.com/user-attachments/assets/d4bbf274-13bf-40e1-8656-c205106959ef" />
7. Hapuslah direktori maret.
<img width="800" height="600" alt="no7" src="https://github.com/user-attachments/assets/b65d2fd5-2731-4299-9409-c89de73f926b" />
8. Ubahkan kepemilikan sub direktori februari sehingga user dan group hanya dapat melakukan read, dan cobalah untuk membuat direktori baru haha pada sub direktori februari.
<img width="800" height="600" alt="VirtualBox_ubuntu_05_10_2026_11_02_54" src="https://github.com/user-attachments/assets/6cffe3ba-74b5-4d84-9c04-6b137c0e8cf9" />
9. Modifikasi umask dari file dataku pada sub direktori januari menjadi 027 dan berapakan nilai default-nya ?
<img width="800" height="600" alt="VirtualBox_ubuntu_05_10_2026_11_03_29" src="https://github.com/user-attachments/assets/03f4b43f-7df5-412b-b284-a7f83a84c043" />
Nilai awal file = 666 umask = 027 karena umask merupakan masker izin, izin yang diblokir adalah :
  - 0 = tidak memblokir izin user
  - 2 = memblokir write pada grup
  - 7 = memblokir read, write, execute pada others
jadi,
  - User = 6 =rw-
  - Grup = 6-2 = 4 = r--
  - Others = 6-7 = 0 - --sehingga nilai deaultnya adalah 640 (rw-r--)
10.Buatlah link dari file dataku ke file dataku.ini dan file dataku.juga dan dengan perintah list perhatikan berapa link yang terjadi ?
<img width="800" height="600" alt="VirtualBox_ubuntu_05_10_2026_11_13_49" src="https://github.com/user-attachments/assets/320ccc0c-711d-4aca-a305-b79c20ed1128" />

