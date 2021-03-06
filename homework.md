![George Stibitz](https://history-computer.com/ModernComputer/Relays/images/stibitz_portrait2.jpg "George Stibitz")
# **喬治．斯特比茲的中繼式計算機**
可憐的爆肝不專業翻譯：Stefan L  [點擊查看原文](https://history-computer.com/ModernComputer/Relays/Stibitz.html)

  ---
西元1925年，貝爾系統增設了 __「貝爾電話實驗室公司」__ 作為基礎研究機構，因而開始了一個堪稱「物理、化學等現代科技領域相關的基礎和精彩研究的前沿」的機構。在這精彩的地方竟在接下來的幾十年做了許多研究，將許多發明家推上了諾貝爾的領獎台。許多資訊科技領域的發明也是在這裡完成的，如最初的邏輯模型 __「二極體」__(1942年)和 __「觸點式電晶體」__(1947年)、第一座 __「全電晶體電腦」__ (TRADIC) (1955年)、第一座 __「數據機」__ (1960年)、第一座 __「單晶片微電腦」__(1980年)、 __「UNIX作業系統」__(1969年)、 __「C語言」__(1973年)和　__「C++語言」__(1983年)等。

![George Stibitz](https://history-computer.com/ModernComputer/Relays/images/ModelKStibitz.jpg "George Stibitz")

1937年十一月的某個傍晚，一位數學家兼研究人員 __喬治．斯特比茲__ 離開了工作崗位，從貝爾公司的倉庫帶走了兩座電話繼電器、一些手電筒的燈泡、一條電線和一顆電池，準備回家。回到家，他開始在餐桌前，打算以他帶回來的零件和金屬香菸盒做的開關，組裝一支簡單的邏輯裝置。不一會兒，他就做出了第一支 __中繼式二進位加法器__ ，以亮燈代表二進位數據中的「1」，而以不亮的燈代表「0」。他的妻子朵洛瑟雅以「餐桌」(kitchen table)　將裝置命名為「模型K」(The K-model)。隔天，斯特比茲太太到了丈夫的公司向同事展示了模型K，同事們就預測以繼電裝置組裝出一座計算機的可能性不低。他們表示，現行的任何使用二進式運算的繼電式計算機都需要數百個繼電器，因此比先前實驗室裡使用得商用電子計算機還來得貴，又占空間。

然而斯特比茲意識到的是，中繼式計算機能進行的運算不只是單一的，而是一系列的運算，因為它能運用中繼迴路引導執行的先後順序，以及應需求儲存階段性的運算結果。具體而言，它可以進行一系列運用到複數的乘、除法運算，而這兩種運算是貝爾實驗室中其他所有的研究人員，都經常需要連接長距離迴圈所用到的濾波器和放大器設計，才能進行運算。在1930年代，實驗室裡是由一屋子的人類「運算機」，利用商用電子計算機解複數的商和運算結果。雖然計算過程本身直截了當，但一個複數的乘法運算需要六個簡單的運算程序，一個複數的除法運算則需要十幾個，兩種運算都需要暫存空間來儲存即刻的運算結果。

斯特比茲並不知道，德國工程師康拉德．楚澤同時在柏林也在做幾乎一樣的事情，但斯特比茲是知道美國工程師克勞德．香儂在麻省理工學院當研究生時，也曾運用二進位制中繼式迴圈，研究符號邏輯狀態的對應的。香儂以此為研究論文的論題(1938年出版)，而後來到了貝爾實驗室，在這裡和斯特比茲相互切磋，但香儂並沒有積極的參與斯特比茲計算機的設計。而以繼電器實際運用二進位運算邏輯的想法也在1930年代後期相當普遍，是眾所皆知的。(如在日本有相似的科學發現。)

![George Stibitz](https://history-computer.com/ModernComputer/Relays/images/StibitzTerminalSchema.jpg "George Stibitz")
示意圖為複數計算機的電傳印字機。

斯特比茲首次向行政主管展示他的模型K運算機時，他們並沒有很滿意。沒有煙火，沒有香檳，就算他隨後想到了也沒有。然而不過一年，行政主管就改變了對斯特比茲發明的想法。這個決定中很重要的因素是，貝爾公司對於要找到對逐漸增加的複數數學問題的解決方法的壓力愈來愈大。公司同意以資金支助建造一台很大的斯特比茲發明的實驗模型。斯特比茲在1938年二月就完成了他的設計，四月份就讓貝爾公司的一位配電工程師山謬．威廉斯開始建構設計的機器。最終的成品在十月份完成，1940年一月8日首次投入生產，便一直持續運作到1949年。在貝爾實驗室在戰爭期間建造其他中繼式計算機時，名稱從最初的「複數計算機」變為「模型一」，要價兩萬多美元。

起初複數計算機只用來做複數乘、除法的運算，但之後的一些簡單的改版，讓它也能夠做加、減法的運算。它用了約400至450個二進位制繼電器、六至八片面板和十個多方向、多極的，稱作「橫梁」繼電器來暫存數字。這台機器的每個數字一開始都是使用有固定小數點的十進位制系統，從內部來說，透過二進位n+3的編碼，使用一個代表十進位小數我們稱之為n的編碼來使每個二進位的中繼將每個小數/數據編碼。這是簡化小數/數據承載及減法問題。(excess-three二進位小數編碼至今仍叫做Stibitz-code)這機器在他的寄存器中可掌握十個數據，但表現及顯示出來的答案則是八個數據(範圍??0.99999999)。舉裡來說，要將兩組複數(2+3i)及(4+5i)相成，操作員會先輸入(可見於上方鍵盤圖片):   M +.2 +i .3 +.4 -i .5 =
M帶表乘法(鍵盤中的D代表分配除法)注意小數在每個四位數前的位置。機器通常會做(0.3+0.5i) x (0.4-0.2i)的運算，然後答案顯示0.07000000+i 0.22000000。操作者需要根據結果(乘上100)去規範。一個簡單的相加運算需耗時100微秒，然而相乘2個複數需要45秒。

![George Stibitz](https://history-computer.com/ModernComputer/Relays/images/StibitzTerminal.jpg "George Stibitz")

計算單位是個特別的終端，有四個暫存器，且和輸入和輸出單位是完全分開的不同單位(見上圖)。計算機本體置於實驗室的隔離房間內，因此看過的人很少。操作員以三台改造過的電傳印字機(鍵盤與列印裝置)中的其中一台遠端遙控，使房裡的計算機運作，再使用多元電路匯流排連接到處理器，最後放到別的地方去，因為無論如何也無法同時運作。

斯特比茲更進一步的將遠端和多重接取的想法放進運算機設計上。1940年九月11日，美國數學學會在位於新罕布夏州漢諾瓦的達特茅斯學院開會，那裡距離位於紐約的貝爾實驗室，也就是複數運算機所在的地方，有幾百英里。斯特比茲安排要用電話線(28線電傳印字機線組)，將複數運算機連上一台安裝在那裡電傳印字機單位。複數運算機運作得很順利，而無疑的讓些用過的人留下了好印象。那場會議有很多美國最著名的數學家參與，包括有些在往後領銜一些中藥的電腦相關企劃，如約翰．馮．諾伊曼、約翰．莫奇利、諾伯特．維納以及加勒特．伯克霍夫。那場達特茅斯演示事件預告了遠端計算的新世代，這種類型的遠端存取技術在接下來的十年都沒有重現過。

![George Stibitz](https://history-computer.com/ModernComputer/Relays/images/CNCofStibitz.jpg "George Stibitz")

複數運算機無法用程式控制，而是由繼電迴圈組長久的控制它的運作順序。那些繼電器和一些處理數字的繼電器一樣，但處理數字的繼電器沒有用來「控制」運算順序的分開、清楚的部分。(之後貝爾實驗室的運算機就有了。)在複數運算機發明後，建造者發現它基礎的運算元素過度的被和控制迴圈的融合體約束，直綁著做複數運算，因此程式控制的概念在貝爾實驗室產生了。(提到複雜的運算，他們世著讓運算機做多項式運算，也就是複數運算的特殊狀況，但機器被約束得無法進行。)

複數運算機的成功激勵了斯特比茲提出更多有以打孔紙帶控制計算機運算的功能的，大膽嘗試的設計。起初實驗室打回了他的提案，但隨著1941年十二月二戰美國參戰，貝爾實驗室將研究重心轉移到軍事的企劃上，而軍事企劃包含比在和平時代的研究更多的運算。雖實驗室在戰爭時代的成果大多是關於類比電腦的研發，但他們也為了軍事的需求，建造了五台中繼式數位運算器，戰後又應內部需求建造了一台，加上複數運算機，一共建造了七台中繼事數位運算器。

其中第一個軍用的計算機是1943年在華盛頓特區安裝的 **中繼式內插電路**，也就是之後聞名的「模型二」。它是以440個繼電器和容納的下七個數字的記憶體容量建造而成的，以一個式子四秒的速度做乘法運算(利用重複加成的方式)。它主要是用來解關於指揮防空用軍火的問題的，而它也以用紙膠帶向機器提供的插入功能值執行一系列的運算獲得了成功。它就像複數運算機一樣，是有特別用途的機器，但它的運算順序並不像中繼式計算機那樣永久的以電線建構，而是以 __「公式膠帶」__(五道式紙膠帶)黏成一個迴圈，因此不同的膠帶即可利用不同解法的插件。模型二除了插件外，並沒有很多用處，但基於插件是讓機器解決許多科學和工程上問題的途徑，這台機器在戰後的其他政府機關也持續的在運作。

接下來的兩臺由斯蒂比茨設計的機器是彈道計算機和誤差檢測器Mark22(後稱爲Model III和IV)是相同的機器,這是1944年安裝在德克薩斯州布利斯堡,1945年初安裝的第二臺機器(每臺售價65000美元)。 它們有大約1400個繼電器,內存容量爲10個。 乘法速度爲1秒(用表格查找法乘法)。 這些機器還使用紙帶進行數據和公式輸入,由一圈紙帶提供算術序列。 模型三和模型四與模型二一樣,也解決了與高射炮瞄準和跟蹤有關的問題。 然而,它們是更復雜的機器,它不僅能夠進行插值,而且能夠評價描述目標飛機和高射彈殼路徑的彈道方程。 一種附加的紙帶,指示機器哪些功能是用來評估的。 因此,Model III和N是貝爾實驗室數字計算器中第一個具有一定程度的一般程序可操作性的,儘管兩者都不是完全通用計算器。 他們的存儲器和算術單位具有適中的能力:精確度只有6個十進制數字,每臺機器的存儲器只有10個數字。

系列中最大的一臺,也是最後一臺由斯蒂比茨設計的,是型號V,其中貝爾實驗室在1946年和1947年爲軍方建造了兩臺複印機。 那是一臺巨大的(重10噸)和非常昂貴的(50萬美元)機器。 每臺都裝有9000多個繼電器和處理用科學記數表示的數字。 這家商店最多能容納30個數字,紙帶閱讀器可以同時輸入程序步驟和數字數據。 倍增速度0.8秒。 模型V的設計最有趣的是它有兩個獨立的算術單元,每個算術單元都能夠作爲獨立的計算機運行,擁有自己的內存寄存器和輸入輸出設備。 小規模的問題可以在機器上成雙地運行,節省時間,而更大的問題可以接管這兩個處理器。 每個處理器(使用現代術語)有15個內存寄存器,整臺機器總共30個。 主控制單元根據可用性向一個或兩個處理器下達指令。 這個控制裝置與處理器的控制裝置是分開的,這些控制裝置指示了算術,存儲器和輸入輸出操作的順序;可以說它控制了控制(斯蒂比茨稱之爲"超級分支"功能)。 因此,從非常實際的意義上說,V型車擁有一個現在稱爲"操作系統"的控制系統,即一個監督和管理計算機工作流量的控制單元。

除了編程能力外,後來的貝爾計算機還強調非常可靠。 作爲邏輯和存儲器操作的基本元素的繼電器有間歇失效的趨勢。 如果兩個繼電器接點之間有一塊灰塵,電路就會失效,儘管其餘的繼電器都正常。 幾周後,塵埃顆粒會自行鬆動,然後一切就會恢復正常。 因此,在診斷會話中,沒有出現任何機器故障,整個計算可能就大打折扣了。

貝爾的工程師們設計出能在每個運算步驟自我檢測的電腦循環。循環的被設計出來，不只在加、減、儲存數字等之外，他們也負責檢查那些操作是否正確，並阻止機器繼續執行。貝爾的工程師們也被設計電話循環的經驗所引領，這項設計必須長時間在無人看管的惡劣環境下作業。這些循環是被設計來讓半成熟/未成熟的技術員修復的。若每次電話線或電話出問題時都要請工程師前來，電話循環服務會是極大的成本。貝爾實驗室模型2到6都使用7個而非4個二進位的中繼設備來編每個小數的碼。他們被分為2和7，兩組中繼設備。小數編碼如以下：

 |Decimal digit|Relays| |
 |-------------|----------|--------:|
0|01|00001
1|01|00010
2|01|00100
3|01|01000
4|	01|	10000
5|	10|	00001
6|	10|	00010
7|	10|	00100
8|	10|	01000
9|	10|	10000

由於(the relays)中繼設備有  一或五  ，所以貝爾實驗室便稱這系統為一個”bi-quinary”符號。事實上他並非為最基本的數字所組成的，而是由7位元的混合十進位程式碼。所有貝爾實驗室的中繼電腦都以十進位(進行)算數/演算/運算。有一種特別的循環會去檢查/驗算那兩個中繼設備是否觸發/刺激各十進位元/十進位數。另一個循環會檢查/驗算在每個群體中唯一啟動的電腦中繼，以夠避免兩個分開的錯誤相互抵銷不過仍有一些不正常錯誤的組合仍未被發現。

---
單字參照：

1. incorporate (v.) 包含；將…包括在內
2. synonymous (adj.) 等同的
3. the frontiers of sth 知識領域的前線
4. relay (n.) 繼電器
5. cell (n.) 電池
6. assemble (v.) 組裝
7. consist (v.) 存在
8. speculate (v.) 推斷
9. arithmetic (n.) 運算
10. bulky (adj.) 龐大，占空間
11. circuit (n.) 迴路
12. interim (n.) 過渡時期的
13. roomful (n.) 一屋子的人
14. quotient (n.) (數學)商
15. implement (v.) 實施
16. initial (adj.) 最初的
17. prominent (adj.) 著名的
18. permanent (adj.) 長久，永恆
19. arise (v.) 產生
20. polynomial (adj.) 多項式的
21. capacity (n.) 容量
22. antiaircraft (adj.) 防空的
23. interpolate (v.) 插入
