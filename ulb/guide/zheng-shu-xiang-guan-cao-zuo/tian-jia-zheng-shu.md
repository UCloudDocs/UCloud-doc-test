# 添加证书

证书管理将证书存储在ULB证书管理系统中，用于HTTPS协议。

注意：证书不可跨Region使用。若多地域均需要使用，则多个地域均需要上传证书。

### 操作步骤

进入**负载均衡 ULB页面**，点击**证书管理**。 

1、点击**添加证书，**弹出添加证书弹窗。

2、需要填写以下信息

<table>
  <thead>
    <tr>
      <th style="text-align:left">&#x914D;&#x7F6E;</th>
      <th style="text-align:left">&#x8BF4;&#x660E;</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">&#x8BC1;&#x4E66;&#x540D;&#x79F0;</td>
      <td style="text-align:left">&#x8BC1;&#x4E66;&#x540D;&#x79F0;&#xFF0C;&#x5FC5;&#x586B;&#x9879;&#x3002;</td>
    </tr>
    <tr>
      <td style="text-align:left">&#x8BC1;&#x4E66;&#x5185;&#x5BB9;</td>
      <td style="text-align:left">
        <ul>
          <li>&#x672C;&#x5730;&#x4E0A;&#x4F20;&#x8BC1;&#x4E66;&#xFF0C;&#x9009;&#x62E9;&#x60A8;&#x672C;&#x5730;&#x7684;&#x6388;&#x6743;&#x8BC1;&#x4E66;&#xFF0C;&#x5305;&#x62EC;.crt&#x6587;&#x4EF6;&#x4E0E;.key&#x6587;&#x4EF6;&#x3002;</li>
          <li>&#x624B;&#x52A8;&#x8F93;&#x5165;&#x8BC1;&#x4E66;&#xFF0C;&#x5219;&#x9700;&#x8981;&#x5728;&#x8F93;&#x5165;&#x6846;&#x4E2D;&#x624B;&#x52A8;&#x586B;&#x5199;&#x8BC1;&#x4E66;&#xFF0C;&#x8BC1;&#x4E66;&#x683C;&#x5F0F;&#x89C1;&#x8BC1;&#x4E66;&#x683C;&#x5F0F;&#x8981;&#x6C42;&#xFF08;&#x76F8;&#x5BF9;&#x8DEF;&#x5F84;&#xFF09;</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">&#x8BC1;&#x4E66;&#x683C;&#x5F0F;</td>
      <td style="text-align:left">
        <p></p>
        <ul>
          <li>&#x6388;&#x6743;&#x8BC1;&#x4E66;(.crt&#x6587;&#x4EF6;)&#xFF1A;&#x8BC1;&#x4E66;&#x673A;&#x6784;&#x4E0B;&#x53D1;&#x7684;&#x516C;&#x94A5;&#x6587;&#x4EF6;</li>
          <li>&#x6388;&#x6743;&#x8BC1;&#x4E66;(.key&#x6587;&#x4EF6;)&#xFF1A;&#x8BC1;&#x4E66;&#x673A;&#x6784;&#x4E0B;&#x53D1;&#x7684;&#x79C1;&#x94A5;&#x6587;&#x4EF6;</li>
          <li>CA&#x673A;&#x6784;&#x8BC1;&#x4E66;(.crt&#x6587;&#x4EF6;)&#xFF1A;&#x8BC1;&#x4E66;&#x673A;&#x6784;&#x8BC1;&#x660E;&#x81EA;&#x8EAB;&#x662F;&#x6743;&#x5A01;&#x673A;&#x6784;&#x7684;&#x8BC1;&#x660E;</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>