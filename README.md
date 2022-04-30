# sat-arm

```bash
git clone https://github.com/suborbital/sat.git
cd sat
env GOOS=linux GOARCH=arm64 go build -o ../sat-arm64 -tags netgo,wasmtime .
```

