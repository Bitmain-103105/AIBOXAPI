# Table of contents

* [版本列表](README.md)
* [语言/Language](yu-yan-language.md)

## 版本1.0 <a id="v1.0"></a>

* [1.0 快速导航](v1.0/1.0-kuai-su-dao-hang.md)
* [1.1 API列表](v1.0/1.1-api-lie-biao/README.md)
  * [1.1.1 基于Rabbit MQ的端云对接说明](v1.0/1.1-api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/README.md)
    * [1. 基于Rabbit MQ的端云系统架构设计](v1.0/1.1-api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/1.-ji-yu-rabbit-mq-de-duan-yun-xi-tong-jia-gou-she-ji.md)
    * [2. MQ接口流程说明](v1.0/1.1-api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/2.-mq-jie-kou-liu-cheng-shuo-ming/README.md)
      * [2.1 建立连接](v1.0/1.1-api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/2.-mq-jie-kou-liu-cheng-shuo-ming/2.1-jian-li-lian-jie.md)
      * [2.2 用户管理](v1.0/1.1-api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/2.-mq-jie-kou-liu-cheng-shuo-ming/2.2-yong-hu-guan-li.md)
    * [3. 状态码详细说明](v1.0/1.1-api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/3.-zhuang-tai-ma-xiang-xi-shuo-ming.md)
    * [4. 管理平台系统登录接口](v1.0/1.1-api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/4.-guan-li-ping-tai-xi-tong-deng-lu-jie-kou.md)
    * [5. MQ命令接口详细说明](v1.0/1.1-api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/5.-mq-ming-ling-jie-kou-xiang-xi-shuo-ming/README.md)
      * [5.1 用户管理MQ消息](v1.0/1.1-api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/5.-mq-ming-ling-jie-kou-xiang-xi-shuo-ming/5.1-yong-hu-guan-li-mq-xiao-xi/README.md)
        * [5.1.1 添加或更新用户（add\_users\_plus）](v1.0/1.1-api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/5.-mq-ming-ling-jie-kou-xiang-xi-shuo-ming/5.1-yong-hu-guan-li-mq-xiao-xi/5.1.1-tian-jia-huo-geng-xin-yong-hu-addusersplus.md)
        * [5.1.2 删除用户（delete\_users）](v1.0/1.1-api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/5.-mq-ming-ling-jie-kou-xiang-xi-shuo-ming/5.1-yong-hu-guan-li-mq-xiao-xi/5.1.2-shan-chu-yong-hu-deleteusers.md)
      * [5.2 设备数据清理MQ消息](v1.0/1.1-api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/5.-mq-ming-ling-jie-kou-xiang-xi-shuo-ming/5.2-she-bei-shu-ju-qing-li-mq-xiao-xi.md)
      * [5.3 人脸图片质量检测（FIQA）MQ消息](v1.0/1.1-api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/5.-mq-ming-ling-jie-kou-xiang-xi-shuo-ming/5.3-ren-lian-tu-pian-zhi-liang-jian-ce-fiqamq-xiao-xi.md)
      * [5.4 mq执行结果返回接口](v1.0/1.1-api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/5.-mq-ming-ling-jie-kou-xiang-xi-shuo-ming/5.4-mq-zhi-hang-jie-guo-fan-hui-jie-kou.md)
    * [6. 向管理平台获取信息的接口定义](v1.0/1.1-api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/6.-xiang-guan-li-ping-tai-huo-qu-xin-xi-de-jie-kou-ding-yi/README.md)
      * [6.1 获取用户详细信息的接口](v1.0/1.1-api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/6.-xiang-guan-li-ping-tai-huo-qu-xin-xi-de-jie-kou-ding-yi/6.1-huo-qu-yong-hu-xiang-xi-xin-xi-de-jie-kou.md)
    * [7. 设备上报信息的接口规范](v1.0/1.1-api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/7.-she-bei-shang-bao-xin-xi-de-jie-kou-gui-fan/README.md)
      * [7.1 实时事件上报内容](v1.0/1.1-api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/7.-she-bei-shang-bao-xin-xi-de-jie-kou-gui-fan/7.1-shi-shi-shi-jian-shang-bao-nei-rong.md)
      * [7.2 历史事件上报内容](v1.0/1.1-api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/7.-she-bei-shang-bao-xin-xi-de-jie-kou-gui-fan/7.2-li-shi-shi-jian-shang-bao-nei-rong.md)
      * [7.3 设备状态上报内容](v1.0/1.1-api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/7.-she-bei-shang-bao-xin-xi-de-jie-kou-gui-fan/7.3-she-bei-zhuang-tai-shang-bao-nei-rong.md)
      * [7.4 设备操作事件上报](v1.0/1.1-api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/7.-she-bei-shang-bao-xin-xi-de-jie-kou-gui-fan/7.4-she-bei-cao-zuo-shi-jian-shang-bao.md)
    * [8. 云平台配置](v1.0/1.1-api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/8.-yun-ping-tai-pei-zhi/README.md)
      * [8.1 小盒子唯一授权标识字段](v1.0/1.1-api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/8.-yun-ping-tai-pei-zhi/8.1-xiao-he-zi-wei-yi-shou-quan-biao-shi-zi-duan/README.md)
        * [8.1.1 查询授权码/SophonMQ/api/DevSno（GET）](v1.0/1.1-api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/8.-yun-ping-tai-pei-zhi/8.1-xiao-he-zi-wei-yi-shou-quan-biao-shi-zi-duan/8.1.1-cha-xun-shou-quan-ma-sophonmqapidevsnoget.md)
        * [8.1.2 更新授权码/SophonMQ/api/DevSno（PUT）](v1.0/1.1-api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/8.-yun-ping-tai-pei-zhi/8.1-xiao-he-zi-wei-yi-shou-quan-biao-shi-zi-duan/8.1.2-geng-xin-shou-quan-ma-sophonmqapidevsnoput.md)
      * [8.2 管理平台访问是否需要先登录授权](v1.0/1.1-api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/8.-yun-ping-tai-pei-zhi/8.2-guan-li-ping-tai-fang-wen-shi-fou-xu-yao-xian-deng-lu-shou-quan/README.md)
        * [8.2.1 查询管理平台登录地址/SophonMQ/api/LoginUrl（GET）](v1.0/1.1-api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/8.-yun-ping-tai-pei-zhi/8.2-guan-li-ping-tai-fang-wen-shi-fou-xu-yao-xian-deng-lu-shou-quan/8.2.1-cha-xun-guan-li-ping-tai-deng-lu-di-zhi-sophonmqapiloginurlget.md)
        * [8.2.2 更新管理平台登录地址/SophonMQ/api/LoginUrl（PUT）](v1.0/1.1-api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/8.-yun-ping-tai-pei-zhi/8.2-guan-li-ping-tai-fang-wen-shi-fou-xu-yao-xian-deng-lu-shou-quan/8.2.2-geng-xin-guan-li-ping-tai-deng-lu-di-zhi-sophonmqapiloginurlput.md)
    * [9. URL组合](v1.0/1.1-api-lie-biao/1.-ji-yu-rabbit-mq-de-duan-yun-dui-jie-shuo-ming/9.-url-zu-he.md)
  * [1.1.2 Sophon人脸识别雾计算系统开发文档](v1.0/1.1-api-lie-biao/2.sophon-ren-lian-shi-bie-wu-ji-suan-xi-tong-kai-fa-wen-dang.md)

## 版本2.0 <a id="v2.0"></a>

* [暂未上线](v2.0/zan-wei-shang-xian.md)
