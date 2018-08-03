# ELK_Security
# Automation setup ELK stack 
# Automation setup security for ELK

Các bước thực hiện setup ELK:
1. Cài đặt Elasticserach, Kibana, Logstash
2. Chỉnh heap size cho ES và Logstash. Dùng file jvm.options đã được config sẵn, copy file jvm.options mới sang ELK server và backup file jvm.options cũ, file mới sẽ thay thế vai trò của file cũ.
3. Start ELK

Các bước thực hiện setup security:
1. Cài đặt NGINX
2. Tạo username/pasword qua htppasswd
3. Config security. Copy file config có sẵn sang thư mục /.../nginx/sites-available và enable nó
4. Truy cập ES và Kibana qua kết nối VPN
