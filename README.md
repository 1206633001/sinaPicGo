# sinaPicGo
新浪图床 Go语言


```
var sina = sinaimg.NewSinaUp().SetUsername("you username").SetPassword("you password")

//图片支持本地图片和远程图片
fileLink := "/Users/xsc/go/src/test/img/123.png"
fileLink := "https://www.baidu.com/img/bd_logo1.png"

sina.UploadImg(fileLink)

fmt.Println(sina.GetTypeImg(9))

//t定义了返回图片的类型，共9种，数值越小，压缩程度越大！
t = []string{
		"square/",
		"thumb150/",
		"orj360/",
		"orj480/",
		"mw690/",
		"mw1024/",
		"mw2048/",
		"small/",
		"bmiddle/",
		"large/",
	}
```
