# 1.7 设备上报信息的接口规范

SE3 AI 迷你机上每一次人员比对会产生一个比对事件，因为SE3 AI迷你机的存储空间有限。通常的架构设计是 SE3 AI 迷你机存储短期事件（默认1万条），并且把所有的事件上传到管理平台，由云平台做长期历史事件的存储及查询。

目前提供两种事件上报方式，分别适用于不同场景：

<table>
  <thead>
    <tr>
      <th style="text-align:left">Index</th>
      <th style="text-align:left">&#x4E0A;&#x62A5;&#x65B9;&#x5F0F;</th>
      <th style="text-align:left">&#x4E0A;&#x62A5;&#x5185;&#x5BB9;</th>
      <th style="text-align:left">&#x5B9E;&#x73B0;&#x673A;&#x5236;</th>
      <th style="text-align:left">&#x5B9E;&#x65F6;&#x6027;</th>
      <th style="text-align:left">&#x53EF;&#x9760;&#x6027;</th>
      <th style="text-align:left">&#x9002;&#x7528;&#x573A;&#x666F;</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">1</td>
      <td style="text-align:left">&#x5B9E;&#x65F6;&#x4E0A;&#x62A5;</td>
      <td style="text-align:left">&#x53EA;&#x4E0A;&#x62A5;&#x6BD4;&#x5BF9;&#x5206;&#x6570;&#x5927;&#x4E8E;&#x9608;&#x503C;&#x7684;&#x6BD4;&#x5BF9;&#x4E8B;&#x4EF6;</td>
      <td
      style="text-align:left">&#x6BD4;&#x5BF9;&#x5B8C;&#x6210;&#xFF0C;&#x5E76;&#x4E14;&#x5206;&#x6570;&#x5927;&#x4E8E;&#x9608;&#x503C;&#x5373;&#x5F00;&#x59CB;&#x4E0A;&#x62A5;</td>
        <td
        style="text-align:left">&#x9AD8;</td>
          <td style="text-align:left">&#x4F4E;&#xFF08;&#x4E0D;&#x7B49;&#x5F85;&#x63A5;&#x6536;&#x670D;&#x52A1;&#x5668;&#x7684;&#x63A5;&#x6536;&#x5B8C;&#x6210;&#x54CD;&#x5E94;&#xFF09;</td>
          <td
          style="text-align:left">&#x6BD4;&#x5BF9;&#x578B;&#xFF0C;&#x5982;&#x4EBA;&#x8138;&#x8BC6;&#x522B;&#x8FCE;&#x5BBE;&#xFF0C;&#x95F8;&#x673A;&#x95E8;&#x7981;&#x5F00;&#x95E8;&#x63A7;&#x5236;&#x7B49;</td>
    </tr>
    <tr>
      <td style="text-align:left">2</td>
      <td style="text-align:left">&#x5386;&#x53F2;&#x4E8B;&#x4EF6;&#x4E0A;&#x62A5;</td>
      <td style="text-align:left">&#x4E0A;&#x62A5;&#x6240;&#x6709;&#x7684;&#x4E8B;&#x4EF6;</td>
      <td style="text-align:left">
        <p>1 &#x4ECE;&#x5386;&#x53F2;&#x4E8B;&#x4EF6;&#x6570;&#x636E;&#x5E93;&#x4E2D;&#x67E5;&#x8BE2;&#x672A;&#x4E0A;&#x4F20;&#x7684;&#x4E8B;&#x4EF6;&#x8FDB;&#x884C;&#x6279;&#x91CF;&#x4E0A;&#x4F20;&#xFF1B;</p>
        <p>2 &#x4E0A;&#x4F20;&#x5B8C;&#x6210;&#x540E;&#x4F1A;&#x8BB0;&#x5F55;&#x5F53;&#x524D;&#x6E38;&#x6807;&#xFF0C;&#x4F5C;&#x4E3A;&#x4E0B;&#x6B21;&#x4E0A;&#x4F20;&#x7684;&#x8D77;&#x70B9;&#xFF1B;</p>
        <p>3 &#x4E0A;&#x4F20;&#x7684;&#x5468;&#x671F;&#x53EF;&#x914D;&#x7F6E;&#x7684;&#xFF0C;&#x9ED8;&#x8BA4;&#x4E3A;20s&#x3002;&#x5468;&#x671F;&#x53EF;&#x914D;&#x7F6E;&#xFF0C;&#x9700;&#x5927;&#x4E8E;&#x7B49;&#x4E8E;20s&#x3002;</p>
        <p>4 &#x6BCF;&#x6B21;&#x4E0A;&#x4F20;&#x7684;&#x4E8B;&#x4EF6;&#x6570;&#x76EE;&#x4E0D;&#x5927;&#x4E8E;100&#x6761;&#x3002;</p>
      </td>
      <td style="text-align:left">&#x4F4E;</td>
      <td style="text-align:left">&#x9AD8;&#xFF08;&#x4F1A;&#x91CD;&#x8BD5;&#x4E0A;&#x4F20;&#xFF09;</td>
      <td
      style="text-align:left">&#x8BB0;&#x5F55;&#x578B;&#xFF0C;&#x5982;&#x4EBA;&#x8138;&#x8BC6;&#x522B;&#x8003;&#x52E4;&#x7CFB;&#x7EDF;&#xFF0C;&#x5BA2;&#x6D41;&#x7EDF;&#x8BA1;&#x7CFB;&#x7EDF;&#x7B49;</td>
    </tr>
  </tbody>
</table>