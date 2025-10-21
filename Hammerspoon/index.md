https://www.hammerspoon.org

```lua
-- 打开部分应用时，自动切换到英文输入法
local function English()
	hs.keycodes.currentSourceID("com.apple.keylayout.ABC")
end

appWatcher = hs.application.watcher.new(function(appName, eventType, app)
	if (eventType == hs.application.watcher.activated) then
		if (appName == "终端" or appName == "Windsurf" or appName == "Warp") then
			English()
		end
	end
end)

appWatcher:start()
```