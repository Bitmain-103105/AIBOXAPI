# AIBOX

- [版本](README.md)
- [V2.2.1](zh/V2R2C01_README.md)
  - [SE3 AI迷你机说明书](zh/V2R2C01/api-lie-biao/SE3-AI-Mini-ji-shuo-ming-shu/README.md)
  - [系统配置指南](zh/V2R2C01/api-lie-biao/xi-tong-pei-zhi-zhi-nang/README.md)
    - [网络摄像机模式](zh/V2R2C01/api-lie-biao/xi-tong-pei-zhi-zhi-nang/wang-luo-she-xiang-ji-mo-shi/README.md)
    - [闸机模式](zh/V2R2C01/api-lie-biao/xi-tong-pei-zhi-zhi-nang/zha-ji-mo-shi/README.md)
    - [抓拍机模式](zh/V2R2C01/api-lie-biao/xi-tong-pei-zhi-zhi-nang/zhua-pai-ji-mo-shi/README.md)
  - [系统对接](zh/V2R2C01/api-lie-biao/xi-tong-dui-jie-shuo-ming-shu/README.md)
    - [对接管理平台](zh/V2R2C01/api-lie-biao/xi-tong-dui-jie-shuo-ming-shu/dui-jie-guan-li-ping-tai/README.md)
    - [对接SE3盒子](zh/V2R2C01/api-lie-biao/xi-tong-dui-jie-shuo-ming-shu/dui-jie-SE3-he-zi/README.md)
  - [基于Rabbit MQ的端云对接说明](zh/V2R2C01/api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/README.md)
    - [基于Rabbit MQ的端云系统架构设计](zh/V2R2C01/api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/1.-ji-yu-rabbit-mq-de-duan-yun-xi-tong-jia-gou-she-ji.md)
    - [MQ接口流程说明](zh/V2R2C01/api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/2.-mq-jie-kou-liu-cheng-shuo-ming/README.md)
      - [建立连接](zh/V2R2C01/api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/2.-mq-jie-kou-liu-cheng-shuo-ming/2.1-jian-li-lian-jie.md)
      - [用户管理](zh/V2R2C01/api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/2.-mq-jie-kou-liu-cheng-shuo-ming/2.2-yong-hu-guan-li.md)
    - [状态码详细说明](zh/V2R2C01/api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/3.-zhuang-tai-ma-xiang-xi-shuo-ming.md)
    - [管理平台系统登录接口](zh/V2R2C01/api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/4.-guan-li-ping-tai-xi-tong-deng-lu-jie-kou.md)
    - [MQ命令接口详细说明](zh/V2R2C01/api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/5.-mq-ming-ling-jie-kou-xiang-xi-shuo-ming/README.md)
      - [用户管理MQ消息](zh/V2R2C01/api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/5.-mq-ming-ling-jie-kou-xiang-xi-shuo-ming/5.1-yong-hu-guan-li-mq-xiao-xi/README.md)
        - [添加或更新用户（add\_users\_plus）](zh/V2R2C01/api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/5.-mq-ming-ling-jie-kou-xiang-xi-shuo-ming/5.1-yong-hu-guan-li-mq-xiao-xi/5.1.1-tian-jia-huo-geng-xin-yong-hu-addusersplus.md)
        - [删除用户（delete\_users）](zh/V2R2C01/api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/5.-mq-ming-ling-jie-kou-xiang-xi-shuo-ming/5.1-yong-hu-guan-li-mq-xiao-xi/5.1.2-shan-chu-yong-hu-deleteusers.md)
      - [设备数据清理MQ消息](zh/V2R2C01/api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/5.-mq-ming-ling-jie-kou-xiang-xi-shuo-ming/5.2-she-bei-shu-ju-qing-li-mq-xiao-xi.md)
      - [人脸图片质量检测（FIQA）MQ消息](zh/V2R2C01/api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/5.-mq-ming-ling-jie-kou-xiang-xi-shuo-ming/5.3-ren-lian-tu-pian-zhi-liang-jian-ce-fiqamq-xiao-xi.md)
      - [mq执行结果返回接口](zh/V2R2C01/api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/5.-mq-ming-ling-jie-kou-xiang-xi-shuo-ming/5.4-mq-zhi-hang-jie-guo-fan-hui-jie-kou.md)
    - [向管理平台获取信息的接口定义](zh/V2R2C01/api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/6.-xiang-guan-li-ping-tai-huo-qu-xin-xi-de-jie-kou-ding-yi/README.md)
      - [获取用户详细信息的接口](zh/V2R2C01/api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/6.-xiang-guan-li-ping-tai-huo-qu-xin-xi-de-jie-kou-ding-yi/6.1-huo-qu-yong-hu-xiang-xi-xin-xi-de-jie-kou.md)
    - [设备上报信息的接口规范](zh/V2R2C01/api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/7.-she-bei-shang-bao-xin-xi-de-jie-kou-gui-fan/README.md)
      - [实时事件上报内容](zh/V2R2C01/api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/7.-she-bei-shang-bao-xin-xi-de-jie-kou-gui-fan/7.1-shi-shi-shi-jian-shang-bao-nei-rong.md)
      - [设备操作事件上报](zh/V2R2C01/api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/7.-she-bei-shang-bao-xin-xi-de-jie-kou-gui-fan/7.2-she-bei-cao-zuo-shi-jian-shang-bao.md)
    - [云平台配置](zh/V2R2C01/api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/8.-yun-ping-tai-pei-zhi/README.md)
      - [小盒子唯一授权标识字段](zh/V2R2C01/api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/8.-yun-ping-tai-pei-zhi/8.1-xiao-he-zi-wei-yi-shou-quan-biao-shi-zi-duan/README.md)
        - [查询授权码/SophonMQ/api/DevSno（GET）](zh/V2R2C01/api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/8.-yun-ping-tai-pei-zhi/8.1-xiao-he-zi-wei-yi-shou-quan-biao-shi-zi-duan/8.1.1-cha-xun-shou-quan-ma-sophonmqapidevsnoget.md)
        - [更新授权码/SophonMQ/api/DevSno（PUT）](zh/V2R2C01/api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/8.-yun-ping-tai-pei-zhi/8.1-xiao-he-zi-wei-yi-shou-quan-biao-shi-zi-duan/8.1.2-geng-xin-shou-quan-ma-sophonmqapidevsnoput.md)
      - [管理平台访问是否需要先登录授权](zh/V2R2C01/api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/8.-yun-ping-tai-pei-zhi/8.2-guan-li-ping-tai-fang-wen-shi-fou-xu-yao-xian-deng-lu-shou-quan/README.md)
        - [查询管理平台登录地址/SophonMQ/api/LoginUrl（GET）](zh/V2R2C01/api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/8.-yun-ping-tai-pei-zhi/8.2-guan-li-ping-tai-fang-wen-shi-fou-xu-yao-xian-deng-lu-shou-quan/8.2.1-cha-xun-guan-li-ping-tai-deng-lu-di-zhi-sophonmqapiloginurlget.md)
        - [更新管理平台登录地址/SophonMQ/api/LoginUrl（PUT）](zh/V2R2C01/api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/8.-yun-ping-tai-pei-zhi/8.2-guan-li-ping-tai-fang-wen-shi-fou-xu-yao-xian-deng-lu-shou-quan/8.2.2-geng-xin-guan-li-ping-tai-deng-lu-di-zhi-sophonmqapiloginurlput.md)
    - [URL组合](zh/V2R2C01/api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/9.-url-zu-he.md)
  - [Sophon人脸识别雾计算系统开发文档](zh/V2R2C01/api-lie-biao/2.sophon-ren-lian-shi-bie-wu-ji-suan-xi-tong-kai-fa-wen-dang/README.md)
    - [概要](zh/V2R2C01/api-lie-biao/2.sophon-ren-lian-shi-bie-wu-ji-suan-xi-tong-kai-fa-wen-dang/1-gai-yao.md)
    - [Sophon人脸识别雾计算系统架构](zh/V2R2C01/api-lie-biao/2.sophon-ren-lian-shi-bie-wu-ji-suan-xi-tong-kai-fa-wen-dang/2-Sophon-ren-lian-shi-bie-wu-ji-suan-xi-tong-jia-gou.md)
    - [Sophon人脸识别雾计算系统和云端交互方式](zh/V2R2C01/api-lie-biao/2.sophon-ren-lian-shi-bie-wu-ji-suan-xi-tong-kai-fa-wen-dang/3-Sophon-ren-lian-shi-bie-wu-ji-suan-xi-tong-he-yun-duan-jiao-hu-fang-shi.md)
    - [接口API详细说明](zh/V2R2C01/api-lie-biao/2.sophon-ren-lian-shi-bie-wu-ji-suan-xi-tong-kai-fa-wen-dang/4-jie-kou-API-xiang-xi-shuo-ming/README.md)
      - [权限组管理](zh/V2R2C01/api-lie-biao/2.sophon-ren-lian-shi-bie-wu-ji-suan-xi-tong-kai-fa-wen-dang/4-jie-kou-API-xiang-xi-shuo-ming/4.1-quan-xian-zu-guan-li/README.md)
        - [创建分组/SophonFogSys/api/permissions（POST）](zh/V2R2C01/api-lie-biao/2.sophon-ren-lian-shi-bie-wu-ji-suan-xi-tong-kai-fa-wen-dang/4-jie-kou-API-xiang-xi-shuo-ming/4.1-quan-xian-zu-guan-li/1-chuang-jian-fen-zu-SophonFogSysapipermissions（POST）.md)
        - [查询分组/SophonFogSys/api/permissions（GET）](zh/V2R2C01/api-lie-biao/2.sophon-ren-lian-shi-bie-wu-ji-suan-xi-tong-kai-fa-wen-dang/4-jie-kou-API-xiang-xi-shuo-ming/4.1-quan-xian-zu-guan-li/2-cha-xun-fen-zu-SophonFogSysapipermissions（GET）.md)
        - [删除分组/SophonFogSys/api/permissions（DELETE）](zh/V2R2C01/api-lie-biao/2.sophon-ren-lian-shi-bie-wu-ji-suan-xi-tong-kai-fa-wen-dang/4-jie-kou-API-xiang-xi-shuo-ming/4.1-quan-xian-zu-guan-li/3-shan-chu-fen-zu-SophonFogSysapipermissions（DELETE）.md)
        - [更新分组/SophonFogSys/api/permissions（PUT）](zh/V2R2C01/api-lie-biao/2.sophon-ren-lian-shi-bie-wu-ji-suan-xi-tong-kai-fa-wen-dang/4-jie-kou-API-xiang-xi-shuo-ming/4.1-quan-xian-zu-guan-li/4-gen-xin-fen-zu-SophonFogSysapipermissions（PUT）.md)
      - [人脸底库组管理](zh/V2R2C01/api-lie-biao/2.sophon-ren-lian-shi-bie-wu-ji-suan-xi-tong-kai-fa-wen-dang/4-jie-kou-API-xiang-xi-shuo-ming/4.2-ren-lian-di-ku-zu-guan-li/README.md)
        - [创建分组/SophonFogSys/api/groups（POST）](zh/V2R2C01/api-lie-biao/2.sophon-ren-lian-shi-bie-wu-ji-suan-xi-tong-kai-fa-wen-dang/4-jie-kou-API-xiang-xi-shuo-ming/4.2-ren-lian-di-ku-zu-guan-li/1-chuang-jian-fen-zu-SophonFogSysapigroups（POST）.md)
        - [查询分组/SophonFogSys/api/groups（GET）](zh/V2R2C01/api-lie-biao/2.sophon-ren-lian-shi-bie-wu-ji-suan-xi-tong-kai-fa-wen-dang/4-jie-kou-API-xiang-xi-shuo-ming/4.2-ren-lian-di-ku-zu-guan-li/2-cha-xun-fen-zu-SophonFogSysapigroups（GET）.md)
        - [删除分组/SophonFogSys/api/groups（DELETE）](zh/V2R2C01/api-lie-biao/2.sophon-ren-lian-shi-bie-wu-ji-suan-xi-tong-kai-fa-wen-dang/4-jie-kou-API-xiang-xi-shuo-ming/4.2-ren-lian-di-ku-zu-guan-li/3-shan-chu-fen-zu-SophonFogSysapigroups（DELETE）.md)
        - [添加人员到分组/SophonFogSys/api/GroupUsers（PUT）](zh/V2R2C01/api-lie-biao/2.sophon-ren-lian-shi-bie-wu-ji-suan-xi-tong-kai-fa-wen-dang/4-jie-kou-API-xiang-xi-shuo-ming/4.2-ren-lian-di-ku-zu-guan-li/4-tian-jia-ren-yuan-dao-fen-zu-SophonFogSysapiGroupUsers（PUT）.md)
        - [从分组删除人员/SophonFogSys/api/GroupUsers（DELETE）](zh/V2R2C01/api-lie-biao/2.sophon-ren-lian-shi-bie-wu-ji-suan-xi-tong-kai-fa-wen-dang/4-jie-kou-API-xiang-xi-shuo-ming/4.2-ren-lian-di-ku-zu-guan-li/5-cong-fen-zu-shan-chu-ren-yuan-SophonFogSysapiGroupUsers（DELETE）.md)
        - [更新分组SophonFogSysapigroups（PUT）](zh/V2R2C01/api-lie-biao/2.sophon-ren-lian-shi-bie-wu-ji-suan-xi-tong-kai-fa-wen-dang/4-jie-kou-API-xiang-xi-shuo-ming/4.2-ren-lian-di-ku-zu-guan-li/6-gen-xin-fen-zu-SophonFogSysapigroups（PUT）.md)
      - [人员管理](zh/V2R2C01/api-lie-biao/2.sophon-ren-lian-shi-bie-wu-ji-suan-xi-tong-kai-fa-wen-dang/4-jie-kou-API-xiang-xi-shuo-ming/4.3-ren-yuan-guan-li/README.md)
        - [创建人员SophonFogSys/api/users（POST）](zh/V2R2C01/api-lie-biao/2.sophon-ren-lian-shi-bie-wu-ji-suan-xi-tong-kai-fa-wen-dang/4-jie-kou-API-xiang-xi-shuo-ming/4.3-ren-yuan-guan-li/1-chuang-jian-ren-yuan-SophonFogSysapiusers（POST）.md)
        - [查询人员/SophonFogSys/api/users（GET）](zh/V2R2C01/api-lie-biao/2.sophon-ren-lian-shi-bie-wu-ji-suan-xi-tong-kai-fa-wen-dang/4-jie-kou-API-xiang-xi-shuo-ming/4.3-ren-yuan-guan-li/2-cha-xun-ren-yuan-SophonFogSysapiusers（GET）.md)
        - [更新人员/SophonFogSys/api/users（PUT）](zh/V2R2C01/api-lie-biao/2.sophon-ren-lian-shi-bie-wu-ji-suan-xi-tong-kai-fa-wen-dang/4-jie-kou-API-xiang-xi-shuo-ming/4.3-ren-yuan-guan-li/3-geng-xin-ren-yuan-SophonFogSysapiusers（PUT）.md)
        - [删除人员/SophonFogSys/api/users（DELETE）](zh/V2R2C01/api-lie-biao/2.sophon-ren-lian-shi-bie-wu-ji-suan-xi-tong-kai-fa-wen-dang/4-jie-kou-API-xiang-xi-shuo-ming/4.3-ren-yuan-guan-li/4-shan-chu-ren-yuan-SophonFogSysapiusers（DELETE）.md)
      - [事件管理](zh/V2R2C01/api-lie-biao/2.sophon-ren-lian-shi-bie-wu-ji-suan-xi-tong-kai-fa-wen-dang/4-jie-kou-API-xiang-xi-shuo-ming/4.4-shi-jian-guan-li/README.md)
        - [设置事件反馈模式/SophonFogSys/api/GateControllerMode（POST）](zh/V2R2C01/api-lie-biao/2.sophon-ren-lian-shi-bie-wu-ji-suan-xi-tong-kai-fa-wen-dang/4-jie-kou-API-xiang-xi-shuo-ming/4.4-shi-jian-guan-li/1-she-zhi-shi-jian-fan-kui-mo-shi-SophonFogSysapiGateControllerMode（POST）.md)
        - [获取事件反馈模式/SophonFogSys/api/GateControllerMode（GET）](zh/V2R2C01/api-lie-biao/2.sophon-ren-lian-shi-bie-wu-ji-suan-xi-tong-kai-fa-wen-dang/4-jie-kou-API-xiang-xi-shuo-ming/4.4-shi-jian-guan-li/2-huo-qu-shi-jian-fan-kui-mo-shi-SophonFogSysapiGateControllerMode（GET）.md)
        - [请求小盒子响应事件/SophonFogSys/api/EventAction（PUT）](zh/V2R2C01/api-lie-biao/2.sophon-ren-lian-shi-bie-wu-ji-suan-xi-tong-kai-fa-wen-dang/4-jie-kou-API-xiang-xi-shuo-ming/4.4-shi-jian-guan-li/3-qing-qiu-xiao-he-zi-xiang-ying-shi-jian-SophonFogSysapiEventAction（PUT）.md)
        - [配置/修改实时事件上报接收服务器地址/SophonFogSys/api/EventServerUrl（POST）](zh/V2R2C01/api-lie-biao/2.sophon-ren-lian-shi-bie-wu-ji-suan-xi-tong-kai-fa-wen-dang/4-jie-kou-API-xiang-xi-shuo-ming/4.4-shi-jian-guan-li/4-pei-zhi-xiu-gai-shi-shi-shi-jian-shang-bao-jie-shou-fu-wu-qi-di-zhi-SophonFogSysapiEventServerUrl（POST）.md)
        - [获取实时事件上报接收服务器地址/SophonFogSys/api/EventServerUrl（GET）](zh/V2R2C01/api-lie-biao/2.sophon-ren-lian-shi-bie-wu-ji-suan-xi-tong-kai-fa-wen-dang/4-jie-kou-API-xiang-xi-shuo-ming/4.4-shi-jian-guan-li/5-huo-qu-shi-shi-shi-jian-shang-bao-jie-shou-fu-wu-qi-di-zhi-SophonFogSysapiEventServerUrl（GET）.md)
        - [实时上报事件具体内容（p0）](zh/V2R2C01/api-lie-biao/2.sophon-ren-lian-shi-bie-wu-ji-suan-xi-tong-kai-fa-wen-dang/4-jie-kou-API-xiang-xi-shuo-ming/4.4-shi-jian-guan-li/6-shi-shi-shang-bao-shi-jian-ju-ti-nei-rong（p0）.md)
        - [配置/修改历史事件上报接收服务器地址/SophonFogSys/api/HistoryEventUrl](zh/V2R2C01/api-lie-biao/2.sophon-ren-lian-shi-bie-wu-ji-suan-xi-tong-kai-fa-wen-dang/4-jie-kou-API-xiang-xi-shuo-ming/4.4-shi-jian-guan-li/7-pei-zhi-xiu-gai-li-shi-shi-jian-shang-bao-jie-shou-fu-wu-qi-di-zhi-SophonFogSysapiHistoryEventUrl.md)
        - [获取历史事件上报接收服务器地址/SophonFogSys/api/HistoryEventUrl（GET）](zh/V2R2C01/api-lie-biao/2.sophon-ren-lian-shi-bie-wu-ji-suan-xi-tong-kai-fa-wen-dang/4-jie-kou-API-xiang-xi-shuo-ming/4.4-shi-jian-guan-li/8-huo-qu-li-shi-shi-jian-shang-bao-jie-shou-fu-wu-qi-di-zhi-SophonFogSysapiHistoryEventUrl（GET）.md)
        - [异步上报事件具体内容](zh/V2R2C01/api-lie-biao/2.sophon-ren-lian-shi-bie-wu-ji-suan-xi-tong-kai-fa-wen-dang/4-jie-kou-API-xiang-xi-shuo-ming/4.4-shi-jian-guan-li/9-yi-bu-shang-bao-shi-jian-ju-ti-nei-rong.md)
      - [雾端状态管理](zh/V2R2C01/api-lie-biao/2.sophon-ren-lian-shi-bie-wu-ji-suan-xi-tong-kai-fa-wen-dang/4-jie-kou-API-xiang-xi-shuo-ming/4.5-wu-duan-zhuan-tai-guan-li/README.md)
        - [配置/修改状态上报接收服务器地址/SophonFogSys/api/MonitorServerUrl（POST）](zh/V2R2C01/api-lie-biao/2.sophon-ren-lian-shi-bie-wu-ji-suan-xi-tong-kai-fa-wen-dang/4-jie-kou-API-xiang-xi-shuo-ming/4.5-wu-duan-zhuan-tai-guan-li/1-pei-zhi-xiu-gai-zhuan-tai-shang-bao-jie-shou-fu-wu-qi-di-zhi-SophonFogSysapiMonitorServerUrl（POST）.md)
        - [获取状态上报接收服务器地址/SophonFogSys/api/MonitorServerUrl（GET）](zh/V2R2C01/api-lie-biao/2.sophon-ren-lian-shi-bie-wu-ji-suan-xi-tong-kai-fa-wen-dang/4-jie-kou-API-xiang-xi-shuo-ming/4.5-wu-duan-zhuan-tai-guan-li/2-huo-qu-zhuan-tai-shang-bao-jie-shou-fu-wu-qi-di-zhi-SophonFogSysapiMonitorServerUrl（GET）.md)
        - [主动上报雾端状态](zh/V2R2C01/api-lie-biao/2.sophon-ren-lian-shi-bie-wu-ji-suan-xi-tong-kai-fa-wen-dang/4-jie-kou-API-xiang-xi-shuo-ming/4.5-wu-duan-zhuan-tai-guan-li/3-zhu-dong-shang-bao-wu-duan-zhuan-tai.md)
        - [清空数据/SophonFogSys/api/WipeData（POST）](zh/V2R2C01/api-lie-biao/2.sophon-ren-lian-shi-bie-wu-ji-suan-xi-tong-kai-fa-wen-dang/4-jie-kou-API-xiang-xi-shuo-ming/4.5-wu-duan-zhuan-tai-guan-li/4-qing-kong-shu-ju-SophonFogSysapiWipeData（POST）.md)
  - [客户支持文档](zh/V2R2C01/api-lie-biao/3.ke-hu-zhi-chi/README.md)
    - [人脸识别系统闸机门禁机模式快速配置指南](zh/V2R2C01/api-lie-biao/3.ke-hu-zhi-chi/1.zha-ji-men-jin-ji-mo-shi-kuai-su-pei-zhi-zhi-nan/README.md)
      - [系统网络图](zh/V2R2C01/api-lie-biao/3.ke-hu-zhi-chi/1.zha-ji-men-jin-ji-mo-shi-kuai-su-pei-zhi-zhi-nan/1.xi-tong-wang-luo.md)
      - [闸机和门禁机设置](zh/V2R2C01/api-lie-biao/3.ke-hu-zhi-chi/1.zha-ji-men-jin-ji-mo-shi-kuai-su-pei-zhi-zhi-nan/2.zha-ji-he-men-jin-ji-she-zhi.md)
      - [SE3 AI迷你机设置](zh/V2R2C01/api-lie-biao/3.ke-hu-zhi-chi/1.zha-ji-men-jin-ji-mo-shi-kuai-su-pei-zhi-zhi-nan/3.AI-Mini-ji-she-zhi.md)
      - [系统功能验证](zh/V2R2C01/api-lie-biao/3.ke-hu-zhi-chi/1.zha-ji-men-jin-ji-mo-shi-kuai-su-pei-zhi-zhi-nan/4.xi-tong-gong-neng-yan-zheng.md)
    - [人脸识别迎宾系统快速设置指南](zh/V2R2C01/api-lie-biao/3.ke-hu-zhi-chi/2.ying-bin-xi-tong-kuai-su-she-zhi-zhi-nan/README.md)
      - [迎宾机系统组网图](zh/V2R2C01/api-lie-biao/3.ke-hu-zhi-chi/2.ying-bin-xi-tong-kuai-su-she-zhi-zhi-nan/1.ying-bin-ji-xi-tong-zu-wang-tu.md)
      - [迎宾机系统基本功能](zh/V2R2C01/api-lie-biao/3.ke-hu-zhi-chi/2.ying-bin-xi-tong-kuai-su-she-zhi-zhi-nan/2.ying-bin-ji-xi-tong-ji-ben-gong-neng.md)
      - [抓拍机设置](zh/V2R2C01/api-lie-biao/3.ke-hu-zhi-chi/2.ying-bin-xi-tong-kuai-su-she-zhi-zhi-nan/3.zhua-pai-ji-she-zhi.md)
      - [迎宾电视APK操作指南](zh/V2R2C01/api-lie-biao/3.ke-hu-zhi-chi/2.ying-bin-xi-tong-kuai-su-she-zhi-zhi-nan/4.ying-bin-dian-shi-APK-cao-zuo-zhi-nan.md)
    

