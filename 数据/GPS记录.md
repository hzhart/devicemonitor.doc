# GPS记录

> 更新记录

<table>
    <tr>
        <th style="width:250px;">日期</th>
        <th>更新内容</th>
    </tr>
    <tr>
        <td>2018-06-04 10:53:38</td>
        <td>生成时间</td>
    </tr>
</table>

> 字段

<table>
    <tr>
        <th style="width:150px;">属性名称</th>
        <th style="width:60px;">类型</th>
        <th style="width:200px;">说明</th>
        <th>备注</th>
    </tr>
    <tr>
        <td>stationId</td>
        <td>string</td>
        <td>站点ID</td>
        <td>-</td>
    </tr>
    <tr>
        <td>commNo</td>
        <td>string</td>
        <td>通讯编号</td>
        <td>-</td>
    </tr>
    <tr>
        <td>funCode</td>
        <td>int</td>
        <td>功能码</td>
        <td>-</td>
    </tr>
    <tr>
        <td>lon</td>
        <td>decimal</td>
        <td>经度</td>
        <td>-</td>
    </tr>
    <tr>
        <td>lat</td>
        <td>decimal</td>
        <td>纬度</td>
        <td>-</td>
    </tr>    
    <tr>
        <td>timestamp</td>
        <td>int</td>
        <td>上传时间戳</td>
        <td>-</td>
    </tr>
    <tr>
        <td>createdAt</td>
        <td>datetime</td>
        <td>创建时间</td>
        <td>-</td>
    </tr>   
</table>

## GPS记录

```
GET /admin/data/v1/gpslog
```

> 参数
<table>
    <tr>
        <th style="width:150px;">名称</th>
        <th style="width:60px;">类型</th>
        <th style="width:60px;">必填</th>
        <th style="width:200px;">说明</th>
        <th>备注</th>
    </tr>
    <tr>
        <td>startTime</td>
        <td>datetime</td>
        <td>是</td>
        <td>开始时间</td>
        <td>格式: 2001-02-03 04:05:06</td>
    </tr>
    <tr>
        <td>endTime</td>
        <td>datetime</td>
        <td>是</td>
        <td>结束时间</td>
        <td>格式: 2001-02-03 04:05:06</td>
    </tr>
    <tr>
        <td>stationId</td>
        <td>int</td>
        <td>是</td>
        <td>站点ID</td>
        <td>-</td>
    </tr>
</table>