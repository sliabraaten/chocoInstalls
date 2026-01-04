Navigate to proper location in powershell, run choco export
Done

Choco Export Examples
    choco export
    choco export --include-version-numbers
    choco export "'c:\temp\packages.config'"
    choco export "'c:\temp\packages.config'" --include-version-numbers
    choco export -o="'c:\temp\packages.config'"
    choco export -o="'c:\temp\packages.config'" --include-version-numbers
    choco export --output-file-path="'c:\temp\packages.config'"
    choco export --output-file-path="'c:\temp\packages.config'" --include-version-numbers