<!DOCTYPE html>
<html lang="zh-Hant">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>🚀 玩具總動員探險隊 | 香港迪士尼親子之旅隨身 APP</title> 
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+TC:wght@400;500;700;900&family=Fredoka:wght@500;600;700&display=swap" rel="stylesheet">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['"Noto Sans TC"', 'sans-serif'],
                        en: ['"Fredoka"', 'sans-serif'],
                    },
                    colors: {
                        toystory: {
                            bg: '#E0F2FE', sky: '#38BDF8', dark: '#1D4ED8',
                            woody: '#F59E0B', woodyDark: '#B45309', buzz: '#84CC16',
                            purple: '#8B5CF6', red: '#EF4444', snow: '#FFFFFF'
                        }
                    },
                    animation: {
                        'spin-slow': 'spin 12s linear infinite',
                        'bounce-slow': 'bounce 3s infinite',
                    }
                }
            }
        }
    </script>
    <style>
        body { background-color: #E0F2FE; background-image: radial-gradient(#F0F9FF 1px, transparent 1px); background-size: 20px 20px; -webkit-tap-highlight-color: transparent; }
        .scrollbar-hide::-webkit-scrollbar { display: none; }
        .scrollbar-hide { -ms-overflow-style: none; scrollbar-width: none; }
        /* 嚴格的分頁隔離與動畫 */
        .page-view { display: none !important; animation: fadeIn 0.3s cubic-bezier(0.4, 0, 0.2, 1); }
        .page-view.active { display: block !important; }
        @keyframes fadeIn { from { opacity: 0; transform: translateY(10px); } to { opacity: 1; transform: translateY(0); } }
        /* 行程時間軸 */
        .timeline-line::before { content: ''; position: absolute; left: 21px; top: 28px; bottom: -20px; width: 4px; background: repeating-linear-gradient(to bottom, #84CC16, #84CC16 6px, #8B5CF6 6px, #8B5CF6 12px); z-index: 0; border-radius: 2px; opacity: 0.6; }
        .time-slot:last-child .timeline-line::before { display: none; }
        .checked-item { text-decoration: line-through; color: #9CA3AF; }
        /* Modal 動畫 */
        .modal-enter { animation: modalFadeIn 0.2s ease-out forwards; }
        @keyframes modalFadeIn { from { opacity: 0; transform: scale(0.95); } to { opacity: 1; transform: scale(1); } }
    </style>
</head>
<body class="text-gray-800 pb-24 font-sans antialiased relative">

    <header class="bg-gradient-to-b from-toystory-dark to-toystory-sky text-white pt-8 pb-12 px-6 rounded-b-[2.5rem] shadow-xl relative overflow-hidden border-b-8 border-toystory-woody">
        <div class="absolute top-4 right-4 opacity-20 text-7xl animate-bounce-slow"><i class="fas fa-rocket"></i></div>
        <div class="absolute bottom-2 left-6 opacity-20 text-6xl"><i class="fas fa-hat-cowboy"></i></div>
        <div class="relative z-10 text-center">
            <span class="inline-flex items-center gap-1.5 bg-toystory-buzz text-white rounded-full px-4 py-1.5 text-[11px] font-bold mb-3 tracking-wider shadow-md border-2 border-toystory-purple uppercase">
                <i class="fas fa-space-shuttle animate-pulse"></i> TOY SOLDIER MISSION
            </span>
            <h1 class="text-3xl font-black tracking-widest mb-1 drop-shadow-[0_2px_4px_rgba(0,0,0,0.3)]">香港迪士尼冒險隊</h1>
            <p class="text-sky-100 text-xs font-bold flex items-center justify-center gap-1 drop-shadow-md">
                <i class="fas fa-star text-toystory-woody animate-spin-slow"></i> 飛向宇宙，親子滿電大作戰！
            </p>
        </div>
    </header>

    <div class="max-w-md mx-auto px-4 -mt-6 relative z-20 pb-20">

        <!-- ==================== 1. 首頁視圖 (HOME) ==================== -->
        <div id="view-home" class="page-view active space-y-4">
            <!-- 快速狀態卡片 -->
            <div class="bg-white rounded-2xl shadow-md p-4 border-2 border-toystory-sky/30 flex justify-around text-center">
                <div><div class="text-[10px] text-gray-400 font-bold mb-1">冒險天數</div><div class="text-xl font-black text-toystory-dark font-en">4 <span class="text-xs font-normal text-gray-500">Days</span></div></div>
                <div class="border-r border-gray-100"></div>
                <div><div class="text-[10px] text-gray-400 font-bold mb-1">裝備打包</div><div id="home-pack-progress" class="text-xl font-black text-toystory-buzz font-en">0%</div></div>
                <div class="border-r border-gray-100"></div>
                <div><div class="text-[10px] text-gray-400 font-bold mb-1">目前花費</div><div id="home-budget-progress" class="text-xl font-black text-toystory-red font-en">NT$ 0</div></div>
            </div>

            <!-- 即時匯率換算器 -->
            <div class="bg-gradient-to-r from-blue-50 to-sky-50 rounded-2xl shadow-md p-4 border border-blue-100">
                <h3 class="text-xs font-bold text-toystory-dark mb-2.5 flex justify-between items-center">
                    <span><i class="fas fa-exchange-alt text-toystory-sky mr-1"></i> 即時港幣匯率換算</span>
                    <span id="rate-display" class="text-[10px] bg-white px-2 py-0.5 rounded text-gray-500 shadow-sm">載入中...</span>
                </h3>
                <div class="flex items-center gap-2">
                    <div class="relative flex-1">
                        <span class="absolute left-3 top-1/2 -translate-y-1/2 text-gray-400 font-en text-xs">HK$</span>
                        <input type="number" id="calc-hkd" placeholder="輸入港幣" oninput="calculateExchange()" class="w-full bg-white border border-gray-200 rounded-xl pl-9 pr-3 py-2 text-sm font-black focus:outline-none focus:border-toystory-sky transition-colors">
                    </div>
                    <i class="fas fa-arrow-right text-gray-300"></i>
                    <div class="relative flex-1">
                        <span class="absolute left-3 top-1/2 -translate-y-1/2 text-gray-400 font-en text-xs">NT$</span>
                        <input type="text" id="calc-twd" readonly placeholder="台幣" class="w-full bg-gray-100 border border-transparent rounded-xl pl-9 pr-3 py-2 text-sm font-black text-toystory-red focus:outline-none">
                    </div>
                </div>
            </div>

            <!-- 航班資訊 -->
            <div class="bg-white rounded-2xl p-4 shadow-md border-2 border-toystory-sky/20">
                <h3 class="text-xs font-bold text-toystory-dark tracking-wider mb-3"><i class="fas fa-plane text-toystory-red mr-1"></i> 國泰航空 航班資訊</h3>
                <div class="space-y-3">
                    <!-- 去程 -->
                    <div class="flex items-center justify-between bg-gray-50 p-3 rounded-xl border border-gray-100">
                        <div class="text-center w-14"><div class="text-[10px] text-gray-400 font-bold">6/17 去程</div><div class="font-en text-toystory-dark font-black">CX431</div></div>
                        <div class="flex-1 px-3 flex items-center justify-between">
                            <div class="text-center"><div class="text-lg font-black font-en leading-none">11:10</div><div class="text-[10px] font-bold text-gray-500 mt-1">KHH 高雄</div></div>
                            <div class="flex flex-col items-center px-2 text-gray-300 w-16">
                                <i class="fas fa-plane text-sm text-toystory-sky mb-0.5"></i>
                                <div class="h-0.5 w-full bg-gray-200 rounded"></div>
                                <div class="text-[9px] mt-1 text-gray-400 font-en">1h 30m</div>
                            </div>
                            <div class="text-center"><div class="text-lg font-black font-en leading-none">12:40</div><div class="text-[10px] font-bold text-gray-500 mt-1">HKG 香港</div></div>
                        </div>
                    </div>
                    <!-- 回程 -->
                    <div class="flex items-center justify-between bg-gray-50 p-3 rounded-xl border border-gray-100">
                        <div class="text-center w-14"><div class="text-[10px] text-gray-400 font-bold">6/19 回程</div><div class="font-en text-toystory-dark font-black">CX458</div></div>
                        <div class="flex-1 px-3 flex items-center justify-between">
                            <div class="text-center"><div class="text-lg font-black font-en leading-none">16:35</div><div class="text-[10px] font-bold text-gray-500 mt-1">HKG 香港</div></div>
                            <div class="flex flex-col items-center px-2 text-gray-300 w-16">
                                <i class="fas fa-plane text-sm text-toystory-buzz mb-0.5"></i>
                                <div class="h-0.5 w-full bg-gray-200 rounded"></div>
                                <div class="text-[9px] mt-1 text-gray-400 font-en">1h 30m</div>
                            </div>
                            <div class="text-center"><div class="text-lg font-black font-en leading-none">18:05</div><div class="text-[10px] font-bold text-gray-500 mt-1">KHH 高雄</div></div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- 住宿資訊 -->
            <div class="bg-white rounded-2xl p-4 shadow-md border-2 border-toystory-sky/20">
                <h3 class="text-xs font-bold text-toystory-dark tracking-wider mb-3"><i class="fas fa-hotel text-toystory-woody mr-1"></i> 住宿基地</h3>
                <div class="bg-amber-50/50 p-3 rounded-xl border border-amber-100 flex items-start gap-3">
                    <div class="w-12 h-12 bg-amber-200 rounded-lg flex items-center justify-center shrink-0 shadow-sm text-amber-700 text-xl"><i class="fas fa-campground"></i></div>
                    <div class="flex-1">
                        <h4 class="font-bold text-sm text-amber-900">迪士尼探索家度假酒店</h4>
                        <div class="text-[11px] text-amber-800/80 mt-1 space-y-1">
                            <p><i class="fas fa-phone-alt w-4 text-center"></i> +852 3510 2000</p>
                            <p class="leading-tight"><i class="fas fa-map-marker-alt w-4 text-center"></i> 香港大嶼山香港迪士尼樂園度假區</p>
                        </div>
                        <a href="https://www.google.com/maps/search/?api=1&query=迪士尼探索家度假酒店" target="_blank" class="mt-2 inline-flex items-center gap-1 bg-amber-500 hover:bg-amber-600 text-white text-[10px] font-bold px-3 py-1.5 rounded-full transition-colors shadow-sm">
                            <i class="fas fa-location-arrow"></i> 一鍵開啟導航
                        </a>
                    </div>
                </div>
            </div>

            <!-- 後勤備忘錄 -->
            <div class="bg-white rounded-2xl p-4 shadow-md border-2 border-toystory-sky/20">
                <h3 class="text-xs font-bold text-toystory-buzz tracking-wider mb-2.5 flex items-center gap-1.5">
                    <i class="fas fa-info-circle"></i> 太空港通訊指南
                </h3>
                <ul class="text-[11px] space-y-2 text-gray-600">
                    <li class="flex items-start gap-2"><i class="fas fa-check text-toystory-buzz mt-0.5"></i><span>簽證：電子簽證紙本列印，與護照放一起。</span></li>
                    <li class="flex items-start gap-2"><i class="fas fa-check text-toystory-buzz mt-0.5"></i><span>APP：提前下載迪士尼APP綁定門票。</span></li>
                    <li class="flex items-start gap-2"><i class="fas fa-check text-toystory-buzz mt-0.5"></i><span>交通：往返機場直接搭紅色計程車（約HK$150-180），育兒神隊友。</span></li>
                </ul>
            </div>
        </div>

        <!-- ==================== 2. 行程視圖 (ITINERARY) ==================== -->
        <div id="view-itinerary" class="page-view hidden space-y-4">
            <!-- 橫向滾動日期天數 -->
            <div class="flex gap-2 overflow-x-auto pb-1 scrollbar-hide sticky top-0 bg-[#E0F2FE] py-2 z-30">
                <button onclick="switchDay(0)" id="btn-day-0" class="day-btn shrink-0 px-4 py-2 rounded-full text-xs font-bold transition-all shadow-sm bg-toystory-sky text-white border-2 border-white/50">6/16 前夜</button>
                <button onclick="switchDay(1)" id="btn-day-1" class="day-btn shrink-0 px-4 py-2 rounded-full text-xs font-bold transition-all bg-white text-gray-500">6/17 D1</button>
                <button onclick="switchDay(2)" id="btn-day-2" class="day-btn shrink-0 px-4 py-2 rounded-full text-xs font-bold transition-all bg-white text-gray-500">6/18 D2</button>
                <button onclick="switchDay(3)" id="btn-day-3" class="day-btn shrink-0 px-4 py-2 rounded-full text-xs font-bold transition-all bg-white text-gray-500">6/19 D3</button>
            </div>

            <!-- 各日行程內容區 -->
            <div class="bg-white rounded-2xl shadow-md p-4 min-h-[400px] border-2 border-toystory-sky/20">
                
                <!-- Day 0 (6/16) -->
                <div id="day-content-0" class="day-content space-y-5">
                    <div class="border-b pb-3 mb-2">
                        <div class="flex justify-between items-center mb-2">
                            <div><span class="bg-blue-100 text-toystory-dark font-bold px-2 py-0.5 rounded text-[10px] mr-1.5 font-en">前哨站</span><span class="text-sm font-bold text-gray-700">高雄富野度假酒店</span></div>
                        </div>
                        <div id="weather-d0" class="bg-sky-50 rounded-lg p-2 flex items-center justify-between border border-sky-100">
                            <span class="text-xs font-bold text-sky-800"><i class="fas fa-map-marker-alt mr-1"></i>高雄即時天氣</span>
                            <span class="text-xs text-gray-600 font-en animate-pulse">抓取中...</span>
                        </div>
                    </div>
                    <div class="time-slot flex gap-3 relative timeline-line">
                        <div class="w-10 text-right shrink-0 font-en font-bold text-xs text-toystory-sky mt-1">17:52</div>
                        <div class="flex-1 bg-gray-50 p-3 rounded-xl border border-gray-100">
                            <h4 class="font-bold text-sm text-gray-800">搭乘台鐵自強號</h4>
                            <p class="text-[11px] text-gray-500 mt-1">車上提前幫小孩準備點心、手動繪本或拼圖打發時間。</p>
                        </div>
                    </div>
                    <div class="time-slot flex gap-3 relative timeline-line">
                        <div class="w-10 text-right shrink-0 font-en font-bold text-xs text-toystory-sky mt-1">20:10</div>
                        <div class="flex-1 bg-gray-50 p-3 rounded-xl border border-gray-100">
                            <h4 class="font-bold text-sm text-gray-800">高雄車站 ➔ 飯店</h4>
                            <p class="text-[11px] text-gray-500 mt-1">出站直接叫計程車一車直達，免轉乘捷運。</p>
                        </div>
                    </div>
                    <div class="time-slot flex gap-3 relative">
                        <div class="w-10 text-right shrink-0 font-en font-bold text-xs text-toystory-sky mt-1">21:00</div>
                        <div class="flex-1 bg-blue-50 p-3 rounded-xl border border-blue-100">
                            <h4 class="font-bold text-sm text-toystory-dark">洗澡睡覺 💤</h4>
                            <p class="text-[11px] text-blue-900/80 mt-1">讓全家小隊員睡飽充飽電，準備隔天登機！</p>
                        </div>
                    </div>
                </div>

                <!-- Day 1 (6/17) -->
                <div id="day-content-1" class="day-content hidden space-y-5">
                    <div class="border-b pb-3 mb-2">
                        <div class="flex justify-between items-center mb-2">
                            <div><span class="bg-rose-100 text-toystory-red font-bold px-2 py-0.5 rounded text-[10px] mr-1.5 font-en">大本營</span><span class="text-sm font-bold text-gray-700">迪士尼探索家度假酒店</span></div>
                        </div>
                        <div id="weather-d1" class="bg-amber-50 rounded-lg p-2 flex items-center justify-between border border-amber-100">
                            <span class="text-xs font-bold text-amber-800"><i class="fas fa-map-marker-alt mr-1"></i>香港即時天氣</span>
                            <span class="text-xs text-gray-600 font-en animate-pulse">抓取中...</span>
                        </div>
                    </div>
                    <div class="bg-white/60 p-2.5 rounded-xl border border-gray-200 text-[11px] text-gray-700 leading-tight mb-4 shadow-sm">
                        <strong>💡 今日核心概念：</strong> 下午進園體力有限，沿著樂園左側（探險世界 ➔ 迷離莊園 ➔ 反斗奇兵）順時針走一圈，此區設施溫和、不需買 DPA 也能輕鬆排到，最後回到中央看煙火，完全不走回頭路。
                    </div>
                    <div class="time-slot flex gap-3 relative timeline-line">
                        <div class="w-10 text-right shrink-0 font-en font-bold text-xs text-toystory-sky mt-1">11:10</div>
                        <div class="flex-1 bg-gray-50 p-3 rounded-xl border border-gray-100">
                            <h4 class="font-bold text-sm text-gray-800">國泰航空 ✈️ 飛往香港</h4>
                        </div>
                    </div>
                    <div class="time-slot flex gap-3 relative timeline-line">
                        <div class="w-10 text-right shrink-0 font-en font-bold text-xs text-toystory-sky mt-1">13:40</div>
                        <div class="flex-1 bg-gray-50 p-3 rounded-xl border border-gray-100">
                            <h4 class="font-bold text-sm text-gray-800">搭乘紅色大計程車</h4>
                            <p class="text-xs text-gray-500 mt-1">機場直達飯店寄放行李，輕裝出發！</p>
                        </div>
                    </div>
                    <div class="time-slot flex gap-3 relative timeline-line">
                        <div class="w-10 text-right shrink-0 font-en font-bold text-xs text-toystory-sky mt-1">15:30</div>
                        <div class="flex-1 bg-blue-50 p-3 rounded-xl border border-blue-100">
                            <h4 class="font-bold text-sm text-toystory-dark"><i class="fas fa-magic text-toystory-sky mr-1"></i> 大門入園與儀式感</h4>
                            <p class="text-[11px] text-blue-900/80 mt-1">一入園先去「美國小鎮大街」的市鎮會堂 (City Hall)，請工作人員幫兩位寶貝量身高（90cm）並索取「身高手環/貼紙」。接下來兩天只要秀出貼紙，設施門口就不用反覆重測。</p>
                        </div>
                    </div>
                    <div class="time-slot flex gap-3 relative timeline-line">
                        <div class="w-10 text-right shrink-0 font-en font-bold text-xs text-toystory-sky mt-1">16:00</div>
                        <div class="flex-1 bg-green-50 p-3 rounded-xl border border-green-100">
                            <h4 class="font-bold text-sm text-green-900"><i class="fas fa-leaf text-green-600 mr-1"></i> 探險世界 (暖身適應)</h4>
                            <p class="text-[11px] text-green-800/80 mt-1"><strong>森林河流之旅 [90cm+]：</strong> 坐大船看動物特效，微風吹拂，是最不費體力的開場。</p>
                        </div>
                    </div>
                    <div class="time-slot flex gap-3 relative timeline-line">
                        <div class="w-10 text-right shrink-0 font-en font-bold text-xs text-toystory-sky mt-1">16:40</div>
                        <div class="flex-1 bg-purple-50 p-3 rounded-xl border border-purple-100">
                            <h4 class="font-bold text-sm text-purple-900"><i class="fas fa-ghost text-purple-600 mr-1"></i> 迷離莊園 (視覺震撼)</h4>
                            <p class="text-[11px] text-purple-800/80 mt-1"><strong>迷離大宅 [90cm+]：</strong> 無軌電車體驗，進入冷氣房躲避下午的暑氣。</p>
                        </div>
                    </div>
                    <div class="time-slot flex gap-3 relative timeline-line">
                        <div class="w-10 text-right shrink-0 font-en font-bold text-xs text-toystory-sky mt-1">17:30</div>
                        <div class="flex-1 bg-orange-50 p-3 rounded-xl border border-orange-100">
                            <h4 class="font-bold text-sm text-orange-900"><i class="fas fa-horse text-orange-500 mr-1"></i> 反斗奇兵大本營 (夕陽美拍)</h4>
                            <p class="text-[11px] text-orange-800/80 mt-1">順著路走到此區，此時剛好傍晚不熱且準備點燈。玩第一次<strong>轉轉彈弓狗 [90cm+]</strong>，建立孩子對遊樂設施的熱愛，並與巨大的胡迪、翠絲公仔合照。</p>
                        </div>
                    </div>
                    <div class="time-slot flex gap-3 relative timeline-line">
                        <div class="w-10 text-right shrink-0 font-en font-bold text-xs text-toystory-sky mt-1">18:30</div>
                        <div class="flex-1 bg-gray-50 p-3 rounded-xl border border-gray-100">
                            <h4 class="font-bold text-sm text-gray-800"><i class="fas fa-utensils text-gray-500 mr-1"></i> 晚餐休息</h4>
                            <p class="text-[11px] text-gray-500 mt-1">慢慢散步回中央城堡廣場附近用餐。</p>
                        </div>
                    </div>
                    <div class="time-slot flex gap-3 relative">
                        <div class="w-10 text-right shrink-0 font-en font-bold text-xs text-toystory-sky mt-1">19:30</div>
                        <div class="flex-1 bg-indigo-50 p-3 rounded-xl border border-indigo-100">
                            <h4 class="font-bold text-sm text-indigo-900"><i class="fas fa-star text-yellow-500 mr-1"></i> 浪漫收尾</h4>
                            <p class="text-[11px] text-indigo-800/80 mt-1">城堡前準備觀賞《星夢光影之旅》煙火秀，看完直接搭接駁車回探索家酒店休息。</p>
                        </div>
                    </div>
                </div>

                <!-- Day 2 (6/18) -->
                <div id="day-content-2" class="day-content hidden space-y-5">
                    <div class="border-b pb-3 mb-2">
                        <div class="flex justify-between items-center mb-2">
                            <div><span class="bg-green-100 text-toystory-buzz font-bold px-2 py-0.5 rounded text-[10px] mr-1.5 font-en">主戰場</span><span class="text-sm font-bold text-gray-700">迪士尼樂園</span></div>
                        </div>
                        <div id="weather-d2" class="bg-amber-50 rounded-lg p-2 flex items-center justify-between border border-amber-100">
                            <span class="text-xs font-bold text-amber-800"><i class="fas fa-map-marker-alt mr-1"></i>香港即時天氣</span>
                            <span class="text-xs text-gray-600 font-en animate-pulse">抓取中...</span>
                        </div>
                    </div>
                    
                    <div class="bg-white/60 p-2.5 rounded-xl border border-gray-200 text-[11px] text-gray-700 leading-tight mb-4 shadow-sm">
                        <strong>💡 今日核心概念：</strong> 趁早上體力滿點，直衝樂園右後方「冰雪奇緣」與「幻想世界」，中午用冷氣設施(小小世界)收尾並回飯店午睡，下午再攻略右前方的「明日世界」，傍晚進入無限 Repeat 模式！
                    </div>

                    <div class="time-slot flex gap-3 relative timeline-line">
                        <div class="w-10 text-right shrink-0 font-en font-bold text-xs text-toystory-sky mt-1">10:00</div>
                        <div class="flex-1 bg-cyan-50 p-3 rounded-xl border border-cyan-100">
                            <h4 class="font-bold text-sm text-cyan-900"><i class="fas fa-snowflake text-cyan-500 mr-1"></i> 魔雪奇緣世界 (一級戰區)</h4>
                            <p class="text-[11px] text-cyan-800/80 mt-1">入園直接往右後方走。<strong>魔雪奇幻之旅 [90cm+]</strong>（視當天APP人潮決定是否買單項DPA）。</p>
                        </div>
                    </div>
                    <div class="time-slot flex gap-3 relative timeline-line">
                        <div class="w-10 text-right shrink-0 font-en font-bold text-xs text-toystory-sky mt-1">11:00</div>
                        <div class="flex-1 bg-pink-50 p-3 rounded-xl border border-pink-100">
                            <h4 class="font-bold text-sm text-pink-900"><i class="fas fa-crown text-pink-500 mr-1"></i> 幻想世界 (幼童主戰場)</h4>
                            <ul class="text-[11px] text-pink-800/80 mt-1 space-y-1 list-disc pl-3">
                                <li><strong>小熊維尼歷險之旅 [90cm+]：</strong> 強烈建議使用DPA，節省體力。</li>
                                <li><strong>小飛象 / 灰姑娘木馬 [90cm+]：</strong> 讓小孩自己決定要飛上天還是騎馬。</li>
                            </ul>
                        </div>
                    </div>
                    <div class="time-slot flex gap-3 relative timeline-line">
                        <div class="w-10 text-right shrink-0 font-en font-bold text-xs text-toystory-sky mt-1">12:30</div>
                        <div class="flex-1 bg-blue-50 p-3 rounded-xl border border-blue-100">
                            <h4 class="font-bold text-sm text-toystory-dark"><i class="fas fa-music text-blue-500 mr-1"></i> 午睡前的催眠曲</h4>
                            <p class="text-[11px] text-blue-900/80 mt-1"><strong>小小世界 [90cm+]：</strong> 最重要的安排！在最熱的中午坐這趟約15分鐘的冷氣船，聽著輕柔音樂，孩子下來就準備揉眼睛了。</p>
                        </div>
                    </div>
                    <div class="time-slot flex gap-3 relative timeline-line">
                        <div class="w-10 text-right shrink-0 font-en font-bold text-xs text-toystory-sky mt-1">13:00</div>
                        <div class="flex-1 bg-gray-100 p-3 rounded-xl border border-gray-200">
                            <h4 class="font-bold text-sm text-gray-700"><i class="fas fa-bed text-gray-500 mr-1"></i> 戰術性撤退 (至15:30)</h4>
                            <p class="text-[11px] text-gray-500 mt-1">回探索家酒店午睡充電，避開最高溫。</p>
                        </div>
                    </div>
                    <div class="time-slot flex gap-3 relative timeline-line">
                        <div class="w-10 text-right shrink-0 font-en font-bold text-xs text-toystory-sky mt-1">16:00</div>
                        <div class="flex-1 bg-gray-50 p-3 rounded-xl border border-gray-200 shadow-sm border-l-4 border-l-gray-400">
                            <h4 class="font-bold text-sm text-gray-800"><i class="fas fa-rocket text-gray-600 mr-1"></i> 明日世界 (下午放電)</h4>
                            <p class="text-[11px] text-gray-600 mt-1 mb-1">回到園區，先走右前方的明日世界。</p>
                            <ul class="text-[11px] text-gray-600 space-y-1 list-disc pl-3">
                                <li><strong>蟻俠與黃蜂女 [90cm+]：</strong> 吹冷氣玩射擊遊戲。</li>
                                <li><strong>太空飛碟 [90cm+]：</strong> 剛好解鎖的高空旋轉設施，刺激好玩。</li>
                            </ul>
                        </div>
                    </div>
                    <div class="time-slot flex gap-3 relative timeline-line">
                        <div class="w-10 text-right shrink-0 font-en font-bold text-xs text-toystory-sky mt-1">17:30</div>
                        <div class="flex-1 bg-orange-50 p-3 rounded-xl border border-orange-100">
                            <h4 class="font-bold text-sm text-orange-900"><i class="fas fa-hamburger text-orange-500 mr-1"></i> 晚餐與 Encore 時間</h4>
                            <p class="text-[11px] text-orange-800/80 mt-1 mb-2">建議在「火箭餐廳」或「皇室宴會廳」用餐。如果孩子精神百倍，趁煙火前人潮往城堡聚集，反向去二刷<strong>彈弓狗</strong>或<strong>跳降傘</strong>。</p>
                        </div>
                    </div>
                    <div class="time-slot flex gap-3 relative">
                        <div class="w-10 text-right shrink-0 font-en font-bold text-xs text-toystory-sky mt-1">19:30</div>
                        <div class="flex-1 bg-indigo-50 p-3 rounded-xl border border-indigo-100">
                            <h4 class="font-bold text-sm text-indigo-900"><i class="fas fa-fireworks text-indigo-500 mr-1"></i> 煙火觀賞雙策略</h4>
                            <div class="text-[10px] text-indigo-800/80 mt-2 space-y-2">
                                <div class="bg-white/60 p-2 rounded border border-indigo-100">
                                    <strong class="text-indigo-900">🏆 策略 A (最推薦)：專屬觀賞區通行證</strong><br>
                                    提前在Klook購買(約HK$300/人，2.5歲免)。擁有城堡前專屬草地，不用提早擠，19:40 輕鬆入場坐下，視野完全不被前方擋住。
                                </div>
                                <div class="bg-white/60 p-2 rounded border border-indigo-100">
                                    <strong class="text-indigo-900">🍽️ 策略 B：預訂餐廳煙火套餐</strong><br>
                                    預訂廣場飯店或大街餐廳晚餐，優雅吃完在專屬觀賞區或露台觀賞，免推推車找位痛苦。
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Day 3 (6/19) -->
                <div id="day-content-3" class="day-content hidden space-y-5">
                    <div class="border-b pb-3 mb-2">
                        <div class="flex justify-between items-center mb-2">
                            <div><span class="bg-purple-100 text-toystory-purple font-bold px-2 py-0.5 rounded text-[10px] mr-1.5 font-en">D3</span><span class="text-sm font-bold text-gray-700">凱旋歸國</span></div>
                        </div>
                        <div id="weather-d3" class="bg-amber-50 rounded-lg p-2 flex items-center justify-between border border-amber-100">
                            <span class="text-xs font-bold text-amber-800"><i class="fas fa-map-marker-alt mr-1"></i>香港即時天氣</span>
                            <span class="text-xs text-gray-600 font-en animate-pulse">抓取中...</span>
                        </div>
                    </div>
                    <div class="time-slot flex gap-3 relative timeline-line">
                        <div class="w-10 text-right shrink-0 font-en font-bold text-xs text-toystory-sky mt-1">08:30</div>
                        <div class="flex-1 bg-gray-50 p-3 rounded-xl border border-gray-100">
                            <h4 class="font-bold text-sm text-gray-800">飯店花園探索</h4>
                            <p class="text-[11px] text-gray-500 mt-1">悠閒享用早餐，逛四大主題花園。</p>
                        </div>
                    </div>
                    <div class="time-slot flex gap-3 relative timeline-line">
                        <div class="w-10 text-right shrink-0 font-en font-bold text-xs text-toystory-sky mt-1">11:30</div>
                        <div class="flex-1 bg-yellow-50/60 p-3 rounded-xl border border-yellow-100">
                            <h4 class="font-bold text-sm text-yellow-900"><i class="fas fa-sign-out-alt text-toystory-woody mr-1"></i> 退房 ＆ 機場午餐</h4>
                        </div>
                    </div>
                    <div class="time-slot flex gap-3 relative">
                        <div class="w-10 text-right shrink-0 font-en font-bold text-xs text-toystory-sky mt-1">16:35</div>
                        <div class="flex-1 bg-gray-50 p-3 rounded-xl border border-gray-100">
                            <h4 class="font-bold text-sm text-gray-800">✈️ CX458 飛返高雄</h4>
                            <p class="text-[11px] text-gray-500 mt-1">預計 18:05 抵達，平安回家！</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- ==================== 3. 設施踩點視圖 (RIDES) ==================== -->
        <div id="view-rides" class="page-view hidden space-y-4">
            <div class="bg-white rounded-2xl shadow-md p-5 border-2 border-toystory-sky/20">
                <div class="flex justify-between items-center border-b pb-3 mb-4">
                    <h3 class="font-bold text-sm text-toystory-dark flex items-center gap-1.5">
                        <i class="fas fa-ticket-alt text-toystory-purple transform -rotate-12"></i> 樂園設施踩點地圖
                    </h3>
                    <span id="rides-count" class="text-xs bg-purple-50 text-toystory-purple font-bold px-2 py-0.5 rounded-full font-en">0/0</span>
                </div>
                
                <!-- 總體進度條 -->
                <div class="w-full bg-gray-100 rounded-full h-2.5 mb-5 overflow-hidden shadow-inner">
                    <div id="rides-progress-bar" class="bg-gradient-to-r from-toystory-purple to-toystory-sky h-2.5 w-0 transition-all duration-500"></div>
                </div>

                <div class="space-y-4" id="rides-list-container"></div>
            </div>
        </div>

        <!-- ==================== 4. 記帳視圖 (BUDGET) ==================== -->
        <div id="view-budget" class="page-view hidden space-y-4">
            <div class="bg-white rounded-2xl shadow-md p-5 border-2 border-toystory-sky/20">
                <h3 class="font-bold text-sm text-toystory-dark flex items-center gap-1.5 mb-3">
                    <i class="fas fa-wallet text-toystory-buzz"></i> 戰術現金支出記帳簿
                </h3>
                
                <div class="flex justify-between items-end border-b pb-3 mb-4 bg-gray-50/50 p-3 rounded-xl border border-gray-100">
                    <div>
                        <div class="text-[10px] text-gray-400 font-bold mb-0.5">總花費 (HKD)</div>
                        <div class="text-2xl font-black text-toystory-dark font-en leading-none" id="total-hkd">HK$ 0</div>
                    </div>
                    <div class="text-right flex flex-col justify-end">
                        <div class="text-[10px] text-gray-400 font-bold mb-0.5">自動換算台幣 (TWD)</div>
                        <div class="text-lg font-bold text-toystory-red font-en leading-none" id="total-twd">NT$ 0</div>
                    </div>
                </div>

                <!-- 新增消費表單 -->
                <div class="space-y-2 bg-sky-50/50 p-3 rounded-xl border border-sky-100 shadow-inner mb-4">
                    <div class="flex gap-2">
                        <input type="date" id="expense-date" class="bg-white border border-gray-200 rounded-xl px-2 py-2 text-xs focus:outline-none focus:border-toystory-sky font-en text-gray-600 w-1/3 shadow-sm">
                        <select id="expense-category" class="bg-white border border-gray-200 rounded-xl px-2 py-2 text-xs focus:outline-none focus:border-toystory-sky font-medium flex-1 shadow-sm">
                            <option value="🍔 美食">🍔 美食</option>
                            <option value="🛍️ 購物">🛍️ 購物</option>
                            <option value="🚌 交通">🚌 交通</option>
                            <option value="🎢 玩樂">🎢 玩樂</option>
                            <option value="✨ 其他">✨ 其他</option>
                        </select>
                    </div>
                    <div class="flex gap-2">
                        <input type="text" id="expense-name" placeholder="消費項目..." class="flex-1 bg-white border border-gray-200 rounded-xl px-3 py-2 text-xs focus:outline-none focus:border-toystory-sky font-medium shadow-sm">
                        <div class="relative w-1/3 shadow-sm rounded-xl shrink-0">
                            <span class="absolute left-2 top-1/2 -translate-y-1/2 text-gray-400 font-en text-[10px] font-bold">HK$</span>
                            <input type="number" id="expense-amount" placeholder="金額" class="w-full bg-white border border-gray-200 rounded-xl pl-8 pr-2 py-2 text-xs font-black text-gray-700 focus:outline-none focus:border-toystory-sky font-en">
                        </div>
                    </div>
                    <button onclick="addExpense()" class="w-full bg-toystory-buzz hover:bg-green-600 text-white font-bold px-4 py-2 rounded-xl text-xs shadow-md transition-all flex justify-center items-center gap-1 active:scale-95 mt-1">
                        <i class="fas fa-plus"></i> 記錄這筆花費
                    </button>
                </div>

                <div class="flex justify-between items-center mb-2">
                    <h3 class="font-bold text-xs text-gray-500"><i class="fas fa-list-ul mr-1"></i> 消費明細</h3>
                </div>
                <div class="space-y-2" id="expense-list-container">
                    <!-- JS 生成明細 -->
                </div>
            </div>
        </div>

        <!-- ==================== 5. 行李清單視圖 (PACKING) ==================== -->
        <div id="view-packing" class="page-view hidden space-y-4">
            <div class="bg-white rounded-2xl shadow-md p-5 border-2 border-toystory-sky/20">
                <div class="flex justify-between items-center border-b pb-3 mb-4">
                    <h3 class="font-bold text-sm text-toystory-dark flex items-center gap-1.5">
                        <i class="fas fa-clipboard-list text-toystory-sky"></i> 綠色兵團行李打包清單
                    </h3>
                    <span id="pack-count" class="text-xs bg-sky-50 text-toystory-sky font-bold px-2 py-0.5 rounded-full font-en">0/0</span>
                </div>
                <div class="space-y-5 text-sm" id="packing-list-container"></div>
            </div>
        </div>

    </div>

    <!-- 底部固定導航列 (5個按鈕平均分配) -->
    <nav class="fixed bottom-0 left-0 right-0 bg-white/95 backdrop-blur-xl border-t-4 border-toystory-sky pb-safe z-50 shadow-[0_-8px_20px_rgba(0,0,0,0.05)]">
        <div class="max-w-md mx-auto flex justify-between items-center h-16 px-1">
            <button onclick="switchView('home')" id="nav-home" class="nav-btn flex flex-col items-center justify-center flex-1 h-full text-toystory-sky transition-all"><i class="fas fa-home text-lg mb-0.5"></i><span class="text-[10px] font-bold tracking-wider">首頁</span></button>
            <button onclick="switchView('itinerary')" id="nav-itinerary" class="nav-btn flex flex-col items-center justify-center flex-1 h-full text-gray-400 hover:text-toystory-sky transition-all"><i class="fas fa-map-marked-alt text-lg mb-0.5"></i><span class="text-[10px] font-bold tracking-wider">行程</span></button>
            <button onclick="switchView('rides')" id="nav-rides" class="nav-btn flex flex-col items-center justify-center flex-1 h-full text-gray-400 hover:text-toystory-sky transition-all"><i class="fas fa-ticket-alt text-lg mb-0.5"></i><span class="text-[10px] font-bold tracking-wider">設施</span></button>
            <button onclick="switchView('budget')" id="nav-budget" class="nav-btn flex flex-col items-center justify-center flex-1 h-full text-gray-400 hover:text-toystory-sky transition-all"><i class="fas fa-wallet text-lg mb-0.5"></i><span class="text-[10px] font-bold tracking-wider">記帳</span></button>
            <button onclick="switchView('packing')" id="nav-packing" class="nav-btn flex flex-col items-center justify-center flex-1 h-full text-gray-400 hover:text-toystory-sky transition-all"><i class="fas fa-suitcase text-lg mb-0.5"></i><span class="text-[10px] font-bold tracking-wider">打包</span></button>
        </div>
    </nav>

    <!-- 編輯記帳 Modal -->
    <div id="edit-modal" class="fixed inset-0 z-[60] bg-black/50 backdrop-blur-sm hidden items-center justify-center px-4">
        <div class="bg-white rounded-2xl w-full max-w-sm p-5 shadow-2xl border-4 border-toystory-sky modal-enter">
            <h3 class="font-bold text-lg text-toystory-dark mb-4 border-b pb-2">✏️ 編輯消費</h3>
            <input type="hidden" id="edit-idx">
            <div class="space-y-3">
                <div>
                    <label class="text-[10px] font-bold text-gray-500 mb-1 block">日期</label>
                    <input type="date" id="edit-date" class="w-full bg-gray-50 border border-gray-200 rounded-xl px-3 py-2 text-sm focus:outline-none focus:border-toystory-sky">
                </div>
                <div>
                    <label class="text-[10px] font-bold text-gray-500 mb-1 block">分類與名稱</label>
                    <div class="flex gap-2">
                        <select id="edit-cat" class="bg-gray-50 border border-gray-200 rounded-xl px-2 py-2 text-sm focus:outline-none focus:border-toystory-sky w-1/3"></select>
                        <input type="text" id="edit-name" class="flex-1 bg-gray-50 border border-gray-200 rounded-xl px-3 py-2 text-sm focus:outline-none focus:border-toystory-sky">
                    </div>
                </div>
                <div>
                    <label class="text-[10px] font-bold text-gray-500 mb-1 block">金額 (HKD)</label>
                    <input type="number" id="edit-amount" class="w-full bg-gray-50 border border-gray-200 rounded-xl px-3 py-2 text-sm font-black focus:outline-none focus:border-toystory-sky font-en">
                </div>
            </div>
            <div class="flex gap-3 mt-6">
                <button onclick="closeEditModal()" class="flex-1 bg-gray-100 hover:bg-gray-200 text-gray-600 font-bold py-2.5 rounded-xl text-sm transition-colors">取消</button>
                <button onclick="saveEdit()" class="flex-1 bg-toystory-sky hover:bg-blue-500 text-white font-bold py-2.5 rounded-xl text-sm shadow-md transition-colors">儲存</button>
            </div>
        </div>
    </div>

    <script>
        let currentRate = 4.15; 

        const defaultPackingData = [
            { category: "隨身包（重要物品）", items: ["護照正本(大人/小孩)", "香港電子簽證（需帶紙本)", "錢包(港幣現金+少量台幣+信用卡)", "手機/行動電源"] },
            { category: "衣物鞋履", items: ["大人衣物（外出服/睡衣/內衣褲/襪子)", "幼童衣物（外出服+睡衣/襪子)", "薄外套/防曬罩衫（大人/幼童各1件）", "好走的鞋"] },
            { category: "防曬/防雨/抗熱", items: ["推車雨罩（防風雨、冷氣）", "輕便雨衣/折疊傘", "遮陽帽（大人/小孩）", "太陽眼鏡（大人/小孩）", "小風扇", "防曬乳/防蚊液/防蚊貼（小孩專用）"] },
            { category: "日常備品/衛生清潔", items: ["尿布", "濕紙巾/乾洗手", "水壺", "拋棄式圍兜/餐具", "洗漱用品（牙膏/牙刷/洗面乳/卸妝）", "化妝包", "幼童餐具"] },
            { category: "3C用品", items: ["多孔擴充插頭/轉接頭（香港通用）", "充電線（手機線/手錶線)"] },
            { category: "健康護理", items: ["過敏藥水/常備感冒腸胃藥", "OK 繃/小傷口藥膏", "藥品急救包 (退燒藥水、體溫計、感冒藥、止癢藥膏)"] },
            { category: "其他", items: ["密封夾鏈袋/塑膠提袋 (裝髒衣物/垃圾)", "安撫小物（iPad/貼紙書/零食/玩具）"] }
        ];

        const defaultRidesData = [
            {
                area: "美國小鎮大街 (Main Street, U.S.A.)",
                note: "此區為購物與餐飲中心，無遊樂設施",
                items: []
            },
            {
                area: "反斗奇兵大本營 (Toy Story Land)",
                note: "動線建議：進園後先往左側直走。",
                items: [
                    { name: "轉轉彈弓狗", tags: "[90cm+]", desc: "必玩，速度溫和。", ok: true },
                    { name: "玩具兵團跳降傘", tags: "[90cm+]", desc: "升降速度緩慢，視覺刺激。", ok: true },
                    { name: "RC 賽車", tags: "需 120cm", desc: "過於刺激", ok: false }
                ]
            },
            {
                area: "迷離莊園 (Mystic Point)",
                note: "動線建議：反斗奇兵出來後繼續往前。",
                items: [
                    { name: "迷離大宅", tags: "[90cm+]", desc: "無身高限制，聲光特效極佳，必玩。", ok: true }
                ]
            },
            {
                area: "灰熊山谷 (Grizzly Gulch)",
                note: "動線建議：迷離莊園隔壁。",
                items: [
                    { name: "灰熊山極速礦車", tags: "需 112cm", desc: "較為刺激，不建議幼童", ok: false }
                ]
            },
            {
                area: "探險世界 (Adventureland)",
                note: "動線建議：灰熊山谷出來後往中央走。",
                items: [
                    { name: "森林河流之旅", tags: "[90cm+]", desc: "坐船，看特效，適合小孩。", ok: true },
                    { name: "歷奇噴水池", tags: "[90cm+]", desc: "適合放電。", ok: true },
                    { name: "獅子王慶典", tags: "[90cm+]", desc: "室內劇場，必看，必備冷氣。", ok: true }
                ]
            },
            {
                area: "魔雪奇緣世界 (World of Frozen)",
                note: "動線建議：靠近幻想世界。",
                items: [
                    { name: "魔雪奇幻之旅", tags: "[90cm+]", desc: "坐船故事體驗，必玩。", ok: true },
                    { name: "雪嶺滑雪橇", tags: "需 95cm", desc: "雲霄飛車性質", ok: false }
                ]
            },
            {
                area: "幻想世界 (Fantasyland) — 幼童核心區",
                note: "動線建議：園區最後方，這裡是您的基地。",
                items: [
                    { name: "灰姑娘旋轉木馬", tags: "[90cm+]", desc: "經典遊樂設施。", ok: true },
                    { name: "小飛象旋轉世界", tags: "[90cm+]", desc: "可自行控制高度。", ok: true },
                    { name: "瘋帽子旋轉杯", tags: "[90cm+]", desc: "可控制旋轉速度。", ok: true },
                    { name: "小熊維尼歷險之旅", tags: "[90cm+]", desc: "熱門設施，必玩。", ok: true },
                    { name: "小小世界", tags: "[90cm+]", desc: "冷氣強，視覺豐富，必玩。", ok: true },
                    { name: "童話園林", tags: "[90cm+]", desc: "戶外互動走廊。", ok: true },
                    { name: "米奇幻想曲", tags: "[90cm+]", desc: "室內 4D 電影，必備冷氣。", ok: true }
                ]
            },
            {
                area: "明日世界 (Tomorrowland)",
                note: "動線建議：靠近大門入口右側。",
                items: [
                    { name: "蟻俠與黃蜂女：擊戰特攻！", tags: "[90cm+]", desc: "室內射擊互動遊戲。", ok: true },
                    { name: "太空飛碟", tags: "[90cm+]", desc: "類似小飛象，但飛得比較高。", ok: true },
                    { name: "星戰極速穿梭", tags: "需 102cm", desc: "過於刺激", ok: false }
                ]
            }
        ];

        function getTodayString() {
            const tzoffset = (new Date()).getTimezoneOffset() * 60000;
            return (new Date(Date.now() - tzoffset)).toISOString().split('T')[0];
        }

        document.addEventListener("DOMContentLoaded", () => {
            // 資料初始化 (更新金鑰確保資料重置為新格式)
            if(!localStorage.getItem("pack_ts_v9")) {
                localStorage.setItem("pack_ts_v9", JSON.stringify(defaultPackingData.map(c => ({
                    ...c, items: c.items.map(i => ({text: i, checked: false}))
                }))));
            }
            if(!localStorage.getItem("budget_ts_v9")) {
                localStorage.setItem("budget_ts_v9", JSON.stringify([]));
            }
            if(!localStorage.getItem("rides_ts_v9")) {
                localStorage.setItem("rides_ts_v9", JSON.stringify(defaultRidesData.map(c => ({
                    ...c, items: c.items.map(i => ({...i, checked: false}))
                }))));
            }
            
            document.getElementById("expense-date").value = getTodayString();
            const catSelect = document.getElementById('expense-category');
            document.getElementById('edit-cat').innerHTML = catSelect.innerHTML;

            renderPackingList();
            renderRidesList();
            renderBudgetList();
            fetchExchangeRate();
            fetchWeather();
        });

        function switchView(viewId) {
            // 嚴格隔離頁籤：先隱藏全部
            document.querySelectorAll('.page-view').forEach(view => {
                view.classList.remove('active');
            });
            // 顯示目標
            const targetView = document.getElementById('view-' + viewId);
            if(targetView) targetView.classList.add('active');

            // 更新按鈕樣式
            document.querySelectorAll('.nav-btn').forEach(btn => {
                btn.className = 'nav-btn flex flex-col items-center justify-center flex-1 h-full text-gray-400 hover:text-toystory-sky transition-all';
            });
            const targetBtn = document.getElementById('nav-' + viewId);
            if(targetBtn) {
                targetBtn.className = 'nav-btn flex flex-col items-center justify-center flex-1 h-full text-toystory-sky transition-all';
            }
            window.scrollTo({ top: 0, behavior: 'auto' });
        }

        function switchDay(dayNum) {
            document.querySelectorAll('.day-content').forEach(content => content.classList.add('hidden'));
            document.getElementById('day-content-' + dayNum).classList.remove('hidden');

            document.querySelectorAll('.day-btn').forEach(btn => btn.className = 'day-btn shrink-0 px-4 py-2 rounded-full text-xs font-bold transition-all bg-white text-gray-500');
            const activeBtn = document.getElementById('btn-day-' + dayNum);
            activeBtn.className = 'day-btn shrink-0 px-4 py-2 rounded-full text-xs font-bold transition-all shadow-sm bg-toystory-sky text-white border-2 border-white/50';
            activeBtn.scrollIntoView({ behavior: 'smooth', block: 'nearest', inline: 'center' });
        }

        async function fetchExchangeRate() {
            try {
                const res = await fetch('https://api.exchangerate-api.com/v4/latest/HKD');
                const data = await res.json();
                currentRate = data.rates.TWD;
                document.getElementById('rate-display').innerText = `1 HKD = ${currentRate.toFixed(2)} TWD`;
                renderBudgetList(); 
            } catch (e) {
                document.getElementById('rate-display').innerText = `參考匯率: 4.15`;
            }
        }

        function calculateExchange() {
            const hkd = parseFloat(document.getElementById('calc-hkd').value) || 0;
            document.getElementById('calc-twd').value = Math.round(hkd * currentRate).toLocaleString();
        }

        async function fetchWeather() {
            try {
                // Kaohsiung Weather for D0
                const khhRes = await fetch('https://api.open-meteo.com/v1/forecast?latitude=22.6208&longitude=120.3118&current_weather=true');
                const khhData = await khhRes.json();
                updateWeatherUI('weather-d0', khhData.current_weather);

                // HK Weather for D1-D3
                const hkgRes = await fetch('https://api.open-meteo.com/v1/forecast?latitude=22.3193&longitude=114.1694&current_weather=true');
                const hkgData = await hkgRes.json();
                const hkgUI = (data) => {
                    updateWeatherUI('weather-d1', data);
                    updateWeatherUI('weather-d2', data);
                    updateWeatherUI('weather-d3', data);
                };
                hkgUI(hkgData.current_weather);
            } catch(e) {}
        }

        function updateWeatherUI(elementId, weather) {
            const el = document.getElementById(elementId);
            if(!el) return;
            const temp = Math.round(weather.temperature);
            let icon = "☁️";
            if(weather.weathercode <= 3) icon = "☀️";
            else if(weather.weathercode <= 48) icon = "☁️";
            else if(weather.weathercode <= 69) icon = "🌧️";
            else icon = "⛈️";
            
            el.innerHTML = `
                <span class="text-xs font-bold text-gray-700 flex items-center gap-1"><i class="fas fa-map-marker-alt text-sky-500"></i> 當地即時</span>
                <span class="text-sm font-black text-gray-800 font-en flex items-center gap-1">${icon} ${temp}°C <span class="text-[9px] text-gray-400 font-normal ml-1">體感 ${temp+2}°C</span></span>
            `;
        }

        function renderRidesList() {
            const data = JSON.parse(localStorage.getItem("rides_ts_v9"));
            const container = document.getElementById("rides-list-container");
            container.innerHTML = "";
            let total = 0, checked = 0;

            data.forEach((areaData, catIdx) => {
                const section = document.createElement("div");
                section.className = "bg-purple-50/50 rounded-xl p-3 border border-purple-100 shadow-sm";

                let headerHtml = `
                    <div class="mb-3">
                        <h4 class="font-bold text-toystory-dark text-sm">${areaData.area}</h4>
                        ${areaData.note ? `<div class="text-[11px] bg-white text-blue-700 px-2.5 py-1.5 rounded-lg mt-1.5 border border-blue-100 shadow-sm inline-flex items-start gap-1"><i class="fas fa-route mt-0.5 shrink-0 text-blue-400"></i><span>${areaData.note}</span></div>` : ''}
                    </div>
                `;
                section.innerHTML = headerHtml;

                if(areaData.items && areaData.items.length > 0) {
                    const list = document.createElement("div");
                    list.className = "space-y-2";
                    areaData.items.forEach((item, itemIdx) => {
                        const itemDiv = document.createElement("div");
                        if (item.ok) {
                            total++;
                            if(item.checked) checked++;
                            itemDiv.className = "flex items-start gap-2.5 p-2.5 bg-white rounded-lg border border-gray-100 shadow-sm transition-all";
                            itemDiv.innerHTML = `
                                <input type="checkbox" ${item.checked ? 'checked' : ''} onchange="toggleRide(${catIdx}, ${itemIdx})" class="w-4 h-4 mt-0.5 rounded text-toystory-purple border-gray-300 focus:ring-toystory-purple shrink-0">
                                <div class="flex-1 leading-tight">
                                    <div class="flex items-center gap-1.5 flex-wrap mb-0.5">
                                        <span class="text-xs font-bold ${item.checked ? 'text-gray-400 line-through' : 'text-gray-800'}">${item.name}</span>
                                        <span class="text-[9px] bg-green-100 text-green-700 px-1.5 py-0.5 rounded font-bold">${item.tags}</span>
                                    </div>
                                    <div class="text-[10px] text-gray-500 ${item.checked ? 'line-through opacity-60' : ''}">${item.desc}</div>
                                </div>
                            `;
                        } else {
                            itemDiv.className = "flex items-start gap-2.5 p-2.5 bg-gray-100 rounded-lg border border-gray-200 opacity-60";
                            itemDiv.innerHTML = `
                                <div class="w-4 h-4 mt-0.5 shrink-0 flex items-center justify-center text-red-400"><i class="fas fa-ban"></i></div>
                                <div class="flex-1 leading-tight">
                                    <div class="flex items-center gap-1.5 flex-wrap mb-0.5">
                                        <span class="text-xs font-bold text-gray-500 line-through">${item.name}</span>
                                        <span class="text-[9px] bg-red-100 text-red-700 px-1.5 py-0.5 rounded font-bold">${item.tags}</span>
                                    </div>
                                    <div class="text-[10px] text-gray-400">${item.desc}</div>
                                </div>
                            `;
                        }
                        list.appendChild(itemDiv);
                    });
                    section.appendChild(list);
                }

                container.appendChild(section);
            });

            document.getElementById("rides-count").innerText = `${checked}/${total}`;
            const percent = total > 0 ? Math.round((checked / total) * 100) : 0;
            document.getElementById("rides-progress-bar").style.width = percent + "%";
        }

        function toggleRide(catIdx, itemIdx) {
            const data = JSON.parse(localStorage.getItem("rides_ts_v9"));
            data[catIdx].items[itemIdx].checked = !data[catIdx].items[itemIdx].checked;
            localStorage.setItem("rides_ts_v9", JSON.stringify(data));
            renderRidesList();
        }

        function renderPackingList() {
            const data = JSON.parse(localStorage.getItem("pack_ts_v9"));
            const container = document.getElementById("packing-list-container");
            container.innerHTML = "";
            let total = 0, checked = 0;

            data.forEach((cat, catIdx) => {
                const section = document.createElement("div");
                section.className = "space-y-1.5";
                section.innerHTML = `<h4 class="font-bold text-gray-400 text-[11px] tracking-wider mb-1 uppercase">${cat.category}</h4>`;
                
                cat.items.forEach((item, itemIdx) => {
                    total++; if(item.checked) checked++;
                    const div = document.createElement("div");
                    div.className = "flex items-center gap-3 bg-gray-50 p-2.5 rounded-xl border border-gray-100 text-xs";
                    div.innerHTML = `
                        <input type="checkbox" ${item.checked ? 'checked' : ''} onchange="togglePack(${catIdx}, ${itemIdx})" class="w-4 h-4 rounded text-toystory-sky border-gray-300 focus:ring-toystory-sky shrink-0">
                        <span class="${item.checked ? 'checked-item' : 'text-gray-700 font-medium'}">${item.text}</span>
                    `;
                    section.appendChild(div);
                });
                container.appendChild(section);
            });
            document.getElementById("pack-count").innerText = `${checked}/${total}`;
            document.getElementById("home-pack-progress").innerText = (total > 0 ? Math.round((checked / total) * 100) : 0) + "%";
        }

        function togglePack(catIdx, itemIdx) {
            const data = JSON.parse(localStorage.getItem("pack_ts_v9"));
            data[catIdx].items[itemIdx].checked = !data[catIdx].items[itemIdx].checked;
            localStorage.setItem("pack_ts_v9", JSON.stringify(data));
            renderPackingList();
        }

        function renderBudgetList() {
            const items = JSON.parse(localStorage.getItem("budget_ts_v9")) || [];
            const container = document.getElementById("expense-list-container");
            container.innerHTML = "";
            let totalHkd = 0;

            if(items.length === 0) {
                container.innerHTML = `<div class="text-center py-6 text-gray-400 text-xs">尚無花費紀錄，點擊上方新增吧！</div>`;
            }

            [...items].reverse().forEach((item, revIdx) => {
                const realIdx = items.length - 1 - revIdx;
                totalHkd += item.amount;
                const div = document.createElement("div");
                div.className = "flex items-center justify-between bg-gray-50 p-3 rounded-xl border border-gray-100 cursor-pointer hover:bg-sky-50 transition-colors";
                div.onclick = () => openEditModal(realIdx);
                div.innerHTML = `
                    <div class="flex flex-col flex-1">
                        <div class="flex items-center gap-1.5 mb-0.5">
                            <span class="text-[9px] bg-white border border-gray-200 px-1.5 rounded text-gray-500 font-en">${item.date.substring(5)}</span>
                            <span class="text-[10px] font-bold text-toystory-sky">${item.category}</span>
                        </div>
                        <span class="text-xs font-bold text-gray-800">${item.name}</span>
                    </div>
                    <div class="flex items-center gap-3">
                        <span class="font-en font-black text-gray-800 text-sm">$${item.amount.toLocaleString()}</span>
                        <button onclick="event.stopPropagation(); deleteExpense(${realIdx})" class="text-gray-300 hover:text-red-500 p-2 -mr-2"><i class="fas fa-trash-alt text-xs"></i></button>
                    </div>
                `;
                container.appendChild(div);
            });

            const totalTwd = Math.round(totalHkd * currentRate);
            document.getElementById("total-hkd").innerText = `HK$ ${totalHkd.toLocaleString()}`;
            document.getElementById("total-twd").innerText = `NT$ ${totalTwd.toLocaleString()}`;
            document.getElementById("home-budget-progress").innerText = `NT$ ${totalTwd.toLocaleString()}`;
        }

        function addExpense() {
            const date = document.getElementById("expense-date").value;
            const category = document.getElementById("expense-category").value;
            const name = document.getElementById("expense-name").value.trim();
            const amount = parseFloat(document.getElementById("expense-amount").value);

            if(!name || isNaN(amount) || amount <= 0) return;

            const items = JSON.parse(localStorage.getItem("budget_ts_v9"));
            items.push({ id: Date.now(), date, category, name, amount });
            localStorage.setItem("budget_ts_v9", JSON.stringify(items));
            
            document.getElementById("expense-name").value = "";
            document.getElementById("expense-amount").value = "";
            renderBudgetList();
        }

        function deleteExpense(idx) {
            const items = JSON.parse(localStorage.getItem("budget_ts_v9"));
            items.splice(idx, 1);
            localStorage.setItem("budget_ts_v9", JSON.stringify(items));
            renderBudgetList();
        }

        function openEditModal(idx) {
            const items = JSON.parse(localStorage.getItem("budget_ts_v9"));
            const item = items[idx];
            document.getElementById("edit-idx").value = idx;
            document.getElementById("edit-date").value = item.date;
            document.getElementById("edit-cat").value = item.category;
            document.getElementById("edit-name").value = item.name;
            document.getElementById("edit-amount").value = item.amount;
            
            const modal = document.getElementById("edit-modal");
            modal.style.display = "flex";
        }

        function closeEditModal() {
            document.getElementById("edit-modal").style.display = "none";
        }

        function saveEdit() {
            const idx = document.getElementById("edit-idx").value;
            const date = document.getElementById("edit-date").value;
            const category = document.getElementById("edit-cat").value;
            const name = document.getElementById("edit-name").value.trim();
            const amount = parseFloat(document.getElementById("edit-amount").value);

            if(!name || isNaN(amount) || amount <= 0) return;

            const items = JSON.parse(localStorage.getItem("budget_ts_v9"));
            items[idx] = { ...items[idx], date, category, name, amount };
            localStorage.setItem("budget_ts_v9", JSON.stringify(items));
            
            closeEditModal();
            renderBudgetList();
        }
    </script>
</body>
</html>
