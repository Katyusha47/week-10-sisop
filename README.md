# Tutorial Xinu Shell

Assalamualaikum wr. wb. Kali ini saya akan memberikan tutorial untuk tugas week 10 menambahkan perintah baru ke shell di xinu.

- Pertama, buka development-system nya. Lalu masuk ke directory shell dengan cara:
  ```console
  cd shell
  ```
  ![Masuk ke directory shell](images/masuk-ke-folder-shell.png)

- Selanjutnya, edit file shell.c dengan cara:
  ```console
  gedit shell.c
  ```
  ![Edit file shell.c](images/edit-file-shell,c.png)

 - Lalu, tambahkan `{"mycmd",      xsh_mycmd},` dibawah `{"uptime",      xsh_uptime},` seperti gambar dibawah
  <img src="images/add-mycmd.png" alt="tambahkan xsh_mycmd dibawah xsh_uptime" width="500"/>
