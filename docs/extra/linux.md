# Linux

If you're running Linux, you need to do one extra step for modding to work.

Open your game properties via Steam, and add this to your launch arguments.

```
WINEDLLOVERRIDES="version=n,b" %command%
```
