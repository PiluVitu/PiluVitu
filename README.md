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

###

<div align="center">
  <img src="https://streak-stats.demolab.com?user=PiluVitu&locale=pt-br&mode=weekly&theme=moltack&hide_border=true&border_radius=5&order=3" height="150" alt="streak graph"  />
</div>

###

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=piluvitu&hide_title=true&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=moltack&locale=en&hide_border=false&order=1" height="150" alt="stats graph"  />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=PiluVitu&locale=en&hide_title=true&layout=compact&card_width=320&langs_count=5&theme=moltack&hide_border=true&order=2" height="150" alt="languages graph"  />
</div>

###

<div align="center">
  <img src="https://spotify-recently-played-readme.vercel.app/api?user=paulaobr-hue" alt="Spotify recently played"  />
</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=BF3636&height=130&section=footer" width="100%"/>
