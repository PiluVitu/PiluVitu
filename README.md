<img src="https://capsule-render.vercel.app/api?type=waving&color=BF3636&height=130&section=header" width="100%"/>

```golang
package main

import "fmt"

type PiluVitu struct {
	Name         string
	Area         string
	Stacks       Stacks
	InterestedIn []string
	Portifolio   string
}

type Stacks struct {
	Containers     []string
	Monitoring     []string
	Pipilines      []string
	CloudProviders []string
	IAC            []string
}

func main() {
	piluVitu := PiluVitu{
		Name: "Paulo Victor",
		Area: "DevOps",
		Stacks: Stacks{
			Containers:     []string{"Docker", "Kubernets"},
			Monitoring:     []string{"Prometheus", "Grafana"},
			Pipilines:      []string{"GitHub Actions", "Jenkins"},
			CloudProviders: []string{"AWS"},
			IAC:            []string{"Terraform", "Ansible", "ArgoCD"},
		},
		InterestedIn: []string{"DevOps", "Golang"},
		Portifolio:   "https://piluvitu.dev",
	}

	fmt.Println(piluVitu)
}
```

<div align="center">
    <img width="49%" height="195px" src="https://github-readme-stats.vercel.app/api?username=piluvitu&show_icons=true&count_private=true&hide_border=true&title_color=BF3636&icon_color=D9A282&text_color=BF7154&bg_color=0d1117" alt="Danuzia github stats"/>  
  <img width="41%" height="195px" src="https://github-readme-stats.vercel.app/api/top-langs/?username=piluvitu&layout=compact&hide_border=true&title_color=BF3636&text_color=BF7154&bg_color=0d1117" />
  <img height="160em" width="100%"src="https://streak-stats.demolab.com?user=piluvitu&hide_border=true&locale=pt_BR&date_format=j%20M%5B%20Y%5D&exclude_days=Sun%2CSat&stroke=734949&ring=D9A282&fire=D9A282&currStreakLabel=EB5454&background=EB545400&sideNums=D9A282&sideLabels=EB5454&dates=EB5454&excludeDaysLabel=BF3636&currStreakNum=D9A282">
</div>
<img src="https://capsule-render.vercel.app/api?type=waving&color=BF3636&height=130&section=footer" width="100%"/>
