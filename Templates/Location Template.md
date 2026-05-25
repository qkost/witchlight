```
link:: [Link]()
```

# Metadata
```dataview
TABLE
this.link as Link
WHERE file.name = this.file.name
```
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
WHERE contains(location, this.file.link)
```

# Sub-Locations
* 

# Points of Interest
* 

# Tags
