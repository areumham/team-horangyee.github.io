본 글은 AWS 클라우드 기초 개념과 보안 관점에서의 실습 과정을 정리한 글입니다.  
IAM 기반 권한 관리부터 STS AssumeRole, VPC 네트워크 구성까지 전반적인 흐름을 다룹니다.

실습 과정 중 다수의 이미지가 포함되어 있어,  
자세한 실습 내용은 PDF 문서로 제공합니다.


📄 전체 실습 정리 PDF

[AWS 기초 실습 정리 PDF 보기](/assets/aws_basics.pdf)

글 구성 요약

 1. IAM (Identity and Access Management)
- Root User vs IAM User 차이
- User / Group / Role / Policy 개념
- 최소 권한 원칙 기반 IAM 사용자 구성

 2. Access Key & STS
- 장기 Access Key의 위험성
- AWS STS 기반 임시 자격 증명 구조
- AssumeRole 흐름 및 보안적 장점

 3. STS AssumeRole 실습
- IAM 사용자에 AssumeRole 권한 부여
- Role 생성 및 신뢰 정책 설정
- EC2 + AWS CLI에서 임시 자격 증명 사용
- S3 접근 검증

 4. VPC 기본 개념
- VPC와 Region / AZ 관계
- CIDR 및 사설 IP 대역
- Public / Private Subnet 설계 원칙

 5. 라우팅 테이블 & Internet Gateway
- Local Routing과 외부 라우팅 차이
- Internet Gateway 구성 조건
- Public / Private Subnet 구분 기준

🔗 Reference
- AWS 공식 문서 및 기술 블로그 자료
- 실습 및 개념 참고 링크는 PDF 하단 Reference 섹션에 정리
