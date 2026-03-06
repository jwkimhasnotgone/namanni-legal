---
layout: default
---

<style>
  body { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", "Noto Sans KR", sans-serif; }
  .policy-header { text-align: center; padding: 2rem 0 1.5rem; border-bottom: 2px solid #2DB4A8; margin-bottom: 2rem; }
  .policy-header h1 { font-size: 1.8rem; color: #155f5b; margin-bottom: 0.4rem; }
  .policy-header .date { color: #6b7280; font-size: 0.95rem; }
  .section { margin-bottom: 2rem; }
  .section h2 { font-size: 1.1rem; font-weight: 700; color: #155f5b; border-left: 4px solid #2DB4A8; padding-left: 0.75rem; margin-bottom: 1rem; }
  table { width: 100%; border-collapse: collapse; margin: 0.75rem 0; font-size: 0.92rem; }
  th { background: #e6f7f6; color: #155f5b; font-weight: 600; padding: 0.6rem 0.8rem; border: 1px solid #b2e0dd; text-align: left; }
  td { padding: 0.6rem 0.8rem; border: 1px solid #d1d5db; vertical-align: top; }
  tr:nth-child(even) td { background: #f9fefe; }
  .badge { display: inline-block; padding: 0.2rem 0.5rem; border-radius: 4px; font-size: 0.8rem; font-weight: 600; }
  .badge-required { background: #fef2f2; color: #b91c1c; }
  .badge-optional { background: #f0fdf4; color: #166534; }
  ul { padding-left: 1.4rem; }
  li { margin-bottom: 0.4rem; line-height: 1.6; }
  .contact-box { background: #f0fdf4; border: 1px solid #bbf7d0; border-radius: 8px; padding: 1rem 1.2rem; margin-top: 0.5rem; }
  .contact-box p { margin: 0.2rem 0; font-size: 0.95rem; }
  .note { color: #6b7280; font-size: 0.88rem; margin-top: 0.4rem; }
</style>

<div class="policy-header">
  <h1>개인정보 처리방침</h1>
  <p>남았니 (Namanni)</p>
  <p class="date">시행일: 2026년 3월 7일</p>
</div>

<div class="section">
<h2>1. 수집하는 개인정보</h2>
<table>
  <thead>
    <tr><th>항목</th><th>필수 여부</th><th>수집 목적</th></tr>
  </thead>
  <tbody>
    <tr>
      <td>기기 식별자 (FCM 토큰)</td>
      <td><span class="badge badge-required">필수</span></td>
      <td>푸시 알림 발송</td>
    </tr>
    <tr>
      <td>사용자 식별자 (UUID)</td>
      <td><span class="badge badge-required">필수</span> <span class="note">자동 생성</span></td>
      <td>서비스 이용, 데이터 저장</td>
    </tr>
    <tr>
      <td>이메일 주소</td>
      <td><span class="badge badge-optional">선택</span></td>
      <td>계정 복원, 로그인</td>
    </tr>
    <tr>
      <td>앱 사용 데이터 (응답 패턴)</td>
      <td><span class="badge badge-required">필수</span></td>
      <td>소진 시점 예측, 서비스 개인화</td>
    </tr>
  </tbody>
</table>
</div>

<div class="section">
<h2>2. 보유 및 이용 기간</h2>
<ul>
  <li><strong>회원:</strong> 탈퇴 시까지 보유 후 즉시 파기</li>
  <li><strong>비회원 (게스트):</strong> 앱 삭제 시 접근 불가 (비활성 익명 계정의 데이터는 일정 기간 후 삭제될 수 있습니다)</li>
  <li><strong>활동 로그:</strong> 30일 보관 후 자동 삭제</li>
</ul>
</div>

<div class="section">
<h2>3. 개인정보의 파기 절차 및 방법</h2>
<ul>
  <li><strong>파기 절차:</strong> 보유 기간 만료 또는 처리 목적 달성 후 내부 방침에 따라 지체 없이 파기합니다.</li>
  <li><strong>파기 방법:</strong> 전자적 파일은 복구할 수 없는 방법으로 영구 삭제하며, 종이 문서는 분쇄 또는 소각합니다.</li>
</ul>
</div>

<div class="section">
<h2>4. 제3자 제공</h2>
<p>제3자에게 개인정보를 제공하지 않습니다.</p>
</div>

<div class="section">
<h2>5. 개인정보의 국외 이전</h2>
<p>서비스 제공을 위해 아래 업체에 개인정보 처리를 위탁하고 있습니다.</p>
<table>
  <thead>
    <tr><th>수탁 업체</th><th>위탁 업무</th><th>이전 항목</th><th>보유 기간</th><th>소재지</th></tr>
  </thead>
  <tbody>
    <tr>
      <td>Supabase Inc.</td>
      <td>데이터베이스 호스팅</td>
      <td>UUID, 이메일, 응답 데이터</td>
      <td>회원 탈퇴 또는 데이터 삭제 시까지</td>
      <td>미국</td>
    </tr>
    <tr>
      <td>Google LLC (Firebase)</td>
      <td>푸시 알림 전송</td>
      <td>FCM 토큰</td>
      <td>토큰 갱신 또는 삭제 시까지</td>
      <td>미국</td>
    </tr>
  </tbody>
</table>
<p class="note">정보주체는 국외 이전에 대해 동의를 거부할 수 있으며, 거부 시 푸시 알림 및 클라우드 동기화 기능을 이용할 수 없습니다.</p>
</div>

<div class="section">
<h2>6. 정보주체의 권리 및 행사 방법</h2>
<ul>
  <li>앱 설정 → <strong>"내 데이터 내보내기"</strong>로 수집된 데이터를 JSON 형식으로 다운로드할 수 있습니다.</li>
  <li>앱 설정 → <strong>"데이터 삭제"</strong> 또는 <strong>"회원 탈퇴"</strong>로 모든 데이터를 즉시 삭제할 수 있습니다.</li>
  <li>문의: <a href="mailto:namanni.legal@gmail.com">namanni.legal@gmail.com</a></li>
</ul>
</div>

<div class="section">
<h2>7. 개인정보 보호 책임자</h2>
<div class="contact-box">
  <p><strong>이름:</strong> 김재웅</p>
  <p><strong>이메일:</strong> <a href="mailto:namanni.legal@gmail.com">namanni.legal@gmail.com</a></p>
</div>
</div>

<div class="section">
<h2>8. 개인정보 처리방침 변경</h2>
<p>이 방침은 시행일로부터 적용됩니다. 법령이나 서비스 변경에 따라 내용이 수정될 경우, 변경 사항을 앱 내 공지를 통해 시행 7일 전에 고지합니다.</p>
</div>
