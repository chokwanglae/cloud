## 클라우드 컴퓨팅 =====        
아이티 리소스 -> 언제 어디서든 접속해서 사용 

 [디바이스 ]
->클라우드 컴퓨팅

소유-> 서비스 

데이터 센터 -> 시스템 업그레이드 (5년 주기)   
"온 프리머스"''

금융자산 -- --       ======
서비스 런칭   인터넷기반 서비스 수익창출 
게임     고객 확보       '모바일 '-> 1인 1대   수요 예측 어려움             
온프라이머스 -[ 수요예측 어려움]

사스 소프트웨어 에즈 서비스  제공자 입장 

은행 예금 내부적으로

유닉스 => 고가의 장비 1980중반 

전용서버 -> main service 
           복잡도△  -> 보안▽
클러스터  여러대 연결 -> super computer 


아이티 관리 유지 부담 ->  기존인프라+ 신규 인프라  
빌려서 사용

리소스 공유 제공자 입장에서 => AZURE AWS navercloud 개인사용자 기업사용자 
2.셀프서비스 ->비용 절약 
3. 멀티테너시 지원  -> AWS 클라우드 
시스템 운영체제 윈도우 맥 리눅스  하드웨어 (cpu memory storage network ) 
스케줄링 

AWS  인터넷 클라우드 운영체제

클라우드 운영체제, 
어카운트별로 리소스 격리 유지 ㅡ  멀티 테너시  
4. 탄력적인 확장성 .신속성
scaling 확장성

5. 측정 가능한 서비스 
사용한 만큼 부과되는 -> 종량 과금제 
리스크 최소화 0
클라우드 장점 '

클라우드 장점 
특징 
1비용을 다운시켜서 저렴한 가격에 사용

2광범위 네트웤 접속

3하드웨어 리소스 공유 하면서 각각의 리소스를 격리 멀티테넌시

4신속한 확장성 필요한 시점 프로비져닝 (준비)  바로 사용 가능  가상화 기술 접목

5측정가능한 서비스 사용한 만큼 과금되는 과금제 

○
온프레미스 => 기존 시스템  비용  유지관리 
클라우드 기반  => 하이브리드 셀프서비스 관리형 서비스 
사업 리스크 감안 => 경제성있는 효과 
해당하는 인스턴스 제거 => 비용 절약 
고가용성 아키텍쳐 -> 기본 이중화 

관리형 내결항성 확장성 HA -> 이중화 

셀프서비스 -> 유형 


○SaaS란  Paas  Iaas

soft as a service 


SaaS 설치없이 사용한 만큼 비용 지불 
임대 
CRM ( 고객관리) 

EPP(재무관리)

그룹웨어 (Saas)  구글 APPs 

GCP Azure Aws

기본  HTTP 프로토콜  REST API 
상요작용

제공자 

○ PaaS 개발자를 위한 web호스팅 
                    Hadoop 데이터 처리
                    HPC
                    
