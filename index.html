<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>263班｜课表（图木舒克职院）</title>
    <style>
        * {margin:0;padding:0;box-sizing:border-box;}
        body{
            font-family:"Microsoft YaHei",system-ui,sans-serif;
            background-color:#edf2fb;
            padding:18px;
        }
        .container{
            max-width:920px;
            margin:0 auto;
            background:#ffffff;
            border-radius:14px;
            padding:24px;
            box-shadow:0 2px 14px #00000018;
        }
        .header{
            text-align:center;
            margin-bottom:22px;
        }
        .header h1{
            font-size:22px;
            color:#1f3b73;
            margin-bottom:8px;
        }
        .timeinfo{
            color:#444;
            font-size:15px;
        }
        .tab-bar{
            display:flex;
            gap:10px;
            margin-bottom:16px;
            justify-content:center;
        }
        .tab-bar button{
            padding:8px 18px;
            border:none;
            border-radius:8px;
            background:#d8e4f8;
            color:#1f3b73;
            font-size:16px;
            cursor:pointer;
        }
        .tab-bar button.active{
            background:#2b5cb8;
            color:#fff;
        }
        .title-today{
            font-size:18px;
            font-weight:bold;
            color:#2b5cb8;
            margin:16px 0 12px;
        }
        .course-block{
            border-left:5px solid #2b5cb8;
            background:#e9f1fc;
            border-radius:8px;
            padding:14px 16px;
            margin-bottom:10px;
        }
        .course-time{
            font-size:14px;
            color:#444;
        }
        .course-name{
            font-size:17px;
            font-weight:600;
            margin:4px 0;
        }
        .course-loc{
            font-size:14px;
            color:#555;
        }
        .empty{
            text-align:center;
            padding:32px;
            color:#777;
            font-size:16px;
        }
        /* 完整周课表表格样式 */
        .week-table-wrap{
            overflow-x:auto;
        }
        .week-table{
            width:100%;
            border-collapse: collapse;
        }
        .week-table th,.week-table td{
            border:1px solid #ccd6e8;
            padding:10px 6px;
            text-align:center;
            font-size:14px;
        }
        .week-table th{
            background:#2b5cb8;
            color:#fff;
        }
        .week-table .today-col{
            background:#e9f1fc;
        }
        .week-table .cell-course{
            font-weight:600;
            color:#1f3b73;
        }
        .week-table .cell-teach{
            font-size:12px;
            color:#444;
        }
        .schedule-box{
            margin-top:26px;
            border-top:1px solid #ccc;
            padding-top:20px;
        }
        .schedule-box h3{
            margin-bottom:12px;
            color:#222;
        }
        .schedule-item{
            display:flex;
            justify-content:space-between;
            padding:7px 0;
            border-bottom:1px solid #eee;
        }
        .view-item{
            display:none;
        }
        .view-item.active{
            display:block;
        }
    </style>
</head>
<body>
<div class="container">
    <div class="header">
        <h1>📚计算机网络技术263班 课表</h1>
        <div class="timeinfo" id="nowTime"></div>
    </div>

    <!-- 切换按钮 -->
    <div class="tab-bar">
        <button class="active" onclick="switchView('day')">📅今日课表</button>
        <button onclick="switchView('week')">📖完整周课表</button>
    </div>

    <!-- 今日课表视图 -->
    <div id="view-day" class="view-item active">
        <div class="title-today" id="weekTitle"></div>
        <div id="courseList"></div>
    </div>

    <!-- 完整周课表视图 -->
    <div id="view-week" class="view-item">
        <div class="week-table-wrap">
            <table class="week-table" id="weekTable">
                <thead>
                    <tr>
                        <th>节次</th>
                        <th>周一</th>
                        <th>周二</th>
                        <th>周三</th>
                        <th>周四</th>
                        <th>周五</th>
                    </tr>
                </thead>
                <tbody>
                </tbody>
            </table>
        </div>
    </div>

    <div class="schedule-box">
        <h3>⏱大一夏季作息时间表</h3>
        <div class="schedule-item"><span>第一节（每日一读）</span><span>09:50—10:40</span></div>
        <div class="schedule-item"><span>第二节</span><span>10:50—11:30</span></div>
        <div class="schedule-item"><span>大课间</span><span>11:30—11:45</span></div>
        <div class="schedule-item"><span>第三节</span><span>11:45—12:25</span></div>
        <div class="schedule-item"><span>第四节</span><span>12:35—13:15</span></div>
        <div class="schedule-item"><span>第五节</span><span>16:00—16:40</span></div>
        <div class="schedule-item"><span>第六节</span><span>16:50—17:30</span></div>
        <div class="schedule-item"><span>第七节</span><span>17:40—18:20</span></div>
        <div class="schedule-item"><span>第八节</span><span>18:30—19:10</span></div>
        <div class="schedule-item"><span>晚自习</span><span>20:30—22:00</span></div>
        <div class="schedule-item"><span>宿舍关门</span><span>23:30</span></div>
        <div class="schedule-item"><span>熄灯</span><span>03:00</span></div>
    </div>
</div>

