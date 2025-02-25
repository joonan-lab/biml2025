# biml2025
## 1. Hail을 활용한 WGS 분석 실습

Hail을 이용한 전장유전체 데이터 분석 튜토리얼에 오신 여러분을 환영합니다. 

본 튜토리얼을 구동하기 위해선, 최소 쿼드코어 CPU와 8Gb 메모리 이상의 컴퓨터가 필요합니다. 튜토리얼에 사용하는 데이터는 맨 아래 섹션인 Appendix에서 찾을수 있습니다. 튜토리얼의 데이터는 [1000 Genome Project의 high coverage depth WGS](https://www.internationalgenome.org/data/) VCF 중 염색체 22번 일부를 임의로 추출하였습니다. 

튜토리얼 구글 코랩 버젼 [링크](https://colab.research.google.com/drive/1Gm9prAdXC3rkYA46IzsfO8ZguTNT8Vss?usp=sharing). 참고, Hail은 GPU/TPU를 사용하지 않기 때문에 하드웨어 가속 없이 구동하면 됩니다. 또한 Hail은 일반적으로 CPU 노드 숫자가 중요하기에 코랩은 일반 HPC나 클라우드 환경보다 느립니다. 연습용 코드이니, 실제 구동환경에서는 이보다 빠르게 진행됨을 알려드립니다. 


## 2. CWAS을 활용한 noncoding mutation 분석 실습 

CWAS를 이용한 전장유전체 noncoding mutation 분석 튜토리얼입니다.

본 튜토리얼을 구동하기 위해선, 최소 2코어 CPU와 8Gb 메모리 이상의 컴퓨터가 필요합니다. 튜토리얼의 데이터는 [An et al., Science, 2018](https://pmc.ncbi.nlm.nih.gov/articles/PMC6432922/) 논문의 데이터입니다.

튜토리얼 구글 코랩 버전 [링크](https://colab.research.google.com/drive/1Jx9MFekiuwe2xcNvjjvSO6RKX1Sm3Xbi?usp=sharing).
