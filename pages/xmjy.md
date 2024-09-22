# 项目经验

<div>
    <ol>
      <li class="rounded cursor-pointer"  hover="bg-white bg-opacity-10" @click="$slidev.nav.go(7)">
            CRM电销电商系统 (web&小程序) <carbon:arrow-right class="inline"/>
      </li>
      <li class="rounded cursor-pointer"  hover="bg-white bg-opacity-10" @click="$slidev.nav.go(8)">
            云建-BIM管理系统 (web&小程序) <carbon:arrow-right class="inline"/>
      </li>
      <li class="rounded cursor-pointer" hover="bg-white bg-opacity-10" @click="$slidev.nav.go(9)">
            容联-容视视频会议 (web&小程序) <carbon:arrow-right class="inline"/>
      </li>
      <li class="rounded cursor-pointer" hover="bg-white bg-opacity-10" @click="$slidev.nav.go(10)">
            云建-大众B柱碰撞监控(鸿蒙os/移动端) <carbon:arrow-right class="inline"/>
      </li>
      <li class="rounded cursor-pointer" hover="bg-white bg-opacity-10" @click="$slidev.nav.go(10)">
            逸金科技-卡易还 (移动端) <carbon:arrow-right class="inline"/>
      </li>   
    </ol>
</div>


# 个人作品

<div>
    <ol>
        <li class="rounded cursor-pointer"  hover="bg-white bg-opacity-10" @click="$slidev.nav.go(11)">
           孔大夫在线工具箱（全栈 Rust重构中） <carbon:arrow-right class="inline"/>
        </li>
          <li class="rounded cursor-pointer"  hover="bg-white bg-opacity-10" @click="$slidev.nav.go(11)">
            我做个艺术家 (小程序&公众号) <carbon:arrow-right class="inline"/>
        </li>
           <li class="rounded cursor-pointer" hover="bg-white bg-opacity-10" @click="$slidev.nav.go(12)">
            孔大夫的工具箱 (桌面端) <carbon:arrow-right class="inline"/>
        </li>
         <li class="rounded cursor-pointer"  hover="bg-white bg-opacity-10" @click="$slidev.nav.go(12)">
          JDFund(桌面端) <carbon:arrow-right class="inline"/>
        </li>
         <!-- <li class="rounded cursor-pointer" hover="bg-white bg-opacity-10" @click="$slidev.nav.go(8)">
            KDM (webrtc开源库) <carbon:arrow-right class="inline"/>
        </li> -->
    </ol>
</div>

---

# CRM电商系统

- 技术栈：Vue3、uni-app;
- 项目描述：客户、销售、订单、回款、售后、报表一体化电销管理软件;
- 项目痛点：
  - 技术层面：前端人员技术水平参差不齐，模块较多，无代码规范以及存在依赖版本问题,导致上线困难;
  - 业务层面：一线使用云桌面，配置较低，之前使用监听+轮询的方式来进行状态同步，严重影响性能导致浏览器崩溃;
- 项目业绩：
  - 重构CRM,解决浏览器崩溃问题;
  - 优化前端性能,通过缓存、取消请求、动态加载等方式来优化前端性能;
  - 订阅模式代替监听模式/事件总栈/轮询;
  - 使用 provide/inject 代替 vuex;
  - 封装indexDB,缓存options列表来减少请求次数;
  - 增加tagsview以及缓存解决postmessage导致内存泄漏问题;

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

---

# 大众 B 柱智能监测系统
- 技术栈：uni-app、Vant;
- 项目描述：主要功能有实时视频检测，车辆震动警告，临时密码解锁等功能；
- 项目实现： uni-app 打包成安卓应用；视频流协议采用了 rtmp+hls 实现;

# FRMS  鸿蒙 OS 智能手表应用
  - 技术栈：鸿蒙os
  - 项目描述：国内首款疲劳检测预测系统;通过对接华为 Health Kit 获得健康数据并进行分析预测;
  - 项目实现：通过 JS FA 开发,实现了量表自测,打卡,睡眠检测等功能;


# 卡易还
- 技术栈：Vue2、uni-app、Vant;
- 项目描述：一款基于移动端的信用卡智能还款工具，用户通过App即可实现信用卡智能还款，降低还款成本，提高还款效率;

---

# 个人项目
- 孔大夫在线工具箱 (Rust重构中)

  - 在线地址：https://box.kongdf.com
  - 技术栈：前端使用Vue3+Vite,服务端采用Express+Mysql+Prisma;还有Nuxt的SSR版本;
  - 项目描述：在线工作台，集成了导航收藏、在线备忘录、节假日查询、Word/Excel预览、音视频格式转换、图片压缩、录像录屏、资源收藏以及公众号自动回复管理等多项功能。


- 我做个艺术家（小程序&公众号）
  - 小程序
    - 技术栈：Taro、koa;
    - 项目描述：功能包括美团和饿了么优惠券的领取服务，能为难以抉择的用户提供辅助决策的帮助，并且共享了若干如影视资源之类的内容。
  - 公众号 
    - 项目描述：通过向公众号发送消息来获取和新增一些 Cookie ,使用 nodejs 运行包括京东农场每日浇水、网易云音乐自动签到升级等薅羊毛脚本。

---

# 个人项目


- 孔大夫的工具箱 (桌面端)
  - 项目地址：https://github.com/kongdf/box_tauri
  - 项目描述：一款集合了众多功能的工具箱，核心功能为爬虫与格式转换，涵盖壁纸获取、音视频转换、屏幕录制、pdf 转 Word 以及图片压缩等功能。
  - 项目实现：前端主要以Vue3+Tauri,后端采用Rust+axum;


- JDfund （Rust桌面应用）
  - 项目地址：https://github.com/kongdf/JDfund
  - 项目描述：京东金融的积存金价格实时展示工具;
  - 项目实现：Tauri + Vue 3;


# 结语
前端开发不仅是我的职业，更是我的热爱。我期待能有机会加入贵公司，与志同道合的伙伴们一起，用前沿的技术和无限的创意，打造出引领行业的前端应用。  <span style="margin-left:30px"> ------ 来自chatGPT</span>

---