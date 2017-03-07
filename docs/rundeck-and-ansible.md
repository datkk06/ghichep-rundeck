#Kết hợp giữa Rundeck và Ansible.

- Để nâng cao được hiệu quả làm việc cũng như tận dụng tốt được những tính năng hữu ích trong `Job` của Rundeck thì việc thêm plugin Ansible là 
cực kỳ hữu ích với những người quản trị hệ thống.

- Sau đây là cách để thêm plugin Ansible vào Rundeck đơn giản.

- Thực hiện Download file plugin của Ansible tại [đây](https://github.com/Batix/rundeck-ansible-plugin/releases) là các phiên bản chi tiết của plugin Ansible.

```sh
wget https://github.com/Batix/rundeck-ansible-plugin/releases/download/1.2.3/ansible-plugin-1.2.3.jar
```

- Di chuyển file plugin đến thư mục `/var/lib/rundeck/libext`

```sh
mv ansible-plugin-1.2.3.jar /var/lib/rundeck/libext
```

- Kiểm tra xem plugin đã được thêm vào thành công hay chưa? 

![scr1](http://i.imgur.com/Cfvecox.png)

##Các vấn đề đang giải quyết :

1. làm rõ vai trò của Ansible và Rundeck (đang vẽ mô hình)
2. Một số bài lab để test sự kết hợp giữa Rundeck và Ansible :
	- Dùng Rundeck kết hợp Ansible để cài đặt và cấu hình hệ thống.
	- Sử dụng chức năng chuyển hướng linh động trong Job của Rundeck để kết hợp vs Ansible.