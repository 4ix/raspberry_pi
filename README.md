# 모두의 라즈베리파이
## 2023-02-27(월)
### 라즈베리파이 세팅
1. 기본 정보
- 라즈베리파이: 192.168.10.179
-  내컴: 192.168.10.174

2. 원격 접속 방법
```
sudo apt-get install -y tightvncserver xrdp
```

## 2023-02-24(금)
- 우분투 기본 명령어 확인
```
pwd
mkdir ./work
touch ./work/file1
touch ./file2

ls home/jasper/work/file1
ls home/jasper/file2

cp
rm
mv

file
head
tail
more
less

```

- 파일 권한 수정
```
chmod 664 filename
```

- 링크 생성
```
ln -s file3.txt file3
```

- find
```
find /etc -name '*.conf' | more
find /bin/ -size +10k -size -100k
```

## 2023-02-23(목)
- 우분투 사용 연습
