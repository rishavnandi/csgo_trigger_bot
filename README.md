# CSGO Trigger Bot

A simple Trigger Bot for CSGO.

You can modify the trigger bot activation key in this line

```cpp
// skip if trigger key is not down
if (!GetAsyncKeyState(VK_SHIFT))
    continue;
```

You can find the virtual key codes here https://learn.microsoft.com/en-us/windows/win32/inputdev/virtual-key-codes

Thanks to Cazz for the memory header https://github.com/cazzwastaken/pro-bhop/blob/master/cheat/memory.h
and Hazedumper for the offsets https://github.com/frk1/hazedumper/blob/master/csgo.hpp'

Follow Cazz's tutorial to compile the cheat https://youtu.be/gzKVqeu5H28