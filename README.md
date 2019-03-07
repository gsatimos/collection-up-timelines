#### orm-chart

#### sumo logic

Search based on this query
```

_sourceName="/mnt/ebs/tomcat7/geonetwork_portal/logs/catalina.out"
and _sourceCategory=prod/geonetwork/tomcat/catalina
| parse "title='*'," as title
| parse "Setting * for uuid" as status
| fields Time, status, title
```

#### google charts 

Google timeline chart documentation
https://developers.google.com/chart/interactive/docs/gallery/timeline
