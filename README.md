<div><img width="418" alt="image" src="https://github.com/20161609/FinanceTreeProject/assets/92266688/d6a43b42-ae2c-4db7-8673-470ae91c1c99"></div>
<br>
<br>

# 🌳 프로젝트 소개 (Project Description)
Finance Tree는 금융 거래를 관리하고 조직화하는 커맨드 라인 인터페이스 도구입니다. 사용자는 마치 파일 시스템을 탐색하듯, 금융 거래를 트리 구조로 관리할 수 있습니다. 이 도구는 SQLite 데이터베이스를 사용하여 거래 내역을 저장하며, 다양한 커맨드를 통해 데이터를 쉽게 관리할 수 있습니다.

# 📆 개발 기간 (Period)
2024-01-10 ~ 2024-01-18

# ⚙️ 기능 (Features)
- 트리 구조 관리: 금융 거래를 트리 구조로 관리하여 직관적인 조직화 가능
- 다양한 커맨드 지원: mkdir, rmdir, cd, ls 등의 파일 시스템 커맨드와 유사한 작업 수행
- 데이터베이스 연동: SQLite를 이용한 거래 데이터 저장 및 관리
- 사용자 친화적 인터페이스: 커맨드 라인을 통한 간편한 사용자 인터랙션

# 🔧 설치 방법 (Installation)
이 프로젝트를 사용하기 위해서는 다음 단계를 따르세요.

