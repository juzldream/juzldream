```
func main() {
	profile := `
Hi there 👋
Thanks for visiting my GitHub profile, it's great to meet you here! 😊

Here are some quick things about me:
`
	fmt.Println(profile)
	
	me := map[string]string{
		"name":    "小白鞋",
		"job":     "农名工",
		"slogan":  "用代码写诗的伪文青。 一半工作，一半生活； 一路行走，一路结缘； 一个梦想，一个世界。微信订阅号：蝉溪一梦"
	}
	for k, v := range me {
		fmt.Printf("- %s: %s \n", k, v)
	}

}
```
![](https://img2.baidu.com/it/u=2795724226,3705372660&fm=26&fmt=auto)
