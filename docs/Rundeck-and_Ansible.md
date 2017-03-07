#K?t h?p gi?a Rundeck v� Ansible.

- �? n�ng cao du?c hi?u qu? l�m vi?c cung nhu t?n d?ng t?t du?c nh?ng t�nh nang h?u �ch trong `Job` c?a Rundeck th� vi?c th�m plugin Ansible l� 
c?c k? h?u �ch v?i nh?ng ngu?i qu?n tr? h? th?ng.

- Sau d�y l� c�ch d? th�m plugin Ansible v�o Rundeck don gi?n.

- Th?c hi?n Download file plugin c?a Ansible t?i [d�y](https://github.com/Batix/rundeck-ansible-plugin/releases) l� c�c phi�n b?n chi ti?t c?a plugin Ansible.

```sh
wget https://github.com/Batix/rundeck-ansible-plugin/releases/download/1.2.3/ansible-plugin-1.2.3.jar
```

- Di chuy?n file plugin d?n thu m?c `/var/lib/rundeck/libext`

```sh
mv ansible-plugin-1.2.3.jar /var/lib/rundeck/libext
```

- Ki?m tra xem plugin d� du?c th�m v�o th�nh c�ng hay chua? 

![scr1]()

##C�c v?n d? dang gi?i quy?t :

1. l�m r� vai tr� c?a Ansible v� Rundeck (dang v? m� h�nh)
2. M?t s? b�i lab d? test s? k?t h?p gi?a Rundeck v� Ansible :
	- D�ng Rundeck k?t h?p Ansible d? c�i d?t v� c?u h�nh h? th?ng.
	- S? d?ng ch?c nang chuy?n hu?ng linh d?ng trong Job c?a Rundeck d? k?t h?p vs Ansible.