1. **리포지토리 복제(Clone the repository):**
   ```bash
   git clone https://github.com/20161609/FinanceTreeProject.git

2. **압축 해제**
   executable.zip을 원하는 위치에 압축 해제합니다.



# 📚 사용 방법 (Usage)
*Commands: 기존의 쉘명령어와 유사합니다.
<br>

**help : 이 도움말 메시지를 표시합니다.**
<div>
   <img width="960" alt="help" src="https://github.com/20161609/FinanceTree/assets/92266688/78f435a9-4d0a-400f-9f78-42fa40e9769d">
</div>
<br>
<br>
<br>
<br>


**mkdir, md <dir_name> : 새 디렉토리를 생성합니다.**
<div>
   <img width="960" alt="mkdir" src="https://github.com/20161609/FinanceTree/assets/92266688/ac3fe503-9e1a-4890-bd01-469871028a13">
</div>
<br>
<br>
<br>
<br>

**rmdir, rd <dir_name> : 기존 디렉토리를 삭제합니다.**
**rmdir, rd <dir_number> : 인덱스 번호를 기반으로 한 기존 디렉토리를 삭제합니다.**
<div>
   <img width="963" alt="rmdir" src="https://github.com/20161609/FinanceTree/assets/92266688/6933cb36-115a-4b0c-ac6c-58a3096f1e87">
</div>
<br>
<br>
<br>
<br>

**chdir, cd <path> : 현재 디렉토리를 변경합니다.**
**chdir, cd <dir_number> : 인덱스 번호를 기반으로 현재 디렉토리를 변경합니다.**
**list, ls : 현재 디렉토리의 모든 디렉토리를 나열합니다.**
<div>
   <img width="960" alt="chdir" src="https://github.com/20161609/FinanceTree/assets/92266688/a193dd21-8c62-4310-8642-a45aafc038ea">
</div>
<br>
<br>
<br>
<br>

**mv, move <old_name> <new_name>   : <old_name>에서 <new_name>으로 디렉토리명 변경R**
<div>
   <img width="960" alt="chdir" src="https://github.com/20161609/FinanceTree/assets/92266688/1d4af6a5-c853-48ba-acf5-44392d62f27f">
</div>
<br>
<br>
<br>
<br>

**insert : 새로운 거래 기록을 삽입합니다.**
<div>
   <img width="960" alt="insert" src="https://github.com/20161609/FinanceTree/assets/92266688/0e27866c-ecb0-440e-91cf-013ad5b54f6b">
</div>
<div>
   <img width="960" alt="insert_out" src="https://github.com/20161609/FinanceTree/assets/92266688/a0ff633c-b661-41c1-96f9-0c5af5464eba">
</div>
<br>
<br>
<br>
<br>

**delete :  해당 디렉토리내에 존재하는(자식 디렉토리의 내역은 해당x) 거래 기록을 삭제합니다. (업데이트 날짜로 정렬된 테이블)**
**delete -t : 해당 디렉토리내에 존재하는 거래 기록을 삭제합니다. (거래 날짜로 정렬된 테이블)**

<div>
   <img width="960" alt="delete" src="https://github.com/20161609/FinanceTree/assets/92266688/13eb021a-b02b-4617-81dd-3d291c2dd07f">
</div>
<div>
   <img width="960" alt="delete_all" src="https://github.com/20161609/FinanceTree/assets/92266688/4d6cecb3-f4eb-45d2-bf91-3f9100c82107">
</div>
<br>
<br>
<br>
<br>

**refer, rf -d <period> : 일일 거래를 참조합니다. 기간을 선택적으로 지정할 수 있습니다 (예: 2023/01/01~2023/01/31).**
<div>
   <img width="960" alt="refer" src="https://github.com/20161609/FinanceTree/assets/92266688/11542b89-5da8-4c1c-bbe2-64a87ca6b412">
</div>
<div>
   <img width="960" alt="refer_period" src="https://github.com/20161609/FinanceTree/assets/92266688/2c245100-b8e8-47f7-8493-38c8c6d8db13">
</div>
<br>
<br>
<br>
<br>
      
**refer, rf -m <period> : 월별 거래를 참조합니다. 기간을 선택적으로 지정할 수 있습니다 (예: 2023/01/01~2023/01/31).**
<div>
   <img width="960" alt="refer_m" src="https://github.com/20161609/FinanceTree/assets/92266688/21241354-3bda-40b2-aaba-476899d4d8b5">
</div>
<br>
<br>
<br>
<br>

**refer, rf -t <period>: 거래의 트리 구조를 표시합니다.**
<div>
   <img width="960" alt="refer_t" src="https://github.com/20161609/FinanceTree/assets/92266688/f8558c7c-f861-4ed5-814a-843c4289d4e3">
</div>
<br>
<br>
<br>
<br>

**excel -d <period>: 일일 거래를 참조해 이를 엑셀파일로 출력합니다..**
<div>
   <img width="960" alt="excel_d" src="https://github.com/20161609/FinanceTree/assets/92266688/a86ac28f-2f92-4ae1-b883-1a573f047d51">
</div>
<br>
<br>
<br>
<br>

**excel -m <period>: 월별 거래를 참조해 이를 엑셀파일로 출력합니다..**
<div>
   <img width="960" alt="excel_m" src="https://github.com/20161609/FinanceTree/assets/92266688/af0b0272-0668-4e24-a3cd-822d9634699c">
</div>
<br>
<br>
<br>
<br>

**graph <period>: 월별 잔액을 참조해 이를 막대그래프로 출력합니다.**
<div>
   <img width="960" alt="graph" src="https://github.com/20161609/FinanceTree/assets/92266688/b592d283-afba-4d7f-941a-49ced3d002eb">
</div>

<br>
<br>
<br>
<br>

**graph in <period>: 월별 수입을 참조해 이를 막대그래프로 출력합니다.**
<div>
   <img width="960" alt="graph_in" src="https://github.com/20161609/FinanceTree/assets/92266688/03a30f7a-3f8b-4989-82d2-c7791eb18950">
</div>
<br>
<br>
<br>
<br>

**graph out <period>: 월별 지출을 참조해 이를 막대그래프로 출력합니다.**
<div>
   <img width="960" alt="graph_out" src="https://github.com/20161609/FinanceTree/assets/92266688/8ae2a2e7-4b80-4ffb-9c4f-402453a43ede">
</div>
<br>
<br>
<br>
<br>

<div>* 어떤 작업을 취소하거나 종료하고 싶을 때 언제든지 'q!'를 사용하세요.</div>
<div>
* 날짜 입력은 다양한 입력 방식으로 가능합니다. (예시, 2024년 1월 18일의 경우)
   <div>- "2024-01-18", "2024/01/18"</div>
   <div>- "20240118", "240018" (2000년대 일 경우만 가능) </div>
   <div>- "24-01-18"(2000년대 일 경우만 가능), "24/01/18"(2000년대 일 경우만 가능)</div>
</div>

# 🙋 저자: 안호준 (dksshwns@sogang.ac.kr)
