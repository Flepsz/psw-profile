# Create profile

```
test-path $profile
```

```
New-Item -Path $profile -Type File -Force
```

```
Get-ExecutionPolicy

# Set the ExecutionPolicy to RemoteSigned:
Set-ExecutionPolicy RemoteSigned
```

```
ise $profile
```

```
Set-Alias intellj "C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2023.2.2\bin\idea64.exe"
Set-Alias avenv "./.venv/Scripts/activate"
```
