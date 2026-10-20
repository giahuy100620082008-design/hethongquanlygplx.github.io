# hethongquanlygplx.github.io
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Hệ thống Quản lý Thiếu nhi Thánh Thể Việt Nam – Giáo phận Long Xuyên</title>
<style>
:root{--navy:#12345a;--blue:#1769aa;--gold:#f2bd4b;--bg:#f3f6fb;--text:#203047;--muted:#6b7890;--white:#fff;--red:#c83b4b;--green:#198754}
*{box-sizing:border-box}body{margin:0;font-family:Arial,Helvetica,sans-serif;background:var(--bg);color:var(--text)}
button,input,select{font:inherit}button{cursor:pointer;border:0;border-radius:9px;padding:10px 14px;background:var(--blue);color:white;font-weight:700}button:hover{filter:brightness(.95)}.secondary{background:#e8eef7;color:var(--navy)}.danger{background:var(--red)}.success{background:var(--green)}
.login-screen{min-height:100vh;display:grid;place-items:center;padding:22px;background:linear-gradient(135deg,#0b2545,#1769aa)}
.login-card{width:min(440px,100%);background:white;border-radius:22px;padding:30px;box-shadow:0 20px 60px #06172b55}
.logo{width:74px;height:74px;border-radius:50%;background:#fff3d2;color:#8a5a00;display:grid;place-items:center;font-size:35px;margin:0 auto 12px;border:3px solid var(--gold)}
.login-links{display:flex;justify-content:space-between;gap:10px;margin-top:12px;flex-wrap:wrap}.link-btn{background:transparent;color:var(--blue);padding:5px 0;font-size:13px}.login-card h1{text-align:center;color:var(--navy);font-size:23px;margin:8px 0}.subtitle{text-align:center;color:var(--muted);margin:0 0 24px}
.field{display:flex;flex-direction:column;gap:7px;margin-bottom:15px}.field label{font-size:13px;font-weight:700;color:#42516a}.field input,.field select{width:100%;padding:12px;border:1px solid #d4dce8;border-radius:9px;background:#fff;outline-color:var(--blue)}
.full{width:100%;padding:13px}.hint{font-size:12px;color:var(--muted);line-height:1.6;margin-top:15px}.error{color:var(--red);font-size:13px;min-height:18px}
.app{display:none;min-height:100vh}.sidebar{width:245px;background:var(--navy);color:white;position:fixed;inset:0 auto 0 0;padding:22px 14px;overflow:auto}.brand{display:flex;align-items:center;gap:10px;padding:0 8px 22px;border-bottom:1px solid #ffffff25}.brand .mini-logo{font-size:29px}.brand strong{font-size:15px;line-height:1.35}.nav-label{font-size:11px;color:#a8bfd8;margin:22px 10px 8px;text-transform:uppercase;letter-spacing:1px}.nav-btn{display:flex;align-items:center;gap:11px;width:100%;text-align:left;color:#dce9f7;background:transparent;margin:4px 0;padding:12px;border-radius:9px}.nav-btn.active,.nav-btn:hover{background:#ffffff1c;color:white}
.main{margin-left:245px;padding:24px;max-width:1600px}.topbar{display:flex;justify-content:space-between;align-items:center;gap:14px;margin-bottom:22px}.topbar-left{display:flex;align-items:flex-start;gap:12px}.back-btn{background:#e8eef7;color:var(--navy);white-space:nowrap}.topbar h1{margin:0;font-size:25px;color:var(--navy)}.topbar p{margin:6px 0 0;color:var(--muted);font-size:13px}.userbox{display:flex;align-items:center;gap:10px;background:white;border:1px solid #e3e8f0;padding:8px 12px;border-radius:12px}.avatar{width:36px;height:36px;border-radius:50%;background:#e7f1fc;display:grid;place-items:center;color:var(--blue);font-weight:bold}
.cards{display:grid;grid-template-columns:repeat(4,minmax(0,1fr));gap:15px;margin-bottom:22px}.stat{background:white;border:1px solid #e6ebf2;border-radius:14px;padding:18px}.stat-top{display:flex;justify-content:space-between;color:var(--muted);font-size:13px}.stat .num{font-size:30px;font-weight:800;color:var(--navy);margin-top:12px}.stat .ico{font-size:23px}
.panel{background:white;border:1px solid #e5eaf2;border-radius:14px;padding:20px;margin-bottom:20px;min-width:0}.panel-head{display:flex;align-items:center;justify-content:space-between;gap:12px;margin-bottom:16px;flex-wrap:wrap}.panel h2{font-size:17px;margin:0;color:var(--navy)}.muted{color:var(--muted);font-size:13px}.toolbar{display:flex;gap:9px;flex-wrap:wrap;margin-bottom:14px}.toolbar input,.toolbar select{padding:10px;border:1px solid #d6deea;border-radius:9px;background:white;min-width:150px}
.table-wrap{overflow:auto}table{width:100%;border-collapse:collapse;white-space:nowrap}th,td{text-align:left;padding:12px 11px;border-bottom:1px solid #edf0f5;font-size:13px}th{background:#f7f9fc;color:#607089;font-size:11px;text-transform:uppercase;letter-spacing:.4px}tbody tr:hover{background:#fafcff}.pill{display:inline-block;padding:5px 8px;border-radius:20px;font-size:11px;font-weight:700}.present{background:#dcf7e7;color:#167344}.excused{background:#fff0cc;color:#8a5b00}.absent{background:#ffe1e4;color:#a42333}.neutral{background:#e8eef7;color:#365270}.empty{text-align:center;color:var(--muted);padding:30px}
.form-grid{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:0 14px}.form-actions{display:flex;gap:8px;justify-content:flex-end;margin-top:10px}.hidden{display:none!important}.notice{background:#fff7df;border:1px solid #f3df9f;padding:12px 14px;border-radius:10px;font-size:13px;line-height:1.5;margin-bottom:18px}
.footer{text-align:center;color:#8490a3;font-size:12px;padding:15px}.qr-card{display:flex;gap:18px;align-items:center;flex-wrap:wrap}.qr-card img{width:220px;height:220px;object-fit:contain;background:white;border:1px solid #e5eaf2;padding:8px}.qr-modal{position:fixed;inset:0;background:#10243b99;z-index:1000;display:grid;place-items:center;padding:18px}.qr-modal-box{background:white;border-radius:16px;padding:22px;width:min(520px,100%);max-height:90vh;overflow:auto}.qr-modal-box h2{margin-top:0;color:var(--navy)}
@media(max-width:1000px){.cards{grid-template-columns:repeat(2,minmax(0,1fr))}.sidebar{width:205px}.main{margin-left:205px;padding:18px}}
@media(max-width:700px){.sidebar{position:static;width:100%;padding:12px}.brand{padding-bottom:12px}.sidebar nav{display:flex;overflow:auto;gap:4px}.nav-label{display:none}.nav-btn{white-space:nowrap;width:auto;margin:8px 0;padding:10px}.main{margin:0;padding:14px}.topbar{align-items:flex-start;flex-direction:column}.cards{gap:9px}.stat{padding:13px}.stat .num{font-size:25px}.form-grid{grid-template-columns:1fr}.login-card{padding:23px}}
</style>
</head>
<body>
<section class="login-screen" id="loginScreen">
  <form class="login-card" id="loginForm">
    <div class="logo">✝</div>
    <h1>THIẾU NHI THÁNH THỂ VIỆT NAM</h1>
    <p class="subtitle">Hệ thống quản lý Thiếu nhi Thánh Thể Giáo phận Long Xuyên</p>
    <div class="field"><label for="username">Nhập họ tên để vào hệ thống</label><input id="username" autocomplete="username" placeholder="Nhập họ tên của bạn" required></div>
    <div class="field"><label for="password">Mật khẩu Admin (người dùng thường để trống)</label><input id="password" type="password" autocomplete="current-password" placeholder="Chỉ Admin nhập mật khẩu"></div>
    <div class="error" id="loginError" role="alert"></div>
    <button class="full" type="submit">Vào hệ thống</button>
  </form>
  <form class="login-card hidden" id="registerForm">
    <div class="logo">✝</div><h1>ĐĂNG KÝ TÀI KHOẢN</h1><p class="subtitle">Không cần đăng ký để sử dụng hệ thống</p>
    <div class="field"><label>Họ và tên</label><input id="regName" required maxlength="100" placeholder="Họ tên của bạn"></div>
    <div class="field"><label>Tên đăng nhập</label><input id="regUsername" required minlength="4" maxlength="40" autocomplete="username" placeholder="Ít nhất 4 ký tự"></div>
    <div class="field"><label>Email</label><input id="regEmail" type="email" required autocomplete="email" placeholder="email@example.com"></div>
    <div class="field"><label>Mật khẩu</label><input id="regPassword" type="password" required minlength="8" autocomplete="new-password" placeholder="Ít nhất 8 ký tự"></div>
    <div class="field"><label>Ghi nhớ mã khôi phục (tự đặt)</label><input id="regRecovery" required minlength="6" autocomplete="off" placeholder="Ít nhất 6 ký tự, cất giữ riêng"></div>
    <div class="error" id="registerError" role="alert"></div><button class="full" type="submit">Tạo tài khoản</button><div class="login-links"><button type="button" class="link-btn" id="backLogin1">← Quay lại đăng nhập</button></div>
    <p class="hint">Mã khôi phục không gửi qua email trong bản HTML chạy cục bộ. Hãy cất giữ riêng, không dùng mật khẩu đang dùng ở nơi khác.</p>
  </form>
  <form class="login-card hidden" id="forgotForm">
    <div class="logo">🔐</div><h1>KHÔI PHỤC MẬT KHẨU</h1><p class="subtitle">Nhập thông tin đã đăng ký và mã khôi phục</p>
    <div class="field"><label>Tên đăng nhập</label><input id="forgotUsername" required autocomplete="username"></div>
    <div class="field"><label>Email đã đăng ký</label><input id="forgotEmail" type="email" required autocomplete="email"></div>
    <div class="field"><label>Mã khôi phục</label><input id="forgotRecovery" required minlength="6" autocomplete="off"></div>
    <div class="field"><label>Mật khẩu mới</label><input id="forgotNewPassword" type="password" required minlength="8" autocomplete="new-password"></div>
    <div class="error" id="forgotError" role="alert"></div><button class="full" type="submit">Đặt lại mật khẩu</button><div class="login-links"><button type="button" class="link-btn" id="backLogin2">← Quay lại đăng nhập</button></div>
  </form>
</section>

<div class="app" id="app">
  <aside class="sidebar">
    <div class="brand"><span class="mini-logo">✝</span><strong>HỆ THỐNG QUẢN LÝ<br>THIẾU NHI THÁNH THỂ VIỆT NAM<br>GIÁO PHẬN LONG XUYÊN</strong></div>
    <div class="nav-label">Tổng quan</div>
    <nav>
      <button class="nav-btn active" data-page="dashboard">🏠 Tổng quan</button>
      <button class="nav-btn" data-page="members">👧 Thiếu Nhi </button>
      <button class="nav-btn" data-page="attendance">📋 Điểm danh</button>
      <button class="nav-btn" data-page="violations">⚠️ Vi phạm</button>
      <button class="nav-btn" data-page="grades">📝 Nhập điểm</button>
      <button class="nav-btn" data-page="leaders">🧑‍🏫 Giáo lý viên </button>
      <button class="nav-btn" data-page="profile">👤 Thông tin cá nhân</button>
      <button class="nav-btn" data-page="accountSettings">🔐 Đổi tên đăng nhập / mật khẩu</button>
      <button class="nav-btn" data-page="settings">⚙️ Thông tin xứ đoàn</button>
      <button class="nav-btn" data-page="parishes">⛪ giáo xứ</button>
      <button class="nav-btn hidden" data-page="accounts" id="accountsNav">🔐 Quản lý tài khoản</button>
    </nav>
    <div class="nav-label">Tài khoản</div>
    <button class="nav-btn" id="logoutBtn">↪ Đăng xuất</button>
  </aside>
  <main class="main">
    <header class="topbar">
      <div class="topbar-left"><button type="button" class="back-btn" id="backBtn">← Quay lại</button><div><h1 id="pageTitle">Tổng quan</h1><p id="parishSubtitle">Xin chào! Chúc bạn một ngày phục vụ đầy niềm vui.</p></div></div>
      <div class="userbox"><div class="avatar">A</div><div><b>Quản trị viên</b><div class="muted">Administrator</div></div></div>
    </header>
    <div id="page-dashboard" class="page">
      <div class="notice">🙏 <b>Hiệp hành – Phục vụ – Yêu thương.</b>  </div>
      <div class="cards">
        <div class="stat"><div class="stat-top">Tổng thiếu nhi <span class="ico">👧</span></div><div class="num" id="totalMembers">0</div><div class="muted">Thiếu nhi đang quản lý</div></div>
        <div class="stat"><div class="stat-top">Giáo lý viên <span class="ico">🧑‍🏫</span></div><div class="num" id="totalLeaders">0</div><div class="muted">Đang phục vụ</div></div>
        <div class="stat"><div class="stat-top">Có mặt hôm nay <span class="ico">✅</span></div><div class="num" id="presentCount">0</div><div class="muted">Theo điểm danh gần nhất</div></div>
        <div class="stat"><div class="stat-top">Vắng hôm nay <span class="ico">🗓️</span></div><div class="num" id="absentCount">0</div><div class="muted">Có phép và không phép</div></div>
        <div class="stat"><div class="stat-top">Tổng ghi nhận vi phạm <span class="ico">⚠️</span></div><div class="num" id="totalViolations">0</div><div class="muted">Tất cả ghi nhận đã lưu</div></div>
      </div>
      <section class="panel"><div class="panel-head"><h2>📊 Tổng quan vi phạm / nề nếp</h2><button onclick="showPage('violations')">Quản lý vi phạm →</button></div><div class="cards" style="margin-bottom:16px"><div class="stat"><div class="stat-top">Vắng không phép</div><div class="num" id="overviewUnexcused">0</div></div><div class="stat"><div class="stat-top">Vắng có phép</div><div class="num" id="overviewExcused">0</div></div><div class="stat"><div class="stat-top">Vi phạm khác</div><div class="num" id="overviewOther">0</div></div></div><div class="muted" style="margin-bottom:10px">Danh sách hiển thị toàn bộ ghi nhận vi phạm đã lưu, không giới hạn số dòng hiển thị bởi ứng dụng.</div><div class="table-wrap"><table><thead><tr><th>Ngày</th><th>Buổi</th><th>Thiếu nhi</th><th>Ngành</th><th>Nội dung</th><th>Ghi chú</th></tr></thead><tbody id="dashboardViolations"></tbody></table></div></section>
      <section class="panel"><div class="panel-head"><h2>Thiếu nhi mới cập nhật</h2><button onclick="showPage('members')">Quản lý thiếu nhi →</button></div><div class="table-wrap"><table><thead><tr><th>Họ và tên</th><th>Ngành</th><th>Lớp giáo lý</th><th>Ngày sinh</th></tr></thead><tbody id="recentMembers"></tbody></table></div></section>
    </div>

    <div id="page-members" class="page hidden">
      <section class="panel">
        <div class="panel-head"><div><h2>Danh sách thiếu nhi</h2><div class="muted">Thêm mới, tìm kiếm và xóa thông tin thiếu nhi.</div></div><button id="addMemberBtn">＋ Thêm thiếu nhi</button></div>
        <div class="toolbar"><input id="memberSearch" placeholder="Tìm theo họ tên..." aria-label="Tìm thiếu nhi"><select id="memberFilter"><option value="">Tất cả ngành</option><option>Chiên Con</option><option>Ấu Nhi</option><option>Thiếu Nhi</option><option>Nghĩa Sĩ</option></select><select id="memberParishFilter" aria-label="Chọn giáo xứ để xem hoặc thêm thiếu nhi"><option value="">Tất cả giáo xứ</option></select><button class="secondary" id="importMembersBtn">⬆ Tải tệp lên / Nhập danh sách</button><input id="importMembersFile" type="file" accept=".xlsx,.xls,.csv,.txt,.json" class="hidden"><button class="success" id="exportMembers">⬇ Tải Excel thông tin thiếu nhi</button></div><p class="muted" style="margin:8px 0 14px">Cách dùng: chọn một giáo xứ ở danh sách trên, sau đó nhấn “Thêm thiếu nhi”; giáo xứ đã chọn sẽ tự điền vào biểu mẫu. Danh sách bên dưới chỉ hiển thị thiếu nhi thuộc giáo xứ đang chọn.</p>
        <div id="memberFormWrap" class="hidden">
          <form id="memberForm" class="panel" style="background:#f8faff">
            <div class="panel-head"><h2>Thông tin thiếu nhi</h2></div><input type="hidden" id="memberId">
            <div class="form-grid">
              <div class="field"><label>Họ và tên *</label><input id="mName" required></div>
              <div class="field"><label>Ngày sinh</label><input id="mBirth" type="date"></div>
              <div class="field"><label>Giới tính</label><select id="mGender"><option>Nam</option><option>Nữ</option><option>Khác</option></select></div>
              <div class="field"><label>Ngành</label><select id="mBranch"><option>Chiên Con</option><option>Ấu Nhi</option><option>Thiếu Nhi</option><option>Nghĩa Sĩ</option></select></div>
              <div class="field"><label>Lớp giáo lý</label><input id="mClass" placeholder="Ví dụ: Khai tâm 2"></div>
              <div class="field"><label>Người dạy / Giáo lý viên phụ trách</label><input id="mTeacher" placeholder="Tên người dạy"></div>
              <div class="field"><label>Chức vụ đoàn sinh</label><select id="mRole"><option value="">-- Chọn chức vụ --</option><option>Đoàn sinh</option><option>Đội trưởng</option><option>Đội phó</option><option>Phân đoàn trưởng</option><option>Phân đoàn phó</option><option>Ủy viên ngành</option><option>Khác</option></select></div>
              <div class="field"><label>Giáo xứ *</label><select id="mParish" required><option value="">-- Chọn giáo xứ --</option></select></div>
              <div class="field"><label>Số điện thoại phụ huynh</label><input id="mPhone" type="tel" placeholder="Số điện thoại"></div>
            </div><div class="form-actions"><button type="button" class="secondary" id="cancelMember">Hủy</button><button type="submit">Lưu thiếu nhi</button></div>
          </form>
        </div>
        <div class="table-wrap"><table><thead><tr><th>Họ và tên</th><th>Mã số ngành</th><th>Ngày sinh</th><th>Giới tính</th><th>Ngành</th><th>Lớp giáo lý</th><th>Người dạy</th><th>Chức vụ đoàn sinh</th><th>Giáo xứ</th><th>Phụ huynh</th><th>Thao tác</th></tr></thead><tbody id="membersTable"></tbody></table></div>
      </section>
    </div>

    <div id="page-attendance" class="page hidden">
      <section class="panel"><div class="panel-head"><div><h2>Điểm danh sinh hoạt</h2><div class="muted">Chọn ngày và đánh dấu tình trạng tham dự của từng đoàn sinh.</div></div></div>
        <div class="toolbar"><label style="align-self:center;font-size:13px;font-weight:bold">Ngày điểm danh</label><input type="date" id="attendanceDate"><button id="markAllPresent">Tất cả có mặt</button><button class="secondary" id="saveAttendance">Lưu điểm danh</button></div>
        <div class="toolbar"><input id="attendanceSearch" placeholder="Tìm đoàn sinh..." aria-label="Tìm trong điểm danh"><button id="startQrScanner">📷 Quét mã QR điểm danh</button><button class="secondary" id="stopQrScanner">Dừng quét</button></div><div id="qrScannerWrap" class="panel hidden"><div class="muted" style="margin-bottom:10px">Cho phép trình duyệt sử dụng camera, sau đó đưa mã QR của thiếu nhi vào khung quét.</div><div id="qr-reader" style="max-width:480px"></div><div id="qrScanMessage" class="muted" style="margin-top:10px"></div></div>
        <div class="table-wrap"><table><thead><tr><th>Họ và tên</th><th>Ngành</th><th>Tình trạng</th></tr></thead><tbody id="attendanceTable"></tbody></table></div>
      </section>
    </div>

    <div id="page-violations" class="page hidden">
      <section class="panel">
        <div class="panel-head"><div><h2>Ghi nhận vi phạm / nề nếp</h2><div class="muted">Ghi nhận đoàn sinh, ngày tháng năm, buổi sáng/chiều và nội dung vi phạm hoặc vắng mặt.</div></div></div>
        <form id="violationForm" class="panel" style="background:#f8faff">
          <div class="form-grid">
            <div class="field"><label>Chọn thiếu nhi *</label><select id="vMember" required><option value="">-- Chọn thiếu nhi --</option></select></div>
            <div class="field"><label>Ngày tháng năm *</label><input id="vDate" type="date" required></div>
            <div class="field"><label>Buổi *</label><select id="vSession" required><option value="Sáng">Sáng</option><option value="Chiều">Chiều</option></select></div>
            <div class="field"><label>Tên vi phạm *</label><input id="vType" list="violationTypes" required placeholder="Chọn hoặc nhập tên vi phạm"><datalist id="violationTypes"><option value="Hút thuốc"><option value="Sai đồng phục"><option value="Mang dép"><option value="Đi trễ"><option value="Vắng có phép"><option value="Vắng không phép"><option value="Khác"></datalist></div>
            <div class="field"><label>Người nhập *</label><input id="vEnteredBy" required placeholder="Nhập họ tên người ghi nhận"></div>
            <div class="field" style="grid-column:1/-1"><label>Ghi chú / lý do / cách xử lý</label><input id="vNote" maxlength="500" placeholder="Nhập thêm chi tiết (nếu có)"></div>
          </div>
          <div class="form-actions"><button type="reset" class="secondary" id="resetViolation">Làm mới</button><button type="submit">Lưu ghi nhận</button></div>
        </form>
        <div class="toolbar"><input id="violationSearch" placeholder="Tìm theo tên đoàn sinh..."><select id="violationTypeFilter"><option value="">Tất cả nội dung</option><option>Hút thuốc</option><option>Sai đồng phục</option><option>Mang dép</option><option>Đi trễ</option><option>Vắng có phép</option><option>Vắng không phép</option><option>Khác</option></select><input id="violationDateFilter" type="date" aria-label="Lọc theo ngày"><button class="secondary" id="exportViolations">Xuất CSV</button></div>
        <div class="table-wrap"><table><thead><tr><th>Ngày tháng năm</th><th>Buổi</th><th>Thiếu nhi</th><th>Ngành</th><th>Tên vi phạm</th><th>Người nhập</th><th>Ghi chú</th><th>Thao tác</th></tr></thead><tbody id="violationsTable"></tbody></table></div>
      </section>
    </div>

    <div id="page-grades" class="page hidden">
      <section class="panel">
        <div class="panel-head"><div><h2>Nhập điểm đoàn sinh</h2><div class="muted">Nhập điểm từ 1 đến 10 cho từng đoàn sinh. Điểm được lưu trên trình duyệt của thiết bị này.</div></div></div>
        <div class="toolbar">
          <input id="gradeSearch" placeholder="Tìm đoàn sinh..." aria-label="Tìm đoàn sinh nhập điểm">
          <select id="gradeBranchFilter" aria-label="Lọc theo ngành"><option value="">Tất cả ngành</option><option>Chiên Con</option><option>Ấu Nhi</option><option>Thiếu Nhi</option><option>Nghĩa Sĩ</option></select>
          <select id="gradeParishFilter" aria-label="Lọc theo giáo xứ"><option value="">Tất cả giáo xứ</option></select>
        </div>
        <div class="table-wrap"><table><thead><tr><th>Họ và tên</th><th>Ngành</th><th>Giáo xứ</th><th>Điểm (1–10)</th><th>Ghi chú</th><th>Thao tác</th></tr></thead><tbody id="gradesTable"></tbody></table></div>
      </section>
    </div>

    <div id="page-leaders" class="page hidden">
      <section class="panel"><div class="panel-head"><div><h2>Danh sách huynh trưởng</h2><div class="muted">Quản lý người phục vụ trong xứ đoàn.</div></div><button id="addLeaderBtn">＋ Thêm huynh trưởng</button></div>
        <div id="leaderFormWrap" class="hidden"><form id="leaderForm" class="panel" style="background:#f8faff"><input type="hidden" id="leaderId"><div class="form-grid"><div class="field"><label>Họ và tên *</label><input id="lName" required></div><div class="field"><label>Chức vụ</label><input id="lRole" placeholder="Ví dụ: Xứ đoàn trưởng"></div><div class="field"><label>Số điện thoại</label><input id="lPhone" type="tel"></div><div class="field"><label>Email cá nhân</label><input id="lEmail" type="email" placeholder="ten@example.com"></div><div class="field"><label>Ngành phụ trách</label><select id="lBranch"><option>Toàn xứ đoàn</option><option>Chiên Con</option><option>Ấu Nhi</option><option>Thiếu Nhi</option><option>Nghĩa Sĩ</option></select></div><div class="field"><label>Lớp dạy phụ trách</label><input id="lClass" placeholder="Ví dụ: Khai tâm 2, Rước lễ 1, Thêm sức"></div><div class="field"><label>Giáo xứ/giáo họ phục vụ</label><select id="lParish"><option value="">-- Chọn giáo xứ/giáo họ --</option></select></div></div><div class="form-actions"><button type="button" class="secondary" id="cancelLeader">Hủy</button><button type="submit">Lưu huynh trưởng</button></div></form></div>
        <div class="table-wrap"><table><thead><tr><th>Họ và tên</th><th>Chức vụ</th><th>Ngành phụ trách</th><th>Lớp dạy phụ trách</th><th>Giáo xứ/giáo họ phục vụ</th><th>Điện thoại</th><th>Email</th><th>Thao tác</th></tr></thead><tbody id="leadersTable"></tbody></table></div>
      </section>
    </div>

    <div id="page-profile" class="page hidden">
      <section class="panel">
        <div class="panel-head"><div><h2>Thông tin cá nhân</h2><div class="muted">Cập nhật email, số điện thoại và giáo xứ của bạn.</div></div></div>
        <form id="profileForm">
          <div class="form-grid">
            <div class="field"><label for="pName">Họ và tên</label><input id="pName" autocomplete="name" placeholder="Nhập họ và tên"></div>
            <div class="field"><label for="pRole">Chức vụ / vai trò</label><select id="pRole"><option value="">-- Chọn chức vụ --</option><option>Huynh trưởng</option><option>Xứ đoàn trưởng</option><option>Dự trưởng</option><option>Giáo lý viên</option><option>Thầy</option><option>Cha</option><option>Sơ</option><option>Khác</option></select></div>
            <div class="field"><label for="pEmail">Email cá nhân</label><input id="pEmail" type="email" autocomplete="email" placeholder="ten@example.com"></div>
            <div class="field"><label for="pPhone">Số điện thoại</label><input id="pPhone" type="tel" autocomplete="tel" placeholder="Nhập số điện thoại"></div>
            <div class="field"><label for="pParish">Giáo xứ / giáo họ</label><select id="pParish"><option value="">-- Chọn giáo xứ / giáo họ --</option></select></div>
          </div>
          <div class="form-actions"><button type="submit">Lưu thông tin cá nhân</button></div>
        </form>
      </section>
    </div>

    <div id="page-settings" class="page hidden">
      <section class="panel"><div class="panel-head"><h2>Thông tin xứ đoàn</h2></div><form id="settingsForm"><div class="form-grid">
        <div class="field"><label>Tên giáo hạt</label><input id="sDeanery" placeholder="Ví dụ: Giáo hạt Hà Tiên"></div>
        <div class="field"><label>Tên giáo xứ</label><select id="sParish"><option value="">-- Chọn giáo xứ --</option></select></div>
        <div class="field"><label>Tên xứ đoàn</label><input id="sGroup" placeholder="Ví dụ: Xứ đoàn Don Bosco"></div>
        <div class="field"><label>Người phụ trách</label><input id="sManager" placeholder="Tên xứ đoàn trưởng"></div>
      </div><div class="form-actions"><button type="submit">Lưu thông tin</button></div></form></section>
      <section class="panel"><h2>Sao lưu dữ liệu</h2><p class="muted">Tải xuống bản sao dữ liệu đang lưu trên trình duyệt để dự phòng.</p><button id="backupBtn">Tải bản sao lưu JSON</button> <button class="danger" id="clearBtn">Xóa toàn bộ dữ liệu</button></section>
    </div>

    <div id="page-parishes" class="page hidden">
      <section class="panel">
        <div class="panel-head"><div><h2>Danh mục giáo xứ Giáo phận Long Xuyên</h2><div class="muted">Danh sách tham khảo được tổng hợp từ danh bạ giáo xứ trực tuyến; vui lòng đối chiếu với Văn phòng Giáo phận khi cần danh sách hành chính chính thức.</div></div><button class="secondary" id="exportParishes">Xuất danh mục CSV</button></div>
        <div class="toolbar"><input id="parishSearch" placeholder="Tìm tên giáo xứ..." aria-label="Tìm tên giáo xứ"><select id="parishDeaneryFilter"><option value="">Tất cả giáo hạt</option></select><span class="muted" id="parishCount" style="align-self:center"></span></div>
        <div class="table-wrap"><table><thead><tr><th>STT</th><th>Tên giáo xứ/giáo họ</th><th>Giáo hạt</th><th>Thao tác</th></tr></thead><tbody id="parishesTable"></tbody></table></div>
      </section>
      <div class="notice">Lưu ý: danh bạ trực tuyến có cách phân nhóm giáo hạt chưa hoàn toàn thống nhất giữa các nguồn và có mục trùng tên. Danh sách này đã loại mục trùng lặp hiển thị, đồng thời giữ các giáo xứ trùng tên bằng nhãn phân biệt khi cần.</div>
    </div>

    <div id="page-accountSettings" class="page hidden">
      <section class="panel">
        <div class="panel-head"><div><h2>Thay đổi tên đăng nhập và mật khẩu</h2><div class="muted">Mọi tài khoản, kể cả Admin, đều có thể tự cập nhật thông tin đăng nhập của mình.</div></div></div>
        <form id="accountSettingsForm">
          <div class="form-grid">
            <div class="field"><label for="changeCode">Mã xác nhận</label><input id="changeCode" type="password" inputmode="numeric" required placeholder="Nhập mã xác nhận"></div>
            <div class="field"><label for="changeCurrentPassword">Mật khẩu hiện tại</label><input id="changeCurrentPassword" type="password" required autocomplete="current-password" placeholder="Mật khẩu đang dùng"></div>
            <div class="field"><label for="changeUsername">Tên đăng nhập mới</label><input id="changeUsername" required minlength="3" maxlength="40" autocomplete="username"></div>
            <div class="field"><label for="changeNewPassword">Mật khẩu mới (không bắt buộc)</label><input id="changeNewPassword" type="password" minlength="8" autocomplete="new-password" placeholder="Ít nhất 8 ký tự"></div>
            <div class="field"><label for="changeConfirmPassword">Nhập lại mật khẩu mới</label><input id="changeConfirmPassword" type="password" minlength="8" autocomplete="new-password" placeholder="Nhập lại mật khẩu mới"></div>
          </div>
          <div class="error" id="accountSettingsError" role="alert"></div>
          <div class="form-actions"><button type="reset" class="secondary">Làm mới</button><button type="submit">Lưu thay đổi</button></div>
        </form>
      </section>
    </div>

    <div id="page-accounts" class="page hidden">
      <section class="panel"><div class="panel-head"><div><h2>Quản lý tài khoản đăng ký</h2><div class="muted">Chỉ quản trị viên mới xem được danh sách và đặt lại mật khẩu tài khoản.</div></div><button class="secondary" id="refreshAccounts">Làm mới</button></div>
        <div class="notice">Vì lý do bảo mật, hệ thống không hiển thị mật khẩu hiện tại. Quản trị viên có thể đặt mật khẩu mới cho tài khoản.</div>
        <div class="table-wrap"><table><thead><tr><th>Họ tên</th><th>Tên đăng nhập</th><th>Email</th><th>Ngày đăng ký</th><th>Lần đăng nhập gần nhất</th><th>Vai trò</th><th>Đổi mật khẩu</th></tr></thead><tbody id="accountsTable"></tbody></table></div>
      </section>
      <section class="panel"><h2>Đổi mật khẩu quản trị viên</h2><form id="adminPasswordForm" class="form-grid"><div class="field"><label>Mật khẩu hiện tại</label><input id="adminOldPassword" type="password" required></div><div class="field"><label>Mật khẩu mới (ít nhất 8 ký tự)</label><input id="adminNewPassword" type="password" required minlength="8"></div><div class="field"><label>Nhập lại mật khẩu mới</label><input id="adminConfirmPassword" type="password" required minlength="8"></div><div class="form-actions"><button type="submit">Cập nhật mật khẩu</button></div></form><div class="error" id="adminPasswordMessage"></div></section>
    </div>

  
  </main>
</div>
<div id="memberQrModal" class="qr-modal hidden" role="dialog" aria-modal="true" aria-labelledby="qrModalTitle"><div class="qr-modal-box"><div class="panel-head"><h2 id="qrModalTitle">Mã QR thiếu nhi</h2><button class="secondary" type="button" onclick="closeMemberQR()">Đóng</button></div><div id="memberQrContent" class="qr-card"></div><p class="muted">Mã QR chứa mã định danh của thiếu nhi để điểm danh. Không ghi số điện thoại phụ huynh vào mã QR.</p><div class="form-actions"><button type="button" onclick="printMemberQR()">🖨 In mã QR</button><button type="button" class="secondary" onclick="closeMemberQR()">Hoàn tất</button></div></div></div>
<script src="https://cdn.jsdelivr.net/npm/xlsx@0.18.5/dist/xlsx.full.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/html5-qrcode@2.3.8/html5-qrcode.min.js"></script>
<script>
const $ = id => document.getElementById(id);
const STORE='tntt_manager_v1';
let data={members:[],leaders:[],attendance:{},grades:{},violations:[],profile:{name:'',email:'',phone:'',parish:''},settings:{deanery:'',parish:'',group:'',manager:''}};
function loadData(){try{const d=JSON.parse(localStorage.getItem(STORE));if(d)data={...data,...d,grades:d.grades||{},violations:d.violations||[],profile:{...data.profile,...(d.profile||{})},settings:{...data.settings,...(d.settings||{})}}}catch(e){}}
function persist(){ensureMemberCodes();localStorage.setItem(STORE,JSON.stringify(data));renderAll()}
function esc(s=''){return String(s).replace(/[&<>"']/g,c=>({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":'&#39;'}[c]))}
function today(){const d=new Date();return `${d.getFullYear()}-${String(d.getMonth()+1).padStart(2,'0')}-${String(d.getDate()).padStart(2,'0')}`}
let pageHistory=[];let currentPage='dashboard';
function showPage(name,fromBack=false){if(name==='accounts'&&(!currentUser||currentUser.role!=='admin')){alert('Chỉ quản trị viên mới được truy cập mục này.');return}if(name!==currentPage){if(!fromBack)pageHistory.push(currentPage);currentPage=name;}document.querySelectorAll('.page').forEach(p=>p.classList.add('hidden'));$('page-'+name).classList.remove('hidden');document.querySelectorAll('.nav-btn[data-page]').forEach(b=>b.classList.toggle('active',b.dataset.page===name));const titles={dashboard:'Tổng quan',members:'Quản lý thiếu nhi',attendance:'Điểm danh',violations:'Vi phạm / nề nếp',grades:'Nhập điểm đoàn sinh',leaders:'Quản lý huynh trưởng',profile:'Thông tin cá nhân',settings:'Thông tin xứ đoàn',parishes:'Danh mục giáo xứ',accounts:'Quản lý tài khoản',accountSettings:'Đổi tên đăng nhập / mật khẩu'};$('pageTitle').textContent=titles[name];if(name==='attendance')renderAttendance();if(name==='violations'){renderViolationMembers();renderViolations();if(currentUser&&!$('vEnteredBy').value)$('vEnteredBy').value=currentUser.name}if(name==='grades')renderGrades();if(name==='profile')fillProfile();if(name==='settings')fillSettings();if(name==='parishes')initParishDirectory();if(name==='accounts')renderAccounts();if(name==='accountSettings')fillAccountSettings()}
document.querySelectorAll('.nav-btn[data-page]').forEach(b=>b.addEventListener('click',()=>showPage(b.dataset.page)));
$('backBtn').addEventListener('click',()=>{if(pageHistory.length){const previous=pageHistory.pop();showPage(previous,true)}else if(currentPage!=='dashboard'){showPage('dashboard',true)}else{alert('Bạn đang ở trang Tổng quan.')}});
const ACCOUNT_STORE='tntt_accounts_v1';
let currentUser=null;
function readAccounts(){try{return JSON.parse(localStorage.getItem(ACCOUNT_STORE)||'[]')}catch(e){return []}}
function saveAccounts(a){localStorage.setItem(ACCOUNT_STORE,JSON.stringify(a))}
function getAdminUsername(){return localStorage.getItem('tntt_admin_username')||'admin'}
async function hashText(value){if(!window.crypto||!crypto.subtle)throw new Error('Trình duyệt này không hỗ trợ mã hóa mật khẩu. Hãy mở bằng trình duyệt mới hoặc localhost.');const bytes=new TextEncoder().encode(value);const digest=await crypto.subtle.digest('SHA-256',bytes);return [...new Uint8Array(digest)].map(b=>b.toString(16).padStart(2,'0')).join('')}
function showAuth(which){['loginForm','registerForm','forgotForm'].forEach(id=>$(id).classList.toggle('hidden',id!==which));$('loginError').textContent='';$('registerError').textContent='';$('forgotError').textContent=''}
$('backLogin1').addEventListener('click',()=>showAuth('loginForm'));$('backLogin2').addEventListener('click',()=>showAuth('loginForm'));
$('registerForm').addEventListener('submit',async e=>{e.preventDefault();const name=$('regName').value.trim(),username=$('regUsername').value.trim(),email=$('regEmail').value.trim().toLowerCase(),password=$('regPassword').value,recovery=$('regRecovery').value.trim();try{const accounts=readAccounts();if(username.toLowerCase()===getAdminUsername().toLowerCase()||accounts.some(a=>a.username.toLowerCase()===username.toLowerCase()))throw new Error('Tên đăng nhập đã được sử dụng.');if(accounts.some(a=>a.email.toLowerCase()===email))throw new Error('Email này đã được đăng ký.');if(password.length<8||recovery.length<6)throw new Error('Mật khẩu cần ít nhất 8 ký tự, mã khôi phục ít nhất 6 ký tự.');accounts.push({id:crypto.randomUUID(),name,username,email,passwordHash:await hashText(password),recoveryHash:await hashText(recovery),createdAt:new Date().toISOString(),role:'user'});saveAccounts(accounts);alert('Đăng ký thành công! Hãy đăng nhập. Mã khôi phục không thể xem lại, hãy cất giữ riêng.');$('username').value=username;showAuth('loginForm')}catch(err){$('registerError').textContent=err.message||'Không thể đăng ký tài khoản.'}});
$('forgotForm').addEventListener('submit',async e=>{e.preventDefault();try{const accounts=readAccounts(),username=$('forgotUsername').value.trim(),email=$('forgotEmail').value.trim().toLowerCase(),recovery=$('forgotRecovery').value.trim(),next=$('forgotNewPassword').value;const a=accounts.find(x=>x.username.toLowerCase()===username.toLowerCase()&&x.email.toLowerCase()===email);if(!a||a.recoveryHash!==await hashText(recovery))throw new Error('Thông tin hoặc mã khôi phục không chính xác.');if(next.length<8)throw new Error('Mật khẩu mới cần ít nhất 8 ký tự.');a.passwordHash=await hashText(next);saveAccounts(accounts);alert('Đã đặt lại mật khẩu. Bạn có thể đăng nhập.');$('username').value=username;showAuth('loginForm')}catch(err){$('forgotError').textContent=err.message||'Không thể đặt lại mật khẩu.'}});
$('loginForm').addEventListener('submit',async e=>{
  e.preventDefault();
  const username=$('username').value.trim(),password=$('password').value;
  if(!username){$('loginError').textContent='Vui lòng nhập họ tên.';return}
  try{
    if(username.toLowerCase()===getAdminUsername().toLowerCase()){
      if(!password){$('loginError').textContent='Admin bắt buộc phải nhập mật khẩu.';return}
      const stored=localStorage.getItem('tntt_admin_hash');
      const valid=stored?stored===await hashText(password):password==='TNTT2026';
      if(!valid){$('loginError').textContent='Mật khẩu Admin không đúng.';return}
      localStorage.setItem('tntt_admin_last_login',new Date().toLocaleString('vi-VN'));
      currentUser={username:getAdminUsername(),name:'Quản trị viên',role:'admin'};
    }else{
      if(password){$('loginError').textContent='Người dùng thường không cần mật khẩu. Hãy để trống ô mật khẩu.';return}
      currentUser={username:username,name:username,role:'user'};
    }
    sessionStorage.setItem('tntt_logged_in','1');
    sessionStorage.setItem('tntt_user',currentUser.username);
    $('loginError').textContent='';
    enterApp();
  }catch(err){$('loginError').textContent=err.message||'Không thể vào hệ thống.'}
});
function fillAccountSettings(){if(!currentUser)return;$('changeUsername').value=currentUser.username;$('accountSettingsForm').reset();$('changeUsername').value=currentUser.username;$('accountSettingsError').textContent=''}
$('accountSettingsForm').addEventListener('submit',async e=>{e.preventDefault();const error=$('accountSettingsError');error.textContent='';try{
 const code=$('changeCode').value.trim(),current=$('changeCurrentPassword').value,username=$('changeUsername').value.trim(),next=$('changeNewPassword').value,confirmNext=$('changeConfirmPassword').value;
 if(code!=='100628')throw new Error('Mã xác nhận không chính xác.');if(username.length<3)throw new Error('Tên đăng nhập phải có ít nhất 3 ký tự.');if(next&&next.length<8)throw new Error('Mật khẩu mới phải có ít nhất 8 ký tự.');if(next!==confirmNext)throw new Error('Mật khẩu mới nhập lại chưa khớp.');if(!next&&confirmNext)throw new Error('Bạn đã nhập xác nhận nhưng chưa nhập mật khẩu mới.');
 const admin=currentUser.role==='admin';let accounts=readAccounts();if(admin){const valid=localStorage.getItem('tntt_admin_hash')?localStorage.getItem('tntt_admin_hash')===await hashText(current):current==='TNTT2026';if(!valid)throw new Error('Mật khẩu hiện tại không đúng.');if(accounts.some(a=>a.username.toLowerCase()===username.toLowerCase()))throw new Error('Tên đăng nhập này đã được tài khoản khác sử dụng.');localStorage.setItem('tntt_admin_username',username);if(next)localStorage.setItem('tntt_admin_hash',await hashText(next));}
 else{const a=accounts.find(x=>x.username===currentUser.username);if(!a||a.passwordHash!==await hashText(current))throw new Error('Mật khẩu hiện tại không đúng.');if(username.toLowerCase()!==currentUser.username.toLowerCase()&&(username.toLowerCase()===getAdminUsername().toLowerCase()||accounts.some(x=>x.id!==a.id&&x.username.toLowerCase()===username.toLowerCase())))throw new Error('Tên đăng nhập này đã được sử dụng.');a.username=username;if(next)a.passwordHash=await hashText(next);saveAccounts(accounts);}
 currentUser.username=username;sessionStorage.setItem('tntt_user',username);$('accountSettingsForm').reset();$('changeUsername').value=username;document.querySelector('.userbox b').textContent=currentUser.name;alert('Đã cập nhật tên đăng nhập / mật khẩu. Hãy dùng thông tin mới ở lần đăng nhập sau.');
 }catch(err){error.textContent=err.message||'Không thể cập nhật thông tin tài khoản.'}});
function enterApp(){if(!currentUser){const u=sessionStorage.getItem('tntt_user');if(u===getAdminUsername())currentUser={username:getAdminUsername(),name:'Quản trị viên',role:'admin'};else{const a=readAccounts().find(x=>x.username===u);if(a)currentUser={username:a.username,name:a.name,role:'user'}}}if(!currentUser){sessionStorage.removeItem('tntt_logged_in');return} $('loginScreen').style.display='none';$('app').style.display='block';document.querySelector('.userbox b').textContent=currentUser.name;document.querySelector('.userbox .muted').textContent=currentUser.role==='admin'?'Administrator':'Tài khoản người dùng';$('accountsNav').classList.toggle('hidden',currentUser.role!=='admin');renderAll()}
function renderAccounts(){
 if(!currentUser||currentUser.role!=='admin')return;
 const accounts=readAccounts();
 const adminRow=`<tr><td>Quản trị viên</td><td>${esc(getAdminUsername())}</td><td>—</td><td>—</td><td>${esc(localStorage.getItem('tntt_admin_last_login')||'Chưa ghi nhận')}</td><td>Admin</td><td>—</td></tr>`;
 const rows=accounts.map(a=>`<tr><td>${esc(a.name)}</td><td>${esc(a.username)}</td><td>${esc(a.email)}</td><td>${esc((a.createdAt||'').replace('T',' ').slice(0,16)||'—')}</td><td>${esc(a.lastLoginAt?(a.lastLoginAt.replace('T',' ').slice(0,16)):'Chưa đăng nhập')}</td><td>Người dùng</td><td><button onclick="adminResetAccount('${a.id}')">Đặt mật khẩu mới</button></td></tr>`).join('');
 $('accountsTable').innerHTML=adminRow+(rows||'<tr><td colspan="7" class="empty">Chưa có tài khoản đăng ký.</td></tr>');
}
$('refreshAccounts').addEventListener('click',renderAccounts);
$('adminPasswordForm').addEventListener('submit',async e=>{e.preventDefault();const msg=$('adminPasswordMessage');try{const old=$('adminOldPassword').value,next=$('adminNewPassword').value,confirmPass=$('adminConfirmPassword').value,stored=localStorage.getItem('tntt_admin_hash');const valid=stored?stored===await hashText(old):old==='TNTT2026';if(!valid)throw new Error('Mật khẩu hiện tại không đúng.');if(next.length<8)throw new Error('Mật khẩu mới cần ít nhất 8 ký tự.');if(next!==confirmPass)throw new Error('Mật khẩu nhập lại chưa khớp.');localStorage.setItem('tntt_admin_hash',await hashText(next));e.target.reset();msg.textContent='Đã cập nhật mật khẩu quản trị.'}catch(err){msg.textContent=err.message}});
$('logoutBtn').addEventListener('click',()=>{sessionStorage.removeItem('tntt_logged_in');sessionStorage.removeItem('tntt_user');currentUser=null;$('app').style.display='none';$('loginScreen').style.display='grid';$('password').value='';showAuth('loginForm')});
$('logoutBtn').addEventListener('click',()=>{sessionStorage.removeItem('tntt_logged_in');$('app').style.display='none';$('loginScreen').style.display='grid';$('password').value='';$('loginError').textContent=''});
function statusPill(s){let c=s==='Có mặt'?'present':s==='Vắng có phép'?'excused':s==='Vắng không phép'?'absent':'neutral';return `<span class="pill ${c}">${esc(s||'Chưa điểm danh')}</span>`}
function renderAll(){renderMembers();renderLeaders();renderDashboard();fillSettings();if(!$('page-attendance').classList.contains('hidden'))renderAttendance();if(!$('page-violations').classList.contains('hidden')){renderViolationMembers();renderViolations()}}
function renderDashboard(){const a=data.attendance[today()]||{};$('totalMembers').textContent=data.members.length;$('totalLeaders').textContent=data.leaders.length;$('presentCount').textContent=Object.values(a).filter(v=>v==='Có mặt').length;$('absentCount').textContent=Object.values(a).filter(v=>v==='Vắng có phép'||v==='Vắng không phép').length;const violations=Array.isArray(data.violations)?data.violations:[];$('totalViolations').textContent=violations.length;$('overviewUnexcused').textContent=violations.filter(v=>v.type==='Vắng không phép').length;$('overviewExcused').textContent=violations.filter(v=>v.type==='Vắng có phép').length;$('overviewOther').textContent=violations.filter(v=>v.type!=='Vắng có phép'&&v.type!=='Vắng không phép').length;const sortedViolations=violations.slice().sort((x,y)=>(y.date||'').localeCompare(x.date||'')||(y.createdAt||'').localeCompare(x.createdAt||''));$('dashboardViolations').innerHTML=sortedViolations.length?sortedViolations.map(v=>{const m=data.members.find(x=>x.id===v.memberId);return `<tr><td>${esc(v.date||'—')}</td><td>${esc(v.session||'—')}</td><td><b>${esc(m?.name||v.memberName||'Thiếu nhi đã xóa')}</b></td><td>${esc(m?.branch||v.branch||'—')}</td><td>${esc(v.type||'—')}</td><td>${esc(v.note||'—')}</td></tr>`}).join(''):`<tr><td colspan="6" class="empty">Chưa có ghi nhận vi phạm.</td></tr>`;const recent=[...data.members].slice(-5).reverse();$('recentMembers').innerHTML=recent.length?recent.map(m=>`<tr><td>${esc(m.name)}</td><td>${esc(m.branch)}</td><td>${esc(m.className||'—')}</td><td>${esc(m.birth||'—')}</td></tr>`).join(''):`<tr><td colspan="4" class="empty">Chưa có đoàn sinh. Hãy vào mục Quản lý đoàn sinh để thêm mới.</td></tr>`;$('parishSubtitle').textContent=[data.settings.deanery,data.settings.parish,data.settings.group].filter(Boolean).join(' · ')||'Xin chào! Chúc bạn một ngày phục vụ đầy niềm vui.'}
function memberCodePrefix(branch){const b=String(branch||'').toLocaleLowerCase('vi');if(b.includes('nghĩa sĩ')||b.includes('nghia si'))return 'NSI';if(b.includes('thiếu nhi')||b.includes('thieu nhi'))return 'TNI';if(b.includes('rước lễ')||b.includes('ruoc le'))return 'RLE';if(b.includes('bao đồng')||b.includes('bao dong'))return 'BDD';if(b.includes('chiên con')||b.includes('chien con'))return 'CIN';if(b.includes('ấu nhi')||b.includes('au nhi'))return 'ANI';return 'TNI'}
function ensureMemberCodes(){if(!Array.isArray(data.members))return;const used={};for(const m of data.members){const prefix=memberCodePrefix(m.branch);const match=String(m.memberCode||'').match(/^([A-Z]{3}) (\d+)$/);if(match&&match[1]===prefix&&!(used[prefix]||new Set()).has(Number(match[2]))&&Number(match[2])>0){m.memberCode=prefix+' '+Number(match[2]);(used[prefix]||(used[prefix]=new Set())).add(Number(match[2]));}}for(const m of data.members){const prefix=memberCodePrefix(m.branch);const match=String(m.memberCode||'').match(/^([A-Z]{3}) (\d+)$/);if(!match||match[1]!==prefix||!used[prefix]?.has(Number(match[2]))){const set=used[prefix]||(used[prefix]=new Set());let n=1;while(set.has(n))n++;m.memberCode=prefix+' '+n;set.add(n)}}}
function renderMembers(){ensureMemberCodes();const q=$('memberSearch').value.toLocaleLowerCase('vi'),f=$('memberFilter').value,pf=$('memberParishFilter')?.value||'';const arr=data.members.filter(m=>m.name.toLocaleLowerCase('vi').includes(q)&&(!f||m.branch===f)&&(!pf||m.parish===pf));$('membersTable').innerHTML=arr.length?arr.map(m=>`<tr><td><b>${esc(m.name)}</b></td><td><code>${esc(m.memberCode||'—')}</code></td><td>${esc(m.birth||'—')}</td><td>${esc(m.gender||'—')}</td><td>${esc(m.branch||'—')}</td><td>${esc(m.className||'—')}</td><td>${esc(m.teacher||'—')}</td><td>${esc(m.memberRole||'—')}</td><td>${esc(m.parish||'—')}</td><td>${esc(m.phone||'—')}</td><td><button class="secondary" onclick="showMemberQR('${m.id}')">▦ Mã QR</button> <button class="secondary" onclick="editMember('${m.id}')">Sửa</button> <button class="danger" onclick="deleteMember('${m.id}')">Xóa</button></td></tr>`).join(''):`<tr><td colspan="11" class="empty">Chưa có dữ liệu phù hợp.</td></tr>`}
$('memberSearch').addEventListener('input',renderMembers);$('memberFilter').addEventListener('change',renderMembers);$('memberParishFilter').addEventListener('change',renderMembers);
function openMember(m=null){$('memberFormWrap').classList.remove('hidden');$('memberId').value=m?.id||'';$('mName').value=m?.name||'';$('mBirth').value=m?.birth||'';$('mGender').value=m?.gender||'Nam';$('mBranch').value=m?.branch||'Chiên Con';$('mClass').value=m?.className||'';$('mTeacher').value=m?.teacher||'';$('mRole').value=m?.memberRole||'';populateMemberParishes();$('mParish').value=m?.parish||$('memberParishFilter').value||'';$('mPhone').value=m?.phone||'';$('mName').focus()}
$('addMemberBtn').addEventListener('click',()=>openMember());$('cancelMember').addEventListener('click',()=>$('memberFormWrap').classList.add('hidden'));
$('memberForm').addEventListener('submit',e=>{e.preventDefault();const id=$('memberId').value||crypto.randomUUID();const old=data.members.find(x=>x.id===id);const m={id,memberCode:old?.memberCode||'',name:$('mName').value.trim(),birth:$('mBirth').value,gender:$('mGender').value,branch:$('mBranch').value,className:$('mClass').value.trim(),teacher:$('mTeacher').value.trim(),memberRole:$('mRole').value,parish:$('mParish').value,phone:$('mPhone').value.trim()};const i=data.members.findIndex(x=>x.id===id);if(i>=0)data.members[i]=m;else data.members.push(m);ensureMemberCodes();$('memberFormWrap').classList.add('hidden');persist()});
function editMember(id){const m=data.members.find(x=>x.id===id);if(m)openMember(m)}
function deleteMember(id){const m=data.members.find(x=>x.id===id);if(m&&confirm(`Xóa đoàn sinh "${m.name}"?`)){data.members=data.members.filter(x=>x.id!==id);Object.values(data.attendance).forEach(day=>delete day[id]);persist()}}
let currentQrMemberId=null;let qrScanner=null;let qrScanBusy=false;
function qrPayload(m){return 'TNTT|'+m.id}
function qrImageUrl(payload){return 'https://api.qrserver.com/v1/create-qr-code/?size=300x300&data='+encodeURIComponent(payload)}
function showMemberQR(id){const m=data.members.find(x=>x.id===id);if(!m)return;currentQrMemberId=id;$('memberQrContent').innerHTML=`<img alt="Mã QR của ${esc(m.name)}" src="${qrImageUrl(qrPayload(m))}"><div><h3>${esc(m.name)}</h3><p><b>Ngành:</b> ${esc(m.branch||'—')}</p><p><b>Giáo xứ:</b> ${esc(m.parish||'—')}</p><p><b>Mã số ngành:</b> <code>${esc(m.memberCode||'—')}</code></p><p><b>Mã định danh:</b> <code>${esc(m.id)}</code></p></div>`;$('memberQrModal').classList.remove('hidden')}
function closeMemberQR(){$('memberQrModal').classList.add('hidden');currentQrMemberId=null}
function printMemberQR(){const m=data.members.find(x=>x.id===currentQrMemberId);if(!m)return;const w=window.open('','_blank','width=500,height=650');if(!w){alert('Trình duyệt đã chặn cửa sổ in. Hãy cho phép cửa sổ bật lên.');return}w.document.write(`<!doctype html><html lang="vi"><meta charset="utf-8"><title>Mã QR - ${esc(m.name)}</title><style>body{font-family:Arial;text-align:center;padding:28px}img{width:280px;height:280px}h2{margin-bottom:5px}</style><h2>THIẾU NHI THÁNH THỂ</h2><h3>${esc(m.name)}</h3><p>${esc(m.branch||'')} · ${esc(m.parish||'')}</p><h3>${esc(m.memberCode||'')}</h3><img src="${qrImageUrl(qrPayload(m))}"><p>Quét mã để điểm danh</p><script>window.onload=()=>window.print()<\/script></html>`);w.document.close()}
async function startQrScanner(){if(!window.isSecureContext){const msg='Camera quét QR chỉ hoạt động khi mở hệ thống bằng HTTPS hoặc localhost. Bạn đang mở file HTML trực tiếp hoặc bằng địa chỉ HTTP. Hãy đưa file lên dịch vụ HTTPS (ví dụ GitHub Pages), rồi mở lại đường dẫn https:// trên điện thoại.';$('qrScannerWrap').classList.remove('hidden');$('qrScanMessage').textContent=msg;alert(msg);return}if(!navigator.mediaDevices||!navigator.mediaDevices.getUserMedia){alert('Trình duyệt này không hỗ trợ camera. Hãy dùng Chrome mới nhất và mở trang HTTPS.');return}if(typeof Html5Qrcode==='undefined'){alert('Không tải được thư viện quét QR. Hãy kết nối Internet rồi tải lại trang.');return}if(qrScanner)return;$('qrScannerWrap').classList.remove('hidden');$('qrScanMessage').textContent='Đang khởi động camera…';qrScanner=new Html5Qrcode('qr-reader');try{await qrScanner.start({facingMode:'environment'},{fps:10,qrbox:{width:240,height:240}},decodedText=>{if(qrScanBusy)return;qrScanBusy=true;handleAttendanceQR(decodedText);setTimeout(()=>qrScanBusy=false,1600)},()=>{});$('qrScanMessage').textContent='Camera đang hoạt động. Hướng camera vào mã QR của thiếu nhi.'}catch(e){qrScanner=null;$('qrScanMessage').textContent='Không mở được camera. Hãy cấp quyền camera và mở trang bằng HTTPS hoặc localhost.';alert('Không thể mở camera. Hãy cấp quyền camera và dùng trang HTTPS hoặc localhost. Kiểm tra quyền camera của Chrome.') }}
async function stopQrScanner(){if(qrScanner){try{await qrScanner.stop();qrScanner.clear()}catch(e){}qrScanner=null}$('qrScannerWrap').classList.add('hidden')}
function handleAttendanceQR(text){const match=String(text||'').match(/^TNTT\|(.+)$/);if(!match){$('qrScanMessage').textContent='Mã QR không thuộc hệ thống Thiếu Nhi Thánh Thể.';return}const m=data.members.find(x=>x.id===match[1]);if(!m){$('qrScanMessage').textContent='Không tìm thấy thiếu nhi có mã này.';return}const date=$('attendanceDate').value||today();$('attendanceDate').value=date;if(!data.attendance[date])data.attendance[date]={};data.attendance[date][m.id]='Có mặt';persist();$('qrScanMessage').textContent='✓ Đã điểm danh có mặt: '+m.name+' — '+date;}
$('startQrScanner').addEventListener('click',startQrScanner);$('stopQrScanner').addEventListener('click',stopQrScanner);
function renderAttendance(){if(!$('attendanceDate').value)$('attendanceDate').value=today();const date=$('attendanceDate').value,records=data.attendance[date]||{},q=$('attendanceSearch').value.toLocaleLowerCase('vi');const arr=data.members.filter(m=>m.name.toLocaleLowerCase('vi').includes(q));$('attendanceTable').innerHTML=arr.length?arr.map(m=>`<tr><td><b>${esc(m.name)}</b></td><td>${esc(m.branch)}</td><td><select aria-label="Tình trạng ${esc(m.name)}" data-attendance-id="${m.id}"><option value="">Chưa điểm danh</option><option ${records[m.id]==='Có mặt'?'selected':''}>Có mặt</option><option ${records[m.id]==='Vắng có phép'?'selected':''}>Vắng có phép</option><option ${records[m.id]==='Vắng không phép'?'selected':''}>Vắng không phép</option></select></td></tr>`).join(''):`<tr><td colspan="3" class="empty">Chưa có đoàn sinh để điểm danh.</td></tr>`}
$('attendanceDate').value=today();$('attendanceDate').addEventListener('change',renderAttendance);$('attendanceSearch').addEventListener('input',renderAttendance);
$('markAllPresent').addEventListener('click',()=>document.querySelectorAll('[data-attendance-id]').forEach(s=>s.value='Có mặt'));
$('saveAttendance').addEventListener('click',()=>{const date=$('attendanceDate').value;if(!date){alert('Vui lòng chọn ngày điểm danh.');return}const records={...(data.attendance[date]||{})};document.querySelectorAll('[data-attendance-id]').forEach(s=>{if(s.value)records[s.dataset.attendanceId]=s.value;else delete records[s.dataset.attendanceId]});data.attendance[date]=records;persist();alert('Đã lưu điểm danh ngày '+date+'.')});
function renderViolationMembers(){
  const select=$('vMember'); if(!select)return; const current=select.value;
  select.innerHTML='<option value="">-- Chọn thiếu nhi --</option>'+data.members.slice().sort((a,b)=>a.name.localeCompare(b.name,'vi')).map(m=>`<option value="${esc(m.id)}">${esc(m.name)}${m.branch?' — '+esc(m.branch):''}</option>`).join('');
  if(data.members.some(m=>m.id===current))select.value=current;
}
function renderViolations(){
  const q=($('violationSearch')?.value||'').toLocaleLowerCase('vi'),type=$('violationTypeFilter')?.value||'',date=$('violationDateFilter')?.value||'';
  const list=(data.violations||[]).filter(v=>{const m=data.members.find(x=>x.id===v.memberId);return (!q||(m?.name||v.memberName||'').toLocaleLowerCase('vi').includes(q))&&(!type||v.type===type)&&(!date||v.date===date)}).slice().sort((a,b)=>(b.date||'').localeCompare(a.date||'')||(b.createdAt||'').localeCompare(a.createdAt||''));
  $('violationsTable').innerHTML=list.length?list.map(v=>{const m=data.members.find(x=>x.id===v.memberId);return `<tr><td>${esc(v.date||'—')}</td><td>${esc(v.session||'—')}</td><td><b>${esc(m?.name||v.memberName||'Thiếu nhi đã xóa')}</b></td><td>${esc(m?.branch||v.branch||'—')}</td><td><span class="pill ${v.type==='Vắng không phép'?'absent':v.type==='Vắng có phép'?'excused':'neutral'}">${esc(v.type||'—')}</span></td><td>${esc(v.enteredBy||'—')}</td><td>${esc(v.note||'—')}</td><td><button class="danger" onclick="deleteViolation('${esc(v.id)}')">Xóa</button></td></tr>`}).join(''):`<tr><td colspan="8" class="empty">Chưa có ghi nhận phù hợp.</td></tr>`;
}
$('vDate').value=today();
$('vEnteredBy').value=currentUser?.name||'';
$('violationForm').addEventListener('submit',e=>{e.preventDefault();const member=data.members.find(m=>m.id===$('vMember').value);if(!member){alert('Vui lòng chọn đoàn sinh.');return}const record={id:crypto.randomUUID(),memberId:member.id,memberName:member.name,branch:member.branch||'',date:$('vDate').value,session:$('vSession').value,type:$('vType').value.trim(),enteredBy:$('vEnteredBy').value.trim(),note:$('vNote').value.trim(),createdAt:new Date().toISOString()};if(!record.date){alert('Vui lòng chọn ngày.');return}if(!data.violations)data.violations=[];data.violations.push(record);persist();$('vMember').value='';$('vNote').value='';$('vType').value='';$('vEnteredBy').value=currentUser?.name||'';$('vDate').value=today();alert('Đã lưu ghi nhận.')});
$('violationSearch').addEventListener('input',renderViolations);$('violationTypeFilter').addEventListener('change',renderViolations);$('violationDateFilter').addEventListener('change',renderViolations);
$('resetViolation').addEventListener('click',()=>setTimeout(()=>{$('vDate').value=today();$('vEnteredBy').value=currentUser?.name||''},0));
function deleteViolation(id){const v=(data.violations||[]).find(x=>x.id===id);if(v&&confirm('Bạn muốn xóa ghi nhận này?')){data.violations=data.violations.filter(x=>x.id!==id);persist()}}
$('exportViolations').addEventListener('click',()=>{const rows=[['Ngày tháng năm','Buổi','Họ tên thiếu nhi','Ngành','Tên vi phạm','Người nhập','Ghi chú'],...(data.violations||[]).map(v=>{const m=data.members.find(x=>x.id===v.memberId);return [v.date,v.session,m?.name||v.memberName,m?.branch||v.branch,v.type,v.enteredBy,v.note]})];const csv='\ufeff'+rows.map(r=>r.map(v=>'"'+String(v||'').replace(/"/g,'""')+'"').join(',')).join('\r\n');downloadFile(csv,'danh-sach-vi-pham.csv','text/csv;charset=utf-8')});

function renderGrades(){
  const q=$('gradeSearch').value.toLocaleLowerCase('vi');
  const branch=$('gradeBranchFilter').value;
  const parish=$('gradeParishFilter').value;
  const members=data.members.filter(m=>m.name.toLocaleLowerCase('vi').includes(q)&&(!branch||m.branch===branch)&&(!parish||m.parish===parish));
  const gradeData=data.grades||{};
  $('gradesTable').innerHTML=members.length?members.map(m=>{
    const g=gradeData[m.id]||{};
    const score=(g.score===undefined||g.score===null)?'':g.score;
    return `<tr><td><b>${esc(m.name)}</b></td><td>${esc(m.branch||'—')}</td><td>${esc(m.parish||'—')}</td><td><input type="number" min="1" max="10" step="1" value="${esc(score)}" data-grade-id="${esc(m.id)}" aria-label="Điểm của ${esc(m.name)}" style="width:95px;padding:8px;border:1px solid #d6deea;border-radius:8px" placeholder="1–10"></td><td><input type="text" value="${esc(g.note||'')}" data-grade-note-id="${esc(m.id)}" aria-label="Ghi chú điểm của ${esc(m.name)}" style="min-width:140px;padding:8px;border:1px solid #d6deea;border-radius:8px" placeholder="Nhận xét (nếu có)"></td><td><button onclick="saveGrade('${esc(m.id)}')">Lưu điểm</button></td></tr>`;
  }).join(''):`<tr><td colspan="6" class="empty">Chưa có đoàn sinh phù hợp. Hãy thêm đoàn sinh trong mục Quản lý đoàn sinh.</td></tr>`;
}
function populateGradeParishFilter(){
  const select=$('gradeParishFilter');
  if(!select)return;
  const current=select.value;
  const names=[...new Set(PARISH_DIRECTORY.map(p=>p.name))].sort((a,b)=>a.localeCompare(b,'vi'));
  select.innerHTML='<option value="">Tất cả giáo xứ</option>'+names.map(n=>`<option value="${esc(n)}">${esc(n)}</option>`).join('');
  select.value=current;
}
function saveGrade(id){
  const input=document.querySelector(`[data-grade-id="${CSS.escape(id)}"]`);
  const note=document.querySelector(`[data-grade-note-id="${CSS.escape(id)}"]`);
  if(!input)return;
  const raw=input.value.trim();
  if(raw!==''&&(!Number.isInteger(Number(raw))||Number(raw)<1||Number(raw)>10)){
    alert('Điểm phải là số nguyên từ 1 đến 10.');
    input.focus();
    return;
  }
  if(!data.grades)data.grades={};
  if(raw===''){
    delete data.grades[id];
  }else{
    data.grades[id]={score:Number(raw),note:note?.value.trim()||'',updatedAt:new Date().toISOString()};
  }
  persist();
  renderGrades();
  alert(raw===''?'Đã xóa điểm của đoàn sinh.':'Đã lưu điểm '+raw+' cho đoàn sinh.');
}
$('gradeSearch').addEventListener('input',renderGrades);
$('gradeBranchFilter').addEventListener('change',renderGrades);
$('gradeParishFilter').addEventListener('change',renderGrades);

function renderLeaders(){$('leadersTable').innerHTML=data.leaders.length?data.leaders.map(l=>`<tr><td><b>${esc(l.name)}</b></td><td>${esc(l.role||'—')}</td><td>${esc(l.branch||'—')}</td><td>${esc(l.className||'—')}</td><td>${esc(l.parish||'—')}</td><td>${esc(l.phone||'—')}</td><td>${esc(l.email||'—')}</td><td><button class="secondary" onclick="editLeader('${l.id}')">Sửa</button> <button class="danger" onclick="deleteLeader('${l.id}')">Xóa</button></td></tr>`).join(''):`<tr><td colspan="8" class="empty">Chưa có huynh trưởng.</td></tr>`}
function populateLeaderParishes(){const select=$('lParish');if(!select)return;const current=select.value;select.innerHTML='<option value="">-- Chọn giáo xứ/giáo họ --</option>'+PARISH_DIRECTORY.slice().sort((a,b)=>a.name.localeCompare(b.name,'vi')).map(p=>`<option value="${esc(p.name)}">${esc(p.type||'Giáo xứ')} ${esc(p.name)} (${esc(p.deanery)})</option>`).join('');select.value=current}
function openLeader(l=null){$('leaderFormWrap').classList.remove('hidden');$('leaderId').value=l?.id||'';$('lName').value=l?.name||'';$('lRole').value=l?.role||'';$('lPhone').value=l?.phone||'';$('lEmail').value=l?.email||'';$('lBranch').value=l?.branch||'Toàn xứ đoàn';$('lClass').value=l?.className||'';populateLeaderParishes();$('lParish').value=l?.parish||'';$('lName').focus()}
$('addLeaderBtn').addEventListener('click',()=>openLeader());$('cancelLeader').addEventListener('click',()=>$('leaderFormWrap').classList.add('hidden'));
$('leaderForm').addEventListener('submit',e=>{e.preventDefault();const id=$('leaderId').value||crypto.randomUUID(),l={id,name:$('lName').value.trim(),role:$('lRole').value.trim(),phone:$('lPhone').value.trim(),email:$('lEmail').value.trim(),branch:$('lBranch').value,className:$('lClass').value.trim(),parish:$('lParish').value};const i=data.leaders.findIndex(x=>x.id===id);if(i>=0)data.leaders[i]=l;else data.leaders.push(l);$('leaderFormWrap').classList.add('hidden');persist()});
function editLeader(id){const l=data.leaders.find(x=>x.id===id);if(l)openLeader(l)}
function deleteLeader(id){const l=data.leaders.find(x=>x.id===id);if(l&&confirm(`Xóa huynh trưởng "${l.name}"?`)){data.leaders=data.leaders.filter(x=>x.id!==id);persist()}}
function populateMemberParishes(){
  const filter = $('memberParishFilter');
  if(filter){const selected=filter.value;const names=[...new Set(PARISH_DIRECTORY.map(p=>p.name))].sort((a,b)=>a.localeCompare(b,'vi'));filter.innerHTML='<option value="">Tất cả giáo xứ/giáo họ</option>'+names.map(n=>{const p=PARISH_DIRECTORY.find(x=>x.name===n);return `<option value="${esc(n)}">${esc(p?.type||'Giáo xứ')} ${esc(n)}</option>`}).join('');filter.value=selected;}
  const select = $('mParish');
  if(!select) return;
  const current = select.value;
  select.innerHTML = '<option value="">-- Chọn giáo xứ --</option>' + PARISH_DIRECTORY
    .slice().sort((a,b)=>a.name.localeCompare(b.name,'vi'))
    .map(p=>`<option value="${esc(p.name)}">${esc(p.type||'Giáo xứ')} ${esc(p.name)} (${esc(p.deanery)})</option>`).join('');
  select.value = current;
}
function populateProfileParishes(){const select=$('pParish');if(!select)return;const current=select.value;select.innerHTML='<option value="">-- Chọn giáo xứ / giáo họ --</option>'+PARISH_DIRECTORY.slice().sort((a,b)=>a.name.localeCompare(b.name,'vi')).map(p=>`<option value="${esc(p.name)}">${esc(p.type||'Giáo xứ')} ${esc(p.name)} (${esc(p.deanery)})</option>`).join('');select.value=current}
function fillProfile(){const p=data.profile||{};$('pName').value=p.name||'';$('pRole').value=p.role||'';$('pEmail').value=p.email||'';$('pPhone').value=p.phone||'';populateProfileParishes();$('pParish').value=p.parish||''}
$('profileForm').addEventListener('submit',e=>{e.preventDefault();data.profile={name:$('pName').value.trim(),role:$('pRole').value,email:$('pEmail').value.trim(),phone:$('pPhone').value.trim(),parish:$('pParish').value};persist();alert('Đã lưu thông tin cá nhân.')});
function fillSettings(){const s=data.settings;$('sDeanery').value=s.deanery||'';$('sParish').value=s.parish||'';$('sGroup').value=s.group||'';$('sManager').value=s.manager||''}
$('settingsForm').addEventListener('submit',e=>{e.preventDefault();data.settings={deanery:$('sDeanery').value.trim(),parish:$('sParish').value.trim(),group:$('sGroup').value.trim(),manager:$('sManager').value.trim()};persist();alert('Đã lưu thông tin xứ đoàn.')});
// Nhập danh sách thiếu nhi từ Excel (.xlsx/.xls), CSV, TXT hoặc tệp sao lưu JSON.
$('importMembersBtn').addEventListener('click',()=>$('importMembersFile').click());
$('importMembersFile').addEventListener('change',async e=>{
  const file=e.target.files?.[0]; if(!file)return;
  try{
    let rows=[]; const ext=file.name.split('.').pop().toLowerCase();
    if(ext==='json'){
      const obj=JSON.parse(await file.text());
      rows=Array.isArray(obj)?obj:(Array.isArray(obj.members)?obj.members:[]);
      if(rows.length && (rows[0].name!==undefined || rows[0].hoTen!==undefined)){
        rows=rows.map(x=>({memberCode:x.memberCode||x.maNganh||x['Mã số ngành']||'',name:x.name||x.hoTen||x['Họ và tên']||'',branch:x.branch||x.nganh||x['Ngành']||'',memberRole:x.memberRole||x.chucVu||x['Chức vụ đoàn sinh']||'',teacher:x.teacher||x.nguoiDay||x['Người dạy / Giáo lý viên phụ trách']||'',phone:x.phone||x.lienHePhuHuynh||x['Liên hệ phụ huynh']||'',className:x.className||x.lop||x['Lớp giáo lý']||'',birth:x.birth||x.ngaySinh||x['Ngày sinh']||'',gender:x.gender||x.gioiTinh||x['Giới tính']||'',parish:x.parish||x.giaoXu||x['Giáo xứ']||''}));
      }
    } else if(window.XLSX && ['xlsx','xls','csv','txt'].includes(ext)) {
      const buf=await file.arrayBuffer(); const wb=XLSX.read(buf,{type:'array',cellDates:false});
      const sheet=wb.Sheets[wb.SheetNames[0]]; rows=XLSX.utils.sheet_to_json(sheet,{defval:'',raw:false});
    } else {
      const txt=await file.text(); rows=parseImportCsv(txt);
    }
    if(!rows.length) throw new Error('Không tìm thấy dòng dữ liệu trong tệp.');
    const norm=v=>String(v??'').trim().toLocaleLowerCase('vi').normalize('NFD').replace(/[\u0300-\u036f]/g,'').replace(/đ/g,'d').replace(/[^a-z0-9]/g,'');
    const get=(o,names)=>{const keys=Object.keys(o);for(const n of names){const k=keys.find(x=>norm(x)===norm(n));if(k!==undefined)return String(o[k]??'').trim()}return ''};
    const fallbackParish=$('memberParishFilter')?.value||data.settings?.parish||'';
    let added=0,skipped=0;
    for(const raw of rows){
      const name=get(raw,['Họ và tên','Họ tên','Tên','name','hoTen']); if(!name){skipped++;continue;}
      const parish=get(raw,['Giáo xứ','Xứ đoàn','parish','giaoXu'])||fallbackParish;
      const exists=data.members.some(m=>norm(m.name)===norm(name)&&norm(m.parish||'')===norm(parish));
      if(exists){skipped++;continue;}
      let branch=get(raw,['Ngành','branch','nganh']);
      const branchOptions=['Chiên Con','Ấu Nhi','Thiếu Nhi','Nghĩa Sĩ'];
      if(!branchOptions.some(x=>norm(x)===norm(branch))) branch=branchOptions.find(x=>norm(x)===norm(branch))||'Chiên Con';
      data.members.push({id:crypto.randomUUID(),memberCode:get(raw,['Mã số ngành','memberCode','maNganh']),name,birth:get(raw,['Ngày sinh','birth','ngaySinh']),gender:get(raw,['Giới tính','gender','gioiTinh'])||'Nam',branch,className:get(raw,['Lớp giáo lý','Lớp','className','lop']),teacher:get(raw,['Người dạy','Giáo lý viên phụ trách','Người dạy / Giáo lý viên phụ trách','teacher','nguoiDay']),memberRole:get(raw,['Chức vụ đoàn sinh','Chức vụ','memberRole','chucVu']),parish,phone:get(raw,['Liên hệ phụ huynh','Số điện thoại phụ huynh','Phụ huynh','phone','lienHePhuHuynh'])});
      added++;
    }
    persist(); alert(`Nhập danh sách hoàn tất!\nĐã thêm: ${added} thiếu nhi.\nBỏ qua: ${skipped} dòng (thiếu họ tên hoặc trùng tên trong cùng giáo xứ).${!fallbackParish?'\nLưu ý: các dòng không có cột Giáo xứ sẽ để trống giáo xứ.':''}`);
  }catch(err){alert('Không thể nhập tệp: '+(err?.message||'Định dạng không hợp lệ')+'\nHãy dùng Excel (.xlsx) hoặc CSV có hàng đầu là tiêu đề cột.');}
  e.target.value='';
});
function parseImportCsv(text){
  const first=text.split(/\r?\n/,1)[0]||''; const delimiter=first.includes('\t')?'\t':(first.split(';').length>first.split(',').length?';':',');
  const out=[];let row=[],field='',quoted=false;
  for(let i=0;i<text.length;i++){const c=text[i];if(c==='"'){if(quoted&&text[i+1]==='"'){field+='"';i++;}else quoted=!quoted;}else if(c===delimiter&&!quoted){row.push(field);field='';}else if((c==='\n'||c==='\r')&&!quoted){if(c==='\r'&&text[i+1]==='\n')i++;row.push(field);if(row.some(v=>v.trim()))out.push(row);row=[];field='';}else field+=c;}
  row.push(field);if(row.some(v=>v.trim()))out.push(row);if(out.length<2)return [];
  const headers=out.shift().map(h=>h.replace(/^\uFEFF/, '').trim());return out.map(r=>Object.fromEntries(headers.map((h,i)=>[h,r[i]||''])));
}

$('exportMembers').addEventListener('click',()=>{
  const headers=['Họ và tên','Mã số ngành','Ngành','Chức vụ đoàn sinh','Người dạy / Giáo lý viên phụ trách','Liên hệ phụ huynh','Lớp giáo lý','Ngày sinh','Giới tính','Giáo xứ'];
  const rows=data.members.map(m=>[m.name,m.memberCode,m.branch,m.memberRole,m.teacher,m.phone,m.className,m.birth,m.gender,m.parish]);
  const cell=v=>`<td style="mso-number-format:'\\@';">${esc(v==null?'':String(v))}</td>`;
  const table=`<table border="1"><thead><tr>${headers.map(h=>`<th>${esc(h)}</th>`).join('')}</tr></thead><tbody>${rows.map(r=>`<tr>${r.map(cell).join('')}</tr>`).join('')}</tbody></table>`;
  const workbook=`<html xmlns:o="urn:schemas-microsoft-com:office:office" xmlns:x="urn:schemas-microsoft-com:office:excel" xmlns="http://www.w3.org/TR/REC-html40"><head><meta charset="UTF-8"><!--[if gte mso 9]><xml><x:ExcelWorkbook><x:ExcelWorksheets><x:ExcelWorksheet><x:Name>Thong tin thieu nhi</x:Name><x:WorksheetOptions><x:DisplayGridlines/></x:WorksheetOptions></x:ExcelWorksheet></x:ExcelWorksheets></x:ExcelWorkbook></xml><![endif]--></head><body><h2>Danh sách thông tin Thiếu nhi Thánh Thể</h2>${table}</body></html>`;
  downloadFile('\ufeff'+workbook,'thong-tin-thieu-nhi.xls','application/vnd.ms-excel;charset=utf-8');
});
$('backupBtn').addEventListener('click',()=>downloadFile(JSON.stringify(data,null,2),'sao-luu-tntt.json','application/json'));
function downloadFile(content,name,type){const blob=new Blob([content],{type}),url=URL.createObjectURL(blob),a=document.createElement('a');a.href=url;a.download=name;a.click();URL.revokeObjectURL(url)}
$('clearBtn').addEventListener('click',()=>{if(confirm('Bạn chắc chắn muốn xóa toàn bộ đoàn sinh, huynh trưởng, điểm danh và thông tin xứ đoàn? Nên sao lưu trước.')){data={members:[],leaders:[],attendance:{},grades:{},violations:[],profile:{name:'',email:'',phone:'',parish:''},settings:{deanery:'',parish:'',group:'',manager:''}};persist();alert('Đã xóa dữ liệu trên trình duyệt này.')}});

const PARISH_DIRECTORY = [{"name": "An Bình", "deanery": "Rạch Giá"}, {"name": "An Châu", "deanery": "Long Xuyên"}, {"name": "An Dũng", "deanery": "Vĩnh Thạnh"}, {"name": "An Hòa", "deanery": "Long Xuyên"}, {"name": "An Sơn", "deanery": "Vĩnh Thạnh"}, {"name": "An Thới", "deanery": "Phú Quốc"}, {"name": "An Tôn", "deanery": "Tân Hiệp"}, {"name": "Ba Bần", "deanery": "Long Xuyên"}, {"name": "Ba Hòn", "deanery": "Hà Tiên"}, {"name": "Bắc Xuyên", "deanery": "Vĩnh Thạnh"}, {"name": "Bình An", "deanery": "Rạch Giá"}, {"name": "Bình Châu", "deanery": "Tân Hiệp"}, {"name": "Bình Lộc", "deanery": "Tân Hiệp"}, {"name": "Bình Minh", "deanery": "Vĩnh Thạnh"}, {"name": "Bình Sơn", "deanery": "Rạch Giá"}, {"name": "Bình Tây", "deanery": "Long Xuyên"}, {"name": "Bình Thái", "deanery": "Vĩnh Thạnh"}, {"name": "Bò Ót", "deanery": "Vĩnh Thạnh"}, {"name": "Cái Dầu", "deanery": "Long Xuyên"}, {"name": "Cái Đôi", "deanery": "Chợ Mới"}, {"name": "Cản Đá", "deanery": "Long Xuyên"}, {"name": "Cần Thay", "deanery": "Chợ Mới"}, {"name": "Cần Xây", "deanery": "Long Xuyên"}, {"name": "Chánh Tòa", "deanery": "Long Xuyên"}, {"name": "Châu Đốc", "deanery": "Long Xuyên"}, {"name": "Châu Long", "deanery": "Vĩnh Thạnh"}, {"name": "Châu Thái", "deanery": "Vĩnh Thạnh"}, {"name": "Chi Lăng", "deanery": "Long Xuyên"}, {"name": "Chợ Mới", "deanery": "Chợ Mới"}, {"name": "Chợ Thủ", "deanery": "Chợ Mới"}, {"name": "Cờ Trắng", "deanery": "Hà Tiên"}, {"name": "Cừ Đứt", "deanery": "Hà Tiên", "type": "Giáo điểm"}, {"name": "Cồn Én", "deanery": "Chợ Mới"}, {"name": "Cồn Phước", "deanery": "Chợ Mới"}, {"name": "Cồn Trên", "deanery": "Chợ Mới"}, {"name": "Cù Lao Giêng", "deanery": "Chợ Mới"}, {"name": "Đa Minh", "deanery": "Tân Hiệp"}, {"name": "Đài Đức Mẹ", "deanery": "Tân Hiệp"}, {"name": "Đất Hứa", "deanery": "Hà Tiên"}, {"name": "Đảo Hải Tặc", "deanery": "Phú Quốc", "type": "Nhà thờ"}, {"name": "Đền thánh Giuse", "deanery": "Rạch Giá"}, {"name": "Đền Thánh Giuse An Bình", "deanery": "Vĩnh Thạnh"}, {"name": "Định Mỹ", "deanery": "Long Xuyên"}, {"name": "Đồng Công", "deanery": "Vĩnh Thạnh"}, {"name": "Đông Hòa", "deanery": "Rạch Giá"}, {"name": "Đông Hưng", "deanery": "Rạch Giá"}, {"name": "Đồng Phú", "deanery": "Tân Hiệp"}, {"name": "Đồng Tâm", "deanery": "Tân Hiệp"}, {"name": "Đức Mẹ Vô Nhiễm", "deanery": "Rạch Giá"}, {"name": "Dương Đông", "deanery": "Phú Quốc"}, {"name": "Duy Ninh", "deanery": "Tân Hiệp"}, {"name": "Fatima", "deanery": "Long Xuyên"}, {"name": "Giang Thành", "deanery": "Hà Tiên", "type": "Giáo họ"}, {"name": "Giu Đức", "deanery": "Tân Hiệp"}, {"name": "Giuse", "deanery": "Tân Hiệp"}, {"name": "Hà Tiên", "deanery": "Hà Tiên"}, {"name": "Hải Châu", "deanery": "Tân Hiệp"}, {"name": "Hải Hưng", "deanery": "Vĩnh Thạnh"}, {"name": "Hiệp Hòa", "deanery": "Tân Hiệp"}, {"name": "Hiệp Tâm", "deanery": "Tân Hiệp"}, {"name": "Hiếu Hiệp", "deanery": "Vĩnh Thạnh"}, {"name": "Hiếu Sơn", "deanery": "Vĩnh Thạnh"}, {"name": "Hiếu Thuận", "deanery": "Vĩnh Thạnh"}, {"name": "Hòa Giang", "deanery": "Hà Tiên"}, {"name": "Hòa Hưng", "deanery": "Rạch Giá"}, {"name": "Hòa Lợi", "deanery": "Long Xuyên"}, {"name": "Hội An", "deanery": "Chợ Mới"}, {"name": "Hòn Chông", "deanery": "Hà Tiên"}, {"name": "Hợp Châu", "deanery": "Tân Hiệp"}, {"name": "Hợp Tiến", "deanery": "Vĩnh Thạnh"}, {"name": "Khánh Bình", "deanery": "Long Xuyên"}, {"name": "Khiết Tâm", "deanery": "Vĩnh Thạnh"}, {"name": "Kiên Bình", "deanery": "Hà Tiên", "type": "Giáo họ"}, {"name": "Kiên Lương", "deanery": "Hà Tiên", "type": "Giáo xứ"}, {"name": "Hòn Tre", "deanery": "Phú Quốc", "type": "Giáo xứ"}, {"name": "Kim Hòa", "deanery": "Vĩnh Thạnh"}, {"name": "Kim Long", "deanery": "Vĩnh Thạnh"}, {"name": "Kinh Tràm", "deanery": "Rạch Giá"}, {"name": "Kinh Xáng", "deanery": "Long Xuyên"}, {"name": "Kitô Vua (Tân Hiệp)", "deanery": "Tân Hiệp"}, {"name": "Kitô Vua (Vĩnh Thạnh)", "deanery": "Vĩnh Thạnh"}, {"name": "Lạng Sơn", "deanery": "Tân Hiệp"}, {"name": "Lấp Vò", "deanery": "Chợ Mới"}, {"name": "Lộ Đức", "deanery": "Long Xuyên"}, {"name": "Long Bình", "deanery": "Vĩnh Thạnh"}, {"name": "Martinô", "deanery": "Vĩnh Thạnh"}, {"name": "Mẫu Tâm", "deanery": "Tân Hiệp"}, {"name": "Minh Châu", "deanery": "Rạch Giá"}, {"name": "Minh Hòa", "deanery": "Rạch Giá"}, {"name": "Môi Khôi", "deanery": "Vĩnh Thạnh"}, {"name": "Mong Thọ", "deanery": "Rạch Giá"}, {"name": "Mông Triệu", "deanery": "Tân Hiệp"}, {"name": "Mỹ Luông", "deanery": "Chợ Mới"}, {"name": "Mỹ Thạnh", "deanery": "Long Xuyên"}, {"name": "Năng Gù", "deanery": "Long Xuyên"}, {"name": "Ngọc Thạch", "deanery": "Vĩnh Thạnh"}, {"name": "Nhơn Mỹ", "deanery": "Chợ Mới"}, {"name": "Ninh Cù", "deanery": "Tân Hiệp"}, {"name": "Núi Sam", "deanery": "Long Xuyên"}, {"name": "Núi Sập", "deanery": "Long Xuyên"}, {"name": "Núi Tượng", "deanery": "Long Xuyên"}, {"name": "Ông Chưởng", "deanery": "Chợ Mới"}, {"name": "Ong Dèo", "deanery": "Rạch Giá"}, {"name": "Phan Sinh", "deanery": "Tân Hiệp"}, {"name": "Phaolô", "deanery": "Tân Hiệp"}, {"name": "Phú An", "deanery": "Long Xuyên"}, {"name": "Phú Hòa", "deanery": "Rạch Giá"}, {"name": "Phú Vĩnh", "deanery": "Long Xuyên"}, {"name": "Phụng Hưng", "deanery": "Vĩnh Thạnh"}, {"name": "Quý Phụng", "deanery": "Rạch Giá"}, {"name": "Rạch Đùng", "deanery": "Hà Tiên"}, {"name": "Rạch Giá", "deanery": "Rạch Giá"}, {"name": "Rạch Sâu", "deanery": "Chợ Mới"}, {"name": "Rạch Sỏi", "deanery": "Rạch Giá"}, {"name": "Nhà thờ Sơn Hải", "deanery": "Hà Tiên", "type": "Nhà thờ"}, {"name": "Sáu Bọng", "deanery": "Vĩnh Thạnh"}, {"name": "Tân Bình (Rạch Giá)", "deanery": "Rạch Giá"}, {"name": "Tân Bình (Tân Hiệp)", "deanery": "Tân Hiệp"}, {"name": "Tân Bùi", "deanery": "Tân Thạnh"}, {"name": "Tân Châu", "deanery": "Long Xuyên"}, {"name": "Tân Chu", "deanery": "Tân Hiệp"}, {"name": "Tân Hải", "deanery": "Vĩnh Thạnh"}, {"name": "Tân Hiệp", "deanery": "Tân Hiệp"}, {"name": "Tân Hóa", "deanery": "Rạch Giá"}, {"name": "Tân Lập", "deanery": "Rạch Giá"}, {"name": "Tân Long", "deanery": "Tân Hiệp"}, {"name": "Tân Mỹ", "deanery": "Vĩnh Thạnh"}, {"name": "Tân Thành", "deanery": "Tân Hiệp"}, {"name": "Tân Thuận", "deanery": "Tân Hiệp"}, {"name": "Têrêsa", "deanery": "Long Xuyên"}, {"name": "Thái An", "deanery": "Tân Hiệp"}, {"name": "Thái Hòa", "deanery": "Tân Hiệp"}, {"name": "Tham Buôn", "deanery": "Chợ Mới"}, {"name": "Thạnh An", "deanery": "Vĩnh Thạnh"}, {"name": "Thánh Chiểu", "deanery": "Tân Hiệp"}, {"name": "Thánh Gia (Tân Hiệp)", "deanery": "Tân Hiệp"}, {"name": "Thánh Gia (Vĩnh Thạnh)", "deanery": "Vĩnh Thạnh"}, {"name": "Thánh Giuse", "deanery": "Tân Hiệp"}, {"name": "Thanh Hải", "deanery": "Vĩnh Thạnh"}, {"name": "Thánh Huy", "deanery": "Tân Hiệp"}, {"name": "Thánh Linh", "deanery": "Vĩnh Thạnh"}, {"name": "Thanh Long", "deanery": "Vĩnh Thạnh"}, {"name": "Thánh Tâm (Tân Hiệp)", "deanery": "Tân Hiệp"}, {"name": "Thánh Tâm (Vĩnh Thạnh)", "deanery": "Vĩnh Thạnh"}, {"name": "Thị Đạm", "deanery": "Long Xuyên"}, {"name": "Thức Hóa", "deanery": "Tân Hiệp"}, {"name": "Trái Tim", "deanery": "Tân Hiệp"}, {"name": "Trảng Tranh", "deanery": "Rạch Giá"}, {"name": "Tri Tôn", "deanery": "Long Xuyên"}, {"name": "Trinh Vương (Tân Hiệp)", "deanery": "Tân Hiệp"}, {"name": "Trinh Vương (Vĩnh Thạnh)", "deanery": "Vĩnh Thạnh"}, {"name": "Trung Thành", "deanery": "Tân Hiệp"}, {"name": "Vàm Cống", "deanery": "Chợ Mới"}, {"name": "Vạn Đồn", "deanery": "Vĩnh Thạnh"}, {"name": "Vĩnh Nhuận", "deanery": "Long Xuyên"}, {"name": "Vinh Sơn", "deanery": "Tân Hiệp"}, {"name": "Vô Nhiễm", "deanery": "Tân Hiệp"}, {"name": "Xáng Cụt", "deanery": "Rạch Giá"}, {"name": "Xẻo Dầu", "deanery": "Rạch Giá"}, {"name": "Xẻo Dinh", "deanery": "Rạch Giá"}];
function initParishDirectory(){
  const select = $('sParish');
  if(select){
    const current = data.settings.parish || '';
    select.innerHTML = '<option value="">-- Chọn giáo xứ/giáo họ --</option>' + PARISH_DIRECTORY.map(p=>`<option value="${esc(p.name)}">${esc(p.type||'Giáo xứ')} ${esc(p.name)} (${esc(p.deanery)})</option>`).join('');
    select.value = current;
  }
  const filter = $('parishDeaneryFilter');
  if(filter){
    const currentFilter = filter.value;
    const deaneries = [...new Set(PARISH_DIRECTORY.map(p=>p.deanery))].sort((a,b)=>a.localeCompare(b,'vi'));
    filter.innerHTML = '<option value="">Tất cả giáo hạt</option>' + deaneries.map(d=>`<option value="${esc(d)}">${esc(d)}</option>`).join('');
    filter.value = currentFilter;
  }
  renderParishDirectory();
}
function renderParishDirectory(){
  const body = $('parishesTable');
  if(!body) return;
  const q = ($('parishSearch')?.value || '').toLocaleLowerCase('vi');
  const d = $('parishDeaneryFilter')?.value || '';
  const filtered = PARISH_DIRECTORY.filter(p => p.name.toLocaleLowerCase('vi').includes(q) && (!d || p.deanery===d));
  $('parishCount').textContent = `Hiển thị ${filtered.length} / ${PARISH_DIRECTORY.length} mục`;
  body.innerHTML = filtered.length ? filtered.map((p,i)=>`<tr><td>${i+1}</td><td><b>${esc(p.type||'Giáo xứ')} ${esc(p.name.replace(/\s*\([^)]*\)$/, ''))}</b></td><td>${esc(p.deanery)}</td><td><button class="small" onclick="chooseParish('${esc(p.name).replace(/'/g, '&#39;')}')">Chọn giáo xứ</button></td></tr>`).join('') : '<tr><td colspan="4" class="empty">Không tìm thấy giáo xứ phù hợp.</td></tr>';
}
function chooseParish(name){
  data.settings.parish = name;
  persist();
  showPage('settings');
  fillSettings();
  alert('Đã chọn giáo xứ: ' + name + '. Nhấn “Lưu thông tin” để lưu cấu hình xứ đoàn.');
}
$('parishSearch').addEventListener('input', renderParishDirectory);
$('parishDeaneryFilter').addEventListener('change', renderParishDirectory);
$('exportParishes').addEventListener('click', ()=>{
  const rows = [['Loại','Tên','Giáo hạt'], ...PARISH_DIRECTORY.map(p=>[p.type||'Giáo xứ',p.name,p.deanery])];
  const csv='\\ufeff'+rows.map(r=>r.map(v=>'"'+String(v).replace(/"/g,'""')+'"').join(',')).join('\\r\\n');
  downloadFile(csv,'danh-muc-giao-xu-giao-ho.csv','text/csv;charset=utf-8');
});

loadData();initParishDirectory();populateMemberParishes();populateLeaderParishes();populateGradeParishFilter();if(sessionStorage.getItem('tntt_logged_in')==='1'){const u=sessionStorage.getItem('tntt_user')||'admin';currentUser=u==='admin'?{username:'admin',name:'Quản trị viên',role:'admin'}:(()=>{const a=readAccounts().find(x=>x.username===u);return a?{username:a.username,name:a.name,role:'user'}:null})();if(currentUser)enterApp();else sessionStorage.removeItem('tntt_logged_in')}
</script>
</body>
</html>
