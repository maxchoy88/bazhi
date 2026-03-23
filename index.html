<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>倪氏天纪紫微详批系统</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://unpkg.com/lucide@latest"></script>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Serif+SC:wght@400;700;900&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Noto Serif SC', serif;
            background-color: #ece6d9;
        }
        .writing-vertical-lr {
            writing-mode: vertical-lr;
        }
        .custom-scrollbar::-webkit-scrollbar {
            width: 8px;
        }
        .custom-scrollbar::-webkit-scrollbar-thumb {
            background: #cbd5e1;
            border-radius: 20px;
        }
        
        /* 打印专用样式 */
        @media print {
            .no-print { display: none !important; }
            body { background: white !important; margin: 0; padding: 0; }
            .print-only { display: block !important; }
            .print-container { padding: 40px !important; background: white !important; min-height: 100vh; }
            .page-break { page-break-after: always; }
        }
        
        .print-only { display: none; }
        
        .palace-card:hover {
            transform: translateY(-4px);
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1);
        }
        .loader {
            border-top-color: #7f1d1d;
            animation: spinner 0.6s linear infinite;
        }
        @keyframes spinner {
            to { transform: rotate(360deg); }
        }
    </style>
</head>
<body class="p-2 md:p-6 text-slate-900">

    <!-- 网页显示区域 -->
    <div class="max-w-7xl mx-auto space-y-4 no-print">
        <!-- Header -->
        <header class="bg-white border-b-[12px] border-red-950 rounded-3xl p-8 shadow-2xl flex flex-col md:flex-row justify-between items-center gap-6 relative overflow-hidden">
            <div class="absolute top-0 left-0 w-48 h-48 bg-red-900/5 rounded-full blur-[80px]"></div>
            <div class="flex items-center gap-8 z-10">
                <div class="bg-red-950 p-6 rounded-3xl text-white shadow-2xl ring-4 ring-red-50 relative group">
                    <i data-lucide="compass" class="w-10 h-10"></i>
                    <div class="absolute -top-2 -right-2 bg-amber-500 w-6 h-6 rounded-full flex items-center justify-center border-2 border-white shadow-lg animate-bounce">
                        <i data-lucide="zap" class="w-3 h-3 text-white"></i>
                    </div>
                </div>
                <div>
                    <h1 class="text-4xl md:text-5xl font-black tracking-tighter text-slate-900">倪氏天纪·紫微详批系统</h1>
                    <div class="flex items-center gap-4 text-red-900 font-black text-xs mt-3 uppercase tracking-[0.4em] bg-red-50/50 w-fit px-3 py-1 rounded-full">
                        <i data-lucide="award" class="w-3 h-3"></i> 职业级 · 庚申 乙酉 丙午 庚寅
                    </div>
                </div>
            </div>

            <div class="flex flex-col items-center gap-3 z-10">
                <button id="ai-btn" class="bg-red-800 text-white px-8 py-3 rounded-2xl text-sm font-black hover:bg-black transition-all shadow-xl flex items-center gap-3">
                    <i data-lucide="sparkles" class="w-4 h-4"></i>
                    倪师 AI 深度解盘 ✨
                </button>
            </div>
        </header>

        <div class="grid grid-cols-1 lg:grid-cols-12 gap-6">
            <!-- Sidebar -->
            <div class="lg:col-span-3 space-y-4">
                <section class="bg-white rounded-[2.5rem] p-8 shadow-xl border border-slate-200">
                    <h2 class="text-xs font-black mb-8 flex items-center gap-2 text-slate-500 uppercase tracking-widest border-b border-slate-50 pb-4">
                        <i data-lucide="calendar" class="w-4 h-4 text-red-900"></i> 生辰录入
                    </h2>
                    <div class="space-y-6">
                        <div class="space-y-5">
                            <div>
                                <label class="text-[11px] font-black text-slate-400 block mb-2 px-1">命主名讳</label>
                                <input type="text" id="input-name" value="阿盛" class="w-full bg-slate-50 border-2 border-slate-100 rounded-2xl px-5 py-4 text-sm focus:border-red-900 outline-none transition-all shadow-sm" />
                            </div>
                            <div class="grid grid-cols-2 gap-4">
                                <div>
                                    <label class="text-[11px] font-black text-slate-400 block mb-2 px-1">性别</label>
                                    <select id="input-gender" class="w-full bg-slate-50 border-2 border-slate-100 rounded-2xl px-4 py-4 text-sm font-bold">
                                        <option value="男">男</option>
                                        <option value="女">女</option>
                                    </select>
                                </div>
                                <div>
                                    <label class="text-[11px] font-black text-slate-400 block mb-2 px-1">生辰(支)</label>
                                    <select id="input-time" class="w-full bg-slate-50 border-2 border-slate-100 rounded-2xl px-4 py-4 text-sm font-bold">
                                        <option value="寅">寅时</option>
                                        <option value="子">子时</option>
                                        <option value="丑">丑时</option>
                                        <option value="卯">卯时</option>
                                        <option value="辰">辰时</option>
                                        <option value="巳">巳时</option>
                                        <option value="午">午时</option>
                                        <option value="未">未时</option>
                                        <option value="申">申时</option>
                                        <option value="酉">酉时</option>
                                        <option value="戌">戌时</option>
                                        <option value="亥">亥时</option>
                                    </select>
                                </div>
                            </div>
                            <div>
                                <label class="text-[11px] font-black text-slate-400 block mb-2 px-1">出生年月日 (农历)</label>
                                <div class="grid grid-cols-3 gap-3">
                                    <input type="number" id="input-year" value="1980" class="bg-slate-50 border-2 border-slate-100 rounded-2xl py-3 text-sm text-center font-bold" />
                                    <input type="number" id="input-month" value="9" class="bg-slate-50 border-2 border-slate-100 rounded-2xl py-3 text-sm text-center font-bold" />
                                    <input type="number" id="input-day" value="30" class="bg-slate-50 border-2 border-red-200 rounded-2xl py-3 text-sm text-center font-black text-red-900 shadow-inner" />
                                </div>
                            </div>
                        </div>
                    </div>
                </section>

                <section class="bg-red-950 rounded-[2.5rem] p-10 text-red-50 shadow-2xl relative overflow-hidden group">
                    <div class="absolute inset-0 bg-[url('https://www.transparenttextures.com/patterns/natural-paper.png')] opacity-20"></div>
                    <h2 class="text-xs font-black mb-6 flex items-center gap-2 text-red-400 uppercase tracking-[0.3em]">
                        <i data-lucide="shield" class="w-4 h-4"></i> 倪师秘要
                    </h2>
                    <div class="space-y-6 text-sm leading-relaxed italic opacity-80 border-l-2 border-red-900/50 pl-4 font-serif">
                        <p>“天纪看象，地纪看位，人纪看心。”</p>
                        <p>“善易者不占，懂得理即是懂得命。”</p>
                    </div>
                </section>
            </div>

            <!-- Main Content -->
            <div class="lg:col-span-9 space-y-4">
                <div class="bg-white rounded-[3rem] p-6 md:p-12 shadow-2xl border border-slate-200 relative overflow-hidden min-h-[800px]">
                    <div class="flex flex-col md:flex-row justify-between items-center mb-12 gap-8">
                        <div class="flex p-2 bg-slate-100 rounded-[2.5rem] shadow-inner ring-1 ring-slate-200">
                            <button onclick="switchTab('chart')" id="tab-chart" class="tab-btn px-12 py-3.5 rounded-[2rem] text-sm font-black transition-all bg-white text-red-950 shadow-2xl scale-105">乾坤布阵</button>
                            <button onclick="switchTab('analysis')" id="tab-analysis" class="tab-btn px-12 py-3.5 rounded-[2rem] text-sm font-black transition-all text-slate-400">三才详批</button>
                        </div>
                        <button onclick="prepareAndPrint()" class="bg-red-950 text-white px-12 py-4 rounded-2xl text-sm font-black hover:bg-black transition-all shadow-2xl flex items-center gap-4">
                            <i data-lucide="printer" class="w-5 h-5"></i> 导出馆藏级深入报告
                        </button>
                    </div>

                    <!-- Chart View -->
                    <div id="view-chart" class="block overflow-x-auto pb-6 custom-scrollbar">
                        <div id="palace-grid" class="min-w-[800px] grid grid-cols-4 grid-rows-4 gap-4 p-2 bg-slate-50/50 rounded-[3rem]">
                            <!-- Grid rendered by JS -->
                        </div>
                    </div>

                    <!-- Analysis View -->
                    <div id="view-analysis" class="hidden space-y-12 pr-4 max-h-[800px] overflow-y-auto custom-scrollbar font-serif">
                        <div id="ai-response-container" class="hidden bg-amber-50 p-8 rounded-[3rem] border-2 border-amber-200 shadow-xl relative">
                            <div class="flex justify-between items-start mb-6">
                                <div class="flex items-center gap-3">
                                    <i data-lucide="sparkles" class="w-6 h-6 text-amber-600"></i>
                                    <h4 class="text-2xl font-black text-amber-900">倪师 AI 深度解盘 ✨</h4>
                                </div>
                                <button id="tts-btn" class="bg-amber-600 text-white p-3 rounded-full hover:bg-amber-700 shadow-lg">
                                    <i data-lucide="volume-2" class="w-5 h-5"></i>
                                </button>
                            </div>
                            <p id="ai-text" class="text-xl text-amber-950 leading-[2.6] whitespace-pre-wrap pl-6 border-l-4 border-amber-200"></p>
                        </div>
                        <div id="static-analysis" class="grid grid-cols-1 md:grid-cols-2 gap-12 text-lg">
                            <!-- Populated by JS -->
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- 打印专用区域 (平时隐藏) -->
    <div id="print-report" class="print-only print-container font-serif">
        <div class="max-w-4xl mx-auto space-y-12">
            <!-- 封面页/标题 -->
            <div class="text-center border-b-[16px] border-double border-red-950 pb-16">
                <div class="mb-10 flex justify-center">
                    <div class="w-24 h-24 border-4 border-red-900 rounded-2xl flex items-center justify-center p-4 rotate-45">
                       <i data-lucide="compass" class="w-16 h-16 text-red-950 -rotate-45"></i>
                    </div>
                </div>
                <h1 class="text-6xl font-black text-slate-900 mb-6">倪氏三才深入详批报告</h1>
                <p class="text-xl tracking-[0.5em] text-red-900 uppercase opacity-60">Heaven & Earth Analytics Master Edition</p>
                <div id="print-user-info" class="mt-16 text-xl border-y-2 border-slate-100 py-6 grid grid-cols-2 gap-8 font-black text-slate-500">
                    <!-- JS fills this -->
                </div>
            </div>

            <!-- 命盘大图打印版 -->
            <div class="space-y-6 page-break">
                <h2 class="text-3xl font-black border-l-8 border-red-900 pl-6 mb-10">乾坤命造布阵图</h2>
                <div id="print-grid" class="grid grid-cols-4 grid-rows-4 gap-2 border-2 border-slate-200 p-2 rounded-2xl scale-[0.85] origin-top">
                    <!-- JS clones current grid here -->
                </div>
            </div>

            <!-- 详细解析打印版 -->
            <div class="space-y-16">
                <section>
                    <h2 class="text-3xl font-black border-l-8 border-red-900 pl-6 mb-8">天纪与地纪详断</h2>
                    <div id="print-static-analysis" class="space-y-10 text-xl leading-[2.2] text-slate-800">
                        <!-- JS fills this -->
                    </div>
                </section>

                <section id="print-ai-section" class="hidden">
                    <h2 class="text-3xl font-black border-l-8 border-amber-600 pl-6 mb-8 text-amber-900">倪师 AI 深度解盘</h2>
                    <div id="print-ai-text" class="text-xl leading-[2.4] text-amber-900 bg-amber-50 p-10 rounded-3xl border-2 border-amber-100 whitespace-pre-wrap">
                        <!-- JS fills this -->
                    </div>
                </section>
            </div>

            <!-- 结语 -->
            <div class="mt-40 pt-20 border-t-4 border-double border-slate-100 text-center text-slate-300">
                <p class="text-3xl italic mb-12 text-slate-400">“心医胜过中医，位正方能命顺。”</p>
                <p class="text-sm font-black tracking-[1.5em]">— 谨以本报告致敬一代宗师倪海厦 —</p>
            </div>
        </div>
    </div>

    <!-- Fullscreen Loader Overlay -->
    <div id="global-loader" class="hidden fixed inset-0 bg-slate-900/60 backdrop-blur-md z-[100] flex items-center justify-center">
        <div class="bg-white p-10 rounded-[3rem] shadow-2xl flex flex-col items-center">
            <div class="loader ease-linear rounded-full border-4 border-t-4 border-slate-200 h-16 w-16 mb-4"></div>
            <h2 class="text-xl font-black text-slate-800">倪师正在推演乾坤...</h2>
        </div>
    </div>

    <script>
        // --- Configuration ---
        const apiKey = "";
        const GEMINI_MODEL = "gemini-2.5-flash-preview-09-2025";
        const TTS_MODEL = "gemini-2.5-flash-preview-tts";

        // --- Data ---
        const EARTHLY_BRANCHES = ["子", "丑", "寅", "卯", "辰", "巳", "午", "未", "申", "酉", "戌", "亥"];
        const HEAVENLY_STEMS = ["甲", "乙", "丙", "丁", "戊", "己", "庚", "辛", "壬", "癸"];
        const PALACES_NAMES = ["命宫", "兄弟", "夫妻", "子女", "财帛", "疾厄", "迁移", "奴仆", "官禄", "田宅", "福德", "父母"];

        const getElementColor = (item) => {
            const wood = ["甲", "乙", "寅", "卯"];
            const fire = ["丙", "丁", "巳", "午"];
            const earth = ["戊", "己", "辰", "戌", "丑", "未"];
            const metal = ["庚", "辛", "申", "酉"];
            const water = ["壬", "癸", "亥", "子"];
            if (wood.includes(item)) return "text-emerald-700";
            if (fire.includes(item)) return "text-red-600";
            if (earth.includes(item)) return "text-amber-700";
            if (metal.includes(item)) return "text-yellow-600";
            if (water.includes(item)) return "text-blue-700";
            return "text-slate-500";
        };

        const getBrightness = (star, branch) => {
            const miao = ["子", "午", "寅", "申"];
            const xian = ["卯", "酉", "辰", "戌"];
            if (miao.includes(branch)) return "庙";
            if (xian.includes(branch)) return "陷";
            return "旺";
        };

        // --- State Management ---
        let state = {
            name: "阿盛",
            gender: "男",
            year: 1980,
            month: 9,
            day: 30,
            time: "寅",
            aiAnalysis: "",
            isLoading: false
        };

        // --- Core Logic ---
        function calculatePalaces() {
            const yearStemIndex = (state.year - 4) % 10;
            const yearStem = HEAVENLY_STEMS[yearStemIndex];
            const startStemIndex = (yearStemIndex % 5) * 2 + 2;
            const timeIndex = EARTHLY_BRANCHES.indexOf(state.time);
            
            const mingGongIndexFromYin = (state.month - 1 - timeIndex + 12) % 12; 
            const shenGongIndexFromYin = (state.month - 1 + timeIndex) % 12;

            let result = [];
            for (let i = 0; i < 12; i++) {
                const branchIdx = (i + 2) % 12;
                const branch = EARTHLY_BRANCHES[branchIdx];
                const stemIdx = (startStemIndex + i) % 10;
                const stem = HEAVENLY_STEMS[stemIdx];
                const nameIdx = (i - mingGongIndexFromYin + 12) % 12;
                const name = PALACES_NAMES[nameIdx];
                
                const majorStars = [];
                const minorStars = [];
                if (name === "命宫") {
                    majorStars.push({ name: "紫微", b: getBrightness("紫微", branch) });
                    majorStars.push({ name: "七杀", b: "旺" });
                    minorStars.push({ name: "左辅", lucky: true });
                }
                if (name === "官禄") {
                    majorStars.push({ name: "廉贞", b: "庙" });
                    minorStars.push({ name: "文昌", lucky: true });
                }
                if (name === "财帛") {
                    majorStars.push({ name: "武曲", b: "庙" });
                    minorStars.push({ name: "禄存", lucky: true });
                }
                if (name === "迁移") majorStars.push({ name: "天府", b: "庙" });

                let siHua = "";
                if (yearStem === "庚") {
                    if (majorStars.some(s => s.name === "太阳")) siHua = "禄";
                    if (majorStars.some(s => s.name === "武曲")) siHua = "权";
                    if (majorStars.some(s => s.name === "太阴")) siHua = "科";
                    if (majorStars.some(s => s.name === "天同")) siHua = "忌";
                }

                result.push({
                    branch, stem, name, majorStars, minorStars, siHua,
                    isMingGong: name === "命宫",
                    isShenGong: i === shenGongIndexFromYin,
                    daYun: `${i * 10 + 5} - ${i * 10 + 14}`
                });
            }
            return result;
        }

        // --- Render UI ---
        function renderChart() {
            const palaces = calculatePalaces();
            const grid = document.getElementById('palace-grid');
            grid.innerHTML = '';

            const order = [5, 6, 7, 8, 4, 'center', 9, 3, 'center', 10, 2, 1, 0, 11];
            
            order.forEach(idx => {
                if (idx === 'center') {
                    if (document.querySelectorAll('.center-block').length === 0) {
                        const center = document.createElement('div');
                        center.className = 'center-block col-span-2 row-span-2 bg-[#fdfaf2] border-8 border-double border-red-900/20 rounded-[4rem] flex flex-col items-center justify-center p-8 relative shadow-2xl';
                        center.innerHTML = `
                            <div class="text-center z-10 space-y-6">
                                <h3 class="text-7xl font-black text-slate-900 mb-2 tracking-tighter">紫微</h3>
                                <div class="grid grid-cols-4 gap-4 px-4 py-4 bg-white/40 rounded-3xl border border-red-900/5">
                                    <div class="flex flex-col"><span class="text-[9px] text-slate-400 font-black">年</span><span class="text-xs font-black">庚申</span></div>
                                    <div class="flex flex-col"><span class="text-[9px] text-slate-400 font-black">月</span><span class="text-xs font-black">乙酉</span></div>
                                    <div class="flex flex-col"><span class="text-[9px] text-red-400 font-black">日</span><span class="text-xs font-black text-red-900">丙午</span></div>
                                    <div class="flex flex-col"><span class="text-[9px] text-slate-400 font-black">时</span><span class="text-xs font-black">${state.time}时</span></div>
                                </div>
                                <div class="flex justify-center gap-4">
                                    <span class="px-5 py-1 bg-red-900 text-white text-[10px] font-black rounded-full">木三局</span>
                                    <span class="px-5 py-1 bg-slate-800 text-white text-[10px] font-black rounded-full">庚午生人</span>
                                </div>
                            </div>
                        `;
                        grid.appendChild(center);
                    }
                    return;
                }

                const p = palaces[idx];
                const card = document.createElement('div');
                card.className = `palace-card relative border-[1.5px] p-2 h-40 md:h-48 flex flex-col justify-between transition-all duration-500 ${p.isMingGong ? 'bg-red-50/70 border-red-700 ring-2 ring-red-700/20' : 'bg-[#fffcf5] border-slate-300'}`;
                
                let starsHtml = '';
                p.majorStars.forEach(s => {
                    starsHtml += `<div class="flex flex-col items-center mb-1">
                        <span class="text-sm md:text-lg font-black text-red-900 writing-vertical-lr tracking-tighter leading-none">${s.name}</span>
                        <span class="text-[10px] font-bold text-amber-600 mt-0.5">${s.b || ''}</span>
                    </div>`;
                });

                let minorHtml = '';
                p.minorStars.forEach(s => {
                    minorHtml += `<span class="text-[10px] md:text-xs font-bold writing-vertical-lr leading-none ${s.lucky ? 'text-emerald-700' : 'text-slate-500'}">${s.name}</span>`;
                });

                card.innerHTML = `
                    <div class="flex justify-between items-start">
                        <div class="flex flex-col">
                            <div class="flex items-center gap-1">
                                <span class="text-[11px] font-black px-2 py-0.5 rounded-sm ${p.isMingGong ? 'bg-red-700 text-white' : 'bg-slate-800 text-white'}">${p.name}</span>
                                ${p.isShenGong ? '<span class="text-[9px] font-bold bg-amber-600 text-white px-1 rounded-sm">身宫</span>' : ''}
                            </div>
                            <span class="text-[9px] text-slate-400 mt-1 font-mono">${p.daYun} 岁</span>
                        </div>
                        <div class="text-right flex flex-col items-end">
                            <span class="text-[12px] font-black ${getElementColor(p.stem)}">${p.stem}</span>
                            <span class="text-xs font-black ${getElementColor(p.branch)}">${p.branch}</span>
                        </div>
                    </div>
                    <div class="flex flex-grow items-center justify-around px-1 gap-1">
                        <div class="flex flex-col items-center">${starsHtml}</div>
                        <div class="flex flex-col items-start gap-1">${minorHtml}</div>
                        ${p.siHua ? `<div class="self-center bg-red-800 text-white w-6 h-6 rounded-full flex items-center justify-center text-[10px] font-black shadow-lg border-2 border-white">${p.siHua}</div>` : ''}
                    </div>
                    <div class="absolute bottom-1 right-1 opacity-10 pointer-events-none"><i data-lucide="fingerprint" class="w-8 h-8"></i></div>
                `;
                grid.appendChild(card);
            });
            lucide.createIcons();
            updateStaticAnalysis();
        }

        function updateStaticAnalysis() {
            const container = document.getElementById('static-analysis');
            const analysisHtml = `
                <div class="bg-[#fffdf9] p-10 rounded-[3rem] border border-slate-100 shadow-xl">
                    <h4 class="text-2xl font-black text-red-950 mb-8 border-b-2 border-red-50 pb-5">天纪解析 · 先天之命</h4>
                    <p class="text-slate-700 leading-[2.4] font-serif">
                        阿盛，观您庚申年四柱：庚金带杀，丙火炼之。命宫见紫微七杀，此格谓之“杀破狼”与紫微化权之变局。
                        在倪师体系中，这种格局乃英雄开路之象。武曲化权入财帛，代表您对金钱掌控欲极强，具备从零开始积累财富的实干精神。
                    </p>
                </div>
                <div class="bg-[#fffdf9] p-10 rounded-[3rem] border border-slate-100 shadow-xl">
                    <h4 class="text-2xl font-black text-green-950 mb-8 border-b-2 border-green-50 pb-5">地纪建议 · 阳宅之位</h4>
                    <p class="text-slate-700 leading-[2.4] font-serif">
                        长男（庚申年生人）必占震位（东）与乾位（西北）。
                        倪师告诫：西北角决不可见火或厕所。若厨房在西北，主男主人易患头疾且财库虚耗。
                        针对您的丙午日燥火，建议家宅西南位保持开阔，利于纳凉水之气以中和命局。
                    </p>
                </div>
            `;
            container.innerHTML = analysisHtml;
            // 同步到打印区域
            document.getElementById('print-static-analysis').innerHTML = analysisHtml;
        }

        // --- Print Function ---
        function prepareAndPrint() {
            // 更新个人资料
            const info = document.getElementById('print-user-info');
            info.innerHTML = `
                <div class="flex justify-between"><span>姓名：${state.name}</span><span>性别：${state.gender}</span></div>
                <div class="flex justify-between"><span>四柱：庚申 乙酉 丙午 庚寅</span><span>五行局：木三局</span></div>
            `;
            
            // 克隆命盘
            const printGrid = document.getElementById('print-grid');
            printGrid.innerHTML = document.getElementById('palace-grid').innerHTML;
            
            // AI 内容处理
            const printAiSection = document.getElementById('print-ai-section');
            if (state.aiAnalysis) {
                printAiSection.classList.remove('hidden');
                document.getElementById('print-ai-text').textContent = state.aiAnalysis;
            } else {
                printAiSection.classList.add('hidden');
            }
            
            // 触发打印
            window.print();
        }

        // --- Navigation ---
        function switchTab(tab) {
            document.getElementById('view-chart').className = tab === 'chart' ? 'block overflow-x-auto pb-6 custom-scrollbar' : 'hidden';
            document.getElementById('view-analysis').className = tab === 'analysis' ? 'block space-y-12 pr-4 max-h-[800px] overflow-y-auto custom-scrollbar' : 'hidden';
            
            const commonClasses = "tab-btn px-12 py-3.5 rounded-[2rem] text-sm font-black transition-all";
            document.getElementById('tab-chart').className = `${commonClasses} ${tab === 'chart' ? 'bg-white text-red-950 shadow-2xl scale-105' : 'text-slate-400'}`;
            document.getElementById('tab-analysis').className = `${commonClasses} ${tab === 'analysis' ? 'bg-white text-red-950 shadow-2xl scale-105' : 'text-slate-400'}`;
        }

        // --- API Helpers ---
        async function callGemini(prompt, system) {
            const url = `https://generativelanguage.googleapis.com/v1beta/models/${GEMINI_MODEL}:generateContent?key=${apiKey}`;
            const payload = {
                contents: [{ parts: [{ text: prompt }] }],
                systemInstruction: { parts: [{ text: system }] }
            };
            
            for (let i = 0; i < 5; i++) {
                try {
                    const response = await fetch(url, { method: 'POST', body: JSON.stringify(payload), headers: { 'Content-Type': 'application/json' } });
                    const result = await response.json();
                    return result.candidates[0].content.parts[0].text;
                } catch (e) {
                    await new Promise(r => setTimeout(r, Math.pow(2, i) * 1000));
                }
            }
            throw new Error("推演失败");
        }

        // --- Actions ---
        document.getElementById('ai-btn').addEventListener('click', async () => {
            const loader = document.getElementById('global-loader');
            loader.classList.remove('hidden');
            
            const palaces = calculatePalaces();
            const context = `阿盛(Castor), 1980年庚申生人, 宫位数据:${JSON.stringify(palaces.map(p=>({name:p.name, stars:p.majorStars.map(s=>s.name)})))}`;
            const system = "你扮演倪海厦老师。风格：幽默、刚毅、重视地理。请生成一份不少于800字的深入三才报告（天、地、人）。";
            
            try {
                const res = await callGemini(`请根据这份数据做全方位命理诊断：${context}`, system);
                state.aiAnalysis = res;
                document.getElementById('ai-text').textContent = res;
                document.getElementById('ai-response-container').classList.remove('hidden');
                switchTab('analysis');
            } catch (e) {
                console.error(e);
            } finally {
                loader.classList.add('hidden');
            }
        });

        document.getElementById('tts-btn').addEventListener('click', async () => {
            if (!state.aiAnalysis) return;
            const btn = document.getElementById('tts-btn');
            btn.disabled = true;
            try {
                const url = `https://generativelanguage.googleapis.com/v1beta/models/${TTS_MODEL}:generateContent?key=${apiKey}`;
                const payload = {
                    contents: [{ parts: [{ text: `请诵读倪师断语：${state.aiAnalysis}` }] }],
                    generationConfig: {
                        responseModalities: ["AUDIO"],
                        speechConfig: { voiceConfig: { prebuiltVoiceConfig: { voiceName: "Charon" } } }
                    }
                };
                const resp = await fetch(url, { method: 'POST', body: JSON.stringify(payload), headers: { 'Content-Type': 'application/json' } });
                const data = await resp.json();
                const audioBase64 = data.candidates[0].content.parts[0].inlineData.data;
                
                const binary = atob(audioBase64);
                const bytes = new Int16Array(binary.length / 2);
                for (let i = 0; i < binary.length; i += 2) {
                    bytes[i / 2] = (binary.charCodeAt(i + 1) << 8) | binary.charCodeAt(i);
                }
                const wavBlob = pcmToWav(bytes, 24000);
                const audio = new Audio(URL.createObjectURL(wavBlob));
                audio.play();
            } catch (e) {
                console.error(e);
            } finally {
                btn.disabled = false;
            }
        });

        function pcmToWav(pcmData, sampleRate) {
            const buffer = new ArrayBuffer(44 + pcmData.length * 2);
            const view = new DataView(buffer);
            const writeString = (o, s) => { for (let i = 0; i < s.length; i++) view.setUint8(o + i, s.charCodeAt(i)); };
            writeString(0, 'RIFF');
            view.setUint32(4, 32 + pcmData.length * 2, true);
            writeString(8, 'WAVE');
            writeString(12, 'fmt ');
            view.setUint32(16, 16, true);
            view.setUint16(20, 1, true);
            view.setUint16(22, 1, true);
            view.setUint32(24, sampleRate, true);
            view.setUint32(28, sampleRate * 2, true);
            view.setUint16(32, 2, true);
            view.setUint16(34, 16, true);
            writeString(36, 'data');
            view.setUint32(40, pcmData.length * 2, true);
            for (let i = 0; i < pcmData.length; i++) view.setInt16(44 + i * 2, pcmData[i], true);
            return new Blob([view], { type: 'audio/wav' });
        }

        // Input Sync
        ['name', 'gender', 'year', 'month', 'day', 'time'].forEach(key => {
            const el = document.getElementById(`input-${key}`);
            el.addEventListener('change', (e) => {
                state[key] = e.target.value;
                renderChart();
            });
        });

        window.onload = () => {
            renderChart();
        };

    </script>
</body>
</html>
