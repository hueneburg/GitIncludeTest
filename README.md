# GitIncludeTest
Repo for testing Git integration. It also allows testing include and exclude patterns.

# Repo Structure

- /
    - dir1
        - INCLUDE.md
        - EXCLUDE.md
        - dir1
            - EXCLUDE.md
        - dir2
            - dir1
                - Test1.cs
                - Test2.cs
                - Test1.java
                - Test2.java
            - INCLUDE.md
            - EXCLUDE.md
    - dir2
        - INCLUDE.md
        - EXCLUDE.md
    - README.md
    - IGNORE.md
    - LICENSE
