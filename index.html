<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>For Us 💕 - Savings & Contribution Tracker</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://unpkg.com/lucide@latest"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            transition: background-color 0.3s, color 0.3s;
        }
        body.dark-theme {
            background-color: #0f172a;
            color: #f8fafc;
        }
        body.dark-theme .bg-white {
            background-color: #1e293b !important;
            color: #f8fafc !important;
        }
        body.dark-theme .bg-slate-50 {
            background-color: #0f172a !important;
        }
        body.dark-theme .bg-slate-100 {
            background-color: #334155 !important;
        }
        body.dark-theme .text-slate-800, body.dark-theme .text-slate-900 {
            color: #f1f5f9 !important;
        }
        body.dark-theme .text-slate-600, body.dark-theme .text-slate-700 {
            color: #cbd5e1 !important;
        }
        body.dark-theme .text-slate-500 {
            color: #94a3b8 !important;
        }
        body.dark-theme .border-slate-200, body.dark-theme .border-slate-100, body.dark-theme .border-slate-300 {
            border-color: #334155 !important;
        }
        body.dark-theme td, body.dark-theme th {
            border-color: #334155 !important;
            color: #f8fafc !important;
        }
        body.dark-theme td.sticky, body.dark-theme th.sticky {
            background-color: #1e293b !important;
        }
        body.dark-theme table thead tr, body.dark-theme table th {
            background-color: #065f46 !important;
            color: #f8fafc !important;
            border-color: #047857 !important;
        }
        body.dark-theme input, 
        body.dark-theme textarea, 
        body.dark-theme select {
            background-color: #0f172a !important;
            border-color: #475569 !important;
            color: #f8fafc !important;
        }
        body.dark-theme textarea::placeholder,
        body.dark-theme input::placeholder {
            color: #64748b !important;
        }
        .custom-scrollbar::-webkit-scrollbar {
            height: 8px;
            width: 8px;
        }
        .custom-scrollbar::-webkit-scrollbar-track {
            background: #f1f5f9;
            border-radius: 4px;
        }
        body.dark-theme .custom-scrollbar::-webkit-scrollbar-track {
            background: #1e293b;
        }
        .custom-scrollbar::-webkit-scrollbar-thumb {
            background: #cbd5e1;
            border-radius: 4px;
        }
        body.dark-theme .custom-scrollbar::-webkit-scrollbar-thumb {
            background: #475569;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 min-h-screen pb-12">

    <header class="bg-white border-b border-slate-200 sticky top-0 z-30 shadow-xs">
        <div class="max-w-7xl mx-auto px-4 py-4 flex flex-wrap items-center justify-between gap-4">
            <div>
                <h1 class="text-2xl font-black text-rose-600 flex items-center gap-2">
                    For Us 💕
                </h1>
                <p class="text-xs text-slate-500 font-medium mt-0.5">For our Future</p>
            </div>

            <div class="flex flex-wrap items-center gap-2">
                <button onclick="openSyncModal()" id="syncRoomBtn" class="px-3 py-1.5 bg-rose-50 text-rose-700 hover:bg-rose-100 border border-rose-200 rounded-lg text-xs font-semibold flex items-center gap-1.5 transition cursor-pointer" title="Manage Live Device Sync Room">
                    <span id="syncPulse" class="w-2 h-2 rounded-full bg-amber-500 animate-pulse"></span>
                    <i data-lucide="cloud" class="w-4 h-4 text-rose-600"></i>
                    Room: <span id="displaySyncRoom" class="font-bold">our-savings-tracker</span>
                    <i data-lucide="pencil" class="w-3 h-3 text-rose-400 opacity-80"></i>
                </button>
                <button onclick="changeRate()" class="px-3 py-1.5 bg-emerald-50 text-emerald-700 hover:bg-emerald-100 border border-emerald-200 rounded-lg text-xs font-semibold flex items-center gap-1.5 transition">
                    <i data-lucide="coins" class="w-4 h-4 text-emerald-600"></i>
                    Rate: <span id="displayDailyRate">₱20</span>/day
                </button>
                <button onclick="changeInterest()" class="px-3 py-1.5 bg-indigo-50 text-indigo-700 hover:bg-indigo-100 border border-indigo-200 rounded-lg text-xs font-semibold flex items-center gap-1.5 transition cursor-pointer" title="Click to edit interest rate">
                    <i data-lucide="trending-up" class="w-4 h-4 text-indigo-600"></i>
                    Int: <span id="displayInterestRate">3%</span>
                    <i data-lucide="pencil" class="w-3 h-3 text-indigo-500 opacity-70"></i>
                </button>
                <button onclick="toggleTheme()" class="p-2 text-slate-600 hover:bg-slate-100 rounded-lg border border-slate-200 transition" title="Toggle Theme">
                    <i data-lucide="moon" id="themeIcon" class="w-4 h-4"></i>
                </button>
                <button onclick="exportJSONBackup()" class="px-3 py-1.5 bg-slate-100 hover:bg-slate-200 text-slate-700 rounded-lg text-xs font-medium flex items-center gap-1.5 transition" title="Backup all data to a file">
                    <i data-lucide="download" class="w-4 h-4"></i> Backup
                </button>
                <label class="px-3 py-1.5 bg-slate-100 hover:bg-slate-200 text-slate-700 rounded-lg text-xs font-medium flex items-center gap-1.5 transition cursor-pointer" title="Restore data from backup file">
                    <i data-lucide="upload" class="w-4 h-4"></i> Restore
                    <input type="file" id="importFile" accept=".json" onchange="importJSONBackup(event)" class="hidden">
                </label>
            </div>
        </div>
    </header>

    <main class="max-w-7xl mx-auto px-4 py-6 space-y-6">
        
        <div class="bg-white p-4 rounded-xl border border-slate-200 shadow-xs flex flex-wrap items-center justify-between gap-4">
            <div class="flex flex-wrap items-center gap-3">
                <div class="flex items-center gap-2">
                    <label class="text-xs font-semibold text-slate-500 uppercase tracking-wider">Month:</label>
                    <select id="monthSelect" onchange="handleMonthFilterChange(this.value)" class="text-xs font-medium bg-slate-50 border border-slate-300 rounded-lg px-2.5 py-1.5 focus:ring-2 focus:ring-emerald-500 outline-none">
                        <option value="all">All Months</option>
                    </select>
                </div>

                <div class="flex items-center gap-1 bg-slate-100 p-1 rounded-lg">
                    <button onclick="setFilter('all')" id="btnFilterAll" class="px-3 py-1 text-xs font-semibold rounded-md bg-white text-slate-800 shadow-xs">All</button>
                    <button onclick="setFilter('month')" id="btnFilterMonth" class="px-3 py-1 text-xs font-semibold rounded-md text-slate-600 hover:text-slate-900">This Month</button>
                    <button onclick="setFilter('week')" id="btnFilterWeek" class="px-3 py-1 text-xs font-semibold rounded-md text-slate-600 hover:text-slate-900">This Week</button>
                    <button onclick="setFilter('missed')" id="btnFilterMissed" class="px-3 py-1 text-xs font-semibold rounded-md text-slate-600 hover:text-slate-900">Missed</button>
                </div>
            </div>

            <div class="flex flex-wrap items-center gap-2">
                <button onclick="jumpToToday()" class="px-3 py-1.5 bg-amber-500 hover:bg-amber-600 text-white rounded-lg text-xs font-semibold flex items-center gap-1.5 transition shadow-xs">
                    <i data-lucide="crosshair" class="w-4 h-4"></i> Jump to Today
                </button>
                <button onclick="openAddDayModal()" class="px-3 py-1.5 bg-emerald-600 hover:bg-emerald-700 text-white rounded-lg text-xs font-semibold flex items-center gap-1.5 transition shadow-xs">
                    <i data-lucide="plus" class="w-4 h-4"></i> Add Day
                </button>
                <button onclick="openAddMonthModal()" class="px-3 py-1.5 bg-emerald-50 hover:bg-emerald-100 text-emerald-700 border border-emerald-200 rounded-lg text-xs font-semibold flex items-center gap-1.5 transition">
                    <i data-lucide="calendar-plus" class="w-4 h-4"></i> Add Month
                </button>
                <button onclick="toggleOrientation()" id="btnOrientation" class="p-2 bg-slate-100 hover:bg-slate-200 text-slate-700 rounded-lg text-xs font-medium flex items-center justify-center transition" title="Toggle Layout: Dates in Columns ↔️ Rows">
                    <i data-lucide="columns" class="w-4 h-4"></i>
                </button>
            </div>
        </div>

        <div id="tableContainer" class="bg-white rounded-xl border border-slate-200 shadow-xs overflow-hidden">
            <!-- Dynamic Table Content -->
        </div>

        <div id="summaryCardsContainer" class="grid grid-cols-1 md:grid-cols-3 gap-4">
            <!-- Dynamic Summary Cards -->
        </div>
    </main>

    <!-- Sync Modal -->
    <div id="syncModal" class="fixed inset-0 bg-slate-900/50 backdrop-blur-xs z-50 flex items-center justify-center hidden p-4">
        <div class="bg-white rounded-2xl max-w-md w-full p-6 shadow-xl border border-slate-100 space-y-4 max-h-[90vh] overflow-y-auto custom-scrollbar">
            <div class="flex items-center justify-between">
                <h3 class="text-lg font-bold text-slate-800 flex items-center gap-2">
                    <i data-lucide="wifi" class="w-5 h-5 text-rose-600"></i> Pair Devices & Live Sync
                </h3>
                <button onclick="closeSyncModal()" class="text-slate-400 hover:text-slate-600">
                    <i data-lucide="x" class="w-5 h-5"></i>
                </button>
            </div>

            <!-- Sync Status Banner -->
            <div id="syncStatusBanner" class="p-3 rounded-xl border text-xs flex items-start gap-2.5 bg-amber-50 border-amber-200 text-amber-900">
                <i data-lucide="alert-circle" class="w-4 h-4 text-amber-600 shrink-0 mt-0.5"></i>
                <div>
                    <span class="font-bold block" id="syncStatusTitle">Local Storage Mode</span>
                    <span id="syncStatusDesc" class="text-2xs text-amber-700 leading-snug block">
                        Changes are saved on this device only. Set up live sync below!
                    </span>
                </div>
            </div>

            <div>
                <label class="block text-xs font-semibold text-slate-600 mb-1">Room Code / Sync Key:</label>
                <div class="flex gap-2">
                    <input type="text" id="syncRoomInput" class="w-full border border-slate-300 rounded-xl p-2.5 text-sm font-mono focus:ring-2 focus:ring-rose-500 focus:outline-none" placeholder="e.g. matt-and-tif-2026">
                    <button onclick="copySyncCode()" class="px-3 bg-slate-100 hover:bg-slate-200 rounded-xl text-slate-700 text-xs font-semibold flex items-center gap-1 shrink-0" title="Copy code">
                        <i data-lucide="copy" class="w-4 h-4"></i>
                    </button>
                </div>
            </div>

            <div class="pt-2 border-t border-slate-100">
                <button onclick="toggleFirebaseConfigSection()" class="w-full flex items-center justify-between text-xs font-bold text-slate-700 hover:text-rose-600 transition py-1">
                    <span class="flex items-center gap-1.5">
                        <i data-lucide="database" class="w-4 h-4 text-indigo-600"></i>
                        Firebase Cloud Credentials Setup
                    </span>
                    <i data-lucide="chevron-down" id="fbConfigChevron" class="w-4 h-4 transition-transform"></i>
                </button>

                <div id="firebaseConfigSection" class="mt-3 space-y-3 hidden bg-slate-50 p-3.5 rounded-xl border border-slate-200">
                    <p class="text-2xs text-slate-600 leading-relaxed">
                        Paste your <strong>Firebase Web Config</strong> (JSON object) to enable real-time synchronization across devices:
                    </p>
                    <textarea id="firebaseConfigInput" rows="5" class="w-full border border-slate-300 rounded-xl p-2.5 font-mono text-2xs focus:ring-2 focus:ring-indigo-500 focus:outline-none" placeholder='{
  "apiKey": "AIzaSy...",
  "authDomain": "your-app.firebaseapp.com",
  "projectId": "your-app",
  "storageBucket": "your-app.firebasestorage.app",
  "messagingSenderId": "123456789",
  "appId": "1:123456789:web:abcdef"
}'></textarea>
                    <div class="flex gap-2 justify-end">
                        <button onclick="clearFirebaseConfig()" class="px-3 py-1.5 text-rose-600 hover:bg-rose-50 rounded-lg text-2xs font-semibold">Clear Config</button>
                        <button onclick="saveCustomFirebaseConfig()" class="px-3 py-1.5 bg-indigo-600 hover:bg-indigo-700 text-white rounded-lg text-2xs font-semibold shadow-xs">Save Credentials</button>
                    </div>
                </div>
            </div>

            <div class="flex items-center justify-end gap-2 pt-2 border-t border-slate-100">
                <button onclick="closeSyncModal()" class="px-4 py-2 text-slate-600 hover:bg-slate-100 rounded-lg text-xs font-semibold">Cancel</button>
                <button onclick="saveSyncRoom()" class="px-4 py-2 bg-rose-600 hover:bg-rose-700 text-white rounded-lg text-xs font-semibold shadow-xs flex items-center gap-1.5">
                    <i data-lucide="cloud-lightning" class="w-4 h-4"></i> Connect & Sync
                </button>
            </div>
        </div>
    </div>

    <!-- Edit Settings Modal -->
    <div id="editSettingsModal" class="fixed inset-0 bg-slate-900/50 backdrop-blur-xs z-50 flex items-center justify-center hidden p-4">
        <div class="bg-white rounded-2xl max-w-sm w-full p-6 shadow-xl border border-slate-100 space-y-4">
            <div class="flex items-center justify-between">
                <h3 id="settingsModalTitle" class="text-lg font-bold text-slate-800 flex items-center gap-2">
                    <i data-lucide="sliders" class="w-5 h-5 text-indigo-600"></i> Edit Settings
                </h3>
                <button onclick="closeSettingsModal()" class="text-slate-400 hover:text-slate-600">
                    <i data-lucide="x" class="w-5 h-5"></i>
                </button>
            </div>
            <div>
                <label id="settingsModalLabel" class="block text-xs font-semibold text-slate-600 mb-1">Value:</label>
                <input type="number" id="settingsModalInput" step="any" min="0" class="w-full border border-slate-300 rounded-xl p-2.5 text-sm focus:ring-2 focus:ring-indigo-500 focus:outline-none">
            </div>
            <div class="flex items-center justify-end gap-2 pt-2">
                <button onclick="closeSettingsModal()" class="px-4 py-2 text-slate-600 hover:bg-slate-100 rounded-lg text-xs font-semibold">Cancel</button>
                <button onclick="saveSettingsModal()" class="px-4 py-2 bg-indigo-600 hover:bg-indigo-700 text-white rounded-lg text-xs font-semibold shadow-xs">Save Changes</button>
            </div>
        </div>
    </div>

    <!-- Notes Modal -->
    <div id="noteModal" class="fixed inset-0 bg-slate-900/50 backdrop-blur-xs z-50 flex items-center justify-center hidden p-4">
        <div class="bg-white rounded-2xl max-w-md w-full p-6 shadow-xl border border-slate-100 space-y-4">
            <div class="flex items-center justify-between">
                <h3 class="text-lg font-bold text-slate-800 flex items-center gap-2">
                    <i data-lucide="file-text" class="w-5 h-5 text-emerald-600"></i> Entry Notes
                </h3>
                <button onclick="closeModal()" class="text-slate-400 hover:text-slate-600">
                    <i data-lucide="x" class="w-5 h-5"></i>
                </button>
            </div>
            <div>
                <p id="modalSubtext" class="text-xs font-medium text-slate-500 mb-2"></p>
                <textarea id="modalNoteText" rows="4" class="w-full border border-slate-300 rounded-xl p-3 text-sm focus:ring-2 focus:ring-emerald-500 focus:outline-none" placeholder="Add optional details or notes..."></textarea>
            </div>
            <div class="flex items-center justify-between pt-2">
                <button id="btnDeleteNote" onclick="deleteModalNote()" class="px-3 py-2 text-rose-600 hover:bg-rose-50 rounded-lg text-xs font-semibold flex items-center gap-1 transition">
                    <i data-lucide="trash-2" class="w-4 h-4"></i> Delete Note
                </button>
                <div class="flex items-center gap-2">
                    <button onclick="closeModal()" class="px-4 py-2 text-slate-600 hover:bg-slate-100 rounded-lg text-xs font-semibold">Cancel</button>
                    <button onclick="saveModalNote()" class="px-4 py-2 bg-emerald-600 hover:bg-emerald-700 text-white rounded-lg text-xs font-semibold shadow-xs">Save Note</button>
                </div>
            </div>
        </div>
    </div>

    <!-- Add Single Day Modal -->
    <div id="addDayModal" class="fixed inset-0 bg-slate-900/50 backdrop-blur-xs z-50 flex items-center justify-center hidden p-4">
        <div class="bg-white rounded-2xl max-w-sm w-full p-6 shadow-xl border border-slate-100 space-y-4">
            <div class="flex items-center justify-between">
                <h3 class="text-lg font-bold text-slate-800 flex items-center gap-2">
                    <i data-lucide="calendar" class="w-5 h-5 text-emerald-600"></i> Add Single Day
                </h3>
                <button onclick="closeAddDayModal()" class="text-slate-400 hover:text-slate-600">
                    <i data-lucide="x" class="w-5 h-5"></i>
                </button>
            </div>
            <div>
                <label class="block text-xs font-semibold text-slate-600 mb-1">Select Date:</label>
                <input type="date" id="newDateInput" class="w-full border border-slate-300 rounded-xl p-2.5 text-sm focus:ring-2 focus:ring-emerald-500 focus:outline-none">
            </div>
            <div class="flex items-center justify-end gap-2 pt-2">
                <button onclick="closeAddDayModal()" class="px-4 py-2 text-slate-600 hover:bg-slate-100 rounded-lg text-xs font-semibold">Cancel</button>
                <button onclick="saveNewDay()" class="px-4 py-2 bg-emerald-600 hover:bg-emerald-700 text-white rounded-lg text-xs font-semibold shadow-xs">Add Date</button>
            </div>
        </div>
    </div>

    <!-- Add Month Modal -->
    <div id="addMonthModal" class="fixed inset-0 bg-slate-900/50 backdrop-blur-xs z-50 flex items-center justify-center hidden p-4">
        <div class="bg-white rounded-2xl max-w-sm w-full p-6 shadow-xl border border-slate-100 space-y-4">
            <div class="flex items-center justify-between">
                <h3 class="text-lg font-bold text-slate-800 flex items-center gap-2">
                    <i data-lucide="calendar-plus" class="w-5 h-5 text-emerald-600"></i> Add Entire Month
                </h3>
                <button onclick="closeAddMonthModal()" class="text-slate-400 hover:text-slate-600">
                    <i data-lucide="x" class="w-5 h-5"></i>
                </button>
            </div>
            <div>
                <label class="block text-xs font-semibold text-slate-600 mb-1">Select Month & Year:</label>
                <input type="month" id="newMonthInput" class="w-full border border-slate-300 rounded-xl p-2.5 text-sm focus:ring-2 focus:ring-emerald-500 focus:outline-none">
            </div>
            <div class="flex items-center justify-end gap-2 pt-2">
                <button onclick="closeAddMonthModal()" class="px-4 py-2 text-slate-600 hover:bg-slate-100 rounded-lg text-xs font-semibold">Cancel</button>
                <button onclick="saveNewMonth()" class="px-4 py-2 bg-emerald-600 hover:bg-emerald-700 text-white rounded-lg text-xs font-semibold shadow-xs">Generate Month</button>
            </div>
        </div>
    </div>

    <!-- Non-intrusive Toast Notification -->
    <div id="toastNotification" class="fixed bottom-5 right-5 z-50 bg-emerald-600 text-white px-4 py-3 rounded-xl shadow-lg flex items-center gap-2 transition-all duration-300 opacity-0 pointer-events-none transform translate-y-2">
        <i id="toastIcon" data-lucide="check-circle-2" class="w-5 h-5"></i>
        <span id="toastText" class="text-xs font-semibold"></span>
    </div>

    <script type="module">
        import { initializeApp, getApps, getApp, deleteApp } from "https://www.gstatic.com/firebasejs/11.6.1/firebase-app.js";
        import { getAuth, signInAnonymously, signInWithCustomToken } from "https://www.gstatic.com/firebasejs/11.6.1/firebase-auth.js";
        import { getFirestore, doc, setDoc, onSnapshot } from "https://www.gstatic.com/firebasejs/11.6.1/firebase-firestore.js";

        const appId = typeof __app_id !== 'undefined' ? __app_id : 'for-us-savings-tracker';

        const defaultData = {
            dailyRate: 20,
            interestRate: 3,
            people: ["Matt", "Tif"],
            dates: [
                "August 23, 2026", "August 24, 2026", "August 25, 2026",
                "August 26, 2026", "August 27, 2026", "August 28, 2026", "August 29, 2026", "August 30, 2026",
                "August 31, 2026", "September 1, 2026", "September 2, 2026", "September 3, 2026", "September 4, 2026",
                "September 5, 2026", "September 6, 2026", "September 7, 2026", "September 8, 2026", "September 9, 2026",
                "September 10, 2026", "September 11, 2026", "September 12, 2026", "September 13, 2026", "September 14, 2026",
                "September 15, 2026", "September 16, 2026", "September 17, 2026", "September 18, 2026", "September 19, 2026",
                "September 20, 2026", "September 21, 2026", "September 22, 2026", "September 23, 2026", "September 24, 2026",
                "September 25, 2026", "September 26, 2026"
            ],
            cells: {
                "r0_c2": { status: "done", checked: true, timestamp: "Aug 25 · 09:30 AM", notes: "Saved ₱20" },
                "r1_c2": { status: "done", checked: true, timestamp: "Aug 25 · 10:15 AM", notes: "Saved ₱20" }
            }
        };

        const HARDCODED_FIREBASE_CONFIG = {
            apiKey: "AIzaSyBeL_RP3j8HoKCQLRrQtSMrW3aHOhplL-4",
            authDomain: "our-savings-app.firebaseapp.com",
            databaseURL: "https://our-savings-app-default-rtdb.firebaseio.com",
            projectId: "our-savings-app",
            storageBucket: "our-savings-app.firebasestorage.app",
            messagingSenderId: "425975640293",
            appId: "1:425975640293:web:93c90879946cad8600a40c",
            measurementId: "G-5MHPDSCL33"
        };

        let db = null;
        let auth = null;
        let unsubscribeSync = null;
        let isSyncingFromCloud = false;

        let appData = JSON.parse(JSON.stringify(defaultData));
        window.appData = appData;

        let activeFilter = 'all'; 
        let currentMonthFilter = 'all'; 
        let orientation = localStorage.getItem('savings_tracker_orientation') || 'vertical'; 
        let currentModalTarget = null; 
        let currentRoomId = localStorage.getItem('savings_tracker_room_id') || 'our-savings-tracker';

        function showToast(msg, iconType = 'check') {
            const toast = document.getElementById('toastNotification');
            const toastText = document.getElementById('toastText');
            const toastIcon = document.getElementById('toastIcon');
            if (!toast || !toastText) return;

            toastText.textContent = msg;
            if (toastIcon) {
                toastIcon.setAttribute('data-lucide', iconType === 'error' ? 'alert-circle' : 'check-circle-2');
                if (window.lucide) lucide.createIcons();
            }

            toast.classList.remove('opacity-0', 'pointer-events-none', 'translate-y-2');
            toast.classList.add('opacity-100', 'translate-y-0');

            setTimeout(() => {
                toast.classList.remove('opacity-100', 'translate-y-0');
                toast.classList.add('opacity-0', 'pointer-events-none', 'translate-y-2');
            }, 3000);
        }
        window.showToast = showToast;

        function escapeHtml(text) {
            if (!text) return '';
            return String(text)
                .replace(/&/g, "&amp;")
                .replace(/</g, "&lt;")
                .replace(/>/g, "&gt;")
                .replace(/"/g, "&quot;")
                .replace(/'/g, "&#039;");
        }

        function getFirebaseConfig() {
            const savedConfig = localStorage.getItem('savings_tracker_firebase_config');
            if (savedConfig) {
                try {
                    return JSON.parse(savedConfig);
                } catch(e) {}
            }
            if (HARDCODED_FIREBASE_CONFIG && HARDCODED_FIREBASE_CONFIG.apiKey) {
                return HARDCODED_FIREBASE_CONFIG;
            }
            if (typeof __firebase_config !== 'undefined' && __firebase_config) {
                try {
                    return typeof __firebase_config === 'string' ? JSON.parse(__firebase_config) : __firebase_config;
                } catch(e) {}
            }
            return null;
        }

        function updateSyncUIStatus(status, message = '') {
            const pulse = document.getElementById('syncPulse');
            const title = document.getElementById('syncStatusTitle');
            const desc = document.getElementById('syncStatusDesc');

            if (!pulse || !title || !desc) return;

            if (status === 'live') {
                pulse.className = "w-2 h-2 rounded-full bg-emerald-500 animate-pulse";
                title.textContent = "Live Cloud Sync Active";
                desc.textContent = `Real-time updates enabled in Room: ${currentRoomId}`;
            } else if (status === 'connecting') {
                pulse.className = "w-2 h-2 rounded-full bg-amber-500 animate-pulse";
                title.textContent = "Connecting to Cloud...";
                desc.textContent = "Establishing live database connection.";
            } else if (status === 'error') {
                pulse.className = "w-2 h-2 rounded-full bg-rose-500";
                title.textContent = "Sync Connection Issue";
                desc.textContent = message || "Could not connect to Firebase cloud. Running in local storage mode.";
            } else {
                pulse.className = "w-2 h-2 rounded-full bg-slate-400";
                title.textContent = "Local Storage Mode";
                desc.textContent = "Data is saved locally on this device.";
            }
        }

        async function saveToCloud() {
            if (!db || isSyncingFromCloud) return;
            try {
                const trackerRef = doc(db, 'artifacts', appId, 'public', 'data', 'trackers', currentRoomId);
                await setDoc(trackerRef, {
                    data: window.appData,
                    updatedAt: new Date().toISOString(),
                    updatedBy: auth?.currentUser?.uid || 'anonymous'
                }, { merge: true });
            } catch (err) {
                console.error("Failed to sync to cloud:", err);
            }
        }
        window.saveToCloud = saveToCloud;

        function setupRealtimeSync(roomId) {
            if (!db) return;
            const trackerRef = doc(db, 'artifacts', appId, 'public', 'data', 'trackers', roomId);

            updateSyncUIStatus('connecting');

            unsubscribeSync = onSnapshot(trackerRef, (docSnap) => {
                if (docSnap.exists()) {
                    const cloudDoc = docSnap.data();
                    if (cloudDoc && cloudDoc.data) {
                        isSyncingFromCloud = true;
                        window.appData = Object.assign({}, defaultData, cloudDoc.data);
                        appData = window.appData;

                        saveLocalData();
                        populateMonthSelectOptions();
                        renderAll(true);

                        isSyncingFromCloud = false;
                        updateSyncUIStatus('live');
                    }
                } else {
                    updateSyncUIStatus('live');
                    saveToCloud();
                }
            }, (error) => {
                console.warn("Realtime sync error:", error);
                updateSyncUIStatus('error', error.message || 'Permission denied or network offline.');
            });
        }

        async function initCloudSync() {
            const roomDisplay = document.getElementById('displaySyncRoom');
            if (roomDisplay) roomDisplay.textContent = currentRoomId;

            const firebaseConfig = getFirebaseConfig();

            if (!firebaseConfig || !firebaseConfig.apiKey) {
                updateSyncUIStatus('offline');
                return;
            }

            try {
                if (unsubscribeSync) {
                    unsubscribeSync();
                    unsubscribeSync = null;
                }

                if (getApps().length > 0) {
                    await deleteApp(getApp());
                }

                const app = initializeApp(firebaseConfig);
                auth = getAuth(app);
                db = getFirestore(app);

                let authenticated = false;

                if (typeof __initial_auth_token !== 'undefined' && __initial_auth_token) {
                    try {
                        await signInWithCustomToken(auth, __initial_auth_token);
                        authenticated = true;
                    } catch (tErr) {}
                }

                if (!authenticated) {
                    try {
                        await signInAnonymously(auth);
                    } catch (aErr) {
                        console.warn("Anonymous sign-in skipped/failed:", aErr.message);
                    }
                }

                setupRealtimeSync(currentRoomId);
            } catch (err) {
                console.error("Initialization error:", err);
                updateSyncUIStatus('error', err.message || "Failed to connect to Firebase.");
            }
        }

        function loadLocalData() {
            const saved = localStorage.getItem('contributionTrackerData');
            if (saved) {
                try {
                    appData = JSON.parse(saved);
                    if (appData.dailyRate === undefined) appData.dailyRate = 20;
                    if (appData.interestRate === undefined) appData.interestRate = 3;
                } catch (e) {
                    appData = JSON.parse(JSON.stringify(defaultData));
                }
            } else {
                appData = JSON.parse(JSON.stringify(defaultData));
            }
            window.appData = appData;
            populateMonthSelectOptions();
            renderAll();
        }

        function saveLocalData() {
            localStorage.setItem('contributionTrackerData', JSON.stringify(appData));
        }

        function isTodayDate(dateStr) {
            const today = new Date();
            const parsed = new Date(dateStr);
            if (isNaN(parsed.getTime())) return false;
            return parsed.getDate() === today.getDate() &&
                   parsed.getMonth() === today.getMonth() &&
                   parsed.getFullYear() === today.getFullYear();
        }

        function isPastDate(dateStr) {
            const today = new Date();
            today.setHours(0, 0, 0, 0);
            const parsed = new Date(dateStr);
            if (isNaN(parsed.getTime())) return false;
            parsed.setHours(0, 0, 0, 0);
            return parsed < today;
        }

        function getCellId(pIndex, dIndex) {
            return `r${pIndex}_c${dIndex}`;
        }

        function toggleCellCheckbox(pIndex, dIndex, isChecked) {
            const cellId = getCellId(pIndex, dIndex);
            if (!appData.cells[cellId]) {
                appData.cells[cellId] = { status: '', notes: '', timestamp: '' };
            }

            if (isChecked) {
                const now = new Date();
                const dateString = now.toLocaleDateString('en-US', { month: 'short', day: 'numeric' });
                const timeString = now.toLocaleTimeString([], { hour: '2-digit', minute: '2-digit' });
                appData.cells[cellId].status = 'done';
                appData.cells[cellId].checked = true;
                appData.cells[cellId].timestamp = `${dateString} · ${timeString}`;
            } else {
                appData.cells[cellId].status = '';
                appData.cells[cellId].checked = false;
                appData.cells[cellId].timestamp = '';
            }

            saveLocalData();
            saveToCloud();
            renderAll(true);
        }
        window.toggleCellCheckbox = toggleCellCheckbox;

        function getFilteredDateIndices() {
            let indices = appData.dates.map((_, i) => i);

            if (currentMonthFilter !== 'all') {
                indices = indices.filter(i => {
                    const d = new Date(appData.dates[i]);
                    if (isNaN(d.getTime())) return false;
                    const monthKey = `${d.getFullYear()}-${String(d.getMonth() + 1).padStart(2, '0')}`;
                    return monthKey === currentMonthFilter;
                });
            }

            if (activeFilter === 'month') {
                const today = new Date();
                const curYear = today.getFullYear();
                const curMonth = today.getMonth();

                indices = indices.filter(i => {
                    const d = new Date(appData.dates[i]);
                    return !isNaN(d.getTime()) && d.getFullYear() === curYear && d.getMonth() === curMonth;
                });
            } else if (activeFilter === 'week') {
                const today = new Date();
                const startOfWeek = new Date(today);
                startOfWeek.setDate(today.getDate() - today.getDay());
                startOfWeek.setHours(0,0,0,0);
                
                const endOfWeek = new Date(startOfWeek);
                endOfWeek.setDate(startOfWeek.getDate() + 6);
                endOfWeek.setHours(23,59,59,999);

                indices = indices.filter(i => {
                    const d = new Date(appData.dates[i]);
                    return d >= startOfWeek && d <= endOfWeek;
                });
            } else if (activeFilter === 'missed') {
                indices = indices.filter(dIndex => {
                    const dateStr = appData.dates[dIndex];
                    if (!isPastDate(dateStr)) return false;
                    return appData.people.some((_, pIndex) => {
                        const cellId = getCellId(pIndex, dIndex);
                        const cell = appData.cells[cellId];
                        return !(cell && (cell.status === 'done' || cell.checked));
                    });
                });
            }

            return indices;
        }

        function calculateStreaksAndStats() {
            const todayObj = new Date();
            todayObj.setHours(0, 0, 0, 0);

            return appData.people.map((person, pIndex) => {
                let totalChecked = 0;
                let currentStreak = 0;
                let bestStreak = 0;
                let tempStreak = 0;

                appData.dates.forEach((_, dIndex) => {
                    const cellId = getCellId(pIndex, dIndex);
                    const cell = appData.cells[cellId];
                    const isDone = cell && (cell.status === 'done' || cell.checked);

                    if (isDone) {
                        totalChecked++;
                        tempStreak++;
                        if (tempStreak > bestStreak) bestStreak = tempStreak;
                    } else {
                        tempStreak = 0;
                    }
                });

                let lastCheckableIndex = -1;
                for (let i = appData.dates.length - 1; i >= 0; i--) {
                    const d = new Date(appData.dates[i]);
                    if (!isNaN(d.getTime())) {
                        d.setHours(0, 0, 0, 0);
                        if (d <= todayObj) {
                            lastCheckableIndex = i;
                            break;
                        }
                    }
                }

                if (lastCheckableIndex === -1) {
                    lastCheckableIndex = appData.dates.length - 1;
                }

                for (let i = lastCheckableIndex; i >= 0; i--) {
                    const cellId = getCellId(pIndex, i);
                    const cell = appData.cells[cellId];
                    const isDone = cell && (cell.status === 'done' || cell.checked);

                    if (isDone) {
                        currentStreak++;
                    } else {
                        const d = new Date(appData.dates[i]);
                        d.setHours(0, 0, 0, 0);
                        if (d.getTime() === todayObj.getTime() && currentStreak === 0) {
                            continue;
                        }
                        break;
                    }
                }

                return {
                    person,
                    totalChecked,
                    currentStreak,
                    bestStreak,
                    totalSaved: totalChecked * appData.dailyRate
                };
            });
        }

        function createCellTd(pIndex, dIndex, isToday = false) {
            const cellId = getCellId(pIndex, dIndex);
            const cellData = appData.cells[cellId] || { status: '', notes: '', timestamp: '' };
            const isChecked = cellData.status === 'done' || cellData.checked || false;
            const dateStr = appData.dates[dIndex];
            const isPast = isPastDate(dateStr);
            const isMissed = isPast && !isChecked;

            const td = document.createElement('td');
            const borderClass = isToday 
                ? 'border-r-2 border-l-2 border-amber-300/80' 
                : (isMissed ? 'border-r border-rose-200/60' : 'border-r border-slate-200/60');
            td.className = `${borderClass} p-0 relative text-center min-w-[160px]`;

            let bgClass = '';
            if (isChecked) {
                bgClass = isToday ? 'bg-emerald-100/90' : 'bg-emerald-50/80';
            } else if (isMissed) {
                bgClass = 'bg-rose-50/60';
            } else if (isToday) {
                bgClass = 'bg-amber-50/60';
            }

            const hasNotes = Boolean(cellData.notes);
            const safeNotes = escapeHtml(cellData.notes);

            const noteBtnHtml = hasNotes
                ? `<button onclick="openModal(${pIndex}, ${dIndex})" class="absolute top-1 right-1 text-emerald-700 hover:text-emerald-900 p-1 bg-white/90 rounded-full shadow-xs" title="${safeNotes}">
                    <i data-lucide="file-text" class="w-3.5 h-3.5"></i>
                   </button>`
                : `<button onclick="openModal(${pIndex}, ${dIndex})" class="absolute top-1 right-1 text-slate-300 hover:text-slate-500 opacity-0 group-hover/cell:opacity-100 transition p-1" title="Add Details / Notes">
                    <i data-lucide="sticky-note" class="w-3.5 h-3.5"></i>
                   </button>`;

            const timeBadge = (isChecked && cellData.timestamp)
                ? `<span class="text-2xs font-semibold text-emerald-800 bg-emerald-100 px-2 py-0.5 rounded-full shadow-xs mt-1 border border-emerald-200/60">${cellData.timestamp}</span>`
                : (isMissed ? `<span class="text-2xs font-semibold text-rose-700 bg-rose-100/80 px-2 py-0.5 rounded-full shadow-xs mt-1 border border-rose-200">Missed</span>` : '');

            const checkboxBorder = isMissed ? 'border-rose-300 bg-rose-50' : 'border-slate-300';

            td.innerHTML = `
                <div class="w-full h-full min-h-[60px] flex flex-col items-center justify-center relative group/cell ${bgClass} p-2 transition">
                    <input type="checkbox" ${isChecked ? 'checked' : ''} onchange="toggleCellCheckbox(${pIndex}, ${dIndex}, this.checked)" class="w-5 h-5 rounded-md ${checkboxBorder} text-emerald-600 focus:ring-emerald-500 cursor-pointer accent-emerald-600 transition shadow-xs">
                    ${timeBadge}
                    ${noteBtnHtml}
                </div>
            `;
            return td;
        }

        function populateMonthSelectOptions() {
            const select = document.getElementById('monthSelect');
            if (!select) return;

            const existingMonths = new Set();
            appData.dates.forEach(dateStr => {
                const d = new Date(dateStr);
                if (!isNaN(d.getTime())) {
                    const monthKey = `${d.getFullYear()}-${String(d.getMonth() + 1).padStart(2, '0')}`;
                    const monthName = d.toLocaleDateString('en-US', { month: 'long', year: 'numeric' });
                    existingMonths.add(JSON.stringify({ key: monthKey, name: monthName }));
                }
            });

            const sortedMonths = Array.from(existingMonths)
                .map(item => JSON.parse(item))
                .sort((a, b) => a.key.localeCompare(b.key));

            select.innerHTML = '<option value="all">All Months</option>';
            sortedMonths.forEach(m => {
                const option = document.createElement('option');
                option.value = m.key;
                option.textContent = m.name;
                select.appendChild(option);
            });

            select.value = currentMonthFilter;
        }
        window.populateMonthSelectOptions = populateMonthSelectOptions;

        function renderHorizontalTable() {
            const container = document.getElementById('tableContainer');
            const filteredIndices = getFilteredDateIndices();

            if (filteredIndices.length === 0) {
                container.innerHTML = `
                    <div class="p-8 text-center text-slate-500 space-y-2">
                        <i data-lucide="check-circle-2" class="w-10 h-10 text-emerald-500 mx-auto opacity-80"></i>
                        <p class="font-bold text-sm text-slate-700">No missed contributions!</p>
                        <p class="text-xs text-slate-500">You're completely up to date with your savings goal!</p>
                    </div>`;
                return;
            }

            let html = `
                <div class="overflow-x-auto custom-scrollbar">
                    <table class="w-full text-left border-collapse text-xs">
                        <thead>
                            <tr class="bg-emerald-800 text-white border-b border-emerald-900 font-bold uppercase tracking-wider">
                                <th class="sticky left-0 z-20 bg-emerald-800 p-3 text-center min-w-[140px] border-r border-emerald-700 shadow-md">
                                    Date
                                </th>`;

            appData.people.forEach((person) => {
                html += `
                    <th class="p-3 text-center min-w-[160px] border-r border-emerald-700">
                        <div class="font-extrabold text-sm text-white">${person}</div>
                    </th>`;
            });

            html += `</tr></thead><tbody class="divide-y divide-slate-200">`;

            filteredIndices.forEach((dIndex) => {
                const dateStr = appData.dates[dIndex];
                const isToday = isTodayDate(dateStr);
                const isPast = isPastDate(dateStr);

                let dateBg = 'bg-slate-50';
                let dateBadge = '';

                if (isToday) {
                    dateBg = 'bg-amber-100 text-amber-900 border-r-2 border-amber-300';
                    dateBadge = `<span class="block text-2xs font-bold text-amber-700 uppercase tracking-wider">Today</span>`;
                } else if (isPast) {
                    dateBg = 'bg-slate-100/80 text-slate-700';
                }

                html += `<tr id="date-row-${dIndex}" class="hover:bg-slate-50/80 transition">
                    <th class="sticky left-0 z-10 ${dateBg} p-3 font-semibold text-center border-r border-slate-200 shadow-xs whitespace-nowrap">
                        <div class="text-xs text-slate-800 font-bold whitespace-nowrap">${dateStr}</div>
                        ${dateBadge}
                    </th>`;

                appData.people.forEach((_, pIndex) => {
                    const tempTd = createCellTd(pIndex, dIndex, isToday);
                    html += tempTd.outerHTML;
                });

                html += `</tr>`;
            });

            html += `</tbody></table></div>`;
            container.innerHTML = html;
        }

        function renderVerticalTable() {
            const container = document.getElementById('tableContainer');
            const filteredIndices = getFilteredDateIndices();

            if (filteredIndices.length === 0) {
                container.innerHTML = `
                    <div class="p-8 text-center text-slate-500 space-y-2">
                        <i data-lucide="check-circle-2" class="w-10 h-10 text-emerald-500 mx-auto opacity-80"></i>
                        <p class="font-bold text-sm text-slate-700">No missed contributions!</p>
                        <p class="text-xs text-slate-500">You're completely up to date with your savings goal!</p>
                    </div>`;
                return;
            }

            let html = `
                <div class="overflow-x-auto custom-scrollbar">
                    <table class="w-full text-left border-collapse text-xs">
                        <thead>
                            <tr class="bg-emerald-800 text-white border-b border-emerald-900 font-bold uppercase tracking-wider">
                                <th class="sticky left-0 z-20 bg-emerald-800 p-3 text-center min-w-[140px] border-r border-emerald-700 shadow-md">
                                    Contributor
                                </th>`;

            filteredIndices.forEach((dIndex) => {
                const dateStr = appData.dates[dIndex];
                const isToday = isTodayDate(dateStr);
                const isPast = isPastDate(dateStr);

                let headerBg = 'bg-emerald-800 text-white border-emerald-700';
                let todayIndicator = '';

                if (isToday) {
                    headerBg = 'bg-amber-500 text-white border-amber-600';
                    todayIndicator = `<span class="block text-2xs uppercase tracking-wider text-amber-100 font-bold">Today</span>`;
                }

                html += `
                    <th id="date-col-${dIndex}" class="p-3 text-center border-r ${headerBg} whitespace-nowrap">
                        <div class="font-bold text-xs whitespace-nowrap">${dateStr}</div>
                        ${todayIndicator}
                    </th>`;
            });

            html += `</tr></thead><tbody class="divide-y divide-slate-200">`;

            appData.people.forEach((person, pIndex) => {
                html += `
                    <tr class="hover:bg-slate-50/80 transition">
                        <th class="sticky left-0 z-10 bg-slate-50 p-3 font-extrabold text-slate-800 text-center border-r border-slate-200 shadow-xs min-w-[140px]">
                            <div class="text-sm">${person}</div>
                        </th>`;

                filteredIndices.forEach((dIndex) => {
                    const dateStr = appData.dates[dIndex];
                    const isToday = isTodayDate(dateStr);
                    const tempTd = createCellTd(pIndex, dIndex, isToday);
                    html += tempTd.outerHTML;
                });

                html += `</tr>`;
            });

            html += `</tbody></table></div>`;
            container.innerHTML = html;
        }

        function renderSummaryCards() {
            const container = document.getElementById('summaryCardsContainer');
            const stats = calculateStreaksAndStats();

            let jointSavings = 0;
            stats.forEach(s => jointSavings += s.totalSaved);

            const interestRate = appData.interestRate || 3;
            const projectedInterest = jointSavings * (interestRate / 100);
            const totalFutureValue = jointSavings + projectedInterest;

            const personThemes = [
                { dot: 'bg-sky-500', badgeBg: 'bg-sky-50', badgeBorder: 'border-sky-200', badgeText: 'text-sky-700' },
                { dot: 'bg-rose-500', badgeBg: 'bg-rose-50', badgeBorder: 'border-rose-200', badgeText: 'text-rose-700' },
                { dot: 'bg-purple-500', badgeBg: 'bg-purple-50', badgeBorder: 'border-purple-200', badgeText: 'text-purple-700' },
                { dot: 'bg-amber-500', badgeBg: 'bg-amber-50', badgeBorder: 'border-amber-200', badgeText: 'text-amber-700' }
            ];

            let html = '';

            // Individual Progress Cards (e.g., Matt's Progress, Tif's Progress)
            stats.forEach((s, pIndex) => {
                const theme = personThemes[pIndex % personThemes.length];
                html += `
                    <div class="bg-white rounded-2xl p-5 border border-slate-200/80 shadow-xs flex flex-col justify-between space-y-4">
                        <!-- Card Header -->
                        <div class="flex items-center justify-between pb-3 border-b border-slate-100">
                            <div class="flex items-center gap-2 font-bold text-slate-900 text-base">
                                <span class="w-3 h-3 rounded-full ${theme.dot} shrink-0"></span>
                                <span>${escapeHtml(s.person)}'s Progress</span>
                            </div>
                            <div class="px-3 py-1 rounded-full border ${theme.badgeBg} ${theme.badgeBorder} ${theme.badgeText} text-xs font-semibold flex items-center gap-1 shadow-2xs">
                                <span>🔥</span> ${s.currentStreak} Day Streak
                            </div>
                        </div>

                        <!-- Card Stats Grid -->
                        <div class="grid grid-cols-2 gap-4 pt-1">
                            <div>
                                <div class="text-xs text-slate-400 font-medium">Total Checkmarks</div>
                                <div class="text-lg font-bold text-slate-900 mt-1">${s.totalChecked} ${s.totalChecked === 1 ? 'day' : 'days'}</div>
                            </div>
                            <div>
                                <div class="text-xs text-slate-400 font-medium">Money Saved</div>
                                <div class="text-lg font-extrabold text-emerald-600 mt-1">₱${s.totalSaved.toLocaleString()}</div>
                            </div>
                        </div>
                    </div>`;
            });

            // Joint Future Savings Card
            html += `
                <div class="bg-[#0f172a] text-slate-100 rounded-2xl p-5 shadow-lg border border-slate-800 flex flex-col justify-between space-y-4">
                    <!-- Header -->
                    <div class="flex items-center justify-between">
                        <div class="flex items-center gap-2 font-bold text-white text-base">
                            <i data-lucide="piggy-bank" class="w-5 h-5 text-amber-400"></i>
                            <span>Joint Future Savings</span>
                        </div>
                        <button onclick="changeInterest()" class="px-3 py-1 rounded-full border border-amber-500/40 bg-amber-500/10 hover:bg-amber-500/20 text-amber-400 text-xs font-semibold flex items-center gap-1.5 transition cursor-pointer" title="Edit interest rate">
                            +${interestRate}% Interest
                            <i data-lucide="pencil" class="w-3 h-3 text-amber-400"></i>
                        </button>
                    </div>

                    <!-- Breakdown Rows -->
                    <div class="space-y-2 pt-1">
                        <div class="flex items-center justify-between text-xs md:text-sm">
                            <span class="text-slate-300 font-medium">Base Savings:</span>
                            <span class="font-bold text-white">₱${jointSavings.toLocaleString()}</span>
                        </div>
                        <div class="flex items-center justify-between text-xs md:text-sm">
                            <span class="text-emerald-400 font-medium">Projected Interest (+${interestRate}%):</span>
                            <span class="font-bold text-emerald-400">₱${projectedInterest.toLocaleString(undefined, { minimumFractionDigits: 2, maximumFractionDigits: 2 })}</span>
                        </div>
                    </div>

                    <!-- Divider & Total -->
                    <div class="border-t border-slate-700/80 pt-3">
                        <div class="flex items-center justify-between">
                            <span class="font-extrabold text-amber-400 text-sm md:text-base">Total Future Value:</span>
                            <span class="font-black text-amber-400 text-lg md:text-xl">₱${totalFutureValue.toLocaleString(undefined, { minimumFractionDigits: 2, maximumFractionDigits: 2 })}</span>
                        </div>
                    </div>
                </div>`;

            container.innerHTML = html;
        }

        function renderAll(preserveScroll = false) {
            let windowScrollX = 0;
            let windowScrollY = 0;
            let tableScrollLeft = 0;
            let tableScrollTop = 0;

            const container = document.getElementById('tableContainer');
            const scrollableInner = container ? container.querySelector('.overflow-x-auto') : null;

            if (preserveScroll) {
                windowScrollX = window.scrollX || window.pageXOffset || 0;
                windowScrollY = window.scrollY || window.pageYOffset || 0;
                if (scrollableInner) {
                    tableScrollLeft = scrollableInner.scrollLeft;
                    tableScrollTop = scrollableInner.scrollTop;
                }
            }

            if (orientation === 'horizontal') {
                renderHorizontalTable();
            } else {
                renderVerticalTable();
            }

            renderSummaryCards();

            if (preserveScroll && container) {
                const newScrollableInner = container.querySelector('.overflow-x-auto');
                if (newScrollableInner) {
                    newScrollableInner.scrollLeft = tableScrollLeft;
                    newScrollableInner.scrollTop = tableScrollTop;
                }
                window.scrollTo(windowScrollX, windowScrollY);
            }

            if (window.lucide) {
                lucide.createIcons();
            }
        }

        function openModal(pIndex, dIndex) {
            currentModalTarget = { pIndex, dIndex };
            const cellId = getCellId(pIndex, dIndex);
            const cellData = appData.cells[cellId] || { notes: '' };

            const personName = appData.people[pIndex];
            const dateStr = appData.dates[dIndex];

            const modalSubtext = document.getElementById('modalSubtext');
            const modalNoteText = document.getElementById('modalNoteText');
            const noteModal = document.getElementById('noteModal');

            if (modalSubtext) modalSubtext.textContent = `${personName} - ${dateStr}`;
            if (modalNoteText) modalNoteText.value = cellData.notes || '';

            if (noteModal) noteModal.classList.remove('hidden');
        }
        window.openModal = openModal;

        function closeModal() {
            const noteModal = document.getElementById('noteModal');
            if (noteModal) noteModal.classList.add('hidden');
            currentModalTarget = null;
        }
        window.closeModal = closeModal;

        function saveModalNote() {
            if (!currentModalTarget) return;
            const { pIndex, dIndex } = currentModalTarget;
            const cellId = getCellId(pIndex, dIndex);
            const noteText = document.getElementById('modalNoteText').value.trim();

            if (!appData.cells[cellId]) {
                appData.cells[cellId] = { status: '', notes: '', timestamp: '' };
            }
            appData.cells[cellId].notes = noteText;

            saveLocalData();
            saveToCloud();
            renderAll(true);
            closeModal();
            showToast("Note saved!");
        }
        window.saveModalNote = saveModalNote;

        function deleteModalNote() {
            if (!currentModalTarget) return;
            const { pIndex, dIndex } = currentModalTarget;
            const cellId = getCellId(pIndex, dIndex);

            if (appData.cells[cellId]) {
                appData.cells[cellId].notes = '';
            }

            saveLocalData();
            saveToCloud();
            renderAll(true);
            closeModal();
            showToast("Note deleted");
        }
        window.deleteModalNote = deleteModalNote;

        function openSyncModal() {
            const syncModal = document.getElementById('syncModal');
            const roomInput = document.getElementById('syncRoomInput');
            if (roomInput) roomInput.value = currentRoomId;
            if (syncModal) syncModal.classList.remove('hidden');
        }
        window.openSyncModal = openSyncModal;

        function closeSyncModal() {
            const syncModal = document.getElementById('syncModal');
            if (syncModal) syncModal.classList.add('hidden');
        }
        window.closeSyncModal = closeSyncModal;

        function copySyncCode() {
            const roomInput = document.getElementById('syncRoomInput');
            if (roomInput && roomInput.value) {
                const text = roomInput.value.trim();
                if (navigator.clipboard && navigator.clipboard.writeText) {
                    navigator.clipboard.writeText(text);
                } else {
                    document.execCommand('copy');
                }
                showToast("Room code copied!");
            }
        }
        window.copySyncCode = copySyncCode;

        function saveSyncRoom() {
            const roomInput = document.getElementById('syncRoomInput');
            if (!roomInput) return;
            const newRoom = roomInput.value.trim();
            if (!newRoom) {
                showToast("Please enter a room code", 'error');
                return;
            }

            currentRoomId = newRoom;
            localStorage.setItem('savings_tracker_room_id', currentRoomId);

            const displaySyncRoom = document.getElementById('displaySyncRoom');
            if (displaySyncRoom) displaySyncRoom.textContent = currentRoomId;

            closeSyncModal();
            initCloudSync();
            showToast(`Connected to Room: ${currentRoomId}`);
        }
        window.saveSyncRoom = saveSyncRoom;

        function toggleFirebaseConfigSection() {
            const section = document.getElementById('firebaseConfigSection');
            const chevron = document.getElementById('fbConfigChevron');
            if (!section) return;

            if (section.classList.contains('hidden')) {
                section.classList.remove('hidden');
                if (chevron) chevron.classList.add('rotate-180');
            } else {
                section.classList.add('hidden');
                if (chevron) chevron.classList.remove('rotate-180');
            }
        }
        window.toggleFirebaseConfigSection = toggleFirebaseConfigSection;

        function saveCustomFirebaseConfig() {
            const input = document.getElementById('firebaseConfigInput');
            if (!input || !input.value.trim()) {
                showToast("Please paste valid JSON config", 'error');
                return;
            }

            try {
                const parsed = JSON.parse(input.value.trim());
                if (!parsed.apiKey) {
                    showToast("Config missing apiKey", 'error');
                    return;
                }
                localStorage.setItem('savings_tracker_firebase_config', JSON.stringify(parsed));
                showToast("Firebase credentials saved!");
                initCloudSync();
            } catch (e) {
                showToast("Invalid JSON formatting", 'error');
            }
        }
        window.saveCustomFirebaseConfig = saveCustomFirebaseConfig;

        function clearFirebaseConfig() {
            localStorage.removeItem('savings_tracker_firebase_config');
            const input = document.getElementById('firebaseConfigInput');
            if (input) input.value = '';
            showToast("Saved credentials reset");
            initCloudSync();
        }
        window.clearFirebaseConfig = clearFirebaseConfig;

        let activeSettingsType = null;
        function changeRate() {
            activeSettingsType = 'rate';
            const modal = document.getElementById('editSettingsModal');
            const title = document.getElementById('settingsModalTitle');
            const label = document.getElementById('settingsModalLabel');
            const input = document.getElementById('settingsModalInput');

            if (title) title.innerHTML = `<i data-lucide="coins" class="w-5 h-5 text-emerald-600"></i> Change Daily Rate`;
            if (label) label.textContent = "Daily Savings Target (₱):";
            if (input) input.value = appData.dailyRate || 20;

            if (window.lucide) lucide.createIcons();
            if (modal) modal.classList.remove('hidden');
        }
        window.changeRate = changeRate;

        function changeInterest() {
            activeSettingsType = 'interest';
            const modal = document.getElementById('editSettingsModal');
            const title = document.getElementById('settingsModalTitle');
            const label = document.getElementById('settingsModalLabel');
            const input = document.getElementById('settingsModalInput');

            if (title) title.innerHTML = `<i data-lucide="trending-up" class="w-5 h-5 text-indigo-600"></i> Edit Annual Interest Rate`;
            if (label) label.textContent = "Annual Interest Rate (%):";
            if (input) input.value = appData.interestRate || 3;

            if (window.lucide) lucide.createIcons();
            if (modal) modal.classList.remove('hidden');
        }
        window.changeInterest = changeInterest;

        function closeSettingsModal() {
            const modal = document.getElementById('editSettingsModal');
            if (modal) modal.classList.add('hidden');
            activeSettingsType = null;
        }
        window.closeSettingsModal = closeSettingsModal;

        function saveSettingsModal() {
            const input = document.getElementById('settingsModalInput');
            if (!input) return;
            const val = parseFloat(input.value);

            if (isNaN(val) || val < 0) {
                showToast("Please enter a valid positive number", 'error');
                return;
            }

            if (activeSettingsType === 'rate') {
                appData.dailyRate = val;
                const display = document.getElementById('displayDailyRate');
                if (display) display.textContent = `₱${val}`;
                showToast(`Daily rate set to ₱${val}`);
            } else if (activeSettingsType === 'interest') {
                appData.interestRate = val;
                const display = document.getElementById('displayInterestRate');
                if (display) display.textContent = `${val}%`;
                showToast(`Interest rate set to ${val}%`);
            }

            saveLocalData();
            saveToCloud();
            renderAll();
            closeSettingsModal();
        }
        window.saveSettingsModal = saveSettingsModal;

        function toggleTheme() {
            document.body.classList.toggle('dark-theme');
            const isDark = document.body.classList.contains('dark-theme');
            localStorage.setItem('savings_tracker_theme', isDark ? 'dark' : 'light');

            const themeIcon = document.getElementById('themeIcon');
            if (themeIcon) {
                themeIcon.setAttribute('data-lucide', isDark ? 'sun' : 'moon');
                if (window.lucide) lucide.createIcons();
            }
        }
        window.toggleTheme = toggleTheme;

        function exportJSONBackup() {
            const dataStr = "data:text/json;charset=utf-8," + encodeURIComponent(JSON.stringify(appData, null, 2));
            const dlAnchor = document.createElement('a');
            dlAnchor.setAttribute("href", dataStr);
            dlAnchor.setAttribute("download", `for_us_savings_backup_${new Date().toISOString().slice(0,10)}.json`);
            document.body.appendChild(dlAnchor);
            dlAnchor.click();
            dlAnchor.remove();
            showToast("Backup downloaded!");
        }
        window.exportJSONBackup = exportJSONBackup;

        function importJSONBackup(event) {
            const file = event.target.files[0];
            if (!file) return;

            const reader = new FileReader();
            reader.onload = function(e) {
                try {
                    const imported = JSON.parse(e.target.result);
                    if (imported && imported.people && imported.dates) {
                        appData = imported;
                        window.appData = appData;
                        saveLocalData();
                        saveToCloud();
                        populateMonthSelectOptions();
                        renderAll();
                        showToast("Data restored successfully!");
                    } else {
                        showToast("Invalid backup file structure", 'error');
                    }
                } catch (err) {
                    showToast("Error parsing backup file", 'error');
                }
            };
            reader.readAsText(file);
        }
        window.importJSONBackup = importJSONBackup;

        function setFilter(filterType) {
            activeFilter = filterType;
            ['All', 'Month', 'Week', 'Missed'].forEach(type => {
                const btn = document.getElementById(`btnFilter${type}`);
                if (!btn) return;
                if (type.toLowerCase() === filterType) {
                    btn.className = "px-3 py-1 text-xs font-semibold rounded-md bg-white text-slate-800 shadow-xs";
                } else {
                    btn.className = "px-3 py-1 text-xs font-semibold rounded-md text-slate-600 hover:text-slate-900";
                }
            });
            renderAll();
        }
        window.setFilter = setFilter;

        function handleMonthFilterChange(val) {
            currentMonthFilter = val;
            renderAll();
        }
        window.handleMonthFilterChange = handleMonthFilterChange;

        function jumpToToday() {
            const todayIndex = appData.dates.findIndex(d => isTodayDate(d));
            if (todayIndex !== -1) {
                // Reset active month and quick filters so Today's date is guaranteed to be rendered
                currentMonthFilter = 'all';
                activeFilter = 'all';

                const monthSelect = document.getElementById('monthSelect');
                if (monthSelect) monthSelect.value = 'all';

                ['All', 'Month', 'Week', 'Missed'].forEach(type => {
                    const btn = document.getElementById(`btnFilter${type}`);
                    if (!btn) return;
                    if (type === 'All') {
                        btn.className = "px-3 py-1 text-xs font-semibold rounded-md bg-white text-slate-800 shadow-xs";
                    } else {
                        btn.className = "px-3 py-1 text-xs font-semibold rounded-md text-slate-600 hover:text-slate-900";
                    }
                });

                renderAll();
                setTimeout(() => {
                    let elem = null;
                    if (orientation === 'horizontal') {
                        elem = document.getElementById(`date-row-${todayIndex}`);
                    } else {
                        elem = document.getElementById(`date-col-${todayIndex}`);
                    }
                    if (elem) {
                        elem.scrollIntoView({ behavior: 'smooth', block: 'center', inline: 'center' });
                    }
                }, 100);
            } else {
                showToast("Today's date is not in list. Add it using + Add Day", 'error');
            }
        }
        window.jumpToToday = jumpToToday;

        function openAddDayModal() {
            const modal = document.getElementById('addDayModal');
            const input = document.getElementById('newDateInput');
            if (input) input.value = new Date().toISOString().slice(0, 10);
            if (modal) modal.classList.remove('hidden');
        }
        window.openAddDayModal = openAddDayModal;

        function closeAddDayModal() {
            const modal = document.getElementById('addDayModal');
            if (modal) modal.classList.add('hidden');
        }
        window.closeAddDayModal = closeAddDayModal;

        function saveNewDay() {
            const input = document.getElementById('newDateInput');
            if (!input || !input.value) return;

            const selected = new Date(input.value);
            const dateStr = selected.toLocaleDateString('en-US', { month: 'long', day: 'numeric', year: 'numeric' });

            if (appData.dates.includes(dateStr)) {
                showToast("Date already exists in list", 'error');
                return;
            }

            appData.dates.push(dateStr);
            appData.dates.sort((a, b) => new Date(a) - new Date(b));

            saveLocalData();
            saveToCloud();
            populateMonthSelectOptions();
            renderAll();
            closeAddDayModal();
            showToast(`Added ${dateStr}`);
        }
        window.saveNewDay = saveNewDay;

        function openAddMonthModal() {
            const modal = document.getElementById('addMonthModal');
            const input = document.getElementById('newMonthInput');
            if (input) {
                const now = new Date();
                input.value = `${now.getFullYear()}-${String(now.getMonth() + 1).padStart(2, '0')}`;
            }
            if (modal) modal.classList.remove('hidden');
        }
        window.openAddMonthModal = openAddMonthModal;

        function closeAddMonthModal() {
            const modal = document.getElementById('addMonthModal');
            if (modal) modal.classList.add('hidden');
        }
        window.closeAddMonthModal = closeAddMonthModal;

        function saveNewMonth() {
            const input = document.getElementById('newMonthInput');
            if (!input || !input.value) return;

            const [year, month] = input.value.split('-').map(Number);
            const daysInMonth = new Date(year, month, 0).getDate();

            let addedCount = 0;
            for (let day = 1; day <= daysInMonth; day++) {
                const d = new Date(year, month - 1, day);
                const dateStr = d.toLocaleDateString('en-US', { month: 'long', day: 'numeric', year: 'numeric' });

                if (!appData.dates.includes(dateStr)) {
                    appData.dates.push(dateStr);
                    addedCount++;
                }
            }

            appData.dates.sort((a, b) => new Date(a) - new Date(b));

            saveLocalData();
            saveToCloud();
            populateMonthSelectOptions();
            renderAll();
            closeAddMonthModal();
            showToast(`Generated ${addedCount} new dates`);
        }
        window.saveNewMonth = saveNewMonth;

        function toggleOrientation() {
            orientation = orientation === 'horizontal' ? 'vertical' : 'horizontal';
            localStorage.setItem('savings_tracker_orientation', orientation);
            renderAll();
        }
        window.toggleOrientation = toggleOrientation;

        window.addEventListener('DOMContentLoaded', () => {
            const savedTheme = localStorage.getItem('savings_tracker_theme');
            if (savedTheme === 'dark') {
                document.body.classList.add('dark-theme');
                const themeIcon = document.getElementById('themeIcon');
                if (themeIcon) themeIcon.setAttribute('data-lucide', 'sun');
            }

            loadLocalData();

            const rateDisplay = document.getElementById('displayDailyRate');
            if (rateDisplay) rateDisplay.textContent = `₱${appData.dailyRate || 20}`;

            const intDisplay = document.getElementById('displayInterestRate');
            if (intDisplay) intDisplay.textContent = `${appData.interestRate || 3}%`;

            initCloudSync();
        });
    </script>
</body>
</html>
