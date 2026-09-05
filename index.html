<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1.0">
<title>ROGxSheet - Smart Sheet Pro</title>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">

<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:Inter,Arial,sans-serif}
html{scroll-behavior:smooth}
body{
    display:flex;flex-direction:column;min-height:100vh;color:#fff;overflow-x:hidden;
    background:radial-gradient(circle at 50% -15%,rgba(128,102,255,.16),transparent 38%),
                radial-gradient(circle at 10% 50%,rgba(0,200,255,.035),transparent 30%),
                #080b12
}

@property --angle{syntax:"<angle>";initial-value:0deg;inherits:false}

/* NAVBAR */
.navbar{
    width:100%;height:65px;position:sticky;top:0;z-index:100;
    display:flex;align-items:center;justify-content:space-between;
    padding:0 15px;background:rgba(8,11,18,.82);
    border-bottom:1px solid rgba(255,255,255,.06);
    backdrop-filter:blur(18px)
}
.nav-logo{font-size:18px;font-weight:800;letter-spacing:-.6px}
.nav-logo span{color:#8066ff}

.menu-btn{
    width:38px;height:38px;display:flex;align-items:center;justify-content:center;
    border-radius:50%;background:#111722;border:1px solid rgba(255,255,255,.08);
    color:#aab2c1;font-size:13px;cursor:pointer;transition:.25s
}
.menu-btn:hover{color:#fff;background:#171e2b;border-color:rgba(128,102,255,.5)}

/* SIDEBAR */
.overlay{
    position:fixed;inset:0;z-index:200;background:rgba(0,0,0,.62);
    opacity:0;visibility:hidden;transition:.3s
}
.overlay.active{opacity:1;visibility:visible}

.sidebar{
    position:fixed;top:0;right:0;width:280px;height:100vh;z-index:300;
    padding:22px 16px;background:#0c111a;
    border-left:1px solid rgba(255,255,255,.07);
    transform:translateX(100%);transition:.3s ease;overflow-y:auto
}
.sidebar.active{transform:translateX(0)}

.sidebar-head{
    display:flex;align-items:center;justify-content:space-between;
    margin-bottom:25px;padding:0 8px
}
.sidebar-logo{font-size:18px;font-weight:800}
.sidebar-logo span{color:#8066ff}

.close-btn{
    width:35px;height:35px;border-radius:50%;background:#141a26;color:#7d8798;
    border:0;cursor:pointer;display:flex;align-items:center;justify-content:center
}
.close-btn:hover{color:#fff;background:#1b2331}

.section-title{
    margin:20px 9px 8px;color:#505a6b;font-size:10px;font-weight:700;
    letter-spacing:1.5px;text-transform:uppercase
}

.nav-item{
    display:flex;align-items:center;gap:13px;padding:12px 13px;margin:3px 0;
    border-radius:10px;color:#7f899a;text-decoration:none;font-size:13px;transition:.2s
}
.nav-item i{width:18px;text-align:center}
.nav-item:hover{background:#151c29;color:#fff}
.nav-item.active{background:rgba(128,102,255,.12);color:#927fff}

.set-b-box{
    margin:15px 5px 0;padding:13px;border-radius:11px;background:#101620;
    border:1px solid rgba(255,255,255,.06)
}
.set-b-label{
    display:block;margin-bottom:8px;color:#727d8e;font-size:10px;font-weight:600
}
.set-b-input{
    width:100%;height:38px;padding:0 10px;outline:none;border-radius:8px;
    border:1px solid rgba(255,255,255,.07);background:#0b1018;color:#fff;font-size:11px
}
.set-b-input:focus{border-color:rgba(128,102,255,.5)}
.set-b-btn{
    width:100%;height:36px;margin-top:8px;border:0;border-radius:8px;
    background:#8066ff;color:#fff;font-size:10px;font-weight:700;cursor:pointer
}
.set-b-btn:hover{background:#927fff}

/* MAIN */
.container{
    flex:1;display:flex;flex-direction:column;width:100%;max-width:680px;
    margin:0 auto;padding:40px 10px 0
}

.notes-area{display:flex;flex-direction:column;gap:8px}

.paste-field{
    --angle:0deg;position:relative;width:100%;height:42px;display:flex;
    align-items:center;gap:7px;padding:4px 5px;border-radius:9px;border:1px solid transparent;
    background:linear-gradient(#0d131d,#0d131d) padding-box,
    conic-gradient(from var(--angle),#8b5cf6,#ec4899,#3b82f6,#06b6d4,#22c55e,#eab308,#f97316,#ef4444,#a855f7,#8b5cf6) border-box;
    animation:rainbowRotate 6s linear infinite;transition:.2s
}
.paste-field:focus-within{box-shadow:0 0 16px rgba(128,102,255,.10)}

.paste-input{
    flex:1;min-width:0;height:100%;border:0;outline:0;background:transparent;
    color:#fff;font-size:11px
}
.paste-input::placeholder{color:#596273;font-size:10px}

.paste-btn{
    width:62px;height:31px;flex-shrink:0;border:0;border-radius:7px;
    background:#141a26;color:#8b95a6;font-size:9px;font-weight:700;
    cursor:pointer;transition:.2s
}
.paste-btn:hover{background:#1b2331;color:#fff}

/* ACTIONS */
.actions{
    width:100%;display:grid;grid-template-columns:repeat(4,1fr);
    gap:7px;margin-top:13px
}
.action-btn{
    height:39px;border:0;border-radius:8px;font-size:9px;
    font-weight:700;cursor:pointer;transition:.2s
}
.action-btn i{margin-right:5px}

.action-save{background:#8066ff;color:#fff}
.action-save:hover{background:#927fff}

.action-check{background:#10b981;color:#fff}
.action-check:hover{background:#059669}

.action-delete{
    background:#17131a;color:#f87171;
    border:1px solid rgba(239,68,68,.15)
}
.action-delete:hover{background:rgba(239,68,68,.08)}

.action-copy{
    background:#141a26;color:#aab2c1;
    border:1px solid rgba(255,255,255,.06)
}
.action-copy:hover{color:#fff;background:#1a2230}

.status{
    min-height:15px;margin-top:8px;text-align:center;color:#596579;
    font-size:10px;font-weight:bold;transition:opacity .3s
}
.status.success{color:#4ade80}
.status.error{color:#f87171}
.status.loading{color:#60a5fa}

/* CHECK STATUS */
.check-status-bar{
    display:none;justify-content:space-around;align-items:center;padding:10px;
    margin-top:0;margin-bottom:8px;background:#0d131d;
    border:1px solid rgba(255,255,255,.05);border-radius:8px;
    font-size:11px;font-weight:700
}
.check-live{color:#4ade80}
.check-dead{color:#f87171}
.check-total{color:#94a3b8}

/* SAVED NOTES */
.saved-notes{
    width:100%;display:flex;flex-direction:column;gap:3px;
    margin-top:4px;margin-bottom:20px
}

.saved-row{
    --angle:0deg;position:relative;width:100%;height:38px;min-width:0;
    display:flex;align-items:center;gap:4px;padding:3px;border-radius:6px;
    overflow:hidden;border:1px solid transparent;
    background:linear-gradient(#0d131d,#0d131d) padding-box,
    conic-gradient(from var(--angle),#8b5cf6,#ec4899,#3b82f6,#06b6d4,#22c55e,#eab308,#f97316,#ef4444,#a855f7,#8b5cf6) border-box;
    cursor:pointer;transition:.2s
}
.saved-row:hover{box-shadow:0 0 18px rgba(128,102,255,.08)}

.saved-row.is-live{
    border-color:rgba(74,222,128,.5);
    background:linear-gradient(#08100b,#08100b) padding-box;
    box-shadow:0 0 10px rgba(74,222,128,.15);
    animation:none
}

.saved-row.is-dead{
    border-color:rgba(248,113,113,.5);
    background:linear-gradient(#1a0a0a,#1a0a0a) padding-box;
    box-shadow:0 0 10px rgba(248,113,113,.15);
    animation:none
}

.saved-number{
    width:20px;flex-shrink:0;text-align:center;color:#596579;
    font-size:9px;font-weight:700
}

.saved-data{
    flex:1;min-width:0;display:grid;
    grid-template-columns:1.2fr 1.2fr 1.5fr 1fr 1fr;gap:4px
}

.saved-cell{
    min-width:0;padding:6px 5px;border-radius:4px;background:#111722;
    color:#9da7b7;font-size:8px;text-align:left;white-space:nowrap;
    overflow:hidden;text-overflow:ellipsis
}
.saved-cell.bold-uid{color:#60a5fa;font-weight:bold}

/* POPUP */
.popup-overlay{
    position:fixed;inset:0;z-index:500;display:flex;align-items:center;
    justify-content:center;padding:15px;background:rgba(0,0,0,.68);
    opacity:0;visibility:hidden;transition:.25s
}
.popup-overlay.active{opacity:1;visibility:visible}

.popup{
    width:100%;max-width:390px;padding:18px;border-radius:14px;
    background:#0c111a;border:1px solid rgba(255,255,255,.07);
    box-shadow:0 25px 70px rgba(0,0,0,.5);
    transform:scale(.94);transition:.25s
}
.popup-overlay.active .popup{transform:scale(1)}

.popup-title{
    margin-bottom:13px;color:#fff;font-size:14px;font-weight:700;
    display:flex;justify-content:space-between
}
.popup-status{
    font-size:11px;padding:2px 8px;border-radius:4px;background:#111
}
.popup-fields{display:flex;flex-direction:column;gap:6px}

.popup-input-group{display:flex;gap:5px}

.popup-input{
    flex:1;height:37px;padding:0 10px;outline:none;border-radius:8px;
    border:1px solid rgba(255,255,255,.07);background:#111722;
    color:#fff;font-size:10px
}
.popup-input:focus{border-color:rgba(128,102,255,.5)}

.popup-copy-btn{
    width:37px;height:37px;border-radius:8px;
    border:1px solid rgba(255,255,255,.07);
    background:#111722;color:#8b95a6;cursor:pointer
}
.popup-copy-btn:hover{
    background:#8066ff;color:#fff;border-color:#8066ff
}

.popup-actions{
    display:grid;grid-template-columns:1fr 1fr;
    gap:7px;margin-top:12px
}
.popup-btn{
    height:37px;border:0;border-radius:8px;
    font-size:10px;font-weight:700;cursor:pointer
}
.popup-edit{background:#8066ff;color:#fff}
.popup-remove{
    background:rgba(239,68,68,.08);color:#f87171;
    border:1px solid rgba(239,68,68,.12)
}
.popup-close{
    width:100%;height:34px;margin-top:7px;border:0;border-radius:8px;
    background:#141a26;color:#7d8798;font-size:9px;cursor:pointer
}

/* FOOTER */
.footer{
    margin-top:auto;padding:30px 0 20px;
    border-top:1px solid rgba(255,255,255,.06);text-align:center
}
.footer-brand{margin-bottom:18px}
.footer-brand h3{font-size:17px;margin-bottom:6px}
.footer-brand h3 span{color:#8066ff}
.footer-brand p{color:#555f70;font-size:10px}

.socials{
    display:flex;justify-content:center;gap:8px;margin-bottom:20px
}
.social{
    width:36px;height:36px;display:flex;align-items:center;
    justify-content:center;border-radius:50%;background:#101620;
    border:1px solid rgba(255,255,255,.06);color:#707b8d;
    text-decoration:none;font-size:12px
}

.footer-links{
    display:flex;justify-content:center;gap:18px;margin-bottom:16px
}
.footer-links a{
    color:#596273;text-decoration:none;font-size:9px
}
.copyright{
    padding-top:15px;border-top:1px solid rgba(255,255,255,.045);
    color:#414a59;font-size:9px
}

@keyframes rainbowRotate{
    0%{--angle:0deg}
    100%{--angle:360deg}
}

/* MOBILE */
@media(max-width:550px){
    .actions{grid-template-columns:repeat(2,1fr)}
    .action-btn{height:35px}
    .container{max-width:100%;padding:32px 9px 0}
    .saved-row{height:36px;padding:2px;gap:3px;border-radius:6px}
    .saved-number{width:17px;font-size:8px}
    .saved-data{
        gap:3px;
        grid-template-columns:1fr 1fr 1.2fr 1fr 1fr
    }
    .saved-cell{
        padding:5px 4px;font-size:7px;border-radius:4px
    }
    .saved-notes{gap:2px;margin-top:6px}
}
</style>
</head>

<body>

<!-- NAVBAR -->
<nav class="navbar">
    <div class="nav-logo">ROGx<span>Sheet</span></div>
    <button class="menu-btn" onclick="openMenu()">
        <i class="fa-solid fa-bars"></i>
    </button>
</nav>

<!-- OVERLAY & SIDEBAR -->
<div class="overlay" id="overlay" onclick="closeMenu()"></div>

<aside class="sidebar" id="sidebar">

    <div class="sidebar-head">
        <div class="sidebar-logo">ROGx<span>Sheet</span></div>
        <button class="close-btn" onclick="closeMenu()">
            <i class="fa-solid fa-xmark"></i>
        </button>
    </div>

    <div class="section-title">Set Password & Info</div>

    <div class="set-b-box">
        <label class="set-b-label">
            <i class="fa-solid fa-key"></i> Default Password (Column B)
        </label>

        <input
            id="setBInput"
            class="set-b-input"
            type="text"
            placeholder="Leave empty if not needed"
        >

        <div style="font-size:8px;color:#596273;margin-top:5px;">
            Automatically fills Column B, including Cookie Paste mode.
        </div>

        <button class="set-b-btn" onclick="saveSetB()">
            <i class="fa-solid fa-floppy-disk"></i> Save Password
        </button>
    </div>

    <div class="section-title">Navigation</div>

    <a href="https://zurastore.my.id" class="nav-item">
        <i class="fa-solid fa-house"></i>
        <span>Home</span>
    </a>

    <a href="https://zurastore.my.id/donate.php" class="nav-item">
        <i class="fa-solid fa-hand-holding-dollar"></i>
        <span>Donate</span>
    </a>

    <a href="#" class="nav-item active">
        <i class="fa-solid fa-note-sticky"></i>
        <span>Smart Notes</span>
    </a>

</aside>

<!-- MAIN -->
<main class="container">

    <section class="notes-area">

        <!-- COLUMN A -->
        <div class="paste-field">
            <input
                id="inputA"
                class="paste-input"
                type="text"
                placeholder="1. URL / FB COOKIE / UID"
                onchange="autoFetchUID()"
            >

            <button class="paste-btn" onclick="pasteTo('inputA')">
                <i class="fa-solid fa-paste"></i> Paste
            </button>
        </div>

        <!-- COLUMN B -->
        <div class="paste-field">
            <input
                id="inputB"
                class="paste-input"
                type="text"
                placeholder="2. Password (Auto from Set B if empty)"
            >

            <button class="paste-btn" onclick="pasteTo('inputB')">
                <i class="fa-solid fa-paste"></i> Paste
            </button>
        </div>

        <!-- COLUMN C -->
        <div class="paste-field">
            <input
                id="inputC"
                class="paste-input"
                type="text"
                placeholder="3. COOKIE (Auto) / 2FA / Notes"
            >

            <button class="paste-btn" onclick="pasteTo('inputC')">
                <i class="fa-solid fa-paste"></i> Paste
            </button>
        </div>

        <!-- COLUMN D -->
        <div class="paste-field">
            <input
                id="inputD"
                class="paste-input"
                type="text"
                placeholder="4. Additional Info (Optional)"
            >

            <button class="paste-btn" onclick="pasteTo('inputD')">
                <i class="fa-solid fa-paste"></i> Paste
            </button>
        </div>

        <!-- COLUMN E -->
        <div class="paste-field">
            <input
                id="inputE"
                class="paste-input"
                type="text"
                placeholder="5. Column 5 (Optional)"
            >

            <button class="paste-btn" onclick="pasteTo('inputE')">
                <i class="fa-solid fa-paste"></i> Paste
            </button>
        </div>

    </section>

    <!-- ACTIONS -->
    <div class="actions">

        <button class="action-btn action-save" onclick="saveNotes()">
            <i class="fa-solid fa-floppy-disk"></i> Save
        </button>

        <button class="action-btn action-check" onclick="checkAllUID()">
            <i class="fa-solid fa-magnifying-glass-chart"></i> Check UID
        </button>

        <button class="action-btn action-copy" onclick="copyAll()">
            <i class="fa-solid fa-copy"></i> Copy All
        </button>

        <button class="action-btn action-delete" onclick="deleteAll()">
            <i class="fa-solid fa-trash"></i> Delete All
        </button>

    </div>

    <div id="status" class="status"></div>

    <!-- CHECK STATUS BAR -->
    <div id="checkStatusBar" class="check-status-bar">

        <span class="check-live">
            <i class="fa-solid fa-check-circle"></i>
            Live: <span id="countLive">0</span>
        </span>

        <span class="check-dead">
            <i class="fa-solid fa-times-circle"></i>
            Dead: <span id="countDead">0</span>
        </span>

        <span class="check-total">
            <i class="fa-solid fa-list"></i>
            Total: <span id="countTotal">0</span>
        </span>

    </div>

    <!-- SAVED NOTES -->
    <div id="savedNotes" class="saved-notes"></div>

    <!-- FOOTER -->
    <footer class="footer">

        <div class="footer-brand">
            <h3>ROGx<span>Sheet</span></h3>
            <p>Smart Notes Pro • Advanced FBP Tools</p>
        </div>

        <div class="copyright">
            © ROGxSheet • 2026
        </div>

    </footer>

</main>

<!-- POPUP EDIT -->
<div
    class="popup-overlay"
    id="popupOverlay"
    onclick="closePopupOutside(event)"
>

    <div class="popup">

        <div class="popup-title">
            Note Details
            <span id="popupStatusBadge" class="popup-status"></span>
        </div>

        <div class="popup-fields">

            <div class="popup-input-group">
                <input id="editA" class="popup-input" placeholder="A (UID)">
                <button
                    class="popup-copy-btn"
                    onclick="copySingle('editA')"
                    title="Copy"
                >
                    <i class="fa-regular fa-copy"></i>
                </button>
            </div>

            <div class="popup-input-group">
                <input id="editB" class="popup-input" placeholder="B (Password)">
                <button
                    class="popup-copy-btn"
                    onclick="copySingle('editB')"
                    title="Copy"
                >
                    <i class="fa-regular fa-copy"></i>
                </button>
            </div>

            <div class="popup-input-group">
                <input
                    id="editC"
                    class="popup-input"
                    placeholder="C (Cookie/Info)"
                >
                <button
                    class="popup-copy-btn"
                    onclick="copySingle('editC')"
                    title="Copy"
                >
                    <i class="fa-regular fa-copy"></i>
                </button>
            </div>

            <div class="popup-input-group">
                <input id="editD" class="popup-input" placeholder="D">
                <button
                    class="popup-copy-btn"
                    onclick="copySingle('editD')"
                    title="Copy"
                >
                    <i class="fa-regular fa-copy"></i>
                </button>
            </div>

            <div class="popup-input-group">
                <input id="editE" class="popup-input" placeholder="E">
                <button
                    class="popup-copy-btn"
                    onclick="copySingle('editE')"
                    title="Copy"
                >
                    <i class="fa-regular fa-copy"></i>
                </button>
            </div>

        </div>

        <div class="popup-actions">

            <button
                class="popup-btn popup-edit"
                onclick="updateNote()"
            >
                <i class="fa-solid fa-pen"></i> Save Edit
            </button>

            <button
                class="popup-btn popup-remove"
                onclick="deleteCurrentNote()"
            >
                <i class="fa-solid fa-trash"></i> Delete
            </button>

        </div>

        <button class="popup-close" onclick="closePopup()">
            Close
        </button>

    </div>

</div>

<script>

/* STATE & DOM */
const sidebar = document.getElementById("sidebar");
const overlay = document.getElementById("overlay");

let savedNotes = [];
let editingIndex = -1;

function openMenu(){
    sidebar.classList.add("active");
    overlay.classList.add("active");
}

function closeMenu(){
    sidebar.classList.remove("active");
    overlay.classList.remove("active");
}

document.addEventListener("keydown", e => {
    if(e.key === "Escape"){
        closeMenu();
        closePopup();
    }
});

/* STATUS */
function showStatus(message,type=""){
    const statusEl = document.getElementById("status");

    statusEl.innerHTML = message;
    statusEl.className = "status " + type;

    setTimeout(() => {
        statusEl.innerHTML = "";
        statusEl.className = "status";
    },3000);
}

/* UNIVERSAL PASTE */
async function pasteTo(id){

    let targetInput = document.getElementById(id);
    if(!targetInput) return;

    if(
        typeof window.AndroidJS !== "undefined" ||
        (window.parent && typeof window.parent.AndroidJS !== "undefined")
    ){

        try{

            let textDariHP =
                typeof window.AndroidJS !== "undefined"
                ? window.AndroidJS.getClipboardText()
                : window.parent.AndroidJS.getClipboardText();

            targetInput.value = textDariHP;

            showStatus(
                "<i class='fa-solid fa-check'></i> Pasted via ROGx App!",
                "success"
            );

            if(id === "inputA") autoFetchUID();

        }catch(e){

            showStatus(
                "Failed to access ROGx Bridge.",
                "error"
            );
        }

    }else{

        try{

            const text = await navigator.clipboard.readText();

            targetInput.value = text;

            showStatus(
                "Successfully pasted.",
                "success"
            );

            if(id === "inputA") autoFetchUID();

        }catch(e){

            showStatus(
                "Clipboard access blocked by browser.",
                "error"
            );
        }
    }
}

/* AUTO FETCH UID */
async function autoFetchUID(){

    const inputEl = document.getElementById("inputA");
    let val = inputEl.value.trim();

    if(!val) return;

    if(
        /^\d+$/.test(val) ||
        val.includes("c_user=") ||
        val.includes("xs=")
    ) return;

    let matchId = val.match(/id=(\d+)/);

    if(matchId){

        inputEl.value = matchId[1];

        showStatus(
            "<i class='fa-solid fa-check'></i> ID extracted automatically!",
            "success"
        );

        return;
    }

    showStatus(
        "<i class='fa-solid fa-spinner fa-spin'></i> Extracting UID...",
        "loading"
    );

    try{

        let cleanVal = val
            .replace(/\/+$/,'')
            .replace(
                /^(https?:\/\/)?(www\.|m\.|mobile\.|web\.|mbasic\.)?facebook\.com\//i,
                ''
            );

        const res = await fetch(
            `uid.php?username=${encodeURIComponent(cleanVal)}`
        );

        const data = await res.json();

        if(data.uid){

            inputEl.value = data.uid;

            showStatus(
                `<i class='fa-solid fa-check'></i> UID: ${data.uid}`,
                "success"
            );

        }else{

            showStatus(
                "Failed to extract UID from server.",
                "error"
            );
        }

    }catch(e){

        showStatus(
            "Failed to connect to UID.php.",
            "error"
        );
    }
}

function extractUIDFromCookie(str){

    if(!str) return null;

    let match = str.match(/c_user=(\d+)/);

    return match ? match[1] : null;
}

function ambilID(input){

    let match = input.match(/id=(\d+)/);

    return match ? match[1] : input;
}

/* SET DEFAULT PASSWORD */
function saveSetB(){

    const val =
        document.getElementById("setBInput").value.trim();

    localStorage.setItem("zuraSetB",val);

    showStatus(
        "Default Password for Column B saved.",
        "success"
    );
}

function loadSetB(){

    const val =
        localStorage.getItem("zuraSetB") || "";

    document.getElementById("setBInput").value = val;

    return val;
}

/* SAVE NOTES */
function saveNotes(){

    let rawA =
        document.getElementById("inputA").value.trim();

    let rawB =
        document.getElementById("inputB").value.trim();

    let rawC =
        document.getElementById("inputC").value.trim();

    let rawD =
        document.getElementById("inputD").value.trim();

    let rawE =
        document.getElementById("inputE").value.trim();

    if(!rawA && !rawB && !rawC){

        showStatus(
            "Please enter some data first!",
            "error"
        );

        return;
    }

    let finalA = "";
    let finalB = "";
    let finalC = "";
    let finalD = rawD;
    let finalE = rawE;

    let cookieUid =
        extractUIDFromCookie(rawA);

    let defaultPw = loadSetB();

    let emailToUse =
        rawB !== "" ? rawB : defaultPw;

    if(cookieUid){

        finalA = cookieUid;
        finalB = emailToUse;
        finalC = rawA;

        finalD = "";
        finalE = "";

        showStatus(
            "<i class='fa-solid fa-cookie'></i> Cookie detected & organized!",
            "success"
        );

    }else{

        finalA = ambilID(rawA);
        finalB = emailToUse;
        finalC = rawC;

        if(!finalA || !finalB || !finalC){

            showStatus(
                "Columns A, B and C are required!",
                "error"
            );

            return;
        }

        showStatus(
            "<i class='fa-solid fa-check'></i> Note saved!",
            "success"
        );
    }

    savedNotes.push({
        A:finalA,
        B:finalB,
        C:finalC,
        D:finalD,
        E:finalE,
        status:""
    });

    localStorage.setItem(
        "zuraStoreNotesPro",
        JSON.stringify(savedNotes)
    );

    document.getElementById("inputA").value = "";
    document.getElementById("inputB").value = "";
    document.getElementById("inputC").value = "";
    document.getElementById("inputD").value = "";
    document.getElementById("inputE").value = "";

    renderSavedNotes();
}

/* CHECK UID */
async function checkUIDReal(uid){

    let cleanUid = uid.replace(/\D/g,'');

    if(!cleanUid) cleanUid = uid;

    const url =
        `https://graph.facebook.com/${cleanUid}/picture?type=normal`;

    try{

        const res = await fetch(url,{
            method:"HEAD",
            redirect:"follow",
            cache:"no-store"
        });

        if(
            res.status === 400 ||
            (res.url && res.url.includes("static"))
        ){
            return false;
        }

        return true;

    }catch(e){

        return false;
    }
}

async function checkAllUID(){

    if(!savedNotes.length){

        showStatus(
            "No data available!",
            "error"
        );

        return;
    }

    document.getElementById(
        "checkStatusBar"
    ).style.display = "flex";

    showStatus(
        "<i class='fa-solid fa-spinner fa-spin'></i> Checking UIDs...",
        "loading"
    );

    let live = 0;
    let dead = 0;

    document.getElementById(
        "countTotal"
    ).innerText = savedNotes.length;

    for(let i=0;i<savedNotes.length;i++){

        const isLive =
            await checkUIDReal(savedNotes[i].A);

        if(isLive){

            savedNotes[i].status = "live";
            live++;

        }else{

            savedNotes[i].status = "dead";
            dead++;
        }

        document.getElementById(
            "countLive"
        ).innerText = live;

        document.getElementById(
            "countDead"
        ).innerText = dead;

        localStorage.setItem(
            "zuraStoreNotesPro",
            JSON.stringify(savedNotes)
        );

        renderSavedNotes();
    }

    showStatus(
        "<i class='fa-solid fa-check'></i> UID checking completed!",
        "success"
    );
}

/* LOAD NOTES */
function loadNotes(){

    loadSetB();

    const saved =
        localStorage.getItem("zuraStoreNotesPro");

    if(saved){

        try{

            savedNotes = JSON.parse(saved);

            if(
                savedNotes.length > 0 &&
                Array.isArray(savedNotes[0])
            ){

                savedNotes =
                    savedNotes.map(row => ({
                        A:row[0],
                        B:row[1],
                        C:row[2],
                        D:row[3],
                        E:row[4],
                        status:""
                    }));
            }

        }catch(e){

            savedNotes = [];
        }
    }

    renderSavedNotes();
}

/* RENDER NOTES */
function renderSavedNotes(){

    const container =
        document.getElementById("savedNotes");

    container.innerHTML = "";

    if(!savedNotes.length){

        document.getElementById(
            "checkStatusBar"
        ).style.display = "none";

        return;
    }

    savedNotes.forEach((row,index) => {

        const rowEl =
            document.createElement("div");

        rowEl.className = "saved-row";

        if(row.status === "live")
            rowEl.classList.add("is-live");

        if(row.status === "dead")
            rowEl.classList.add("is-dead");

        rowEl.innerHTML = `
            <div class="saved-number">${index + 1}</div>

            <div class="saved-data">

                <div class="saved-cell bold-uid">
                    ${row.A || "—"}
                </div>

                <div class="saved-cell">
                    ${row.B || "—"}
                </div>

                <div class="saved-cell">
                    ${row.C || "—"}
                </div>

                <div class="saved-cell">
                    ${row.D || "—"}
                </div>

                <div class="saved-cell">
                    ${row.E || "—"}
                </div>

            </div>
        `;

        rowEl.onclick =
            () => openEditPopup(index);

        container.appendChild(rowEl);
    });
}

/* DELETE ROW */
function deleteSavedRow(index){

    savedNotes.splice(index,1);

    localStorage.setItem(
        "zuraStoreNotesPro",
        JSON.stringify(savedNotes)
    );

    renderSavedNotes();
}

/* DELETE ALL */
function deleteAll(){

    if(!savedNotes.length) return;

    if(confirm("Delete ALL notes?")){

        savedNotes = [];

        localStorage.removeItem(
            "zuraStoreNotesPro"
        );

        renderSavedNotes();

        showStatus(
            "All notes cleared.",
            "success"
        );
    }
}

/* COPY ALL */
async function copyAll(){

    if(!savedNotes.length) return;

    const text =
        savedNotes
        .map(r =>
            `${r.A}\t${r.B}\t${r.C}\t${r.D}\t${r.E}`
        )
        .join("\n");

    try{

        await navigator.clipboard.writeText(text);

        showStatus(
            "<i class='fa-solid fa-copy'></i> Copied to Clipboard!",
            "success"
        );

    }catch(e){

        let temp =
            document.createElement("textarea");

        temp.value = text;

        document.body.appendChild(temp);

        temp.select();

        document.execCommand("copy");

        document.body.removeChild(temp);

        showStatus(
            "<i class='fa-solid fa-copy'></i> Copied!",
            "success"
        );
    }
}

/* POPUP EDIT */
function openEditPopup(index){

    editingIndex = index;

    const row =
        savedNotes[index];

    document.getElementById("editA").value =
        row.A || "";

    document.getElementById("editB").value =
        row.B || "";

    document.getElementById("editC").value =
        row.C || "";

    document.getElementById("editD").value =
        row.D || "";

    document.getElementById("editE").value =
        row.E || "";

    const badge =
        document.getElementById("popupStatusBadge");

    if(row.status === "live"){

        badge.innerHTML =
            '<i class="fa-solid fa-check"></i> LIVE';

        badge.style.color = "#4ade80";

    }else if(row.status === "dead"){

        badge.innerHTML =
            '<i class="fa-solid fa-xmark"></i> DEAD';

        badge.style.color = "#f87171";

    }else{

        badge.innerHTML = "Unchecked";
        badge.style.color = "#888";
    }

    document
        .getElementById("popupOverlay")
        .classList.add("active");
}

function closePopup(){

    document
        .getElementById("popupOverlay")
        .classList.remove("active");

    editingIndex = -1;
}

function closePopupOutside(e){

    if(e.target.id === "popupOverlay")
        closePopup();
}

/* COPY SINGLE */
function copySingle(inputId){

    const val =
        document.getElementById(inputId).value;

    navigator.clipboard
        .writeText(val)
        .then(() => {

            showStatus(
                "<i class='fa-solid fa-check'></i> Column copied!",
                "success"
            );

        })
        .catch(e => {

            let temp =
                document.createElement("textarea");

            temp.value = val;

            document.body.appendChild(temp);

            temp.select();

            document.execCommand("copy");

            document.body.removeChild(temp);

            showStatus(
                "<i class='fa-solid fa-check'></i> Copied!",
                "success"
            );
        });
}

/* UPDATE NOTE */
function updateNote(){

    if(editingIndex < 0) return;

    savedNotes[editingIndex].A =
        document.getElementById("editA").value.trim();

    savedNotes[editingIndex].B =
        document.getElementById("editB").value.trim();

    savedNotes[editingIndex].C =
        document.getElementById("editC").value.trim();

    savedNotes[editingIndex].D =
        document.getElementById("editD").value.trim();

    savedNotes[editingIndex].E =
        document.getElementById("editE").value.trim();

    localStorage.setItem(
        "zuraStoreNotesPro",
        JSON.stringify(savedNotes)
    );

    renderSavedNotes();

    closePopup();

    showStatus(
        "Note updated successfully.",
        "success"
    );
}

/* DELETE CURRENT NOTE */
function deleteCurrentNote(){

    if(editingIndex < 0) return;

    deleteSavedRow(editingIndex);

    closePopup();

    showStatus(
        "Note deleted.",
        "success"
    );
}

/* INIT */
loadNotes();

</script>

</body>
</html>
