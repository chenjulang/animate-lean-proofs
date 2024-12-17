项目来源：https://github.com/dwrensha/animate-lean-proofs
可视化改进：https://github.com/dwrensha/animate-lean-proofs/tree/c7e34e00aac5fabe24be279697a5d7040895f6ae
https://github.com/mo271/Chess.lean/blob/main/Chess/Basic.lean

[一键打开](https://gitpod.io/new/#https://github.com/chenjulang/animate-lean-proofs)


# Animate Lean Proofs

Code from [this video](https://youtu.be/KuxFWwwlEtc).

[<img src="http://img.youtube.com/vi/KuxFWwwlEtc/maxresdefault.jpg" height="240px">](http://youtu.be/KuxFWwwlEtc)

## running

```shell
$ lake exe cache get
$ lake exe Animate Input/NNG.lean NNG.mul_pow > /tmp/mul_pow.json
$ blender --python animate_proof.py -- /tmp/mul_pow.json
```

(I've been using blender v4.0.2.)


