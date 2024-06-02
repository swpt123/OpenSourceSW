Linux Command
=============

## top
top : 시스템의 실시간 동작 상태 표시  
  
**-d** : 업데이트 간격을 설정  
**-p** : 특정 PID를 모니터링  
**-u** : 특정 사용자의 프로세스만 표시  

#### Example  
```bash
top -u <user_name>
```
  
## ps  
ps : 명령어는 현재 실행 중인 프로세스의 스냅샷을 제공  
  
**-e** : 모든 프로세스를 표시  
**-f** : 풀 포맷 목록을 제공  
**-u** : 특정 사용자의 프로세스를 표시  

#### Example  
```bash
ps -ef
```

## jobs  
jobs : 현재 셸 세션에서 실행 중인 작업을 표시  

**-l** : 프로세스 ID를 포함한 긴 형식으로 표시  
**-p** : 각 작업의 프로세스 ID만 출력  

#### Example  
```bash
jobs -l
```

## kill
kill : 프로세스를 종료  

**-9** : 강제 종료 (SIGKILL)  
**-l** : 사용할 수 있는 신호 목록을 출력  

#### Example  
```bash
kill -9 1234
```


| Command |    Description   |    Main Options    |        Example        |
|---------|-------------------|--------------------|------------------------|
|  `top`  | 실시간 시스템 상태 | `-d`, `-p`, `-u`  | `top -u user_name`   |
|   `ps`  | 프로세스 스냅샷    | `-e`, `-f`, `-u`  | `ps -ef`              |
|  `jobs`  | 작업 목록         | `-l`, `-p`        | `jobs -l`             |
|  `kill`  | 프로세스 종료     | `-9`, `-l`        | `kill -9 1234`        |