인프라 ( 준비된 APP위에  

○PaaS 서비스 관리형 -  > 고객이 직접 관리할 필요가 없다.

cloud foundry 
redhat openshift
aws E,B
0
PaaS 자동화 - > IaC  (Infra as code)   
 IaaS -> self-Service , 융통성 높다. 
 자동화 ->  Iac (직접 코딩) 융통성 ▽
 
 물리적 서버를 구입 하지 않고 가상 서버 만들 수 잇음
 
프로비전( 프로그램 생성 //준비) 
        aws
PaaS => E.B

IaaS AWS => EC2 +vpc +s3             diy
            
            가상화 
on-premise = >   


 ※퍼블릭 클라우드  누구나

IaaS EC2  = >   처리된 데이터  provider에 저장 


※프라이빗 클라우드 
기업내에서 제공  
누구나 접속X  기업내 특정인 사용 
◇open stack 
◇cloud stack


※ 하이브리드 클라우드 
퍼블릭 + on- premise 
       vpn ==가상 프라이빗 네트웤 

※커뮤니티 클라우드  => 사용목적 보안

a사 b사 같이 사용 


프라이빗 클라우드 종류
                   자체 solution 
openstack -> 산업표준
cloudstack 

호스티드 프라이빗 클라우드 
전용시스템
제공자의 부분을 렌탈하여 사용 

클라우드 온프레미스 비용 비교 

도입비용 
가상머신 <=인스턴스

프로바이더 - 트래픽 조정 autosaling 
기존 것을 복제하여 확장  scale out/ in 
auto scaling
관리형 => 의존 
비용 중요 

로컬 내부 온프레미스 확장성 비교 

온프레미스 -> 기존 시스템 확장 

클라우드 리스크
IaaS 
PaaS 

클라우드 기반 보안 안전성 
ㅖ{{sa
cdn 컨텐츠 AWS 서비스 
데이터 백업
AWS 24 REGION 
해외 데이터 서버 

private cloud  vs  PUblic cloud aws / Azure 
cloud open source solutionn 
nasa - NOVA (computing ec2)          ===> openstack -> cloud stack 
rockspace = object strage source )s3          D.C -> anyone 
										

					| | 
				public, private cloud 
app                      app 
bare-metal 시스템  vs 가상머신 

os 이미지를 파일로 제공   AMI 아마존 머신 이미지

가상 리소스 -- > instance type   
os cent os ubuntu           

◇S3 (Amazon Simple storage)  내부적 3 copy   1년  내구성이 99.999999999% 
object storage service => file +Meta data 


AWS 서비스 SCOPE => administrator <- administrators < 권한
 global (IAM CDN ,ROUTE 53 bucket name
 region (S3 object 저장소, VPC)
 A.Z (Asuability zone) - ec2,EBS, subnet routetable 
IAM 인증 => IAM 유저 -> 아이디 패스워드 자격증명 -> 콘솔
           process -> AK, SC 자격증명 (영구적사용가능) : static 

   	role (역할) - 임시 key (AK, SK) -> STS (security token service)
   권한  용도와  1 AWS service (ec2)
   	 목적    2 account(나의 IAM user / 다른 account IAM user)
                3 web identity ->aws 
                4 SAML2.0  (ADS ,LDAP)
		            Active Directory Service 
			    
AWS 서비스
         account(계정) : 이메일 / pw -> console - fullaccess
IAM 인증 1 IAM 유저  ID/PW 자격증명 - > console
         2 signup - > process->AK/SK 자격증명 ( 영구적 사용가능) :STATIC
	 3 role(역할) -임시key (AK/SK) -> STS (security token service)
	 
    권한  용도와 목적 1 aws service(ec2)
    
 ## 서버가상화 기술
    
    하이버파이저 
    가상머신 게스트 os 
    
 # vmware   
    exsi 유료  / Enterprise 용
    W/S
 각각의 모듈을 분리               MSA 아키텍쳐
마이크로 VM = >  aws lamda 
Firecracker

SAN 물리적인 연결 EBS 가상화 제공 

파일기반 스토리지  EFS /NFS /SMB / CIFS 
PM/ VM mount 파일서버 NFS 서버 
rest full api 사용하는 방식

아마존 이미지 AMI 

IAM 인증 키스톤 웹 => 콘솔로 사용 호라이즌 

OPEN STACK IaaS 오픈소스 솔루션 가상머신 

vm 설치 root abc123 암호

## object storage

S3, Ceph , Swift
Client : EC2 ,접근방식 http 프로톸콜 사용 (Restful api)

## Block 기반 Storage
EBS // ISCSI, SAN ( 여러 개의 시스템을 공유) RDB(Ceph)
CLient : EC2
파일 기반 
## 파일 기반 스토리지
자주 업데이트하는 파일 공유시 사용
이미 구성되어 있어 사용하기에 편리
고비용 스토리지 
EFS ,NFS ,NAS,CEPHFS
## 데이터 베이스

관계형 DB-RDS(SQL) ,NOSQL
Nosql : 일관성 모델을 이용하는 데이터 저장 
SI 7 layer 

 

7계층 : 응용 계층 - HTTP 프로토콜, SMTP 프로토콜

6계층 : 표현 계층 - 암호화, 복호화

5계층 : 세션 계층 - 통신 유지 역할

4계층 : 전송 계층 - LB = 4계층 Switch,  TCP/IP 프로토콜 ,  UDP 프로토콜

3계층 : 네트워크 계층 - 라우터, 클래스별 ip 주소

2계층 : 데이터링크 계층 - 스위치, 브리지 
데이터 전송 가능

1계층 : 물리계층 - h/w, 케이블, 허브, 리피터

## 클라우드 데이터베이스 

AWS RDBMS ==> 아우라
Amazon DynamoDB

## 기간제 시스템
리프트앤 시프트 

온프레미스 => 클라우드 서비스 이전 원할시 

대부분 기업=> vmware




