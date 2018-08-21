# greplum[WIP]
Generate uml image by PlantUML via git managed uml plain text.

# Usage[WIP]
This URL return uml image by PlantUML.
```
greplum.example.com/{github-username}/{plantuml-text-file-path}
```

If you write follow md file on GitHub, greplum read git repository(definited path parameter) and return uml image and be viewable uml on GitHub.
```
## UML SAMPLE
![uml](greplum.example.com/{github-username}/{git-repository-name}/{plantuml-text-file-path})
```

