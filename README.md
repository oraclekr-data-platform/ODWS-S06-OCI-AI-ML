# ODWS-S07-OCI-AI-ML

---

Repository에 포함된 4가지 노트북은 두 가지 버젼으로 제작

1. 'Lab1.ML_modeling-LDA.ipynb', 'Lab2.ML_deployment.ipynb' : 실습용 노트북. 실습자가 A-to-Z로 OCI Data Science를 사용하여 ML 모델을 만들고 배포할 수 있는 버전의 노트북

2. 'Demo1.ML_modeling-LDA.ipynb', 'Demo2.ML_deployment.ipynb' : 데모용 노트북. 발표자가 워크샵에서 발표용으로 사용한 위 실습 버전 노트북의 축약 버전

---

zip 파일로 되어있는 'Wallet_O0MQV2SEVCX6GMH9.zip' 파일은 OCI Data Science에서 사용할 데이터가 있는 ADW의 월렛 파일

해당 월렛 사용 가능. 세션 1부터 워크샵을 실행해보신 실습자 분들은 시나리오1, 시나리오2에서 생성한 ADW의 월렛을 사용해서 노트북 실행해도 무방

Lab1, Demo1 노트북의 데이터 로드하는 부분의 해당하는 부분을 수정해서 사용

    connection_parameters = {     
                              "user_name": 'admin', 
                              "password": "입력한 password", 
                              "service_name": "dbname-연결레벨(high/medium/low)", 
                              "wallet_location": "월렛을 업로드시킨 노트북 세션의 위치"
                            }
