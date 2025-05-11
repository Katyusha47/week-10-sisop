# Tutorial Xinu Shell

Assalamualaikum wr. wb. Kali ini saya akan memberikan tutorial untuk tugas week 10 menambahkan perintah baru ke shell di xinu.

- Pertama, buka development-system nya. Lalu masuk ke directory shell dengan cara:
  ```console
  cd xinu
  cd shell
  ```
  <img src="images/masuk-ke-folder-shell.png" alt="Masuk ke directory shell" width="700"/>

- Selanjutnya, edit file shell.c dengan cara:
  ```console
  gedit shell.c
  ```
  <img src="images/edit-file-shell,c.png" alt="Edit file shell.c" width="1000"/>

- Lalu, tambahkan `{"mycmd",      xsh_mycmd},` dibawah `{"uptime",      xsh_uptime},` seperti gambar dibawah
  <img src="images/add-mycmd.png" alt="tambahkan xsh_mycmd dibawah xsh_uptime" width="700"/>

- Setelah itu, keluar dari directory shell lalu masuk ke directory include dengan cara:
  ```console
  cd ..
  cd include
  ```
  <img src="images/masuk-folder-include.png" alt="masuk kedalam directory include" width="700"/>

- Kali ini kita akan mengedit file `shprototypes.h` dengan cara:
  ```console
  gedit shprototypes.h
  ```
  <img src="images/edit-shprototypes.h.png" alt="gedit shprototypes.h" width="700"/>