<script>
/*
weekDay：1周一，2周二，3周三，4周四，5周五，6周六，7周日
节次对应时间：
1‑2节：09:50‑11:30
3‑4节：11:45‑13:15
5‑6节：16:00‑17:30
7‑8节：17:40‑19:10
*/
const courseData = [
    //====周一 weekDay=1====
    {weekDay:1, start:"09:50", end:"11:30", name:"程序设计基础", teacher:"董壮", room:"12‑3‑6机房[40人]"},
    {weekDay:1, start:"11:45", end:"13:15", name:"程序设计基础", teacher:"董壮", room:"12‑3‑6机房[40人]"},
    {weekDay:1, start:"17:40", end:"19:10", name:"应用文写作与口才训练", teacher:"赵敏", room:"一号阶梯教室[40人]"},
    //====周二 weekDay=2====
    {weekDay:2, start:"09:50", end:"11:30", name:"思想道德与法治", teacher:"李响", room:"1‑10西侧阶梯教室[40人]"},
    {weekDay:2, start:"11:45", end:"13:15", name:"高职公共英语一", teacher:"吴茗芝", room:"一号阶梯教室[40人]"},
    {weekDay:2, start:"16:00", end:"17:30", name:"高等数学一", teacher:"康冰雁", room:"一号阶梯教室[40人]"},
    {weekDay:2, start:"17:40", end:"19:10", name:"Windows Server 操作系统应用", teacher:"尚品", room:"12‑3‑8机房[40人]"},
    //====周三 weekDay=3====
    {weekDay:3, start:"09:50", end:"11:30", name:"高等数学一", teacher:"康冰雁", room:"1‑11思政大讲堂[40人]"},
    {weekDay:3, start:"11:45", end:"13:15", name:"大学体育一", teacher:"比拉·赛买提", room:"田径场[40人]"},
    //====周四 weekDay=4====
    {weekDay:4, start:"09:50", end:"11:30", name:"高职公共英语一", teacher:"吴茗芝", room:"1‑11思政大讲堂[40人]"},
    {weekDay:4, start:"11:45", end:"13:15", name:"应用文写作与口才训练", teacher:"赵敏", room:"一号阶梯教室[40人]"},
    {weekDay:4, start:"16:00", end:"17:30", name:"心理健康教育一 / 形势与政策一", teacher:"苏建荣 / 田康生", room:"二号阶梯教室[40人]"},
    {weekDay:4, start:"17:40", end:"19:10", name:"国家安全教育", teacher:"吴鹍", room:"一号阶梯教室[40人]"},
    //====周五 weekDay=5====
    {weekDay:5, start:"09:50", end:"11:30", name:"思想道德与法治", teacher:"李响", room:"1‑3东侧阶梯教室[40人]"},
    {weekDay:5, start:"11:45", end:"13:15", name:"Windows Server 操作系统应用", teacher:"尚品", room:"12‑3‑10机房[40人]"}
];

const weekCN = ["星期日","星期一","星期二","星期三","星期四","星期五","星期六"];
// 节次配置
const timeBlockList = [
    {title:"1-2节", start:"09:50", end:"11:30"},
    {title:"3-4节", start:"11:45", end:"13:15"},
    {title:"5-6节", start:"16:00", end:"17:30"},
    {title:"7-8节", start:"17:40", end:"19:10"},
];

let currentView = "day";
let todayWeekNum;

// 切换视图：今日 / 完整周
function switchView(mode){
    currentView = mode;
    //按钮激活状态
    const btns = document.querySelectorAll(".tab-bar button");
    btns.forEach(b=>b.classList.remove("active"));
    event.target.classList.add("active");
    //视图显示隐藏
    document.getElementById("view-day").classList.remove("active");
    document.getElementById("view-week").classList.remove("active");
    document.getElementById("view-"+mode).classList.add("active");
}

// 渲染完整周课表表格
function renderWeekTable(todayW){
    const tbody = document.querySelector("#weekTable tbody");
    tbody.innerHTML = "";
    timeBlockList.forEach(block=>{
        const tr = document.createElement("tr");
        //第一列 节次
        let tdTime = document.createElement("td");
        tdTime.innerText = block.title;
        tr.appendChild(tdTime);

        //周一到周五循环
        for(let wd=1;wd<=5;wd++){
            let td = document.createElement("td");
            //匹配这个星期+时间段的课程
            const course = courseData.find(c=> c.weekDay===wd && c.start === block.start);
            if(course){
                td.innerHTML = `<div class="cell-course">${course.name}</div><div class="cell-teach">${course.teacher}<br>${course.room}</div>`;
            }else{
                td.innerText = "—";
            }
            //今天的那一列高亮
            if(wd === todayW){
                td.classList.add("today-col");
            }
            tr.appendChild(td);
        }
        tbody.appendChild(tr);
    })
}

function refreshPage(){
    const now = new Date();
    const y = now.getFullYear();
    const m = now.getMonth()+1;
    const d = now.getDate();
    const hh = String(now.getHours()).padStart(2,'0');
    const mm = String(now.getMinutes()).padStart(2,'0');
    const idx = now.getDay();
    // getDay：0=周日 →映射1~7
    todayWeekNum = idx===0?7:idx;
    const wName = weekCN[idx];

    document.getElementById("nowTime").innerText = `${y}年${m}月${d}日 ${hh}:${mm} ${wName}`;
    document.getElementById("weekTitle").innerText = `📅今日：${wName}`;

    //渲染今日课表
    const todayCourses = courseData.filter(x=>x.weekDay === todayWeekNum);
    todayCourses.sort((a,b)=>a.start.localeCompare(b.start));
    const wrap = document.getElementById("courseList");
    wrap.innerHTML="";
    if(todayCourses.length===0){
        wrap.innerHTML = `<div class="empty">🎉今日没有课，可以好好休息！</div>`;
    }else{
        todayCourses.forEach(c=>{
            const div = document.createElement("div");
            div.className = "course-block";
            div.innerHTML = `
                <div class="course-time">⏰ ${c.start} — ${c.end}</div>
                <div class="course-name">${c.name}</div>
                <div class="course-loc">👨‍🏫教师：${c.teacher}｜📍地点：${c.room}</div>
            `;
            wrap.appendChild(div);
        })
    }
    //渲染完整周课表表格
    renderWeekTable(todayWeekNum);
}

refreshPage();
setInterval(refreshPage,1000);
</script>
</body>
</html>
