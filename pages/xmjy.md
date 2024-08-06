# 项目经验

<div>
    <ol>
        <li class="rounded cursor-pointer"  hover="bg-white bg-opacity-10" @click="$slidev.nav.go(7)">
            御芝林-CRM电商系统 (web&小程序) <carbon:arrow-right class="inline"/>
        </li>
        <li class="rounded cursor-pointer"  hover="bg-white bg-opacity-10" @click="$slidev.nav.go(8)">
            云建-BIM管理系统 (web&小程序) <carbon:arrow-right class="inline"/>
        </li>
        <li class="rounded cursor-pointer" hover="bg-white bg-opacity-10" @click="$slidev.nav.go(9)">
            容联-容视视频会议 (web&小程序) <carbon:arrow-right class="inline"/>
        </li>
         <li class="rounded cursor-pointer" hover="bg-white bg-opacity-10" @click="$slidev.nav.go(9)">
            逸金科技-卡易还 (移动端) <carbon:arrow-right class="inline"/>
        </li>
    </ol>
</div>


# 个人作品



---

# 御芝林CRM电商系统

- 技术栈：Vue3、uni-app;
- 项目描述：客户、销售、订单、回款、售后、报表一体化电销管理软件;
- 项目痛点：
  - 技术层面：前端人员技术水平参差不齐，模块较多，无代码规范以及存在依赖版本问题,导致上线困难;
  - 业务层面：一线使用云桌面，配置较低，之前使用监听+轮询的方式来进行状态同步，严重影响性能导致浏览器崩溃;
- 项目业绩：
  - 订阅模式代替监听模式/事件总栈/轮询;
  - 使用 provide/inject 代替 vuex;
  - 动态加载 CTI 外呼 SDK, 解决坐席云电脑浏览器崩溃问题;
  - 封装indexDB,缓存options列表来减少请求次数;
  - 增加tagsview以及缓存解决postmessage导致内存泄漏问题;
  - 增加取消请求,节省服务器资源;

---

# 云建-BIM管理系统
- web
  - 技术栈：Vue2、Three.js、xeogl.js、uni-app;
  - 项目描述：地面施工管理系统，实现了模型轻量化，将工程项目可视化展示和操作等管理功能;
  - 工作业绩：
    - 通过xeogl.js实现模型轻量化，并展示操作工业级别模型,实现标注、高亮、气泡、动画等功能；
    - 通过Three.js来展示操作大场景模型;
    - 通过调用注册表实现打开Revit一键设计模型;
- 小程序
  - 工作业绩：
    - 通过小程序实现多模型展示、筛选、控制等快捷功能;
    - 集成蓝牙测距仪量设备，为工程人员提供便捷的测量和量房操作。
- 鸿蒙 OS 智能手表应用
  - 项目描述：国内首款疲劳检测预测系统;通过对接华为 Health Kit 获得健康数据并进行分析预测;
  - 项目实现：通过 JS FA 开发,实现了量表自测,打卡,睡眠检测等功能;
 
---

# 容视视频会议

- web:
  - 技术栈：Vue2、webRTC、FFmpeg
  - 项目描述：对标 Zoom 的视频会议办公系统,主要功能有音视频通讯,屏幕共享,语音激励,电子白板,即时通讯,会议纪要,预约会议等;
  - 工作业绩：
    - 通过优化重构,将原始打包文件从30+MB精简至仅4MB，同时引入CDN加速，将页面加载速度优化至仅3秒内。
    - 重写语音激励算法，有效节省了60%的带宽成本;
- 小程序:
  - 工作业绩：
    - 优化小程序的启动速度，从原来的 5 秒缩短至 2 秒以内，提升了用户的使用效率。
    - 针对移动端网络不稳定的情况，优化了视频流的自适应码率调整策略，减少了会议中断的情况发生，保证了会议的流畅性。
    - 实现了小程序与企业微信的集成，方便企业用户在企业微信中直接发起和参与视频会议，提高了工作协同效率。