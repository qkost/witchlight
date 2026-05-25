
# NPCs

```dataview
TABLE
title as "Title",
location as "Location",
statblock as "Statblock",
Related
FROM "NPCs"
FLATTEN list(filter(file.outlinks, (link) => 
	contains(meta(link).path, "NPCs"))) as Related
WHERE contains(orgs, this.file.link)
```

# Motivations
* 

# Connections
* 