# collision

```sh
a=$(python -c "c1 = \"\xc8\xce\xc5\x06\"
c2 = \"\xc8\xce\xc5\x06\"
c3 = \"\xc8\xce\xc5\x06\"
c4 = \"\xc8\xce\xc5\x06\"
c5 = \"\xcc\xce\xc5\x06\"
pw = c1 + c2 + c3 + c4 + c5
print(pw)")
./col $a
```

## Local
```sh
a=$(python pw.py)
./col a
```