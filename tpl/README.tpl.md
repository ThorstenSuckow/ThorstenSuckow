# Hi. I'm [Thorsten](https://thorsten.suckow-homberg.de/about),
## Full Stack Senior and Trainer for Software Development.

### I see [Software Development as craftsmanship](https://thorsten.suckow-homberg.de/docs/articles/software-craftsmanship/).

The focus of my work is on Design and Agile Development of Software.
I favor Object Oriented languages. I do have a soft spot vor JavaScript.

In recent years I had the chance to accompany teams of different sizes in workshops and training sessions on software development. The lessons I have learned through this are among the most valuable in my life.

I'm maintaining several Open Source projects in my spare time. I'm glad many users consider my work beneficial, from individuals to mid-sized enterprises and Fortune 500 companies.

I am grateful that I get to do what I love every day.


## Recent contributions
{{range recentContributions 10}}
- [{{.Repo.Name}}]({{.Repo.URL}}) - {{.Repo.Description}} ({{humanize .OccurredAt}})
  {{- end}}


## Recent Releases
{{range recentReleases 10}}
- [{{.Name}}]({{.URL}}) ([{{.LastRelease.TagName}}]({{.LastRelease.URL}}), {{humanize .LastRelease.PublishedAt}}) - {{.Description}}
  {{- end}}

## Musings and general ideas
{{range rss "https://thorsten.suckow-homberg.de/blog/rss.xml" 10}}
- [{{.Title}}]({{.URL}}) ({{humanize .PublishedAt}})
  {{- end}}
