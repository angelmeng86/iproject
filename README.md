# iproject
ionic project 对工程的基本目录结构进行调整<br/><br/>
一、调整目录为www/js/<br/>
1、www/js/controller   视图控制器目录<br/>
2、www/js/model        实体目录<br/>
3、www/templates       视图目录（未变动）<br/>
4、www/route.js        路由定义（建立页面的跳转流程，以及视图和视图控制器的绑定关系）<br/>
上述目录根据项目具体的业务再适当增加相应的子目录，如login、profile等业务目录<br/>
<br/>
二、新增controler的基本流程<br/>
1、在www/js/controller目录中增加js文件，代码请参考该目录下的实例<br/>
2、在www/js/controllers.js中增加该控制器所对应module名称<br/>
3、在www/index.html中增加js文件的引用<br/>
<br/>
三、新增model的基本流程<br/>
1、在www/js/model目录中增加js文件，代码请参考该目录下的实例<br/>
2、在www/js/services.js中增加该控制器所对应module名称<br/>
3、在www/index.html中增加js文件的引用<br/>
<br/>

<br/>
