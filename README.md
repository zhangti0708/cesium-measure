# cesium-measure

----------------------------------------------------------------------------------------------------------------------------------------
### 基于cesium的三维量测插件
### cesium-measure

### 说明
##### /cesium-measure/src/doc

### 使用

#####  在项目中引入Cesium.js

#####  然后引入 cesium-measure.js 即可

```
    let viewer = new Cesium.Viewer("viewerContainer")

    let measure = new Cesium.Measure(viewer)

    // 空间距离
    measure.drawLineMeasureGraphics({ clampToGround: clampToGround, callback: () => { } });

    // 空间面积
    measure.drawAreaMeasureGraphics({ clampToGround: clampToGround, callback: () => { } });

    // 三维量测
    measure.drawTrianglesMeasureGraphics({ callback: () => { } });

    // 清除
    measure._drawLayer.entities.removeAll();
```
  
<a href="http://zhangticcc.gitee.io/webgis/#/gis/examples?exampleURL=measure&tempUrl=%2Fwebgis%2Fd3kit%2Ftemp.html&type=d3old"><img alt="" height="80%" src="https://img-blog.csdnimg.cn/2020091013540454.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MDkwMjUyNw==,size_16,color_FFFFFF,t_70" width="80%" ></a>&nbsp;
<a href="http://zhangticcc.gitee.io/webgis/#/gis/examples?exampleURL=measure&tempUrl=%2Fwebgis%2Fd3kit%2Ftemp.html&type=d3old"></a><br>

<a href="http://zhangticcc.gitee.io/webgis/#/gis/examples?exampleURL=measure&tempUrl=%2Fwebgis%2Fd3kit%2Ftemp.html&type=d3old"><img alt="" height="80%" src="https://img-blog.csdnimg.cn/20200910135204454.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MDkwMjUyNw==,size_16,color_FFFFFF,t_70" width="80%" ></a>&nbsp;
<a href="http://zhangticcc.gitee.io/webgis/#/gis/examples?exampleURL=measure&tempUrl=%2Fwebgis%2Fd3kit%2Ftemp.html&type=d3old"></a><br>

<a href="http://zhangticcc.gitee.io/webgis/#/gis/examples?exampleURL=measure&tempUrl=%2Fwebgis%2Fd3kit%2Ftemp.html&type=d3old"><img alt="" height="80%" src="https://img-blog.csdnimg.cn/20200910135512635.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MDkwMjUyNw==,size_16,color_FFFFFF,t_70" width="80%" ></a>&nbsp;
<a href="http://zhangticcc.gitee.io/webgis/#/gis/examples?exampleURL=measure&tempUrl=%2Fwebgis%2Fd3kit%2Ftemp.html&type=d3old"></a><br>