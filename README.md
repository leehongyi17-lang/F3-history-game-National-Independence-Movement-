<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
<html>
<head>
  <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
  <meta http-equiv="Content-Style-Type" content="text/css">
  <title></title>
  <meta name="Generator" content="Cocoa HTML Writer">
  <meta name="CocoaVersion" content="2575.7">
  <style type="text/css">
    p.p1 {margin: 0.0px 0.0px 0.0px 0.0px; font: 12.0px Helvetica}
    p.p2 {margin: 0.0px 0.0px 0.0px 0.0px; font: 12.0px Helvetica; min-height: 14.0px}
  </style>
</head>
<body>
<p class="p1">&lt;!DOCTYPE html&gt;</p>
<p class="p1">&lt;html lang="zh-TW"&gt;</p>
<p class="p1">&lt;head&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;meta charset="UTF-8"&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;title&gt;非殖民地化與國家獨立運動 - 探究式歷史 RPG&lt;/title&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;style&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>:root {</p>
<p class="p1"><span class="Apple-converted-space">            </span>--comic-yellow: #FFDE59;</p>
<p class="p1"><span class="Apple-converted-space">            </span>--comic-blue: #004AAD;</p>
<p class="p1"><span class="Apple-converted-space">            </span>--comic-red: #FF3131;</p>
<p class="p1"><span class="Apple-converted-space">            </span>--comic-dark: #1E1E1E;</p>
<p class="p1"><span class="Apple-converted-space">            </span>--comic-white: #FFFFFF;</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>* {</p>
<p class="p1"><span class="Apple-converted-space">            </span>box-sizing: border-box;</p>
<p class="p1"><span class="Apple-converted-space">            </span>font-family: 'PingFang TC', 'Microsoft JhengHei', sans-serif;</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>body {</p>
<p class="p1"><span class="Apple-converted-space">            </span>background-color: var(--comic-yellow);</p>
<p class="p1"><span class="Apple-converted-space">            </span>color: var(--comic-dark);</p>
<p class="p1"><span class="Apple-converted-space">            </span>margin: 0;</p>
<p class="p1"><span class="Apple-converted-space">            </span>padding: 20px;</p>
<p class="p1"><span class="Apple-converted-space">            </span>display: flex;</p>
<p class="p1"><span class="Apple-converted-space">            </span>justify-content: center;</p>
<p class="p1"><span class="Apple-converted-space">            </span>align-items: center;</p>
<p class="p1"><span class="Apple-converted-space">            </span>min-height: 100vh;</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>.game-card {</p>
<p class="p1"><span class="Apple-converted-space">            </span>background: var(--comic-white);</p>
<p class="p1"><span class="Apple-converted-space">            </span>border: 5px solid var(--comic-dark);</p>
<p class="p1"><span class="Apple-converted-space">            </span>box-shadow: 10px 10px 0px var(--comic-dark);</p>
<p class="p1"><span class="Apple-converted-space">            </span>border-radius: 15px;</p>
<p class="p1"><span class="Apple-converted-space">            </span>width: 100%;</p>
<p class="p1"><span class="Apple-converted-space">            </span>max-width: 800px;</p>
<p class="p1"><span class="Apple-converted-space">            </span>padding: 25px;</p>
<p class="p1"><span class="Apple-converted-space">            </span>position: relative;</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>.header {</p>
<p class="p1"><span class="Apple-converted-space">            </span>background: var(--comic-blue);</p>
<p class="p1"><span class="Apple-converted-space">            </span>color: var(--comic-white);</p>
<p class="p1"><span class="Apple-converted-space">            </span>padding: 15px;</p>
<p class="p1"><span class="Apple-converted-space">            </span>border: 3px solid var(--comic-dark);</p>
<p class="p1"><span class="Apple-converted-space">            </span>border-radius: 10px;</p>
<p class="p1"><span class="Apple-converted-space">            </span>text-align: center;</p>
<p class="p1"><span class="Apple-converted-space">            </span>margin-bottom: 20px;</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>.header h1 {</p>
<p class="p1"><span class="Apple-converted-space">            </span>margin: 0 0 10px 0;</p>
<p class="p1"><span class="Apple-converted-space">            </span>font-size: 1.6rem;</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>.identity-badge {</p>
<p class="p1"><span class="Apple-converted-space">            </span>display: inline-block;</p>
<p class="p1"><span class="Apple-converted-space">            </span>background: var(--comic-red);</p>
<p class="p1"><span class="Apple-converted-space">            </span>color: white;</p>
<p class="p1"><span class="Apple-converted-space">            </span>padding: 5px 15px;</p>
<p class="p1"><span class="Apple-converted-space">            </span>border-radius: 20px;</p>
<p class="p1"><span class="Apple-converted-space">            </span>font-weight: bold;</p>
<p class="p1"><span class="Apple-converted-space">            </span>border: 2px solid var(--comic-dark);</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>.progress-bar {</p>
<p class="p1"><span class="Apple-converted-space">            </span>height: 15px;</p>
<p class="p1"><span class="Apple-converted-space">            </span>background: #eee;</p>
<p class="p1"><span class="Apple-converted-space">            </span>border: 2px solid var(--comic-dark);</p>
<p class="p1"><span class="Apple-converted-space">            </span>border-radius: 10px;</p>
<p class="p1"><span class="Apple-converted-space">            </span>margin-top: 10px;</p>
<p class="p1"><span class="Apple-converted-space">            </span>overflow: hidden;</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>.progress-fill {</p>
<p class="p1"><span class="Apple-converted-space">            </span>height: 100%;</p>
<p class="p1"><span class="Apple-converted-space">            </span>background: var(--comic-red);</p>
<p class="p1"><span class="Apple-converted-space">            </span>width: 10%;</p>
<p class="p1"><span class="Apple-converted-space">            </span>transition: width 0.3s ease;</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>.scenario-box {</p>
<p class="p1"><span class="Apple-converted-space">            </span>background: #FFF9E6;</p>
<p class="p1"><span class="Apple-converted-space">            </span>border: 3px dashed var(--comic-dark);</p>
<p class="p1"><span class="Apple-converted-space">            </span>padding: 20px;</p>
<p class="p1"><span class="Apple-converted-space">            </span>border-radius: 10px;</p>
<p class="p1"><span class="Apple-converted-space">            </span>margin-bottom: 20px;</p>
<p class="p1"><span class="Apple-converted-space">            </span>font-size: 1.1rem;</p>
<p class="p1"><span class="Apple-converted-space">            </span>line-height: 1.6;</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>.hint-box {</p>
<p class="p1"><span class="Apple-converted-space">            </span>background: #E8F4FF;</p>
<p class="p1"><span class="Apple-converted-space">            </span>border-left: 5px solid var(--comic-blue);</p>
<p class="p1"><span class="Apple-converted-space">            </span>padding: 10px 15px;</p>
<p class="p1"><span class="Apple-converted-space">            </span>margin-top: 15px;</p>
<p class="p1"><span class="Apple-converted-space">            </span>border-radius: 0 8px 8px 0;</p>
<p class="p1"><span class="Apple-converted-space">            </span>font-size: 0.95rem;</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>.options-grid {</p>
<p class="p1"><span class="Apple-converted-space">            </span>display: grid;</p>
<p class="p1"><span class="Apple-converted-space">            </span>grid-template-columns: 1fr;</p>
<p class="p1"><span class="Apple-converted-space">            </span>gap: 12px;</p>
<p class="p1"><span class="Apple-converted-space">            </span>margin-bottom: 20px;</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>.option-btn {</p>
<p class="p1"><span class="Apple-converted-space">            </span>background: var(--comic-white);</p>
<p class="p1"><span class="Apple-converted-space">            </span>border: 3px solid var(--comic-dark);</p>
<p class="p1"><span class="Apple-converted-space">            </span>padding: 15px;</p>
<p class="p1"><span class="Apple-converted-space">            </span>border-radius: 10px;</p>
<p class="p1"><span class="Apple-converted-space">            </span>text-align: left;</p>
<p class="p1"><span class="Apple-converted-space">            </span>font-size: 1rem;</p>
<p class="p1"><span class="Apple-converted-space">            </span>cursor: pointer;</p>
<p class="p1"><span class="Apple-converted-space">            </span>transition: all 0.2s ease;</p>
<p class="p1"><span class="Apple-converted-space">            </span>box-shadow: 4px 4px 0px var(--comic-dark);</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>.option-btn:hover {</p>
<p class="p1"><span class="Apple-converted-space">            </span>background: var(--comic-yellow);</p>
<p class="p1"><span class="Apple-converted-space">            </span>transform: translate(-2px, -2px);</p>
<p class="p1"><span class="Apple-converted-space">            </span>box-shadow: 6px 6px 0px var(--comic-dark);</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>.modal-overlay {</p>
<p class="p1"><span class="Apple-converted-space">            </span>display: none;</p>
<p class="p1"><span class="Apple-converted-space">            </span>position: fixed;</p>
<p class="p1"><span class="Apple-converted-space">            </span>top: 0; left: 0;</p>
<p class="p1"><span class="Apple-converted-space">            </span>width: 100%; height: 100%;</p>
<p class="p1"><span class="Apple-converted-space">            </span>background: rgba(0,0,0,0.7);</p>
<p class="p1"><span class="Apple-converted-space">            </span>justify-content: center;</p>
<p class="p1"><span class="Apple-converted-space">            </span>align-items: center;</p>
<p class="p1"><span class="Apple-converted-space">            </span>z-index: 1000;</p>
<p class="p1"><span class="Apple-converted-space">            </span>padding: 20px;</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>.modal-content {</p>
<p class="p1"><span class="Apple-converted-space">            </span>background: white;</p>
<p class="p1"><span class="Apple-converted-space">            </span>border: 5px solid var(--comic-dark);</p>
<p class="p1"><span class="Apple-converted-space">            </span>box-shadow: 10px 10px 0px var(--comic-dark);</p>
<p class="p1"><span class="Apple-converted-space">            </span>border-radius: 15px;</p>
<p class="p1"><span class="Apple-converted-space">            </span>padding: 25px;</p>
<p class="p1"><span class="Apple-converted-space">            </span>max-width: 600px;</p>
<p class="p1"><span class="Apple-converted-space">            </span>width: 100%;</p>
<p class="p1"><span class="Apple-converted-space">            </span>text-align: center;</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>.modal-btn {</p>
<p class="p1"><span class="Apple-converted-space">            </span>background: var(--comic-blue);</p>
<p class="p1"><span class="Apple-converted-space">            </span>color: white;</p>
<p class="p1"><span class="Apple-converted-space">            </span>border: 3px solid var(--comic-dark);</p>
<p class="p1"><span class="Apple-converted-space">            </span>padding: 12px 25px;</p>
<p class="p1"><span class="Apple-converted-space">            </span>font-size: 1.1rem;</p>
<p class="p1"><span class="Apple-converted-space">            </span>font-weight: bold;</p>
<p class="p1"><span class="Apple-converted-space">            </span>border-radius: 10px;</p>
<p class="p1"><span class="Apple-converted-space">            </span>cursor: pointer;</p>
<p class="p1"><span class="Apple-converted-space">            </span>margin-top: 20px;</p>
<p class="p1"><span class="Apple-converted-space">            </span>box-shadow: 4px 4px 0px var(--comic-dark);</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">        </span>.modal-btn:hover {</p>
<p class="p1"><span class="Apple-converted-space">            </span>background: var(--comic-red);</p>
<p class="p1"><span class="Apple-converted-space">        </span>}</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/style&gt;</p>
<p class="p1">&lt;/head&gt;</p>
<p class="p1">&lt;body&gt;</p>
<p class="p2"><br></p>
<p class="p1">&lt;div class="game-card"&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;div class="header"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;h1 id="stage-title"&gt;關卡一：民族自決的啟示 📜&lt;/h1&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="identity-badge" id="identity"&gt;主角身分：🎓 被殖民地青年知識份子&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="progress-bar"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div class="progress-fill" id="progress"&gt;&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;div class="scenario-box"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div id="scenario-text"&gt;一戰結束後，美國總統威爾遜向全世界喊出：「每個民族都應該有權決定自己的命運，不該被外國強權統治（民族自決）。」&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div class="hint-box" id="hint-text"&gt;💡 思考引導：過去宗主國總說「因為你們落後，所以我們統治你們是合理的」。現在連西方大國總統都這樣說了，這句話會在你和同胞心中種下什麼想法？💭&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;div class="options-grid" id="options-container"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;!-- 動態渲染選項 --&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/div&gt;</p>
<p class="p1">&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1">&lt;!-- 彈窗 --&gt;</p>
<p class="p1">&lt;div class="modal-overlay" id="modal"&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;div class="modal-content"&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;h2 id="modal-title" style="margin-top:0;"&gt;&lt;/h2&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;p id="modal-body" style="font-size:1.1rem; line-height:1.6; text-align:left;"&gt;&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;button class="modal-btn" id="modal-next-btn"&gt;繼續前進 ➔&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>&lt;/div&gt;</p>
<p class="p1">&lt;/div&gt;</p>
<p class="p2"><br></p>
<p class="p1">&lt;script&gt;</p>
<p class="p1">const gameData = [</p>
<p class="p1"><span class="Apple-converted-space">    </span>{</p>
<p class="p1"><span class="Apple-converted-space">        </span>title: "關卡一：民族自決的啟示 📜",</p>
<p class="p1"><span class="Apple-converted-space">        </span>identity: "🎓 被殖民地青年知識份子",</p>
<p class="p1"><span class="Apple-converted-space">        </span>scenario: "一戰結束後，美國總統威爾遜向全世界喊出：「每個民族都應該有權決定自己的命運，不該被外國強權統治（民族自決）。」",</p>
<p class="p1"><span class="Apple-converted-space">        </span>hint: "💡 思考引導：過去宗主國總說「因為你們落後，所以我們統治你們是合理的」。現在連西方大國總統都這樣說了，這句話會在你和同胞心中種下什麼想法？💭",</p>
<p class="p1"><span class="Apple-converted-space">        </span>options: [</p>
<p class="p1"><span class="Apple-converted-space">            </span>{ text: "[A] 🙇‍♂️「這代表西方人承認他們比較優秀，我們應該永遠被他們統治。」", correct: false, feedback: "❌ 推理偏差：如果自決代表自己作主，就不會想繼續被統治。" },</p>
<p class="p1"><span class="Apple-converted-space">            </span>{ text: "[B] ✊「既然人人平等、民族有權自決，那我們要求擺脫外國統治、自己管理國家也是天經地義的！」", correct: true, feedback: "✅ 正確引導：這就是「民族獨立意識」萌芽的起點！" },</p>
<p class="p1"><span class="Apple-converted-space">            </span>{ text: "[C] 🇺🇸「這代表我們應該立刻放棄自己的文化，變成完全的美國人。」", correct: false, feedback: "❌ 推理偏差：自決強調的是「自己民族」的主權。" },</p>
<p class="p1"><span class="Apple-converted-space">            </span>{ text: "[D] 🌐「這代表世界上所有國家都應該合併成一個國家。」", correct: false, feedback: "❌ 推理偏差：自決追求的是各自獨立。" }</p>
<p class="p1"><span class="Apple-converted-space">        </span>],</p>
<p class="p1"><span class="Apple-converted-space">        </span>truth: "🧠 歷史真相解密：【歷史為什麼這樣發生？】「民族自決」的核心就是「自己的命運自己決定」。這句話點破了殖民統治的不合理性，讓被殖民的人民意識到：我們要求獨立不是犯罪，而是應有的權利！🎯"</p>
<p class="p1"><span class="Apple-converted-space">    </span>},</p>
<p class="p1"><span class="Apple-converted-space">    </span>{</p>
<p class="p1"><span class="Apple-converted-space">        </span>title: "關卡二：不公平的雙重標準 ⚖️",</p>
<p class="p1"><span class="Apple-converted-space">        </span>identity: "🏛️ 巴黎和會外等待消息的亞非代表",</p>
<p class="p1"><span class="Apple-converted-space">        </span>scenario: "1919年巴黎和會上，西方列強高舉「民族自決」，讓東歐被壓迫民族建立了獨立國家。但當你們亞非代表興高采烈去爭取時，列強卻冷冷把你們拒之門外。",</p>
<p class="p1"><span class="Apple-converted-space">        </span>hint: "💡 思考引導：看著東歐人獲得自由，而自己卻因為身在亞非繼續被當二等公民，你內心有何感受？這對你們未來的抗爭態度有何影響？💭",</p>
<p class="p1"><span class="Apple-converted-space">        </span>options: [</p>
<p class="p1"><span class="Apple-converted-space">            </span>{ text: "[A] 🙇‍♀️「我們應該非常感激西方列強，並繼續心甘情願被他們剝削。」", correct: false, feedback: "❌ 不符合人性反應" },</p>
<p class="p1"><span class="Apple-converted-space">            </span>{ text: "[B] 😞「這證明東歐人天生就比我們高等，我們不配擁有自由。」", correct: false, feedback: "❌ 不符合被壓迫者的心理" },</p>
<p class="p1"><span class="Apple-converted-space">            </span>{ text: "[C] 💥「西方列強根本是雙重標準！和平祈求是無用的，我們必須靠自己的力量發起更強烈抵抗！」", correct: true, feedback: "✅ 正確引導：這解釋了為什麼後來的獨立運動走向激進與武裝" },</p>
<p class="p1"><span class="Apple-converted-space">            </span>{ text: "[D] ⚔️「我們應該立刻幫助宗主國去征服更多其他國家。」", correct: false, feedback: "❌ 邏輯不通" }</p>
<p class="p1"><span class="Apple-converted-space">        </span>],</p>
<p class="p1"><span class="Apple-converted-space">        </span>truth: "🧠 歷史真相解密：【歷史為什麼這樣發生？】列強在巴黎和會上的雙重標準（東歐可以獨立，亞非不行），讓亞非人民徹底看清了列強的虛偽。這讓他們不再對宗主國的「恩賜」抱有幻想，轉而採取更堅決的抗爭！🎯"</p>
<p class="p1"><span class="Apple-converted-space">    </span>},</p>
<p class="p1"><span class="Apple-converted-space">    </span>{</p>
<p class="p1"><span class="Apple-converted-space">        </span>title: "關卡三：強權衰落的時機 ⏳",</p>
<p class="p1"><span class="Apple-converted-space">        </span>identity: "⚔️ 二戰剛結束時的殖民地反抗軍",</p>
<p class="p1"><span class="Apple-converted-space">        </span>scenario: "1945年二戰結束了。你的宗主國（如英國、法國）雖然贏了戰爭，但國內城市一片廢墟、財政破產、軍隊傷亡慘重，連自己國家重建的錢都拿不出來。",</p>
<p class="p1"><span class="Apple-converted-space">        </span>hint: "💡 思考引導：過去宗主國靠強大的軍力與財力壓制你們。現在這個「巨人」受了重傷、虛弱不堪。如果你們一直渴望獨立，這時候會怎麼做？💭",</p>
<p class="p1"><span class="Apple-converted-space">        </span>options: [</p>
<p class="p1"><span class="Apple-converted-space">            </span>{ text: "[A] 🚀「敵人最虛弱的時候，就是我們最佳的機會！趁他們無力維持統治，全面推動獨立！」", correct: true, feedback: "✅ 正確引導：這就是二戰後全球爆發「非殖民地化」的主因！" },</p>
<p class="p1"><span class="Apple-converted-space">            </span>{ text: "[B] 😭「宗主國好可憐，我們應該主動交更多稅來幫他們重建軍隊。」", correct: false, feedback: "❌ 不符合被殖民者的立場" },</p>
<p class="p1"><span class="Apple-converted-space">            </span>{ text: "[C] 😰「宗主國雖然衰弱了，但一定會變得比以前更可怕，我們應該放棄希望。」", correct: false, feedback: "❌ 不符合軍力對比的理性判斷" },</p>
<p class="p1"><span class="Apple-converted-space">            </span>{ text: "[D] 💤「我們應該靜靜等待50年，等宗主國恢復強大後再問問看能不能獨立。」", correct: false, feedback: "❌ 錯失歷史良機" }</p>
<p class="p1"><span class="Apple-converted-space">        </span>],</p>
<p class="p1"><span class="Apple-converted-space">        </span>truth: "🧠 歷史真相解密：【歷史為什麼這樣發生？】打敗殖民者的關鍵往往不是我們突然變強了，而是統治我們的強權衰落了！二戰讓西方列強元氣大傷，無力再負擔海外軍事開支，亞非人民正是抓住了這個歷史空檔成功翻身。🎯"</p>
<p class="p1"><span class="Apple-converted-space">    </span>},</p>
<p class="p1"><span class="Apple-converted-space">    </span>{</p>
<p class="p1"><span class="Apple-converted-space">        </span>title: "關卡四：要順從還是要合作？ 🤝",</p>
<p class="p1"><span class="Apple-converted-space">        </span>identity: "🇵🇭 戰後面臨抉擇的菲律賓領袖",</p>
<p class="p1"><span class="Apple-converted-space">        </span>scenario: "二戰剛結束，你的國家滿目瘡痍。宗主國美國跑來對你說：「我可以給你們正式獨立，也可以給你們幾億美元重建家園，但條件是獨立後美軍要繼續留在這裡開基地，美國商人要享有特權。」",</p>
<p class="p1"><span class="Apple-converted-space">        </span>hint: "💡 思考引導：一邊是「什麼都沒有的純粹自由（但人民可能餓死）」，另一邊是「接受一些不平等條件，換取國家活下去的錢與安全保障」。如果你是領袖，你會怎麼權衡？💭",</p>
<p class="p1"><span class="Apple-converted-space">        </span>options: [</p>
<p class="p1"><span class="Apple-converted-space">            </span>{ text: "[A] 💣「寧可所有人餓死，也絕對不拿美國一分錢，立刻對美國宣戰！」", correct: false, feedback: "❌ 過於極端，非菲律賓當時的選擇" },</p>
<p class="p1"><span class="Apple-converted-space">            </span>{ text: "[B] 🙇‍♂️「我們不要獨立了，請美國永遠把我們當成奴隸管轄。」", correct: false, feedback: "❌ 違背獨立初衷" },</p>
<p class="p1"><span class="Apple-converted-space">            </span>{ text: "[C] ⛓️「把所有美國人關進監獄，並宣布我們是歐洲的一部分。」", correct: false, feedback: "❌ 邏輯混亂" },</p>
<p class="p1"><span class="Apple-converted-space">            </span>{ text: "[D] 🏗️「為了讓國家能在戰後生存下去，先接受這些條件換取援助與安全，一步一步實現和平獨立。」", correct: true, feedback: "✅ 正確引導：這就是「宗主國扶植模式」的背後考量！" }</p>
<p class="p1"><span class="Apple-converted-space">        </span>],</p>
<p class="p1"><span class="Apple-converted-space">        </span>truth: "🧠 歷史真相解密：【歷史為什麼這樣發生？】獨立不只是打仗，還要考慮「獨立後怎麼活下去」。菲律賓選擇了「與宗主國協商合作」的路線（扶植模式），雖然讓渡了部分特權，但也換取了和平過渡與經濟重建的資源。🎯"</p>
<p class="p1"><span class="Apple-converted-space">    </span>},</p>
<p class="p1"><span class="Apple-converted-space">    </span>{</p>
<p class="p1"><span class="Apple-converted-space">        </span>title: "關卡五：被逼上絕路的抉擇 🛡️",</p>
<p class="p1"><span class="Apple-converted-space">        </span>identity: "🇻🇳 1950年代的越南抗爭者",</p>
<p class="p1"><span class="Apple-converted-space">        </span>scenario: "戰後，有些宗主國（如英國）願意坐下來談判讓殖民地獨立；但你們的宗主國（法國）態度極度強硬，甚至派武裝軍隊開槍鎮壓你們的和平遊行，堅持要永久統治你們。",</p>
<p class="p1"><span class="Apple-converted-space">        </span>hint: "💡 思考引導：當和平談判的大門被宗主國用槍砲徹底鎖死時，身為不想再當奴隸的被殖民者，你們最後只剩下哪一條路可以走？💭",</p>
<p class="p1"><span class="Apple-converted-space">        </span>options: [</p>
<p class="p1"><span class="Apple-converted-space">            </span>{ text: "[A] 🔫「既然和平談判無望，宗主國用暴力對待我們，我們只能拿起武器發動『武裝鬥爭』！」", correct: true, feedback: "✅ 正確引導：這解釋了為什麼越南/印尼會爆發血腥獨立戰爭！" },</p>
<p class="p1"><span class="Apple-converted-space">            </span>{ text: "[B] 🙇‍♀️「既然宗主國開槍了，那我們就乖乖聽話，永遠不再要求獨立。」", correct: false, feedback: "❌ 忽略了長期積壓的民族憤怒" },</p>
<p class="p1"><span class="Apple-converted-space">            </span>{ text: "[C] ✉️「我們應該寫信請宗主國的國王懲罰這些軍隊。」", correct: false, feedback: "❌ 天真且不切實際" },</p>
<p class="p1"><span class="Apple-converted-space">            </span>{ text: "[D] 🌊「我們應該集體放棄這片土地，搬到海洋中間生活。」", correct: false, feedback: "❌ 無法解決現實問題" }</p>
<p class="p1"><span class="Apple-converted-space">        </span>],</p>
<p class="p1"><span class="Apple-converted-space">        </span>truth: "🧠 歷史真相解密：【歷史為什麼這樣發生？】獨立的方式（和平談判還是流血戰爭）往往取決於宗主國的態度！當荷蘭、法國等國選擇用軍事鎮壓時，被殖民者被逼無可逼，最終只能爆發慘烈的武裝獨立戰爭（如越南反法戰爭）。🎯"</p>
<p class="p1"><span class="Apple-converted-space">    </span>},</p>
<p class="p1"><span class="Apple-converted-space">    </span>{</p>
<p class="p1"><span class="Apple-converted-space">        </span>title: "關卡六：內部矛盾爆發 🕌",</p>
<p class="p1"><span class="Apple-converted-space">        </span>identity: "🇮🇳 英屬印度的普通民眾",</p>
<p class="p1"><span class="Apple-converted-space">        </span>scenario: "英國終於答應讓英屬印度獨立了！但就在這時，你們內部爆發了嚴重的衝突：佔多數的印度教徒希望能建立一個統一的大國；但佔少數的穆斯林極度害怕：「獨立後，我們會在政治上被多數人壓迫，失去我們的宗教自由！」",</p>
<p class="p1"><span class="Apple-converted-space">        </span>hint: "💡 思考引導：當共同的敵人（英國）即將離開，內部兩個不同信仰的族群又互不信任、害怕被對方壓迫時，這塊土地很可能會發生什麼事？💭",</p>
<p class="p1"><span class="Apple-converted-space">        </span>options: [</p>
<p class="p1"><span class="Apple-converted-space">            </span>{ text: "[A] 🕊️「大家會立刻抱在一起，所有宗教矛盾一秒鐘內完全消失。」", correct: false, feedback: "❌ 過度理想化，忽略現實恐懼" },</p>
<p class="p1"><span class="Apple-converted-space">            </span>{ text: "[B] 🗺️「如果無法建立互信，為了避免內部陷入長期的血腥內戰，最終可能走向『拆分國家（分治）』。」", correct: true, feedback: "✅ 正確引導：這就是印度與巴基斯坦分治的歷史原因！" },</p>
<p class="p1"><span class="Apple-converted-space">            </span>{ text: "[C] 🇬🇧「所有人民會一致請求英國軍隊永遠留下來統治他們。」", correct: false, feedback: "❌ 忽略了大家依然想擺脫殖民的心態" },</p>
<p class="p1"><span class="Apple-converted-space">            </span>{ text: "[D] 🙈「穆斯林會決定全部放棄自己的宗教信仰。」", correct: false, feedback: "❌ 不符合宗教與文化現實" }</p>
<p class="p1"><span class="Apple-converted-space">        </span>],</p>
<p class="p1"><span class="Apple-converted-space">        </span>truth: "🧠 歷史真相解密：【歷史為什麼這樣發生？】抗爭時大家有共同敵人（宗主國），但勝利即將到來時，內部的種族與宗教矛盾就會浮上台面。印度與巴基斯坦的分治（以及後來新加坡被逐出馬來西亞），都是因為內部缺乏信任而發生的悲劇。🎯"</p>
<p class="p1"><span class="Apple-converted-space">    </span>},</p>
<p class="p1"><span class="Apple-converted-space">    </span>{</p>
<p class="p1"><span class="Apple-converted-space">        </span>title: "關卡七：獨立後的真正主權 🚢",</p>
<p class="p1"><span class="Apple-converted-space">        </span>identity: "🇪🇬 1956年的埃及總統納薩",</p>
<p class="p1"><span class="Apple-converted-space">        </span>scenario: "你的國家（埃及）在名義上已經獨立了，但你發現橫貫你們國土、最賺錢的「蘇彝士運河」，所有的門票收入和控制權依然握在舊宗主國（英、法）的手裡，你們國家一分錢好處都拿不到。",</p>
<p class="p1"><span class="Apple-converted-space">        </span>hint: "💡 思考引導：如果一個國家的核心財產與戰略要道依然被外國控制，這算不算「真正的完全獨立」？身為國家領袖，你想實現真正的獨立，你必須做什麼？💭",</p>
<p class="p1"><span class="Apple-converted-space">        </span>options: [</p>
<p class="p1"><span class="Apple-converted-space">            </span>{ text: "[A] 🎁「把運河免費送給西方列強，並感謝他們的照顧。」", correct: false, feedback: "❌ 損害國家主權" },</p>
<p class="p1"><span class="Apple-converted-space">            </span>{ text: "[B] 🙈「只要名義上叫獨立國家就好了，錢給外國賺沒關係。」", correct: false, feedback: "❌ 這叫傀儡政權，非真正獨立" },</p>
<p class="p1"><span class="Apple-converted-space">            </span>{ text: "[C] 🔐「把運河的控制權強勢收回國有！只有掌握自己的經濟命脈，才算真正的完全獨立！」", correct: true, feedback: "✅ 正確引導：這就是埃及收回運河控制權的理由！" },</p>
<p class="p1"><span class="Apple-converted-space">            </span>{ text: "[D] 💥「把運河炸毀，讓誰都無法使用。」", correct: false, feedback: "❌ 損人不利己" }</p>
<p class="p1"><span class="Apple-converted-space">        </span>],</p>
<p class="p1"><span class="Apple-converted-space">        </span>truth: "🧠 歷史真相解密：【歷史為什麼這樣發生？】政治獨立只是第一步，經濟自主才是完全獨立的關鍵！埃及納薩總統收回蘇彝士運河，代表著亞非國家不再任由西方搾取資源，給了全非洲獨立運動極大的信心。🎯"</p>
<p class="p1"><span class="Apple-converted-space">    </span>},</p>
<p class="p1"><span class="Apple-converted-space">    </span>{</p>
<p class="p1"><span class="Apple-converted-space">        </span>title: "關卡八：團結就是力量 🌍",</p>
<p class="p1"><span class="Apple-converted-space">        </span>identity: "🇬🇭 1950年代剛獨立的非洲領袖恩克魯瑪",</p>
<p class="p1"><span class="Apple-converted-space">        </span>scenario: "你領導加納成為非洲第一個獨立的黑人國家。但你看向四周，發現非洲大部分地區依然被西方列強分割統治，各個擊破。",</p>
<p class="p1"><span class="Apple-converted-space">        </span>hint: "💡 思考引導：單一一個小國的力量非常微弱，隨時可能被西方強國用經濟或軍事手段重新控制。如果你想保住自己的獨立，並幫其他非洲兄弟擺脫殖民，你應該倡導什麼觀念？💭",</p>
<p class="p1"><span class="Apple-converted-space">        </span>options: [</p>
<p class="p1"><span class="Apple-converted-space">            </span>{ text: "[A] ✊🏿「提倡『非洲屬於非洲人』！全非洲被壓迫的民族必須團結起來（泛非主義），互相支援獨立！」", correct: true, feedback: "✅ 正確引導：這促成了1960『非洲獨立年』與非洲統一組織！" },</p>
<p class="p1"><span class="Apple-converted-space">            </span>{ text: "[B] 🙈「告訴大家每個國家管好自己就好，別人死活與我們無關。」", correct: false, feedback: "❌ 容易被強權各個擊破" },</p>
<p class="p1"><span class="Apple-converted-space">            </span>{ text: "[C] 🙇‍♂️「建議其他非洲國家主動請歐洲人來重新殖民。」", correct: false, feedback: "❌ 背離獨立運動精神" },</p>
<p class="p1"><span class="Apple-converted-space">            </span>{ text: "[D] 🚪「宣佈加納是歐洲的一部分，切斷與非洲同胞的聯繫。」", correct: false, feedback: "❌ 邏輯混亂" }</p>
<p class="p1"><span class="Apple-converted-space">        </span>],</p>
<p class="p1"><span class="Apple-converted-space">        </span>truth: "🧠 歷史真相解密：【歷史為什麼這樣發生？】弱者要對抗強權，唯一的武器就是團結！恩克魯瑪提出的「泛非主義」激發了全非洲的陣營意識，最終在1960年爆發了17國集體獨立的「非洲獨立年」。🎯"</p>
<p class="p1"><span class="Apple-converted-space">    </span>},</p>
<p class="p1"><span class="Apple-converted-space">    </span>{</p>
<p class="p1"><span class="Apple-converted-space">        </span>title: "關卡九：什麼是「第幾世界」？ 🌐",</p>
<p class="p1"><span class="Apple-converted-space">        </span>identity: "🧭 1950年代冷戰中的新獨立國家領袖",</p>
<p class="p1"><span class="Apple-converted-space">        </span>scenario: "二戰後全球進入「冷戰」。世界上有兩大超級強權：1. 第一世界：美國與其資本主義陣營朋友。 2. 第二世界：蘇聯與其社會主義陣營朋友。",</p>
<p class="p1"><span class="Apple-converted-space">        </span>hint: "💡 思考引導：你們這些剛剛擺脫西方殖民、經濟落後但渴望自由的亞、非、拉美新獨立國家，既不想當第一世界，也不想當第二世界。你們應該怎麼稱呼自己這個「第三種力量」？💭",</p>
<p class="p1"><span class="Apple-converted-space">        </span>options: [</p>
<p class="p1"><span class="Apple-converted-space">            </span>{ text: "[A] 👑「我們是『超級第一世界』，因為我們比美蘇加起來還強大。」", correct: false, feedback: "❌ 不符合戰後經濟落後的現實" },</p>
<p class="p1"><span class="Apple-converted-space">            </span>{ text: "[B] 👻「我們不屬於任何世界，因為我們根本不存在於地球上。」", correct: false, feedback: "❌ 荒謬選項" },</p>
<p class="p1"><span class="Apple-converted-space">            </span>{ text: "[C] 🌾「我們是『第三世界』！代表著美、蘇兩大陣營之外，所有新興的發展中國家！」", correct: true, feedback: "✅ 正確引導：推導出『第三世界』概念的由來！" },</p>
<p class="p1"><span class="Apple-converted-space">            </span>{ text: "[D] 🛡️「我們應該自稱是『宗主國預備隊』。」", correct: false, feedback: "❌ 邏輯不通" }</p>
<p class="p1"><span class="Apple-converted-space">        </span>],</p>
<p class="p1"><span class="Apple-converted-space">        </span>truth: "🧠 歷史真相解密：【歷史為什麼這樣發生？】「第三世界」這個詞誕生於冷戰時期。它不是指等級低下，而是指在第一世界（美）與第二世界（蘇）競爭之外，廣大亞非拉美新獨立、追求自主的發展中國家！🎯"</p>
<p class="p1"><span class="Apple-converted-space">    </span>},</p>
<p class="p1"><span class="Apple-converted-space">    </span>{</p>
<p class="p1"><span class="Apple-converted-space">        </span>title: "關卡十：我們最想要什麼？ 🕊️",</p>
<p class="p1"><span class="Apple-converted-space">        </span>identity: "🕊️ 1961年參加「不結盟運動」的第三世界代表",</p>
<p class="p1"><span class="Apple-converted-space">        </span>scenario: "你來到南斯拉夫參加會議。此時美國和蘇聯都帶著大筆鈔票和武器來拉攏你們，要你們選邊站，甚至要你們允許他們在你們土地上建核武器基地。",</p>
<p class="p1"><span class="Apple-converted-space">        </span>hint: "💡 思考引導：你們的國家被外國強權控制和統治了幾百年，好不容易才搶回自由。現在美蘇兩個大霸權又逼你們選邊站，你們現在最想要的是什麼？你們還會想捲入大國的戰爭嗎？💭",</p>
<p class="p1"><span class="Apple-converted-space">        </span>options: [</p>
<p class="p1"><span class="Apple-converted-space">            </span>{ text: "[A] 🇺🇸「我們最想要的是立刻加入美國陣營，幫美國去攻打蘇聯。」", correct: false, feedback: "❌ 再次淪為大國棋子，違背同理心" },</p>
<p class="p1"><span class="Apple-converted-space">            </span>{ text: "[B] 🛠️「我們最想要的是立刻加入蘇聯陣營，把國家主權全交給蘇聯。」", correct: false, feedback: "❌ 再次失去主權，違背同理心" },</p>
<p class="p1"><span class="Apple-converted-space">            </span>{ text: "[C] ⛓️「我們最想要的是請美蘇兩國再次來瓜分殖民我們。」", correct: false, feedback: "❌ 違背歷史同理心" },</p>
<p class="p1"><span class="Apple-converted-space">            </span>{ text: "[D] 🕊️「我們最想要的是『真正的自主與和平』！堅持『不結盟』，絕不當大國的棋子或軍事基地！」", correct: true, feedback: "✅ 正確引導：這就是『不結盟運動』與『新國際經濟秩序』的核心！" }</p>
<p class="p1"><span class="Apple-converted-space">        </span>],</p>
<p class="p1"><span class="Apple-converted-space">        </span>truth: "🧠 歷史真相解密：【歷史為什麼這樣發生？】被控制太久的人，最珍惜的就是「自己作主」！不結盟運動的成立，就是第三世界國家集體向美蘇大國說「不」：我們不結盟、不捲入冷戰，我們要專心發展自己的經濟，維護自己的天然資源！🎯"</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1">];</p>
<p class="p2"><br></p>
<p class="p1">let currentStage = 0;</p>
<p class="p2"><br></p>
<p class="p1">function renderStage() {</p>
<p class="p1"><span class="Apple-converted-space">    </span>const data = gameData[currentStage];</p>
<p class="p1"><span class="Apple-converted-space">    </span>document.getElementById('stage-title').innerText = data.title;</p>
<p class="p1"><span class="Apple-converted-space">    </span>document.getElementById('identity').innerText = data.identity;</p>
<p class="p1"><span class="Apple-converted-space">    </span>document.getElementById('scenario-text').innerText = data.scenario;</p>
<p class="p1"><span class="Apple-converted-space">    </span>document.getElementById('hint-text').innerText = data.hint;</p>
<p class="p1"><span class="Apple-converted-space">    </span>document.getElementById('progress').style.width = `${((currentStage + 1) / gameData.length) * 100}%`;</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>const container = document.getElementById('options-container');</p>
<p class="p1"><span class="Apple-converted-space">    </span>container.innerHTML = '';</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>data.options.forEach((opt) =&gt; {</p>
<p class="p1"><span class="Apple-converted-space">        </span>const btn = document.createElement('button');</p>
<p class="p1"><span class="Apple-converted-space">        </span>btn.className = 'option-btn';</p>
<p class="p1"><span class="Apple-converted-space">        </span>btn.innerText = opt.text;</p>
<p class="p1"><span class="Apple-converted-space">        </span>btn.onclick = () =&gt; handleAnswer(opt, data.truth);</p>
<p class="p1"><span class="Apple-converted-space">        </span>container.appendChild(btn);</p>
<p class="p1"><span class="Apple-converted-space">    </span>});</p>
<p class="p1">}</p>
<p class="p2"><br></p>
<p class="p1">function handleAnswer(option, truthText) {</p>
<p class="p1"><span class="Apple-converted-space">    </span>const modal = document.getElementById('modal');</p>
<p class="p1"><span class="Apple-converted-space">    </span>const modalTitle = document.getElementById('modal-title');</p>
<p class="p1"><span class="Apple-converted-space">    </span>const modalBody = document.getElementById('modal-body');</p>
<p class="p1"><span class="Apple-converted-space">    </span>const modalBtn = document.getElementById('modal-next-btn');</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>modal.style.display = 'flex';</p>
<p class="p2"><br></p>
<p class="p1"><span class="Apple-converted-space">    </span>if (option.correct) {</p>
<p class="p1"><span class="Apple-converted-space">        </span>modalTitle.innerText = "💥 思考推理成功！";</p>
<p class="p1"><span class="Apple-converted-space">        </span>modalTitle.style.color = "#004AAD";</p>
<p class="p1"><span class="Apple-converted-space">        </span>modalBody.innerHTML = `&lt;b&gt;${option.feedback}&lt;/b&gt;&lt;br&gt;&lt;br&gt;${truthText}`;</p>
<p class="p2"><span class="Apple-converted-space">        </span></p>
<p class="p1"><span class="Apple-converted-space">        </span>modalBtn.innerText = currentStage &lt; gameData.length - 1 ? "進入下一關 ➔" : "通關！檢視歷史成效 🎉";</p>
<p class="p1"><span class="Apple-converted-space">        </span>modalBtn.onclick = () =&gt; {</p>
<p class="p1"><span class="Apple-converted-space">            </span>modal.style.display = 'none';</p>
<p class="p1"><span class="Apple-converted-space">            </span>if (currentStage &lt; gameData.length - 1) {</p>
<p class="p1"><span class="Apple-converted-space">                </span>currentStage++;</p>
<p class="p1"><span class="Apple-converted-space">                </span>renderStage();</p>
<p class="p1"><span class="Apple-converted-space">            </span>} else {</p>
<p class="p1"><span class="Apple-converted-space">                </span>showFinalScreen();</p>
<p class="p1"><span class="Apple-converted-space">            </span>}</p>
<p class="p1"><span class="Apple-converted-space">        </span>};</p>
<p class="p1"><span class="Apple-converted-space">    </span>} else {</p>
<p class="p1"><span class="Apple-converted-space">        </span>modalTitle.innerText = "⚠️ 推理遇到瓶頸";</p>
<p class="p1"><span class="Apple-converted-space">        </span>modalTitle.style.color = "#FF3131";</p>
<p class="p1"><span class="Apple-converted-space">        </span>modalBody.innerHTML = `&lt;b&gt;${option.feedback}&lt;/b&gt;&lt;br&gt;&lt;br&gt;請重新站在當時被殖民者或領袖的角度再試一次！`;</p>
<p class="p2"><span class="Apple-converted-space">        </span></p>
<p class="p1"><span class="Apple-converted-space">        </span>modalBtn.innerText = "重新選擇 🔄";</p>
<p class="p1"><span class="Apple-converted-space">        </span>modalBtn.onclick = () =&gt; {</p>
<p class="p1"><span class="Apple-converted-space">            </span>modal.style.display = 'none';</p>
<p class="p1"><span class="Apple-converted-space">        </span>};</p>
<p class="p1"><span class="Apple-converted-space">    </span>}</p>
<p class="p1">}</p>
<p class="p2"><br></p>
<p class="p1">function showFinalScreen() {</p>
<p class="p1"><span class="Apple-converted-space">    </span>document.querySelector('.game-card').innerHTML = `</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;div style="text-align: center; padding: 20px;"&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;h1 style="color: var(--comic-blue); font-size: 2.2rem;"&gt;🎉 恭喜通關！建國成功！&lt;/h1&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;p style="font-size: 1.2rem; line-height: 1.8;"&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>你已經順利完成了 10 個關鍵歷史抉擇。&lt;br&gt;</p>
<p class="p1"><span class="Apple-converted-space">                </span>歷史不是死記硬背，而是理解人民為何在特定時空下做出這些抉擇！</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;/p&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;div style="font-size: 4rem; margin: 20px 0;"&gt;🌍🕊️✊🏿&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">            </span>&lt;button class="modal-btn" onclick="location.reload()"&gt;再玩一次 🔄&lt;/button&gt;</p>
<p class="p1"><span class="Apple-converted-space">        </span>&lt;/div&gt;</p>
<p class="p1"><span class="Apple-converted-space">    </span>`;</p>
<p class="p1">}</p>
<p class="p2"><br></p>
<p class="p1">// 首次渲染</p>
<p class="p1">renderStage();</p>
<p class="p1">&lt;/script&gt;</p>
<p class="p2"><br></p>
<p class="p1">&lt;/body&gt;</p>
<p class="p1">&lt;/html&gt;</p>
</body>
</html>
