# SIMMED

Link docker image: 

Load images: https://drive.google.com/file/d/1-2TyGDFlil07p6niJamZpc82U1NXF-gj/view?usp=sharing

```
docker load < simmed.tar
```

Cd vào SIMMED

```
%cd SIMMED
```

Sau đó chạy lệnh để phát API từ RASA:

```
rasa run -m models --enable-api --cors "*" --debug
```

Gắn thêm thẻ `-p` để edit port nếu cần.

Ví dụ

```
rasa run -m models --enable-api --cors "*" --debug -p 5005
```

### Tải credentials.yaml connect app facebook:

Ở trong thư mục SIMMED

```
gdown --id 1-WyiZYWGjGKbgpJqtHsNMsW3hhmAXkON
```
