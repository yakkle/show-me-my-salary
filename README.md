# Show me my salary

#### 이 프로젝트는 윈도우 피씨가 없어 급여명세서를 회사에서 보지 못했던 불편함을 해소하기 위해 만들어진 프로젝트 입니다. ~~(액티브 엑스 ㅗㅗ)~~

```bash
$ git clone https://github.com/zsaladin/show-me-my-salary
$ cd show-me-my-salary
$ virtualenv venv -p python3
$ source venv/bin/activate
(venv) $ pip install -r requirements.txt
(venv) $ python show_me_my_salary.py "2017000012.htm" 19861212
```

위와 같은 커맨드를 사용하면 해당 htm 파일이 있던 경로에 복호화 된 명세서가 생성 됩니다.

## Requirements
- python3.6 or above
