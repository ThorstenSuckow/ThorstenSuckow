# Thorsten Suckow-Homberg
## Senior Full Stack Engineer

### Advocating [Software Development as a rigorous craft](https://thorsten.suckow-homberg.de/docs/articles/software-craftsmanship/).

I collaborate with international clients to architect maintainable, high-quality web applications. My technical foundation rests on **Object-Oriented Design** and the development of scalable architectures using JavaScript, PHP, and modern frontend frameworks.

### Open Source Leadership
I am the author and lead maintainer of the messaging suite **[conjoon](https://conjoon.org)**. My work on UI libraries, specifically **Ext.ux.Livegrid**, has been validated by widespread industry adoption, including its integration into the **Oracle Enterprise Manager**.

### Academic Focus: Computer Graphics & Engineering
Currently pursuing a **Master’s degree in Computer Science** at Trier University of Applied Sciences, I am expanding my specialization into **Real-Time Rendering Pipelines** and **Computer Graphics**.

Operating at the intersection of mathematics, system architecture, and visual computing, I conduct research on software architecture and game development using **C++** and **OpenGL**. I frequently publish my findings.


## Recent contributions
{{range recentContributions 10}}
- [{{.Repo.Name}}]({{.Repo.URL}}) - {{.Repo.Description}} ({{humanize .OccurredAt}})
 {{- end}}

## Recent Releases
{{range recentReleases 10}}
- [{{.Name}}]({{.URL}}) ([{{.LastRelease.TagName}}]({{.LastRelease.URL}}), {{humanize .LastRelease.PublishedAt}}) - {{.Description}}
 {{- end}}

## Publications & Discourse
{{range rss "https://thorsten.suckow-homberg.de/blog/rss.xml" 10}}
- [{{.Title}}]({{.URL}}) ({{humanize .PublishedAt}})
 {{- end}}
