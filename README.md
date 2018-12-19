# ChinaCitys
中国 省，市，县 信息
# 下载lib 里面的jar包即可。

* 1.获取省份名称<br>
 List<String> provinces=ProvincesUtil.getProvinces();<br>
* 2.获取省份下城市信息<br>
List<String> data=CityUtil.getCitys("河北");<br>

* 3.获取市区下县区名称<br>
List<String> couns= CountyUtis.getCountys("河北","石家庄");
      


