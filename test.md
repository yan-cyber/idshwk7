origin_picture.jpg为原始图片
test0.png为加上“学号_姓名”水印后的图片；
由于水印解码后显示得不够清楚，又采取了另一种方法：
先对“学号_姓名”信息进行base64编码，然后将编码隐藏在颜色信息里，得到test.png。