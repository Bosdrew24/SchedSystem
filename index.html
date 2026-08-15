<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Class Schedule Portal</title>
<style>
* { box-sizing: border-box; }
body {
 margin: 0;
 font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Arial, sans-serif;
 background: #f1f5f9;
 color: #1e293b;
 padding: 16px;
}
@media (min-width: 640px) { body { padding: 24px; } }
.wrap { max-width: 1100px; margin: 0 auto; }
.topbar { height: 6px; background: #0f172a; margin: -16px -16px 16px; }
@media (min-width: 640px) { .topbar { margin: -24px -24px 24px; } }
.nav-bar {
 display: flex;
 justify-content: space-between;
 align-items: center;
 margin-bottom: 20px;
 padding-bottom: 12px;
 border-bottom: 1px solid #e2e8f0;
 gap: 8px;
}
.portal-tag {
 font-size: 12px;
 font-weight: 700;
 text-transform: uppercase;
 letter-spacing: 0.5px;
 color: #64748b;
}
@media (min-width: 640px) { .portal-tag { font-size: 13px; } }
.nav-actions { display: flex; gap: 8px; align-items: center; }
.nav-btn {
 background: #0f172a;
 color: #fff;
 border: none; padding: 8px 12px;
 border-radius: 6px;
 font-weight: 600;
 font-size: 12px;
 cursor: pointer;
 white-space: nowrap; }
@media (min-width: 640px) { .nav-btn { font-size: 13px; padding: 8px 16px; } }
.nav-btn:hover { background: #1e293b; }
.notify-btn {
 background: #4f46e5;
 color: #fff;
 border: none;
 padding: 8px 12px;
 border-radius: 6px;
 font-weight: 600;
 font-size: 12px;
 cursor: pointer;
 display: flex;
 align-items: center;
 gap: 4px;
}
.notify-btn:hover { background: #4338ca; }
.notify-btn.active { background: #059669; }
.view { display: none; }
.view.active { display: block; }
.schedule-header {
 display: flex;
 justify-content: space-between;
 align-items: flex-start;
 margin-bottom: 20px;
 flex-wrap: wrap;
 gap: 16px;
}
.schedule-title {
 font-size: 22px;
 font-weight: 800;
 color: #0f172a;
 margin: 0;
}
@media (min-width: 640px) { .schedule-title { font-size: 28px; } }
.schedule-subtitle {
 font-size: 14px;
 font-weight: 600;
 color: #4f46e5;
 margin-top: 4px;
}
@media (min-width: 640px) { .schedule-subtitle { font-size: 16px; } }

/* Chrome Search Component */
.chrome-search-container {
 position: relative; width: 100%;
}
@media (min-width: 640px) { .chrome-search-container { max-width: 440px; } }
.chrome-search-box {
 position: relative;
 background: #ffffff;
 border: 1px solid #cbd5e1;
 border-radius: 24px;
 transition: all 0.2s ease;
 z-index: 100;
}
.chrome-search-box.open {
 border-top-left-radius: 24px;
 border-top-right-radius: 24px;
 border-bottom-left-radius: 0;
 border-bottom-right-radius: 0;
 box-shadow: 0 4px 16px rgba(0,0,0,0.12);
}
.chrome-input-wrapper {
 display: flex;
 align-items: center;
 padding: 6px 14px;
 height: 44px;
}
.chrome-search-icon {
 width: 18px;
 height: 18px;
 fill: #5f6368;
 margin-right: 12px;
 flex-shrink: 0;
}
.chrome-search-input {
 width: 100%;
 border: none;
 outline: none;
 background: transparent;
 font-size: 15px;
 color: #1f2937;
}

/* Dropdown Menu */
.chrome-dropdown {
 display: none;
 position: absolute; top: 100%;
 left: -1px;
 right: -1px;
 background: #ffffff;
 border: 1px solid #cbd5e1;
 border-top: none;
 border-bottom-left-radius: 24px;
 border-bottom-right-radius: 24px;
 box-shadow: 0 8px 16px rgba(0,0,0,0.12);
 padding: 4px 0 12px 0;
 z-index: 99;
}
.chrome-search-box.open .chrome-dropdown {
 display: block;
}
.chrome-dropdown-item {
 display: flex;
 align-items: center;
 padding: 10px 16px;
 cursor: pointer;
 transition: background 0.15s ease;
}
.chrome-dropdown-item:hover {
 background: #f1f5f9;
}
.chrome-dropdown-item .item-icon {
 width: 16px;
 height: 16px;
 fill: #5f6368;
 margin-right: 14px;
 flex-shrink: 0;
}
.chrome-dropdown-item .item-text {
 font-size: 14px;
 color: #1e293b;
 flex-grow: 1;
}
.chrome-dropdown-item .item-text strong {
 font-weight: 700;
 color: #0f172a;
}
.chrome-dropdown-item .item-badge {
 font-size: 11px;
 padding: 2px 8px;
 background: #e2e8f0;
 color: #475569; border-radius: 10px;
 font-weight: 600;
}
.search-meta { font-size: 12px; color: #64748b; margin-top: 6px; text-align: right; }

/* Filter Bar for Session Groups */
.session-filter-bar {
 display: flex;
 gap: 10px;
 flex-wrap: wrap;
 margin-bottom: 20px;
}
.session-filter-btn {
 background: #ffffff;
 color: #475569;
 border: 1px solid #cbd5e1;
 border-radius: 20px;
 padding: 8px 20px;
 font-size: 13px;
 font-weight: 700;
 cursor: pointer;
 transition: all 0.15s ease-in-out;
 flex: 1;
 text-align: center;
 min-width: 110px;
}
.session-filter-btn:hover { background: #e2e8f0; color: #0f172a; }
.session-filter-btn.active {
 background: #4f46e5;
 color: #ffffff;
 border-color: #4f46e5;
 box-shadow: 0 2px 6px rgba(79, 70, 229, 0.3);
}

/* Empty State Styling */
.empty-state {
 text-align: center;
 padding: 48px 16px;
 background: #ffffff;
 border-radius: 12px;
 border: 1px dashed #cbd5e1;
 color: #64748b;
 margin-top: 20px;
}
.empty-state h3 {
 margin: 0 0 8px 0;
 color: #0f172a;
 font-size: 18px; }

/* Accordion Section UI */
.sections-list {
 display: flex;
 flex-direction: column;
 gap: 12px;
}
.section-wrapper {
 background: #fff;
 border-radius: 12px;
 border: 1px solid #e2e8f0;
 overflow: hidden;
 box-shadow: 0 1px 3px rgba(0,0,0,0.05);
}
.section-toggle-btn {
 width: 100%;
 padding: 16px 20px;
 background: #ffffff;
 border: none;
 font-size: 15px;
 font-weight: 700;
 color: #0f172a;
 text-align: left;
 display: flex;
 justify-content: space-between;
 align-items: center;
 cursor: pointer;
 transition: background 0.15s ease;
}
.section-toggle-btn:hover { background: #f8fafc; }
.section-toggle-btn.active {
 background: #0f172a;
 color: #ffffff;
}
.arrow-icon {
 font-size: 12px;
 transition: transform 0.2s ease;
}
.section-toggle-btn.active .arrow-icon {
 transform: rotate(180deg);
}
.schedule-table-container {
 padding: 16px; border-top: 1px solid #e2e8f0;
}
.schedule-table-container.hidden { display: none; }
.mobile-day-tabs {
 display: flex;
 gap: 6px;
 overflow-x: auto;
 padding-bottom: 12px;
 margin-bottom: 12px;
 border-bottom: 1px solid #e2e8f0;
}
@media (min-width: 769px) { .mobile-day-tabs { display: none; } }
.day-tab {
 padding: 8px 12px;
 font-size: 12px;
 font-weight: 700;
 border: 1px solid #cbd5e1;
 border-radius: 20px;
 background: #fff;
 color: #475569;
 cursor: pointer;
 white-space: nowrap;
 flex-shrink: 0;
}
.day-tab.active { background: #0f172a; color: #fff; border-color: #0f172a; }
.table-container { overflow-x: auto; }
table { width: 100%; border-collapse: collapse; font-size: 13px; }
@media (min-width: 640px) { table { font-size: 14px; table-layout: fixed; } }
th { background: #1e293b; color: #fff; text-align: left; padding: 10px; font-weight: 600; }
@media (min-width: 640px) { th { padding: 12px; } }
th:first-child { border-top-left-radius: 8px; width: 110px; }
@media (min-width: 640px) { th:first-child { width: 130px; } }
th:last-child { border-top-right-radius: 8px; }
th.friday { background: #92400e; }
tbody tr { border-bottom: 1px solid #f1f5f9; }
.time-cell { padding: 10px; vertical-align: top; font-weight: 600; color: #334155; font-size: 12px; }
@media (min-width: 640px) { .time-cell { padding: 12px; font-size: 13px; } }
.class-cell {
 border-left: 1px solid #f1f5f9;
 padding: 10px; vertical-align: top;
 transition: background-color 0.2s ease, opacity 0.2s ease;
}
@media (min-width: 640px) { .class-cell { padding: 12px; } }
.class-cell.friday { background: #fffbeb; }
.cell-code { font-weight: 700; color: #0f172a; }
.cell-name { color: #475569; margin-top: 2px; font-size: 12px; }
.cell-empty { text-align: center; color: #cbd5e1; }
.class-cell.highlight { background-color: #fef08a !important; border-radius: 6px; }
.class-cell.dimmed { opacity: 0.35; }
@media (max-width: 768px) {
 .responsive-table th:not(:first-child),
 .responsive-table td.class-cell { display: none; }
 .responsive-table.show-col-0 th:nth-child(2),
 .responsive-table.show-col-0 td:nth-child(2),
 .responsive-table.show-col-1 th:nth-child(3),
 .responsive-table.show-col-1 td:nth-child(3),
 .responsive-table.show-col-2 th:nth-child(4),
 .responsive-table.show-col-2 td:nth-child(4),
 .responsive-table.show-col-3 th:nth-child(5),
 .responsive-table.show-col-3 td:nth-child(5),
 .responsive-table.show-col-4 th:nth-child(6),
 .responsive-table.show-col-4 td:nth-child(6) { display: table-cell !important; }
}
.auth-container { max-width: 400px; margin: 20px auto; background: #fff; border-radius: 12px; padding: 24px; box-shadow: 0 4px 12px rgba(0,0,0,0.05); }
@media (min-width: 640px) { .auth-container { margin: 40px auto; padding: 32px; } }
.auth-title { font-size: 20px; font-weight: 800; color: #0f172a; margin: 0 0 8px; text-align: center; }
.auth-subtitle { font-size: 13px; color: #64748b; margin-bottom: 20px; text-align: center; }
.auth-form label { display: block; font-size: 13px; font-weight: 600; color: #334155; margin-bottom: 6px; }
.auth-form input { width: 100%; border: 1px solid #cbd5e1; border-radius: 8px; padding: 10px 12px; font-size: 14px; outline: none; margin-bottom: 16px; }
.auth-btn { width: 100%; background: #4f46e5; color: #fff; border: none; font-weight: 700; font-size: 15px; padding: 12px; border-radius: 8px; cursor: pointer; }
.auth-btn:hover { background: #4338ca; }
.auth-toggle { text-align: center; margin-top: 16px; font-size: 13px; color: #64748b; }
.auth-toggle a { color: #4f46e5; font-weight: 600; cursor: pointer; text-decoration: none; }
.auth-error { background: #fef2f2; color: #991b1b; padding: 10px; border-radius: 8px; font-size: 13px; margin-bottom: 16px; display: none; }
.btn-primary { background: #4f46e5; color: #fff; border: none; font-weight: 600; font-size: 13px; padding: 8px 14px; border-radius: 8px; cursor: pointer; }
.btn-primary:hover { background: #4338ca; }
.btn-secondary { background: #fff; border: 1px solid #cbd5e1; color: #334155; font-weight: 600; font-size: 13px; padding: 8px 14px; border-radius: 8px; cursor: pointer; }
.btn-secondary:hover { background: #f8fafc; }
.overlay { display: none; position: fixed; inset: 0; background: rgba(0,0,0,0.4); align-items: center; justify-content: center; padding: 16px; z-index: 50; }
.overlay.open { display: flex; }
.modal { background: #fff; border-radius: 12px; padding: 20px; width: 100%; max-width: 360px; box-shadow: 0 8px 24px rgba(0,0,0,0.15); }
.modal h3 { margin: 0 0 16px; font-size: 16px; font-weight: 700; color: #0f172a; }
.modal label { display: block; font-size: 12px; font-weight: 600; color: #334155; margin-bottom: 4px; }
.modal input { width: 100%; border: 1px solid #cbd5e1; border-radius: 8px; padding: 8px 12px; font-size: 14px; outline: none; margin-bottom: 12px; }
</style>
</head>
<body>
<div class="topbar"></div>
<div class="wrap">
 <div class="nav-bar">
 <span class="portal-tag" id="portal-tag-label">Student Portal (View Only)</span>
 <div class="nav-actions">
 <button class="notify-btn" id="notify-toggle-btn">&#128276; Alerts Off</button>
 <button class="nav-btn" id="portal-switch-btn">Admin Portal</button>
 </div>
 </div>
 <div id="student-view" class="view active">
 <div class="schedule-header">
 <div>
 <h1 class="schedule-title">BS CLASS SCHEDULES</h1>
 <div class="schedule-subtitle">1ST SEM 2026-2027</div>
 </div>
 <div class="chrome-search-container">
 <div class="chrome-search-box" id="chrome-search-box">
 <div class="chrome-input-wrapper">
 <svg class="chrome-search-icon" viewBox="0 0 24 24">
 <path d="M15.5 14h-.79l-.28-.27C15.41 12.59 16 11.11 16 9.5 16 5.91 13.09 3 9.5 3S3 5.91 3 9.5 5.91 16 9.5 16c1.61 0 3.09-.59 4.23-1.57l.27.28v.79l5 4.99L20.49 19l-4.99-5zm-6 0C7.01 14 5 11.99 5 9.5S7.01 5 9.5 5 14 7.01 14 9.5 11.99 14 9.5 14z"/>
 </svg>
 <input type="text" id="student-search-input" class="chrome-search-input" placeholder="Search section, subject, prof, or room..." autocomplete="off">
 </div>
 <div class="chrome-dropdown" id="chrome-dropdown"></div>
 </div>
 <div class="search-meta" id="student-search-meta"></div>
 </div>
 </div>

 <!-- 3 Session Filter Buttons -->
 <div class="session-filter-bar" id="session-filter-buttons">
 <button class="session-filter-btn active" data-session="MORNING">Morning Session</button>
 <button class="session-filter-btn" data-session="AFTERNOON">Afternoon Session</button>
 <button class="session-filter-btn" data-session="EVENING">Evening Session</button>
 </div>

 <div class="mobile-day-tabs" id="mobile-day-tabs"></div>
 
 <!-- Sections Container -->
 <div id="sections-container" class="sections-list"></div>
 </div>

 <div id="auth-view" class="view">
 <div class="auth-container">
 <h2 class="auth-title" id="auth-header">Admin Login</h2>
 <p class="auth-subtitle" id="auth-sub">Access schedule management tools</p>
 <div id="auth-error" class="auth-error"></div>
 <form class="auth-form" id="auth-form" onsubmit="return false;">
 <label>Username</label>
 <input type="text" id="auth-username" placeholder="Enter username" required>
 <label>Password</label>
 <input type="password" id="auth-password" placeholder="Enter password" required>
 <button type="submit" class="auth-btn" id="auth-submit-btn">Sign In</button>
 </form>
 <div class="auth-toggle">
 <span id="auth-toggle-text">Need an account?</span>
 <a id="auth-toggle-btn">Register</a>
 </div>
 </div>
 </div>

<!-- Admin View (Same UI as Student View, but Editable) -->
<div id="admin-view" class="view">
  <div class="schedule-header">
    <div>
      <h1 class="schedule-title">ADMIN PORTAL - SCHEDULE EDITOR</h1>
      <div class="schedule-subtitle">Logged in as <span id="admin-user-display" style="color:#0f172a;">Admin</span> | <span style="color:#059669;">Editable Mode</span></div>
    </div>
    <div style="display:flex; gap:8px; align-items:center;">
      <button class="btn-primary" id="admin-save-top-btn">Save Changes</button>
      <button class="btn-secondary" id="admin-logout-btn">Logout</button>
    </div>
  </div>

  <!-- Admin Search Component -->
  <div class="chrome-search-container" style="margin-bottom: 20px;">
    <div class="chrome-search-box" id="admin-search-box">
      <div class="chrome-input-wrapper">
        <svg class="chrome-search-icon" viewBox="0 0 24 24">
          <path d="M15.5 14h-.79l-.28-.27C15.41 12.59 16 11.11 16 9.5 16 5.91 13.09 3 9.5 3S3 5.91 3 9.5 5.91 16 9.5 16c1.61 0 3.09-.59 4.23-1.57l.27.28v.79l5 4.99L20.49 19l-4.99-5zm-6 0C7.01 14 5 11.99 5 9.5S7.01 5 9.5 5 14 7.01 14 9.5 11.99 14 9.5 14z"/>
        </svg>
        <input type="text" id="admin-search-input" class="chrome-search-input" placeholder="Search section, subject, prof, or room to edit..." autocomplete="off">
      </div>
      <div class="chrome-dropdown" id="admin-dropdown"></div>
    </div>
    <div class="search-meta" id="admin-search-meta"></div>
  </div>

  <!-- Admin Session Filter Buttons -->
  <div class="session-filter-bar" id="admin-session-filter-buttons">
    <button class="session-filter-btn active" data-session="MORNING">Morning Session</button>
    <button class="session-filter-btn" data-session="AFTERNOON">Afternoon Session</button>
    <button class="session-filter-btn" data-session="EVENING">Evening Session</button>
  </div>

  <div class="mobile-day-tabs" id="admin-mobile-day-tabs"></div>

  <!-- Editable Sections Container -->
  <div id="admin-sections-container" class="sections-list"></div>
</div>

<!-- Modal Overlay for Cell Editing -->
<div class="overlay" id="cell-overlay">
  <div class="modal">
    <h3>Edit Schedule Slot</h3>
    <label>Subject Code</label>
    <input type="text" id="subject-input" placeholder="e.g. CC112">
    <label>Professor</label>
    <input type="text" id="professor-input" placeholder="e.g. XPLATA">
    <label>Room</label>
    <input type="text" id="room-input" placeholder="e.g. CL1">
    <div style="display:flex; gap:8px; margin-top:8px;">
      <button class="btn-primary" id="save-cell-btn" style="flex:1;">Save</button>
      <button class="btn-secondary" id="clear-cell-btn" style="flex:1;">Clear</button>
      <button class="btn-secondary" id="cancel-cell-btn" style="flex:1;">Cancel</button>
    </div>
  </div>
</div>

<script>
document.addEventListener("DOMContentLoaded", () => {
  const DAYS = ["MONDAY", "TUESDAY", "WEDNESDAY", "THURSDAY", "FRIDAY ODL (Sync/Async)"];
  const USERS_KEY = "aics_admin_users";
  const SESSION_KEY = "aics_active_user";
  let selectedDayIndex = 0;
  let activeSession = "MORNING";

  // Note: sectionsData contains all your classes
  const sectionsData = [
    {
      code: "BS1MA",
      session: "MORNING",
      title: "BS1MA - MORNING SESSION",
      slots: ["7:00 - 8:00", "8:00 - 9:00", "9:00 - 10:00", "10:00 - 11:00", "11:00 - 12:00"],
      cells: {
        "0-0": { subject: "CC112", professor: "XPLATA", room: "CL1" },
        "1-0": { subject: "CC112", professor: "XPLATA", room: "CL1" },
        "2-0": { subject: "CC112", professor: "XPLATA", room: "CL1" },
        "3-0": { subject: "CC112", professor: "XPLATA", room: "CL1" },
        "0-1": { subject: "PATHFit1", professor: "J.Capitin", room: "101" },
        "1-1": { subject: "PATHFit1", professor: "J.Capitin", room: "101" },
        "2-1": { subject: "NSTP1", professor: "J.Capitin", room: "101" },
        "3-1": { subject: "NSTP1", professor: "J.Capitin", room: "101" },
        "0-2": { subject: "CC111", professor: "JMUYOT", room: "101" },
        "1-2": { subject: "CC111", professor: "JMUYOT", room: "101" },
        "2-2": { subject: "GE1", professor: "R.Villanueva", room: "101" },
        "3-2": { subject: "GE1", professor: "R.Villanueva", room: "101" },
        "0-3": { subject: "GE2", professor: "R.Villanueva", room: "101" },
        "1-3": { subject: "GE2", professor: "R.Villanueva", room: "101" },
        "2-3": { subject: "GE3", professor: "R.Villanueva", room: "101" },
        "3-3": { subject: "GE3", professor: "R.Villanueva", room: "101" },
        "4-3": { subject: "CC111", professor: "JMUYOT", room: "101" },
        "0-4": { subject: "CC112", professor: "XPLATA", room: "" },
        "1-4": { subject: "GE1", professor: "R.Villanueva", room: "" },
        "2-4": { subject: "GE2", professor: "R.Villanueva", room: "" },
        "3-4": { subject: "GE3", professor: "R.Villanueva", room: "" },
        "4-4": { subject: "NSTP1", professor: "J.Capitin", room: "" }
      }
    },
    {
      code: "BG1MA",
      session: "MORNING",
      title: "BG1MA - MORNING SESSION",
      slots: ["7:00 - 8:00", "8:00 - 9:00", "9:00 - 10:00", "10:00 - 11:00", "11:00 - 12:00", "12:00 - 01:00", "1:00 - 02:00"],
      cells: {
        "0-0": { subject: "CPE112", professor: "JMUYOT", room: "CL2" },
        "1-0": { subject: "CPE112", professor: "JMUYOT", room: "CL2" },
        "2-0": { subject: "CPE112", professor: "JMUYOT", room: "CL2" },
        "3-0": { subject: "NPS111", professor: "CPET2", room: "101" },
        "4-0": { subject: "PATHFit1", professor: "J.Capitin", room: "101" },
        "5-0": { subject: "PATHFit1", professor: "J.Capitin", room: "101" },
        "0-1": { subject: "GE2", professor: "R.Villanueva", room: "107" },
        "1-1": { subject: "GE2", professor: "R.Villanueva", room: "107" },
        "2-1": { subject: "GE3", professor: "R.Villanueva", room: "107" },
        "3-1": { subject: "GE3", professor: "R.Villanueva", room: "107" },
        "4-1": { subject: "MAT111", professor: "CPET2", room: "107" },
        "5-1": { subject: "MAT111", professor: "CPET2", room: "107" },
        "6-1": { subject: "CPE112", professor: "JMUYOT", room: "TL" },
        "0-2": { subject: "GE1", professor: "J.Capitin", room: "106" },
        "1-2": { subject: "GE1", professor: "J.Capitin", room: "106" },
        "2-2": { subject: "NSTP1", professor: "J.Capitin", room: "106" },
        "3-2": { subject: "NSTP1", professor: "J.Capitin", room: "104" },
        "4-2": { subject: "CPE111", professor: "CpET1", room: "104" },
        "1-3": { subject: "NPS111", professor: "CPET2", room: "104" },
        "2-3": { subject: "NPS111", professor: "CPET2", room: "104" },
        "3-3": { subject: "NPS111", professor: "CPET2", room: "104" },
        "4-3": { subject: "NPS111", professor: "CPET2", room: "107" },
        "0-4": { subject: "GE1", professor: "J.Capitin", room: "" },
        "1-4": { subject: "MAT111", professor: "CPET2", room: "" },
        "2-4": { subject: "NSTP1", professor: "J.Capitin", room: "" },
        "3-4": { subject: "NPS111", professor: "CPET2", room: "" },
        "4-4": { subject: "GE2", professor: "R.Villanueva", room: "" },
        "5-4": { subject: "GE3", professor: "R.Villanueva", room: "" },
        "6-4": { subject: "CPE112", professor: "JMUYOT", room: "" }
      }
    },
    {
      code: "BS3MA",
      session: "MORNING",
      title: "BS3MA - MORNING SESSION",
      slots: ["7:00 - 8:00", "8:00 - 9:00", "9:00 - 10:00", "10:00 - 11:00", "11:00 - 12:00", "12:00 - 01:00", "1:00 - 02:00"],
      cells: {
        "0-0": { subject: "PATHFit3", professor: "J.Capitin", room: "104" },
        "1-0": { subject: "PATHFit3", professor: "J.Capitin", room: "104" },
        "2-0": { subject: "CS212", professor: "CPET2", room: "104" },
        "3-0": { subject: "CS213", professor: "JMUYOT", room: "CL2" },
        "4-0": { subject: "CS213", professor: "JMUYOT", room: "CL2" },
        "5-0": { subject: "CS213", professor: "JMUYOT", room: "CL2" },
        "6-0": { subject: "CS213", professor: "JMUYOT", room: "104" },
        "0-1": { subject: "CC214", professor: "JMUYOT", room: "CL1" },
        "1-1": { subject: "CC214", professor: "JMUYOT", room: "CL1" },
        "2-1": { subject: "CC214", professor: "JMUYOT", room: "CL1" },
        "3-1": { subject: "CC214", professor: "JMUYOT", room: "CL1" },
        "4-1": { subject: "GE8", professor: "J.Capitin", room: "104" },
        "5-1": { subject: "GE8", professor: "J.Capitin", room: "104" },
        "0-2": { subject: "GE7", professor: "R.Villanueva", room: "104" },
        "1-2": { subject: "GE7", professor: "R.Villanueva", room: "104" },
        "2-2": { subject: "CS212", professor: "CPET2", room: "104" },
        "0-3": { subject: "CIS211", professor: "L.Abanag", room: "CL2" },
        "1-3": { subject: "CIS211", professor: "L.Abanag", room: "CL2" },
        "2-3": { subject: "CIS211", professor: "L.Abanag", room: "CL2" },
        "3-3": { subject: "CIS211", professor: "L.Abanag", room: "CL2" },
        "0-4": { subject: "GE7", professor: "R.Villanueva", room: "" },
        "1-4": { subject: "CC214", professor: "JMUYOT", room: "" },
        "2-4": { subject: "CIS211", professor: "L.Abanag", room: "" },
        "3-4": { subject: "GE8", professor: "J.Capitin", room: "" },
        "4-4": { subject: "CS212", professor: "CPET2", room: "" },
        "5-4": { subject: "CS213", professor: "JMUYOT", room: "" }
      }
    },
    {
      code: "BS5MA",
      session: "MORNING",
      title: "BS5MA - MORNING SESSION",
      slots: ["7:00 - 8:00", "8:00 - 9:00", "9:00 - 10:00", "10:00 - 11:00", "11:00 - 12:00", "12:00 - 01:00"],
      cells: {
        "0-0": { subject: "CS315", professor: "MDLSANTOS", room: "106" },
        "1-0": { subject: "CS315", professor: "MDLSANTOS", room: "106" },
        "2-0": { subject: "GE11", professor: "R.Villanueva", room: "106" },
        "3-0": { subject: "GE11", professor: "R.Villanueva", room: "106" },
        "4-0": { subject: "GE11", professor: "R.Villanueva", room: "106" },
        "5-0": { subject: "CS316", professor: "XPLATA", room: "CL1" },
        "0-1": { subject: "CIS313", professor: "L.Abanag", room: "CL2" },
        "1-1": { subject: "CIS313", professor: "L.Abanag", room: "CL2" },
        "2-1": { subject: "CIS313", professor: "L.Abanag", room: "CL2" },
        "3-1": { subject: "CIS313", professor: "L.Abanag", room: "106" },
        "4-1": { subject: "CSE311", professor: "XPLATA", room: "CL1" },
        "5-1": { subject: "CSE311", professor: "XPLATA", room: "CL1" },
        "2-2": { subject: "CC316", professor: "XPLATA", room: "CL1" },
        "3-2": { subject: "CC316", professor: "XPLATA", room: "CL1" },
        "4-2": { subject: "CC316", professor: "XPLATA", room: "CL1" },
        "5-2": { subject: "CSE311", professor: "XPLATA", room: "CL1" },
        "0-3": { subject: "CS317", professor: "MDLSANTOS", room: "106" },
        "1-3": { subject: "CS317", professor: "MDLSANTOS", room: "106" },
        "2-3": { subject: "CS316", professor: "XPLATA", room: "106" },
        "3-3": { subject: "CS316", professor: "XPLATA", room: "106" },
        "4-3": { subject: "CSE311", professor: "XPLATA", room: "106" },
        "5-3": { subject: "CC316", professor: "XPLATA", room: "CL1" },
        "0-4": { subject: "CS315", professor: "MDLSANTOS", room: "" },
        "1-4": { subject: "CIS313", professor: "L.Abanag", room: "" },
        "2-4": { subject: "CS317", professor: "MDLSANTOS", room: "" },
        "3-4": { subject: "CC316", professor: "XPLATA", room: "" },
        "4-4": { subject: "CSE311", professor: "XPLATA", room: "" }
      }
    },
    {
      code: "BG5MA",
      session: "MORNING",
      title: "BG5MA - MORNING SESSION",
      slots: ["7:00 - 8:00", "8:00 - 9:00", "9:00 - 10:00", "10:00 - 11:00", "11:00 - 12:00", "12:00 - 01:00", "01:00 - 02:00", "02:00 - 03:00", "03:00 - 04:00"],
      cells: {
        "0-0": { subject: "GE11", professor: "R.Villanueva", room: "TL" },
        "1-0": { subject: "GE11", professor: "R.Villanueva", room: "TL" },
        "2-0": { subject: "CPE317", professor: "CpET1", room: "TL" },
        "3-0": { subject: "CPE317", professor: "CpET1", room: "TL" },
        "4-0": { subject: "CPE3214", professor: "CpET1", room: "TL" },
        "5-0": { subject: "CPE3214", professor: "CpET1", room: "TL" },
        "6-0": { subject: "CP33110", professor: "CpET1", room: "TL" },
        "0-1": { subject: "CPE3112", professor: "CpET1", room: "" },
        "1-1": { subject: "CPE3111", professor: "CPET2", room: "TL" },
        "2-1": { subject: "CPE3111", professor: "CPET2", room: "TL" },
        "3-1": { subject: "A313", professor: "CpET1", room: "TL" },
        "4-1": { subject: "A313", professor: "CpET1", room: "TL" },
        "5-1": { subject: "CPE226", professor: "JMUYOT", room: "CL2" },
        "0-2": { subject: "CELEC2", professor: "L.Abanag", room: "CL2" },
        "1-2": { subject: "CELEC2", professor: "L.Abanag", room: "CL2" },
        "2-2": { subject: "CELEC2", professor: "L.Abanag", room: "CL2" },
        "3-2": { subject: "CELEC2", professor: "L.Abanag", room: "TL" },
        "4-2": { subject: "GE11", professor: "R.Villanueva", room: "TL" },
        "5-2": { subject: "CPE226", professor: "JMUYOT", room: "CL2" },
        "6-2": { subject: "CPE226", professor: "JMUYOT", room: "CL2" },
        "0-3": { subject: "CPE317", professor: "CpET1", room: "TL" },
        "1-3": { subject: "CPE317", professor: "CpET1", room: "TL" },
        "2-3": { subject: "CPE317", professor: "CpET1", room: "TL" },
        "3-3": { subject: "CPE3112", professor: "CpET1", room: "" },
        "4-3": { subject: "CP33110", professor: "CpET1", room: "TL" },
        "5-3": { subject: "CPE226", professor: "JMUYOT", room: "CL2" },
        "6-3": { subject: "CPE226", professor: "JMUYOT", room: "CL2" },
        "0-4": { subject: "ELEC2", professor: "L.Abanag", room: "" },
        "1-4": { subject: "CP33110", professor: "CpET1", room: "" },
        "2-4": { subject: "CPE317", professor: "CpET1", room: "" },
        "4-4": { subject: "CPE226", professor: "JMUYOT", room: "" },
        "5-4": { subject: "A313", professor: "CpET1", room: "" },
        "6-4": { subject: "CPE3214", professor: "CpET1", room: "" },
        "7-4": { subject: "CPE3112", professor: "CpET1", room: "" },
        "8-4": { subject: "CPE3111", professor: "CPET2", room: "" }
      }
    },
    {
      code: "BN1AA",
      session: "AFTERNOON",
      title: "BN1AA - AFTERNOON SESSION",
      slots: ["9:00 - 10:00", "10:00 - 11:00", "11:00 - 12:00", "12:00 - 01:00", "01:00 - 02:00", "02:00 - 03:00"],
      cells: {
        "2-0": { subject: "GE1", professor: "L GLACITA", room: "110" },
        "3-0": { subject: "GE1", professor: "L GLACITA", room: "110" },
        "4-0": { subject: "EN1", professor: "L GLACITA", room: "110" },
        "5-0": { subject: "EN1", professor: "L GLACITA", room: "110" },
        "2-1": { subject: "GE2", professor: "L GLACITA", room: "106" },
        "3-1": { subject: "GE2", professor: "L GLACITA", room: "106" },
        "4-1": { subject: "GE3", professor: "R.Villanueva", room: "CL2" },
        "1-2": { subject: "OMT", professor: "L GLACITA", room: "106" },
        "2-2": { subject: "NSTP1", professor: "J.Capitin", room: "106" },
        "3-2": { subject: "GE3", professor: "R.Villanueva", room: "106" },
        "4-2": { subject: "GE3", professor: "R.Villanueva", room: "106" },
        "1-3": { subject: "NSTP1", professor: "J.Capitin", room: "110" },
        "2-3": { subject: "PATHFit1", professor: "J.Capitin", room: "110" },
        "3-3": { subject: "PATHFit1", professor: "J.Capitin", room: "110" },
        "4-3": { subject: "OMT", professor: "L GLACITA", room: "110" },
        "0-4": { subject: "OMT", professor: "L GLACITA", room: "" },
        "1-4": { subject: "EN1", professor: "L GLACITA", room: "" },
        "2-4": { subject: "GE2", professor: "L GLACITA", room: "" },
        "3-4": { subject: "NSTP1", professor: "J.Capitin", room: "" },
        "4-4": { subject: "GE1", professor: "L GLACITA", room: "" }
      }
    },
    {
      code: "BG3AA",
      session: "AFTERNOON",
      title: "BG3AA - AFTERNOON SESSION",
      slots: ["10:00 - 11:00", "11:00 - 12:00", "12:00 - 01:00", "01:00 - 02:00", "02:00 - 03:00", "03:00 - 04:00", "04:00 - 05:00", "05:00 - 06:00"],
      cells: {
        "3-0": { subject: "GE8", professor: "R.Villanueva", room: "104" },
        "4-0": { subject: "A211", professor: "CpET1", room: "104" },
        "5-0": { subject: "A211", professor: "CpET1", room: "104" },
        "6-0": { subject: "A211", professor: "CpET1", room: "104" },
        "7-0": { subject: "CPE123", professor: "JMUYOT", room: "107" },
        "1-1": { subject: "GE7", professor: "R.Villanueva", room: "101" },
        "2-1": { subject: "GE7", professor: "R.Villanueva", room: "101" },
        "3-1": { subject: "M225", professor: "CPET2", room: "104" },
        "4-1": { subject: "M225", professor: "CPET2", room: "104" },
        "5-1": { subject: "M225", professor: "CPET2", room: "104" },
        "6-1": { subject: "PATHFit3", professor: "J.Capitin", room: "104" },
        "7-1": { subject: "PATHFit3", professor: "J.Capitin", room: "104" },
        "2-2": { subject: "A211", professor: "CpET1", room: "104" },
        "3-2": { subject: "A211", professor: "CpET1", room: "104" },
        "4-2": { subject: "CPE123", professor: "JMUYOT", room: "CL2" },
        "5-2": { subject: "CPE123", professor: "JMUYOT", room: "CL2" },
        "6-2": { subject: "CPE123", professor: "JMUYOT", room: "CL2" },
        "7-2": { subject: "GE7", professor: "R.Villanueva", room: "" },
        "1-3": { subject: "GE8", professor: "R.Villanueva", room: "104" },
        "2-3": { subject: "GE8", professor: "R.Villanueva", room: "104" },
        "3-3": { subject: "BES211", professor: "CPET2", room: "TL" },
        "4-3": { subject: "BES211", professor: "CPET2", room: "TL" },
        "0-4": { subject: "A211", professor: "CpET1", room: "" },
        "2-4": { subject: "BES211", professor: "CPET2", room: "" },
        "5-4": { subject: "CPE123", professor: "JMUYOT", room: "CL2" }
      }
    },
    {
      code: "BS3AA",
      session: "AFTERNOON",
      title: "BS3AA - AFTERNOON SESSION",
      slots: ["11:00 - 12:00", "12:00 - 01:00", "01:00 - 02:00", "02:00 - 03:00", "03:00 - 04:00", "04:00 - 05:00", "05:00 - 06:00", "06:00 - 07:00", "07:00 - 08:00"],
      cells: {
        "2-0": { subject: "CS212", professor: "CPET2", room: "101" },
        "3-0": { subject: "CS213", professor: "JMUYOT", room: "101" },
        "4-0": { subject: "CIS211", professor: "L.Abanag", room: "CL2" },
        "5-0": { subject: "CIS211", professor: "L.Abanag", room: "CL2" },
        "6-0": { subject: "CIS211", professor: "L.Abanag", room: "CL2" },
        "7-0": { subject: "CIS211", professor: "L.Abanag", room: "104" },
        "3-1": { subject: "CS213", professor: "JMUYOT", room: "CL2" },
        "4-1": { subject: "CS213", professor: "JMUYOT", room: "CL2" },
        "5-1": { subject: "CS213", professor: "JMUYOT", room: "CL2" },
        "6-1": { subject: "CC214", professor: "JMUYOT", room: "CL2" },
        "7-1": { subject: "CC214", professor: "JMUYOT", room: "101" },
        "0-2": { subject: "CS212", professor: "CPET2", room: "101" },
        "1-2": { subject: "GE8", professor: "J.Capitin", room: "101" },
        "2-2": { subject: "PATHFit3", professor: "J.Capitin", room: "101" },
        "3-2": { subject: "PATHFit3", professor: "J.Capitin", room: "101" },
        "3-3": { subject: "GE8", professor: "J.Capitin", room: "101" },
        "4-3": { subject: "CC214", professor: "JMUYOT", room: "CL1" },
        "5-3": { subject: "CC214", professor: "JMUYOT", room: "CL1" },
        "6-3": { subject: "CC214", professor: "JMUYOT", room: "CL1" },
        "7-3": { subject: "GE7", professor: "R.Villanueva", room: "101" },
        "8-3": { subject: "GE7", professor: "R.Villanueva", room: "101" },
        "2-4": { subject: "GE7", professor: "R.Villanueva", room: "" },
        "3-4": { subject: "CS213", professor: "JMUYOT", room: "" },
        "4-4": { subject: "CIS211", professor: "L.Abanag", room: "" },
        "5-4": { subject: "CS212", professor: "CPET2", room: "" },
        "7-4": { subject: "GE8", professor: "J.Capitin", room: "" }
      }
    },
    {
      code: "BN3AB",
      session: "AFTERNOON",
      title: "BN3AB - AFTERNOON SESSION",
      slots: ["11:00 - 12:00", "12:00 - 01:00", "01:00 - 02:00", "02:00 - 03:00", "03:00 - 04:00", "04:00 - 05:00", "05:00 - 06:00"],
      cells: {
        "0-0": { subject: "GE7", professor: "E.Borlas", room: "107" },
        "1-0": { subject: "GE7", professor: "E.Borlas", room: "107" },
        "2-0": { subject: "GE8", professor: "E.Borlas", room: "107" },
        "3-0": { subject: "GE8", professor: "E.Borlas", room: "107" },
        "4-0": { subject: "PATHFit3", professor: "J.Capitin", room: "107" },
        "5-0": { subject: "PATHFit3", professor: "J.Capitin", room: "107" },
        "2-1": { subject: "GE9", professor: "J.Capitin", room: "107" },
        "3-1": { subject: "GE9", professor: "J.Capitin", room: "107" },
        "4-1": { subject: "GE9", professor: "J.Capitin", room: "107" },
        "5-1": { subject: "ACTG1", professor: "L GLACITA", room: "107" },
        "6-1": { subject: "ACTG1", professor: "L GLACITA", room: "107" },
        "1-3": { subject: "ACTG1", professor: "L GLACITA", room: "107" },
        "2-3": { subject: "ENT3", professor: "G.Maula", room: "107" },
        "3-3": { subject: "ENT3", professor: "G.Maula", room: "107" },
        "4-3": { subject: "ENT4", professor: "G.Maula", room: "107" },
        "5-3": { subject: "ENT4", professor: "G.Maula", room: "107" },
        "2-4": { subject: "GE7", professor: "E.Borlas", room: "" },
        "3-4": { subject: "GE8", professor: "E.Borlas", room: "" },
        "4-4": { subject: "ENT3", professor: "GMAULA", room: "" },
        "5-4": { subject: "ENT4", professor: "GMAULA", room: "" },
        "6-4": { subject: "GE9", professor: "J.Capitin", room: "" }
      }
    },
    {
      code: "BN3AA",
      session: "AFTERNOON",
      title: "BN3AA - AFTERNOON SESSION",
      slots: ["11:00 - 12:00", "12:00 - 01:00", "01:00 - 02:00", "02:00 - 03:00", "03:00 - 04:00", "04:00 - 05:00", "05:00 - 06:00"],
      cells: {
        "2-0": { subject: "PATHFit3", professor: "JCAPITIN", room: "106" },
        "3-0": { subject: "PATHFit3", professor: "JCAPITIN", room: "106" },
        "4-0": { subject: "ACTG1", professor: "L GLACITA", room: "106" },
        "5-0": { subject: "ACTG1", professor: "L GLACITA", room: "106" },
        "2-1": { subject: "ENT3", professor: "G.Maula", room: "106" },
        "3-1": { subject: "ENT3", professor: "G.Maula", room: "106" },
        "4-1": { subject: "ENT4", professor: "G.Maula", room: "106" },
        "5-1": { subject: "ENT4", professor: "G.Maula", room: "106" },
        "0-3": { subject: "GE7", professor: "E.Borlas", room: "101" },
        "1-3": { subject: "GE7", professor: "E.Borlas", room: "101" },
        "2-3": { subject: "GE8", professor: "E.Borlas", room: "106" },
        "3-3": { subject: "GE8", professor: "E.Borlas", room: "106" },
        "4-3": { subject: "GE9", professor: "J.Capitin", room: "106" },
        "5-3": { subject: "GE9", professor: "J.Capitin", room: "106" },
        "0-4": { subject: "GE7", professor: "E.Borlas", room: "" },
        "1-4": { subject: "GE8", professor: "E.Borlas", room: "" },
        "2-4": { subject: "ENT3", professor: "G.Maula", room: "" },
        "3-4": { subject: "ENT4", professor: "G.Maula", room: "" },
        "4-4": { subject: "ACTG1", professor: "L GLACITA", room: "" },
        "6-4": { subject: "GE9", professor: "J.Capitin", room: "" }
      }
    },
    {
      code: "BS5EA",
      session: "EVENING",
      title: "BS5EA - EVENING SESSION",
      slots: ["02:00 - 03:00", "03:00 - 04:00", "04:00 - 05:00", "05:00 - 06:00", "06:00 - 07:00", "07:00 - 08:00", "08:00 - 09:00"],
      cells: {
        "1-0": { subject: "CS317", professor: "XPLATA", room: "CL3" },
        "2-0": { subject: "CS317", professor: "XPLATA", room: "CL3" },
        "3-0": { subject: "CIS313", professor: "R.Valdulla", room: "104" },
        "4-0": { subject: "CIS313", professor: "R.Valdulla", room: "CL2" },
        "5-0": { subject: "CIS313", professor: "R.Valdulla", room: "CL2" },
        "6-0": { subject: "CIS313", professor: "R.Valdulla", room: "CL2" },
        "3-1": { subject: "CSE311", professor: "S.Pamintuan", room: "110" },
        "4-1": { subject: "CSE311", professor: "S.Pamintuan", room: "CL3" },
        "5-1": { subject: "CSE311", professor: "S.Pamintuan", room: "CL3" },
        "6-1": { subject: "CSE311", professor: "S.Pamintuan", room: "CL3" },
        "1-2": { subject: "CS315", professor: "CPET2", room: "106" },
        "2-2": { subject: "CS315", professor: "CPET2", room: "106" },
        "3-2": { subject: "CC316", professor: "S.Hernandez", room: "CL2" },
        "4-2": { subject: "CC316", professor: "S.Hernandez", room: "CL2" },
        "5-2": { subject: "CC316", professor: "S.Hernandez", room: "CL2" },
        "6-2": { subject: "CC316", professor: "S.Hernandez", room: "CL2" },
        "3-3": { subject: "G11", professor: "J.Capitin", room: "104" },
        "4-3": { subject: "G11", professor: "J.Capitin", room: "104" },
        "5-3": { subject: "CS316", professor: "C.Abaricia", room: "104" },
        "6-3": { subject: "CS316", professor: "C.Abaricia", room: "104" },
        "0-4": { subject: "CS315", professor: "CPET2", room: "" },
        "1-4": { subject: "G11", professor: "J.Capitin", room: "" },
        "2-4": { subject: "CC316", professor: "S.Hernandez", room: "" },
        "3-4": { subject: "CSE311", professor: "S.Pamintuan", room: "" },
        "4-4": { subject: "CIS313", professor: "R.Valdulla", room: "" },
        "5-4": { subject: "CS317", professor: "XPLATA", room: "" },
        "6-4": { subject: "CS316", professor: "C.Abaricia", room: "" }
      }
    },
    {
      code: "BS3EA",
      session: "EVENING",
      title: "BS3EA - EVENING SESSION",
      slots: ["03:00 - 04:00", "04:00 - 05:00", "05:00 - 06:00", "06:00 - 07:00", "07:00 - 08:00", "08:00 - 09:00"],
      cells: {
        "1-0": { subject: "CIS211", professor: "R.Valdulla", room: "CL2" },
        "2-0": { subject: "GE7", professor: "R.Villanueva", room: "101" },
        "3-0": { subject: "GE7", professor: "R.Villanueva", room: "101" },
        "4-0": { subject: "CC214", professor: "XPLATA", room: "CL1" },
        "5-0": { subject: "CC214", professor: "XPLATA", room: "CL1" },
        "1-1": { subject: "CS212", professor: "CPET2", room: "101" },
        "2-1": { subject: "CS212", professor: "CPET2", room: "101" },
        "3-1": { subject: "CIS211", professor: "R.Valdulla", room: "CL2" },
        "4-1": { subject: "CIS211", professor: "R.Valdulla", room: "CL2" },
        "5-1": { subject: "CIS211", professor: "R.Valdulla", room: "CL2" },
        "0-2": { subject: "GE8", professor: "J.Capitin", room: "101" },
        "1-2": { subject: "GE8", professor: "J.Capitin", room: "101" },
        "2-2": { subject: "PATHFit3", professor: "J.Capitin", room: "101" },
        "3-2": { subject: "PATHFit3", professor: "J.Capitin", room: "101" },
        "4-2": { subject: "CC214", professor: "XPLATA", room: "CL1" },
        "5-2": { subject: "CC214", professor: "XPLATA", room: "CL1" },
        "1-3": { subject: "CS212", professor: "CPET2", room: "CL2" },
        "2-3": { subject: "CS213", professor: "S.Hernandez", room: "106" },
        "3-3": { subject: "CS213", professor: "S.Hernandez", room: "CL3" },
        "4-3": { subject: "CS213", professor: "S.Hernandez", room: "CL3" },
        "5-3": { subject: "CS213", professor: "S.Hernandez", room: "CL3" },
        "1-4": { subject: "GE8", professor: "J.Capitin", room: "" },
        "2-4": { subject: "CIS211", professor: "R.Valdulla", room: "" },
        "3-4": { subject: "CS213", professor: "S.Hernandez", room: "" },
        "4-4": { subject: "GE7", professor: "R.Villanueva", room: "" },
        "5-4": { subject: "CC214", professor: "XPLATA", room: "" }
      }
    },
    {
      code: "BN5EA",
      session: "EVENING",
      title: "BN5EA - EVENING SESSION",
      slots: ["03:00 - 04:00", "04:00 - 05:00", "05:00 - 06:00", "06:00 - 07:00", "07:00 - 08:00", "08:00 - 09:00"],
      cells: {
        "2-0": { subject: "CSS", professor: "XPLATA", room: "CL1" },
        "3-0": { subject: "CSS", professor: "XPLATA", room: "CL1" },
        "4-0": { subject: "ELT1", professor: "L GLACITA", room: "107" },
        "1-1": { subject: "CSS", professor: "XPLATA", room: "CL1" },
        "2-1": { subject: "CSS", professor: "XPLATA", room: "106" },
        "3-1": { subject: "G11", professor: "R.Villanueva", room: "106" },
        "4-1": { subject: "ENT8", professor: "L GLACITA", room: "106" },
        "2-2": { subject: "ENT8", professor: "L GLACITA", room: "107" },
        "3-2": { subject: "ENT8", professor: "L GLACITA", room: "107" },
        "4-2": { subject: "G11", professor: "R.Villanueva", room: "107" },
        "5-2": { subject: "G11", professor: "R.Villanueva", room: "107" },
        "0-3": { subject: "OPM", professor: "L GLACITA", room: "104" },
        "1-3": { subject: "OPM", professor: "L GLACITA", room: "104" },
        "2-3": { subject: "ELT1", professor: "L GLACITA", room: "107" },
        "3-3": { subject: "ELT1", professor: "L GLACITA", room: "107" },
        "4-3": { subject: "ELT2", professor: "L GLACITA", room: "107" },
        "5-3": { subject: "ELT2", professor: "L GLACITA", room: "107" },
        "3-4": { subject: "CSS", professor: "XPLATA", room: "" },
        "4-4": { subject: "ELT2", professor: "L GLACITA", room: "" },
        "5-4": { subject: "OPM", professor: "L GLACITA", room: "" }
      }
    }
  ];

  let isRegisterMode = false;
  let activeEditingSectionCode = null;
  let activeEditingKey = null;

  // --- STUDENTS SEARCH & DROPDOWN ---
  const searchInput = document.getElementById("student-search-input");
  const searchBox = document.getElementById("chrome-search-box");
  const dropdown = document.getElementById("chrome-dropdown");

  // --- ADMIN SEARCH & DROPDOWN ---
  const adminSearchInput = document.getElementById("admin-search-input");
  const adminSearchBox = document.getElementById("admin-search-box");
  const adminDropdown = document.getElementById("admin-dropdown");

  function getSuggestions(query) {
    if (!query) return [];
    const lowerQuery = query.toLowerCase();
    const results = [];
    const addedTexts = new Set();
    sectionsData.forEach(sec => {
      if (sec.code.toLowerCase().includes(lowerQuery) || sec.title.toLowerCase().includes(lowerQuery)) {
        if (!addedTexts.has(sec.code)) {
          results.push({ text: sec.code, label: `${sec.code} - Section`, badge: "Section" });
          addedTexts.add(sec.code);
        }
      }
      Object.values(sec.cells).forEach(cell => {
        if (cell.subject && cell.subject.toLowerCase().includes(lowerQuery)) {
          if (!addedTexts.has(cell.subject)) {
            results.push({ text: cell.subject, label: cell.subject, badge: "Subject" });
            addedTexts.add(cell.subject);
          }
        }
        if (cell.professor && cell.professor.toLowerCase().includes(lowerQuery)) {
          if (!addedTexts.has(cell.professor)) {
            results.push({ text: cell.professor, label: cell.professor, badge: "Professor" });
            addedTexts.add(cell.professor);
          }
        }
        if (cell.room && cell.room.toLowerCase().includes(lowerQuery)) {
          if (!addedTexts.has(cell.room)) {
            results.push({ text: cell.room, label: `Room ${cell.room}`, badge: "Room" });
            addedTexts.add(cell.room);
          }
        }
      });
    });
    return results.slice(0, 6);
  }

  function setupDropdownBehavior(inputEl, boxEl, dropdownEl, applyCallback) {
    inputEl.addEventListener("input", (e) => {
      const query = e.target.value.trim();
      const suggestions = getSuggestions(query);
      if (suggestions.length === 0) {
        boxEl.classList.remove("open");
        dropdownEl.innerHTML = "";
      } else {
        dropdownEl.innerHTML = suggestions.map(item => {
          const regex = new RegExp(`(${query})`, "gi");
          const highlightedText = item.label.replace(regex, "<strong>$1</strong>");
          return `
            <div class="chrome-dropdown-item" data-value="${item.text}">
              <svg class="item-icon" viewBox="0 0 24 24"><path d="M15.5 14h-.79l-.28-.27C15.41 12.59 16 11.11 16 9.5 16 5.91 13.09 3 9.5 3S3 5.91 3 9.5 5.91 16 9.5 16c1.61 0 3.09-.59 4.23-1.57l.27.28v.79l5 4.99L20.49 19l-4.99-5zm-6 0C7.01 14 5 11.99 5 9.5S7.01 5 9.5 5 14 7.01 14 9.5 11.99 14 9.5 14z"/></svg>
              <div class="item-text">${highlightedText}</div>
              <span class="item-badge">${item.badge}</span>
            </div>`;
        }).join("");
        boxEl.classList.add("open");
        dropdownEl.querySelectorAll(".chrome-dropdown-item").forEach(item => {
          item.addEventListener("click", () => {
            inputEl.value = item.getAttribute("data-value");
            boxEl.classList.remove("open");
            applyCallback();
          });
        });
      }
      applyCallback();
    });

    document.addEventListener("click", (e) => {
      if (!boxEl.contains(e.target)) boxEl.classList.remove("open");
    });
  }

  setupDropdownBehavior(searchInput, searchBox, dropdown, applyStudentFilters);
  setupDropdownBehavior(adminSearchInput, adminSearchBox, adminDropdown, applyAdminFilters);

  // --- NOTIFICATIONS ---
  const notifyBtn = document.getElementById("notify-toggle-btn");
  function updateNotifyBtnUI() {
    if ("Notification" in window && Notification.permission === "granted") {
      notifyBtn.innerHTML = "&#128276; Alerts On";
      notifyBtn.classList.add("active");
    } else {
      notifyBtn.innerHTML = "&#128276; Enable Alerts";
      notifyBtn.classList.remove("active");
    }
  }
  notifyBtn.addEventListener("click", () => {
    if (!("Notification" in window)) return alert("Push notifications not supported.");
    if (Notification.permission === "granted") {
      alert("Class notifications are active!");
    } else if (Notification.permission !== "denied") {
      Notification.requestPermission().then(permission => {
        if (permission === "granted") new Notification("Notifications Enabled!");
        updateNotifyBtnUI();
      });
    }
  });
  updateNotifyBtnUI();

  // --- VIEW SWITCHING ---
  const switchBtn = document.getElementById("portal-switch-btn");
  const portalTag = document.getElementById("portal-tag-label");

  function setView(viewId) {
    document.querySelectorAll('.view').forEach(v => v.classList.remove('active'));
    document.getElementById(viewId).classList.add('active');

    if (viewId === 'student-view') {
      portalTag.textContent = "Student Portal (View Only)";
      switchBtn.textContent = "Admin Portal";
      bindSessionFilterEvents("session-filter-buttons", (session) => {
        activeSession = session;
        applyStudentFilters();
      });
      renderMobileTabs("mobile-day-tabs", () => updateMobileColumnVisibility("sections-container"));
      renderAllSections("sections-container", false);
    } else if (viewId === 'admin-view') {
      portalTag.textContent = "Admin Portal (Management & Editable)";
      switchBtn.textContent = "Back to Student Portal";
      bindSessionFilterEvents("admin-session-filter-buttons", (session) => {
        activeSession = session;
        applyAdminFilters();
      });
      renderMobileTabs("admin-mobile-day-tabs", () => updateMobileColumnVisibility("admin-sections-container"));
      renderAllSections("admin-sections-container", true);
    } else {
      portalTag.textContent = "Admin Authentication";
      switchBtn.textContent = "Back to Student Portal";
    }
  }

  switchBtn.addEventListener("click", () => {
    const currentActive = document.querySelector('.view.active').id;
    if (currentActive === 'student-view') {
      if (localStorage.getItem(SESSION_KEY)) {
        document.getElementById("admin-user-display").textContent = localStorage.getItem(SESSION_KEY);
        setView('admin-view');
      } else {
        setView('auth-view');
      }
    } else {
      setView('student-view');
    }
  });

  // Authentication Handling
  document.getElementById("auth-toggle-btn").addEventListener("click", () => {
    isRegisterMode = !isRegisterMode;
    document.getElementById("auth-header").textContent = isRegisterMode ? "Admin Registration" : "Admin Login";
    document.getElementById("auth-submit-btn").textContent = isRegisterMode ? "Register Account" : "Sign In";
    document.getElementById("auth-toggle-text").textContent = isRegisterMode ? "Already have an account?" : "Need an account?";
    document.getElementById("auth-toggle-btn").textContent = isRegisterMode ? "Login" : "Register";
    document.getElementById("auth-error").style.display = "none";
  });

  document.getElementById("auth-form").addEventListener("submit", () => {
    const user = document.getElementById("auth-username").value.trim();
    const pass = document.getElementById("auth-password").value.trim();
    const errorEl = document.getElementById("auth-error");
    let users = JSON.parse(localStorage.getItem(USERS_KEY)) || [];

    if (isRegisterMode) {
      if (users.find(u => u.username.toLowerCase() === user.toLowerCase())) {
        errorEl.textContent = "Username already exists.";
        errorEl.style.display = "block";
        return;
      }
      users.push({ username: user, password: pass });
      localStorage.setItem(USERS_KEY, JSON.stringify(users));
      localStorage.setItem(SESSION_KEY, user);
    } else {
      const match = users.find(u => u.username.toLowerCase() === user.toLowerCase() && u.password === pass);
      if (!match) {
        errorEl.textContent = "Invalid username or password.";
        errorEl.style.display = "block";
        return;
      }
      localStorage.setItem(SESSION_KEY, match.username);
    }
    document.getElementById("admin-user-display").textContent = localStorage.getItem(SESSION_KEY);
    setView('admin-view');
  });

  document.getElementById("admin-logout-btn").addEventListener("click", () => {
    localStorage.removeItem(SESSION_KEY);
    setView('student-view');
  });

  // --- RENDER FUNCTIONS (Shared Layout for Student & Admin) ---
  function bindSessionFilterEvents(containerId, callback) {
    const buttons = document.querySelectorAll(`#${containerId} .session-filter-btn`);
    buttons.forEach(btn => {
      btn.addEventListener("click", () => {
        buttons.forEach(b => b.classList.remove("active"));
        btn.classList.add("active");
        callback(btn.dataset.session);
      });
    });
  }

  function renderMobileTabs(containerId, callback) {
    const tabsContainer = document.getElementById(containerId);
    tabsContainer.innerHTML = "";
    DAYS.forEach((day, index) => {
      const btn = document.createElement("button");
      btn.className = "day-tab" + (index === selectedDayIndex ? " active" : "");
      btn.textContent = day;
      btn.addEventListener("click", () => {
        selectedDayIndex = index;
        renderMobileTabs(containerId, callback);
        callback();
      });
      tabsContainer.appendChild(btn);
    });
  }

  function updateMobileColumnVisibility(containerId) {
    document.querySelectorAll(`#${containerId} table`).forEach(table => {
      table.className = `responsive-table show-col-${selectedDayIndex}`;
    });
  }

  function renderAllSections(containerId, isEditable) {
    const container = document.getElementById(containerId);
    container.innerHTML = "";
    if (sectionsData.length === 0) {
      container.innerHTML = `<div class="empty-state"><h3>No Sections Available</h3></div>`;
      return;
    }

    sectionsData.forEach(sec => {
      const wrapper = document.createElement("div");
      wrapper.className = "section-wrapper section-card";
      wrapper.dataset.sectionCode = sec.code;
      wrapper.dataset.session = sec.session;
      wrapper.dataset.sectionTitle = sec.title.toLowerCase();

      const toggleBtn = document.createElement("button");
      toggleBtn.className = "section-toggle-btn";
      toggleBtn.innerHTML = `<span>${sec.title}</span><span class="arrow-icon">▼</span>`;

      const tableDiv = document.createElement("div");
      tableDiv.className = "schedule-table-container hidden";

      let html = `<div class="table-container"><table class="responsive-table show-col-${selectedDayIndex}">`;
      html += `<thead><tr><th>TIME</th>`;
      DAYS.forEach(day => {
        html += `<th class="${day.includes("FRIDAY") ? "friday" : ""}">${day}</th>`;
      });
      html += `</tr></thead><tbody>`;

      sec.slots.forEach((slotLabel, rowIdx) => {
        html += `<tr><td class="time-cell">${slotLabel}</td>`;
        DAYS.forEach((day, colIdx) => {
          const key = rowIdx + "-" + colIdx;
          const cell = sec.cells[key];
          const isFri = day.includes("FRIDAY");

          if (cell) {
            const titleStr = cell.room ? `${cell.subject} · ${cell.room}` : cell.subject;
            html += `<td class="class-cell ${isFri ? "friday" : ""}" data-key="${key}" data-subject="${cell.subject}" data-prof="${cell.professor || ''}" data-room="${cell.room || ''}" ${isEditable ? 'style="cursor:pointer;" title="Click to edit slot"' : ''}>
              <div class="cell-code">${titleStr}</div>
              ${cell.professor ? `<div class="cell-name">${cell.professor}</div>` : ''}
            </td>`;
          } else {
            html += `<td class="class-cell ${isFri ? "friday" : ""}" data-key="${key}" ${isEditable ? 'style="cursor:pointer;" title="Click to add slot"' : ''}>
              <div class="${isEditable ? 'cell-empty' : 'cell-empty'}">${isEditable ? '+ Add' : '—'}</div>
            </td>`;
          }
        });
        html += `</tr>`;
      });
      html += `</tbody></table></div>`;
      tableDiv.innerHTML = html;

      toggleBtn.addEventListener("click", () => {
        const isHidden = tableDiv.classList.toggle("hidden");
        toggleBtn.classList.toggle("active", !isHidden);
      });

      // Enable click-to-edit if admin mode
      if (isEditable) {
        tableDiv.querySelectorAll(".class-cell").forEach(td => {
          td.addEventListener("click", () => {
            activeEditingSectionCode = sec.code;
            activeEditingKey = td.getAttribute("data-key");
            openCellEditor(sec, activeEditingKey);
          });
        });
      }

      wrapper.appendChild(toggleBtn);
      wrapper.appendChild(tableDiv);
      container.appendChild(wrapper);
    });

    updateMobileColumnVisibility(containerId);
    if (containerId === "sections-container") applyStudentFilters();
    else applyAdminFilters();
  }

  // --- FILTER ENGINES ---
  function applyStudentFilters() {
    applyFiltersLogic("student-search-input", "sections-container", "student-search-meta");
  }

  function applyAdminFilters() {
    applyFiltersLogic("admin-search-input", "admin-sections-container", "admin-search-meta");
  }

  function applyFiltersLogic(inputId, containerId, metaId) {
    const searchVal = document.getElementById(inputId).value.trim().toLowerCase();
    const metaEl = document.getElementById(metaId);
    const sectionCards = document.querySelectorAll(`#${containerId} .section-card`);
    let matchCount = 0;
    let foundSessions = new Set();

    sectionCards.forEach(card => {
      const cardSession = card.dataset.session;
      const sectionTitle = card.dataset.sectionTitle;

      if (!searchVal) {
        card.style.display = (cardSession !== activeSession) ? "none" : "block";
        card.querySelectorAll(".class-cell").forEach(cell => cell.classList.remove("highlight", "dimmed"));
        return;
      }

      const isSectionMatch = sectionTitle.includes(searchVal);
      let sectionHasMatches = false;

      card.querySelectorAll(".class-cell").forEach(cell => {
        const subject = (cell.dataset.subject || "").toLowerCase();
        const prof = (cell.dataset.prof || "").toLowerCase();
        const room = (cell.dataset.room || "").toLowerCase();
        const isCellMatch = subject.includes(searchVal) || prof.includes(searchVal) || room.includes(searchVal);

        if (isSectionMatch) {
          cell.classList.remove("dimmed", "highlight");
          sectionHasMatches = true;
        } else if (isCellMatch) {
          cell.classList.add("highlight");
          cell.classList.remove("dimmed");
          sectionHasMatches = true;
          matchCount++;
        } else {
          cell.classList.remove("highlight");
          cell.classList.add("dimmed");
        }
      });

      if (isSectionMatch || sectionHasMatches) {
        card.style.display = "block";
        foundSessions.add(cardSession);
        card.querySelector(".schedule-table-container").classList.remove("hidden");
        card.querySelector(".section-toggle-btn").classList.add("active");
      } else {
        card.style.display = "none";
      }
    });

    if (!searchVal) {
      metaEl.textContent = "";
    } else {
      if (foundSessions.size > 0 && !foundSessions.has(activeSession)) {
        activeSession = Array.from(foundSessions)[0];
        document.querySelectorAll(`#${containerId === 'sections-container' ? 'session-filter-buttons' : 'admin-session-filter-buttons'} .session-filter-btn`).forEach(btn => {
          btn.classList.toggle("active", btn.dataset.session === activeSession);
        });
      }
      metaEl.textContent = matchCount === 1 ? "1 match found" : matchCount + " matches found";
    }
  }

  // --- MODAL EDITING HANDLING ---
  function openCellEditor(sec, key) {
    const cell = sec.cells[key] || { subject: "", professor: "", room: "" };
    document.getElementById("subject-input").value = cell.subject;
    document.getElementById("professor-input").value = cell.professor;
    document.getElementById("room-input").value = cell.room;
    document.getElementById("cell-overlay").classList.add("open");
  }

  document.getElementById("cancel-cell-btn").addEventListener("click", () => {
    document.getElementById("cell-overlay").classList.remove("open");
  });

  document.getElementById("clear-cell-btn").addEventListener("click", () => {
    const sec = sectionsData.find(s => s.code === activeEditingSectionCode);
    if (sec) delete sec.cells[activeEditingKey];
    document.getElementById("cell-overlay").classList.remove("open");
    renderAllSections("admin-sections-container", true);
  });

  document.getElementById("save-cell-btn").addEventListener("click", () => {
    const sec = sectionsData.find(s => s.code === activeEditingSectionCode);
    if (!sec) return;

    const subject = document.getElementById("subject-input").value.trim();
    const professor = document.getElementById("professor-input").value.trim();
    const room = document.getElementById("room-input").value.trim();

    if (subject) {
      sec.cells[activeEditingKey] = { subject, professor, room };
    } else {
      delete sec.cells[activeEditingKey];
    }
    document.getElementById("cell-overlay").classList.remove("open");
    renderAllSections("admin-sections-container", true);
  });

  document.getElementById("admin-save-top-btn").addEventListener("click", () => {
    alert("All schedule modifications successfully saved!");
  });

  setView('student-view');
});
</script>
