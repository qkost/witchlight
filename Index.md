
## PCs

```dataview
LIST
FROM "PCs"
```
# NPCs

```dataview
TABLE
title + nickname as "Title/Nickname",
orgs as "Orgs",
location as "Location",
statblock as "Statblock"
FROM "NPCs"
SORT file.name
```

# Locations

```dataview
TABLE
link as "Link"
FROM "Locations"
SORT file.name
```

# Organizations

```dataview
TABLE
link as "Link"
FROM "Organizations"
SORT file.name
```

# Sessions


```dataview
TABLE
date as "Date",
summary as "Summary"
FROM "Session Notes"
SORT file.name
```

