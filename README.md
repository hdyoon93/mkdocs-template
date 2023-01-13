## 읜도우 conda로 사용하기

1. 가상환경 만들기
```powershell
conda create -n mkdocs python=3.8
```

2. 가상환경 조회하기
```powershell
conda env list
```

3. 가상환경 사용하기
```powershell
conda activate mkdocs
```

4. pip 설치하기
```powershell
pip install -r .\requirements.txt
```

6. 로컬 서버 띄우기
```powershell
mkdocs serve
```

6. 가상환경 원복하기
```powershell
conda deactivate 
```

