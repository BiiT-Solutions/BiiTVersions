# BiiT Version Manager

This is a simple pom file to be used as a parent one for any project. The idea is to centralize all versions of the
company in one place, to ensure that all projects are updated correctly.

## Usage

As this is a maven `pom.xml` file, the way to use it is to define it as a parent in your project.

```
<parent>
    <groupId>com.biit</groupId>
    <artifactId>versions</artifactId>
    <version>[0,1)</version>
    <relativePath/> <!-- lookup parent from repository -->
</parent>
```

