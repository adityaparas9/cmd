# cmd

$pythonPath = "$env:LOCALAPPDATA\Programs\Python\Python312"
[Environment]::SetEnvironmentVariable(
    "Path",
    $env:Path + ";$pythonPath;$pythonPath\Scripts",
    "User"
)
