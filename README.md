### macOS

```
echo "int main(){return 0;}" > stop.c
gcc stop.c -o stop
echo "\r" >> stop
```

```
cat bin >> stop
```

```
sed '1d' stop >> binary
```
