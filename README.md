# 📝 계좌 관리 시스템 프로젝트

## ⚙ 주요기능
<ol>
  <li>계좌 생성 : 사용자의 최대 보유 가능 계좌는 10개이며, 이를 초과하거나 사용자가 없는 경우 실패 응답</li>
  <li>계좌 해지 : 사용자가 존재해야 하며, 사용자 아이디와 계좌 소유주가 같아야 하며, 계좌가 해지 상태가 아닌경우, 잔액이 없을 경우 해지하도록 함</li>
  <li>계좌 확인 : 사용자가 존재할 경우 사용자 아이디를 통해 계좌번호와 잔액 정보를 받음</li>
  <li>잔액 사용 : 사용자가 존재하며, 사용자 아이디와 계좌 소유주가 같고, 거래금액이 잔액보다 작으며, 거래금액이 적당한 금액일 때 거래가 가능하도록 함</li>
  <li>잔액 사용 취소 : 원거래 금액과 취소 금액이 같고, 트랜잭션이 해당 계좌의 거래일 때 사용 취소 하도록 함</li>
  <li>거래 확인 : 해당 트랜잭션 아이디가 존재할 경우 해당 거래의 상세정보를 조회함</li>

## 🛠 사용기술
<ul>
  <li>Language : <strong>Java</strong></li>
  <li>Build : <strong>Gradle</strong></li>
  <li>Database : <strong>H2</strong></li>
  <li>JDK : <strong>OpenJDK 21</strong></li>
  <li>Testing : <strong>JUnit<strong><li>
  <li>Library : <strong>Lombok, jpa, validation, web, data-redis, redis client, embedded redis, starter-test</strong></li>
  <li>Tool : <strong>IntelliJ IDEA Ultimate</strong></li>
</ul>
