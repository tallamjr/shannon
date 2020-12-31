# Python Implementations

Much of the code contained here has been modified from [David Mackay's
webpage](https://www.inference.org.uk/mackay/python/compress/)

### Example Usage

_Assuming `conda` environment already set up_

```bash
$ python lossless/lz77/LZ.py
encoding examples:
101101010001000000 (,1)(0,0)(01,1)(10,1)(100,0)(010,0)(001,0)(110,0)(0010,0)
000000000000100000000000 (,0)(1,0)(10,0)(11,0)(010,1)(100,0)(110,0)
decoding examples:
100011101100001000010 1011010100010
Trying:
    print(decode(list("100011101100001000010")))
Expecting:
    1011010100010
ok
Trying:
    print(encode(list("000000000000100000000000"),1))
Expecting:
    (,0)(1,0)(10,0)(11,0)(010,1)(100,0)(110,0)
ok
Trying:
    print(encode(list("000000000000100000000000"),0))
Expecting:
    010100110010110001100
ok
6 items had no tests:
    __main__
    __main__.find
    __main__.node
    __main__.node.__init__
    __main__.printout
    __main__.test
2 items passed all tests:
   1 tests in __main__.decode
   2 tests in __main__.encode
3 tests in 8 items.
3 passed and 0 failed.
Test passed.
```
