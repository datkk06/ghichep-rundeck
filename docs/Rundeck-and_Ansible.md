#K?t h?p gi?a Rundeck và Ansible.

- Ð? nâng cao du?c hi?u qu? làm vi?c cung nhu t?n d?ng t?t du?c nh?ng tính nang h?u ích trong `Job` c?a Rundeck thì vi?c thêm plugin Ansible là 
c?c k? h?u ích v?i nh?ng ngu?i qu?n tr? h? th?ng.

- Sau dây là cách d? thêm plugin Ansible vào Rundeck don gi?n.

- Th?c hi?n Download file plugin c?a Ansible t?i [dây](https://github.com/Batix/rundeck-ansible-plugin/releases) là các phiên b?n chi ti?t c?a plugin Ansible.

```sh
wget https://github.com/Batix/rundeck-ansible-plugin/releases/download/1.2.3/ansible-plugin-1.2.3.jar
```

- Di chuy?n file plugin d?n thu m?c `/var/lib/rundeck/libext`

```sh
mv ansible-plugin-1.2.3.jar /var/lib/rundeck/libext
```

- Ki?m tra xem plugin dã du?c thêm vào thành công hay chua? 

![scr1]()

##Các v?n d? dang gi?i quy?t :

1. làm rõ vai trò c?a Ansible và Rundeck (dang v? mô hình)
2. M?t s? bài lab d? test s? k?t h?p gi?a Rundeck và Ansible :
	- Dùng Rundeck k?t h?p Ansible d? cài d?t và c?u hình h? th?ng.
	- S? d?ng ch?c nang chuy?n hu?ng linh d?ng trong Job c?a Rundeck d? k?t h?p vs Ansible.